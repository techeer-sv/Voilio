<p align="center">
<img width="400" alt="voilioLogo" src="https://user-images.githubusercontent.com/76465887/234565977-19fb200f-dff9-4d6a-9416-207ae0d71f31.png">
</p>

# Voilio ✨

<p align="center">
<strong>영상기반의 포트폴리오 웹 서비스 <br></strong> 당신을 영상에 담아보세요!
</p>
<br>

## 📹 Demo

https://www.youtube.com/watch?v=xF6UP7sfZlM

## 💡Tech Stack

<br>

<p align="center">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">

</p>  
<p align="center">
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white">
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=SpringSecurity&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white">
  </p>
<p align="center">
<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white"/><img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> 
<img src="https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=GitKraken&logoColor=white"> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> 
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white">
<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white">

</p>

```
- Frontend : React
- Backend : Spring Boot
- Web Server: Nginx
- DevOps : Docker
- Database: MySQL
- API Documentation : Swagger
- Deployment : AWS
- VCS: Git
```

## 💻 System Architecture

![VoilioArchitecturePOC (1)](https://github.com/techeer-sv/Voilio/assets/76465887/344fb8c9-e275-48e5-8708-d6540e965687)
## 📗 API

<img width="884" alt="스크린샷 2023-05-09 오후 11 21 11" src="https://github.com/techeer-sv/Voilio/assets/76465887/4409c60b-e742-4724-91cb-8c01bf7903b2">

## 🚀 How to Start

### 1. Clone Repository 

```
git clone --recursive https://github.com/techeer-sv/Voilio.git
```

### 2. Install Pacakages

```
$ cd frontend
$ npm run build
```

### 3. Env Settings

- Add /Voilio/.env file

```bash
# === Database ===
MYSQL_ROOT_PASSWORD=
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_DATABASE=
SPRING_DATASOURCE_PASSWORD=
```

- Add /Voilio/backend/src/resources/application-secret.yml

```bash
# === S3Bucket ===
spring:
  config:
    activate:
      on-profile: secret

cloud:
  aws:
    credentials:
      accessKey: 
      secretKey: 
    s3:
      bucket: 
    region:
      static: 
    stack:
      auto: false
```

### 4. Run Docker

```
$ docker-compose up --build   
# build images and run containers
```


## 👨‍👩‍👧‍👦 Team Port
| Name    | 정길연                                                                            | 강용민                                                                              | 김인철                                                                   | 백한결                                                                             |
| ------- |--------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------|---------------------------------------------------------------------------------| 
| Profile | <img width="200px" src="https://avatars.githubusercontent.com/u/52391627?v=4"> | <img width="200px" src="https://avatars.githubusercontent.com/u/84130518?v=4" /> | <img width="200px" src="https://avatars.githubusercontent.com/u/82080962?v=4"/> | <img width="200px" src="https://avatars.githubusercontent.com/u/76465887?v=4"/> |
| Role    | Team Leader, Backend, Frontend, DevOps                                         | Backend, Frontend                                                                | Backend                                                               | Backend, DevOps                                                                 |
| gitHub  | [gilyeon00](https://github.com/gilyeon00)                                      | [goldapple-ce](https://github.com/goldapple-ce)                                  | [kimich1218](https://github.com/kimich1218)                           | [snake7667](https://github.com/snake7667)                                       |
