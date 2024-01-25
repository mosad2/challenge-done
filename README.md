First this a Dockerfile of client-app which i build use >> sudo docker build -t client-app . 

![docker file client](https://github.com/mosad2/challenge-done/assets/63494835/b8c9d6cc-54a1-4014-9d37-d5156f800b35)

second this a Dockerfile of php-api 
![php dockerfile](https://github.com/mosad2/challenge-done/assets/63494835/869d61e3-d97d-4145-af01-53c5751ed9a3)

these a services of docker compose file 
client-app: A service for your client application, exposed on port 5000.
php-api: A service for your PHP API, which depends on the db service.
db: A MySQL database service on port 3306 
and  a docker comopse file  which i use docker-compose up -d to run it and it is in client directory and all are up to date   
![compose](https://github.com/mosad2/challenge-done/assets/63494835/48377ae6-63da-4692-8088-077317292624)

 and this a client app and api  in my broswer  
 ![app](https://github.com/mosad2/challenge-done/assets/63494835/dd0796c3-0ab6-46cc-b407-782ca7b25199)
![api](https://github.com/mosad2/challenge-done/assets/63494835/4801b5ed-50a7-4927-a323-a6d47e30fc7f)

I Implement CI/CD using GitHub Actions:
Set up workflows to build Docker images for the  Client.
Push the built images to Docker Hub.
Trigger workflows on pushes to the main branch 
![ci cd done](https://github.com/mosad2/challenge-done/assets/63494835/afeeb5de-3558-4499-82f1-613eb011e186)
and this the built image in my dockerhub :

![ww](https://github.com/mosad2/challenge-done/assets/63494835/838f44e4-9986-4ff8-b1ed-6e6189cbf3b1)


finally this a nginx running with port 443 and every informaiton in a file in this repo 
![1 nginx](https://github.com/mosad2/challenge-done/assets/63494835/fa1d603f-f52e-4e1d-8acf-fd2f3356ec89)
![2 nginx](https://github.com/mosad2/challenge-done/assets/63494835/22f61cb6-7339-4c68-86da-f6022c634db7)



