# Launching Gitlab with docker on RedHat
### Follow the steps mentioned in install.txt
Run `docker-compose up -d` to launch docker instance
`docker ps` to view running containers


### to view logs
`docker logs --tail 5 --follow --timestamps <container_name>`