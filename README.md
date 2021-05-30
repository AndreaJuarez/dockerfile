# dockerfile
Repositorio asignado para actividad acerca del manejo de Dockerfile. 

# crear contenedor 
docker run -it -p 8080:8080 -v /workspace/dockerfile/images:/images --name webapp -h webapp webapp:v1

# ejecutar index.php desde la terminal 
docker  run -p 8080:8080 --rm -v $(pwd):$(pwd) php:7.4-cli php -S 0.0.0.0:8080  $(pwd)/index.php