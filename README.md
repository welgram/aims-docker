# aims-docker

- docker 로그인 (네이버클라우드플랫폼 인증키 사용)  
  : docker login aims.ncr.fin-ntruss.com
  
- docker 단독실행  
  : docker run --name aims -e ACTIVE_PROFILE=product -p {hostPort}:80 -d aims.ncr.fin-ntruss.com/welgram/aims:latest

- docker-compose 실행  
  : docker-compose up -d

인증키
: 네이버클라우드플랫폼(https://www.fin-ncloud.com/mypage/manage/auth)
계정관리 > 인증키 
