# docker-tomcat-server
Launching Tomcat server on Amazon Linux 2 based linux instance  by writing docker file

- To get this directory 

$ git clone https://github.com/ankitdattatrayjagtap/docker-tomcat-server.git

- To build docker image

$ docker build -t mytomcat .

- To run image created earlier 

$ docker run -d --name yuor-fav-name -p 8081:8080 mytomcat
