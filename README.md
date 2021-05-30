# dockerfile
Repositorio asignado para actividad acerca del manejo de Dockerfile. 

# crear contenedor 
docker run -it -p 8080:8080 -v /workspace/dockerfile/images:/images --name webapp -h webapp webapp:v1