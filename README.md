# nginx

build the image:

```
docker build -t my-nginx-image .
```

run the container:

```
docker run -p 8080:80 my-nginx-image
```

view the container in your browser by going to http://localhost:8080
