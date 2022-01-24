# Devops-js-quickstart
quickstart project for javascript application with docker 

/www : folder for using nginx server
    /certs : folder for more secure the access by generating key using mkcert
/api : backend project with NestJs 
/app : Empty react Project

Note :  bitbucket-pipelines.yml file to apply some command with bitbucket 

1- clone the project 
2- start docker service ( systemctl start docker )
3- install docker-compose command
4- press command make to execute the script in Makefile
  ---> 3 container will be created 
check the "localhost" link in the browser 
   - https:localhost/ -> redirect to react project
   - https:localhost/api -> redirect to api ( nestJs) project 

TODO:

1- CRUD to backend and frontend with conection to mongodb database 
2- Add kubernetenes   
