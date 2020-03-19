
```bash
make build # construira la imagen de docker builder
s2i build https://gihub.com/[somerepo] golang-s2i-builder golangapp #construira un contenedor con la app y dependencias cuyo nombre sera golangapp
docker run -d -it -p 8080:8080 golangapp
OR
docker run -e"ARGS=arg1=value1 arg2=value2" -d -it -p 8080:8080 golangapp
```

