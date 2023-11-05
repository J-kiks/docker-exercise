#### This project is for the Devops bootcamp exercise for 
#### "Containers - Docker" 

Demo Project:

To configure and run a java application with Mysql DB on a server using docker-compose.

Technologies used:

Docker, Mysql, Phpmyadmin, Java, Nexus, Amazon ECR, Digital Ocean.

Project Desciption:

. Cloned Git repo and edited the code to avoid hardcoding DB creditentials.

. Tested application loaclly using Mysql docker image, then built the jar file to start and run application o localhost.

. Also ran a Mysql GUI container (Phpmyadmin Docker Image) to allow viewing of database data.

. Configured a docker compose file to run Mysql and Phpmyadmin at once with a volume (to persist data) to test my application.

. Created a Dockerfile to turn my java application to a Docker Image.

. Created a docker hosted repository on Nexus (allowing http access persion). Built my Docker image locally and pushed to the Nexus docker repository.

. Updated previous docker compose file by adding my dockerised Image after tagging the image with docker repo URL.

. Copied my docker compose file to server, set all needed environment variables for all the containers and ran my appication on the server.

