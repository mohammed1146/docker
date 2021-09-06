# Docker Training Repository
    **1- Mysql assignment**
        - go to folder mysql_assignment
        - to run locally
            `cd mysql_assignment`
            `docker build -t mysql_image .`
            -t here to tage the image
        - after you build the image. now you can run the image
            `docker run -p 3306:3306 -v mysql:/var/lib/mysql -d mysql_image`
        - to access the container
            `docker exec -it <container_name> mysql -u root -p`

    **2- Docker compose php app**
        This app using docker-compose
        to run this app locall
        `cd docker_compose_php_app`
        `docker-compose build`
        `docker compose up -d`
        then you can go to the localhost
        http://localhost
