los comandos para crear y lanzar una imagen de manera local son
    docker build -t hola-computo-nube:latest 
    docker run -d --name hola-computo -p 80:80 hola-computo-nube:latest
