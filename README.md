# pbl5-docker
## To build the image
docker build . -t [image_name]
## To run the image
docker run --rm -it --name [container_name] -p 3000:3000 -v ${pwd}:[work_direction] [image_name]
## To build the docker compose
docker-compose build
## To run the docker compose
docker-compose up