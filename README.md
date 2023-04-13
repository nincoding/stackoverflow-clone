# stackoverflow-clone

stackoverflow clone app web

## init 명령어

```
// client, server 폴더 생성
// 각각 폴더 안에서 init 설치하기
// 1. client 폴더 init 생성
cd client
npx create-react-app ./

// 2. 필요한 라이브러리 추가
npm i axios jwt-decode moment react-copy-to-clipboard react-router-dom redux react-redux redux-thunk

// 3. 스타일 라이브러리 추가
npm i styled-components

// 1. server 폴더 init 생성
cd server
npm init
npm i bcryptjs jsonwebtoken cors dotenv express mongoose nodemon
```
