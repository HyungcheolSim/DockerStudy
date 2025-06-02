FROM node:latest

WORKDIR /app
# workdir를 /app으로 설정했기 때문에 COPY 에서 상대적 경로를 아래와 같이 설정 가능능
COPY . ./

RUN npm install

# 80 포트를 로컬머신에게 알려줌
EXPOSE 80 


CMD ["node", "server.js"]