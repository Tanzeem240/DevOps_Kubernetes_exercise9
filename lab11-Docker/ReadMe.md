# COMP3104 – Lab 11 – Containerization
Tanzeem Shaikh – 101585484

Simple Python Flask app containerized with Docker.

## Build
docker build --tag=hellodocker .

## Run
docker run -p 4000:80 hellodocker

Open http://localhost:4000
