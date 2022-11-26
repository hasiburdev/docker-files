# Postgres with PGAdmin4

To connect to database the localhost does not work. 
To solve the problem follow this steps: 

First grab the container id with
```sh
docker ps
```

Then run this command to find the ip address that docker assigned to the postgres container.
```sh
docker inspect CONTAINER_ID | grep IPAddress.
```