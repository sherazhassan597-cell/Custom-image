# Custom-image
## Project Overview
This project demonstrates how to build a custom Docker image using Nginx to serve a static HTML website.

## Technologies Used
- Docker
- Nginx
- Linux

## Steps Performed

1. Created a Dockerfile using nginx as base image
2. Copied custom index.html into Nginx web root directory
3. Built Docker image:
   docker build -t mynginx:0.1 .
4. Ran container with port mapping:
   docker run -d -p 80:80 mynginx:0.1
## Commands Used 
docker build . -t mynignx:0.1 
docker run -d  -p 80:80 mynginx:0.1 
## Files Used 
Dockerfile index.html 

##  Output
The container serves a static website accessible via browser on port 80.

##  Key Concepts Learned
- Dockerfile instructions
- Image building
- Port mapping
- Difference between COPY and Volume
- Container lifecycle management
