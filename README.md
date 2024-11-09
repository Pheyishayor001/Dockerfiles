# Dockerfiles
1. API Image: pheyishayor001/wordsmith-api-image
2. web Image: pheyishayor001/wordsmith-web
3. Database image: postgres:13
4. 
5. Copy the docker file to the respective repository/dirctory.

6. Rename the docker files to the regular naming convention.
7. Build an docker image out of the file: **docker build -t <image-name> .**
8. Copy the yaml file to the root directory of the web-app and API repositories.

9. pull postgres:13 image from docker: **docker pull postgres:13**

10. to spin up the containers from the yaml file: **docker-compose up -d**
