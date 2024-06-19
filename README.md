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
8. npm i localtunnel
   localtunnel은 서버를 전세계와 공유하게 해줌. (일시적 무료)
   - lt 커맨드를 이용하여 localtunnel 사용

구글이 무료로 제공하는 STUN 서버를 사용

babel은 작성한 코드를 nodejs 코드로 컴파일

[socket.io](https://admin.socket.io/) 접속시 xhr poll error 수정 setting

Server URL: http://localhost:3000
Advanced Options: 체크
WebSocket only?: 체크
Admin namespace: /admin (기본설정)
Path: /socket.io (기본설정)

webRTC를 이용한 실제 서비스를 만들고 싶다면 STUN 서버를 구매해야함
