*** Board_VS ***
    nodejs 게시판 소스와 cyberir 을 혼합한 형태
    moongoose 사용한 local PC 환경 
    실행 : node app.js
    확인 : http://localhost:3000

*** babel ***
    package.json을 보면 된다 
    "scripts": {
        "compile": "babel src/main.js --out-dir dist  && babel src/lib --out-dir dist/lib --source-maps --watch && babel src/route --out-dir dist/route --source-maps --watch"
    },

    1.1 직접  compile: 이하를 실행하거나. (babel src --out-dir dist  또는 babel src/a.js -o dist/a.js)
    1.2 npm run compile 실행 
    
    
*** GIT ***
    VScode 와 git 연동방법
    1. GitLens 설치
    2. local 에 소스 관리하지만 원격관리(push/pull)하려면 git remote add 사용한다.
        > git remote add Board_VS https://github.com/kimkyunhyung/Board_VS.git
    