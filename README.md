# tooltip
각종 툴 사용 팁

# 1.DBEAVER
https://3rdscholar.tistory.com/83
# 2.git
https://learngitbranching.js.org/?locale=ko
# springboot에서 application.yml이란? 환경설정을 뜻함
예시)
spring.profiles: dev

spring:
  datasource:
    platform: postgresql
    url: jdbc:postgresql://ip/db이름 #개발서버
    username: 
    password: 
    driverClassName: org.postgresql.Driver
    
file.upload.path: 경로

server:
  port: 8081
  servlet:
    session:
      cookie:
        secure: true
        http-only: true
        
logging.path: 경로

# Run Configurations에서 -Dspring.profiles.active=dev 이런식으로 설정하면 위에 설정한거로 붙음
