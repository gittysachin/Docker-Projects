## Microservices

Run the following commands to spin up the docker container running your application - 

1. `docker build -t nodeapp .`
2. `docker-compose up`

To bring the services down - 

1. `docker-compose down` 

Now, open http://localhost:8080/ and try refreshing the page again and again. The APPID is being changed accorging to the Round-Robin algorithm. 