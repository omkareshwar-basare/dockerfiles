# The user instruction is used to specify the user under which the commands should be executed in the Docker container.
# It is used to set the user for the instructions which are present in the Dockerfile

FROM almalinux:9
RUN dnf install nginx -y
USER useradd roboshop
USER roboshop
CMD ["sleep","100"]