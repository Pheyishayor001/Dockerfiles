# Dockerfiles
1. Copy the docker file to the respective repository/dirctory.

2. Rename the docker files to the regular naming convention.
3. Build an docker image out of the file: ** docker build -t <image-name> . **
4. Copy the yaml file to the root directory of the web-app and API repositories.

5. pull postgres:13 image from docker: ** docker pull postgres:13 **

6. to spin up the containers from the yaml file: ** docker-compose up -d **
