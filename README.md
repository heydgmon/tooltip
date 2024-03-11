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

# 프로젝트 어디에 있는건지 찾으려고 할때 -> 인텔리제이 ctrl+shift+f도 있지만, 웹에 접속해서 f12번 누르고 마우스로 클릭해서 경로 찾는 방법도 있다.
  웹에서 돌아가는거 하나씩 까보려면 동작했을때 인텔리제이에 나오는 로그를 보면 된다
