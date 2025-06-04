FROM node:latest



WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ARG DEFAULT_PORT=80

ENV PORT=$DEFAULT_PORT

EXPOSE $PORT
# 호스트 파일 시스템 의 /temp 디렉토리를 컨테이너의 /temp 디렉토리로 마운트합니다.
# VOLUME [ "/temp" ]

CMD ["npm", "start"]