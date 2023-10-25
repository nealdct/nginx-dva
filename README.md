# nginx

build the image:

```
docker build -t nginx-dva .
```

run the container:

```
docker run -p 8080:80 nginx-dva
```

view the container in your browser by going to http://localhost:8080
