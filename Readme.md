# Pasos para Ejerscio 1

* Bajar imagen nicopaez/pingapp

    docker pull nicopaez/pingapp:3.0.0

* nos logueamos
    docker login --username hduchen

* Listamos las imagenes  

    docker image ls

* validamos la que se importo y la renombramos la imagen 

    docker tag nicopaez/pingapp:3.0.0 hduchen/pingpapp:3.0.0 

* subimos la imagen al repo hduchen

    docker push hduchen/pingpapp:3.0.0

* como bajar la imagen subida

    docker pull hduchen/pingpapp:3.0.0 