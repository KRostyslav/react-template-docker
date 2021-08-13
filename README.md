# react-template

Template for docker+react


Build the image and fire up the container:

``` 
$ docker-compose up -d --build
```

Ensure the app is running in the browser and test hot-reloading again. Bring down the container before moving on:

```
$ docker-compose stop
```

Fire up the container:

```
$ docker-compose -f docker-compose.prod.yml up -d --build
```
