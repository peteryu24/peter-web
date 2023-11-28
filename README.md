# web project🌱
spring과 더욱 친해지기 위해 만들어본 게시판 (feat. openlayers)
<br>
<br>
## features 📂
- register, login
- post, comment, file CRUD
- logger with AOP
- security + jwt token(refresh token) + csrf token
- openlayers
## toolkit 🛠️
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
<a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a>

<a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a>
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a>
<br>
<br>
## DEMO 👁️‍🗨️
<img src="https://github.com/peteryu24/peter-web/assets/67302252/6e7b6451-3395-45a5-bc41-eae8f68d2914">
<br>
<br>

## feature details 📋
- [project preview](https://github.com/peteryu24/peter-web/tree/aaadd5c265ab29c0706ab9951a103482b20e4031/src/main)
- [aop](https://github.com/peteryu24/peter-web/tree/e29422021dfa9aee75a75eef748cc1751043f762/src/main/java/gmx/fwd/aop)
- [DB Optimization](https://dudefromkorea.tistory.com/16)
- [security + jwt token(refreshToken)](https://github.com/peteryu24/peter-web/tree/2480a362ed58cad1ed566b2de935709f72ea9433/src/main/java/gmx/fwd/jwt)
- [Prevent View Count Manipulation](https://dudefromkorea.tistory.com/15)
<br>

## project layout 📌
```
🌱 peter-web
├─ src
│  └─ main
│     ├─ java
│     │  └─ gmx
│     │     └─ fwd
│     │        ├─ controller : controller folder
│     │        ├─ service : service folder
│     │        ├─ mapper : mapper interface(linked with mapper.xml - mybatis)
│     │        ├─ interceptor : session based interceptor(now using token)
│     │        ├─ aop : logger using aop
│     │        ├─ jwt : settings for jwt token
│     │        ├─ security : spring security
│     │        └─ vo : known as DAO(Data Access Object)
│     ├─ resources
│     │  ├─ db : query for creating tables
│     │  ├─ gmx
│     │  │  └─ context : folder for settings.xml
│     │  ├─ mapper : xml based query using mybatis
│     │  └─ properties : properties for file downloads
│     └─ webapp
│        ├─ WEB-INF
│        │  ├─ config : place for dispatcher-servlet.xml
│        │  ├─ jsp : folder for jsp files
│        │  └─ web.xml : web settings
│        ├─ css : css folder
│        ├─ error : error.jsp
│        └─ js : folder for js(s)
└─ pom.xml : maven settings
```
<br>

## before using ☢️
make sure `<base href="http://localhost:8080/yourWantedTitleHere/">` is unified on every jsp

