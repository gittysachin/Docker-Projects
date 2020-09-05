## Lighweight Docker Container

Run the following commands to spin up the docker container running your application - 

1. `docker build -t nodeapp .`
2. `docker run --name nodeapp -p 9999:9999 nodeapp`

To kill & destroy the container - 

1. `docker stop nodeapp` 
2. `docker rm nodeapp`

Spin up multiple docker containers, if you want to - 


1. `docker run -d -p 8000:9999 nodeapp`   (-d is used to run the application and detach itself)
2. `docker run -d -p 8001:9999 nodeapp`
3. `docker run -d -p 8002:9999 nodeapp`

There are many more commands that you have to deal on your own as you go deep with docker containerization. 