# its used to display the information of container.
# It will not really open the port but it will just display the information that this port is used by the container. 
# It is used to document the port which is used by the container. 
# It is not mandatory to use EXPOSE instruction in a Dockerfile but it is a good practice to use it to document the port which is used by the container.

FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]