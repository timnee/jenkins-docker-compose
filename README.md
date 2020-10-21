# Quick local jenkins setup using docker

### Steps:
1. clone this repo
2. cd to `jenkins-docker-compose`
3. run `docker-compose -d up`
4. go to http://127-0-0-1.nip.io:8080/

### Update jenkins
1. run `docker pull jenkins/jenkins:lts`
2. run `docker-compose up -d --build`