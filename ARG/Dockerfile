# Its used to provide variable to image during build time. 
# AEG can be first instruction in the Dockerfile and it can be used to set the base image for the Dockerfile.
# It can be used to set the base image for the Dockerfile and it can also be used to set the base image for the Dockerfile.
# It is a good practice to use ARG instruction in a Dockerfile to set the base image for the Dockerfile.    

ARG version=9
FROM almalinux:${version}
RUN dnf install nginx -y 

# we can also pass different version of the base image during build time using --build-arg option.
# For example, if we want to use almalinux:8 as the base image then we can use the following command to build the image:
# docker build --build-arg version=8 -t myimage:latest .