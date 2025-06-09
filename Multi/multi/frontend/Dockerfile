# 프로젝트 설정에 노드가 필요하기 떄문에 import
FROM node:14
WORKDIR /app
COPY package*.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]