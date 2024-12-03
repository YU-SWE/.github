# YUFOOD

## 시작하는 방법

### 프론트엔드 : <https://github.com/YU-SWE/FE>
1.  master 브랜치에서 프로젝트를 받아옵니다.
```angular2html
git clone https://github.com/YU-SWE/FE.git
```

2.  코드가 있는 폴더로 이동을 합니다.
```angular2html
cd ./fe
```

3. node_modules를 다운 받습니다.
```angular2html
npm install
```

4. 설치 완료되면 현 위치에서 아래의 코드를 실행하여 프론트 서버를 실행합니다
```angular2html
npm start
```

5.웹 프론트 서버가 시작되면 웹 브라우저에서 아래의 주수를 들어갑니다
<pre>
http://<a href="http://localhost:3000" target="_blank">localhost:3000</a>
</pre>

### 백엔드 : <https://github.com/YU-SWE/BE>

1. master 브랜치에서 프로젝트를 받아옵니다.
```angular2html
git clone https://github.com/YU-SWE/BE.git
```
<<<<<<< HEAD
2. Redis 다운로드
    *  Window 다운로드 방법
        + https://github.com/microsoftarchive/redis/releases 에서 .msi 파일 다운로드
        + Next를 계속 누르며 다운로드
        + C:\Program Files\Redis\redis-server.exe 를 실행해 레디스 서버 실행
        + C:\Program Files\Redis\redis-cli.exe 실행
      * Mac 다운로드 방법
          + 터미널에서 redis를 install
            ```angular2html
            brew install redis
            ```
          + 터미널에서 redis 실행
            ```angular2html
            brew services start redis
            ```
=======
2. Redis 다운로드 
   *  Window 다운로드 방법
       + https://github.com/microsoftarchive/redis/releases 에서 .msi 파일 다운로드
       + Next를 계속 누르며 다운로드
       + C:\Program Files\Redis\redis-server.exe 를 실행해 레디스 서버 실행
       + C:\Program Files\Redis\redis-cli.exe 실행
   * Mac 다운로드 방법
     + 터미널에서 redis를 install
       ```angular2html
       brew install redis
       ```
     +  터미널에서 redis 실행
       ```angular2html
       brew services start redis
       ```
3. build을 정리합니다
```angular2html
./gradlew clean build
```

4. 받아온 프로젝트의 루트 폴더에서 실행합니다.
```angular2html
./gradlew.bat bootRun
```
5.  웹 백엔드 서버가 구동되고 프론트엔드에서 접속한 사이트를 이용하면 됩니다.

### 선행 조건
```angular2html
JDK 17, MySQL 8.0.33 이상, NodeJS 20.17.0 이상, Spring Boot 3.3.4 이상
```

***

### 프론트 기술
* NodeJS axios 통신
* React
<p align="left">
    <img src="./image/axios.png" align="center" width="32%">
    <img src="./image/react.png" align="center" width="32%">
</p>


***

### 백엔드 기술
* Spring Boot
* JWT
<p align="left">
    <img src="./image/spring_boot.png" align="center" width="32%">
    <img src="./image/jwt.png" align="center" width="32%">
</p>