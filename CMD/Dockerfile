# used to run the command when the container is started. It should be the last line in the dockerfile. 
# It can be any command which we want to run when the container is started.
# It will not run when we build the image but it will run when we start the container. 
# It will run in the foreground and it will keep the container running until the command is running. 
# If the command is not running then the container will stop.

FROM redhat/ubi9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]