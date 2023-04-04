# Simple Python app with Dockerfile (connect with a  mongo docker make outside)

## To see folder
first
```
docker-compose up
```
then
```
docker-compose run --service-ports app sh
```
or
```
docker-compose run --service-ports mongo sh

```

### python-custom -> create container
### python-compose -> create a docker-compose file to initialize multiples containers and connect their connection
### python-compose-permanent-volume -> create a docker-compose file with multiples docker containers with permanent docker volume (the file will be stored at container volume)