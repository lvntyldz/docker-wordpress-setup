## Download 
```
$ git clone https://github.com/docker-wordpress-setup
```

## Navigate to source
```
$ cd docker-wordpress-setup
```

## Down volume data(has any big changes in db setup) 
```
$ docker-compose down --volumes
```

## Run with docker-compose
```
$ docker-compose up -d
```

> You’ll now see along with the docker-compose.yml file and in there the default WordPress files.

##### Accessing phpMyAdmin UI : http://localhost:8081
##### Accessing WordPress Setup : http://localhost:8082

