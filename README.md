getting started

create the required docker network with docker network create nginx-proxy

make sure to add the below code to any new compose file 
```yml
networks:
  default:
    external:
      name: nginx-proxy
```
