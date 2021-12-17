# Build Application from scratch
We will build an application by using docker-compose. We will run the following containers:
- alpine:latest
- postgres:latest
- nginx:latest 

### Create destro service 
We create the destro service by using the **alpine:latest** image:
```
distro:
    image: alpine 
    restart : always 
    container_name: Custom_alpine 
    entrypoint: tail -f /dev/null 
```
### Create datagase service 

### Create web service 