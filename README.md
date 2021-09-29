# postgres-pgadmin-docker
docker-compose file to configure postgres on a server so that you can start developing applications
### START WITH LINUX

_Menciona las herramientas que utilizaste para crear tu proyecto_

* Make a git clone of the project

```
git clone https://github.com/RenderCod/postgres-pgadmin-docker.git
```

* Enter the folder
* run docker command

```
docker-compose up
```
_if not run by permissions_

```
sudo docker-compose up
```
_Open an other terminal_

```
sudo docker inspect postgres
```

_We obtain the ***IP address***, which will help us to make the connection from pgadmin_