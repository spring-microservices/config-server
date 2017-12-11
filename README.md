Spring cloud config sample server, which loads properties from folder `config-client` under the git repository [config-repo ](https://github.com/spring-microservices/config-repo "Config Repo").

To encrypt a value :-  `curl http://localhost:8082/encrypt -d "My prod passwd"`   
To decrypt :-  `curl http://localhost:8082/decrypt --data-urlencode d4a0c9faadc8c7de092fce`   

To see the dev environment properties :-  http://localhost:8082/config-client-dev.json, 
http://localhost:8082/config-client/dev