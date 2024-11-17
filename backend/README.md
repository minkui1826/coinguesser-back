
# 변경사항 

### 1. app.js (애플리케이션 설정 및 로직)
    - app.js는 애플리케이션 로직, 미들웨어, 라우팅 등을 설정
    - 서버 실행 관련 코드는 포함 X


### 2. index.js (서버 실행 파일)
    - index.js는 app.js를 가져와 서버를 실행
    - 엔드포인트도 여기서 ㄱㄱ
    - 최종적으로 실행되는 파일 


### 3. nodemon 사용 
    - 사용 이유 : 코드 수정할 때 새로 컴파일 안 해도 바로 적용   
    - 설치 명령어 : `$ npm install nodemon --save-dev`
        - --save-dev로 개발 환경에서만 설치하고 package 종속성에는 포함되지 않게 함
    - \coinguesser-back\backend 경로에서 
    - 실행 : `$ npx nodemon index.js`
    

### 기타
    - 나머지 js 파일은 /src에 작성하면 됨 

