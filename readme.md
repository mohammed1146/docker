## Docker Training Repository

**1. Mysql assignment**
- go to folder mysql_assignment
- to run locally  
  <br>  
  `cd mysql_assignment` <br>  
  `docker build -t mysql_image .` <br>  
  -t here to tage the image
- after you build the image. now you can run the image <br>  
  `docker run -p 3306:3306 -v mysql:/var/lib/mysql -d mysql_image`  
  <br>
- to access the container <br>  
  `docker exec -it <container_name> mysql -u root -p`  
  <br><br>

**2. Docker compose php app**
- This app using docker-compose
- to run this app locall  
  <br>  
  `cd docker_compose_php_app`  
  <br>  
  `docker-compose build`  
  <br>  
  `docker compose up -d`  
  <br>  
  then you can go to the localhost  
  <br>  
  http://localhost
