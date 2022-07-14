# microservicios2022
Para levantar la imagen en Linux/Mac:

docker run -d -p 8080:8080 -p 50000:50000 -v $(PWD)/jenkins_home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock jenkins-local
 
Para levantar la imagen en Windows:

docker run -d -p 8080:8080 -p 50000:50000 -v "C:/Practicas/Jenkins/jenkins_home/jenkins_home:/var/jenkins_home" -v "//var/run/docker.sock:/var/run/docker.sock" jenkins-local
