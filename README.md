# Noom

Zoom Colne using WebRTC and Websockets.

** projcect setup **

1. npm init -y
2. nodemon.json, babel.config.json 파일 생성
3. git init .
4. npm i @babel/core @babel/cli @babel/node -D
5. .gitignore 파일생성
6. npm i express
7. npm i pug (view engine 설정)

babel은 작성한 코드를 nodejs 코드로 컴파일

[socket.io](https://admin.socket.io/) 접속시 xhr poll error 수정 setting

Server URL: http://localhost:3000
Advanced Options: 체크
WebSocket only?: 체크
Admin namespace: /admin (기본설정)
Path: /socket.io (기본설정)

테스트 readme
ㄴ master_clone branch