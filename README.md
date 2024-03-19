## 간단한 Todo list 보여주기 & Todo 저장하기
간단한 스프링 컨트롤러 사용<br>
간단한 Thymeleaf 사용<br>
간단한 Domain 클래스 작성<br>
간단한 Repository 인터페이스 작성<br>
MySQL Database 연동<br>
Docker 연동

## Tools / Languages

<img src="https://skillicons.dev/icons?i=idea,spring,gradle,java,mysql,html,docker"/>

##Docker Terminal Command

docker stop $(docker ps -q)
docker rm $(docker ps -a -q)
docker rmi -f $(docker images -q)

docker network rm docker-compose_default
docker network rm docker-compose_net-mysql

./gradlew build   

docker network ls
docker network rm todoapp_default
 
docker-compose up -d   
