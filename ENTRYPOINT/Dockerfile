# We can override the command inside the CMD instruction at run time by providing the command in the docker run command.
# For example, if we have a CMD instruction in the Dockerfile which is used to run nginx server and we want to run a different command when we start the container then we can provide the command in the docker run command.

# We cant override the command inside the ENTRYPOINT instruction at run time by providing the command in the docker run command.
# For example, if we have an ENTRYPOINT instruction in the Dockerfile which is used to run nginx server and we want to run a different command when we start the container then we cannot provide the command in the docker run command because the ENTRYPOINT instruction will always run the command which is specified in it.


# for best we should use both CMD and ENTRYPOINT instruction in the Dockerfile. We can use ENTRYPOINT instruction to specify the command which we want to run when the container is started and we can use CMD instruction to specify the default arguments for the command which is specified in the ENTRYPOINT instruction.

FROM almalinux:9
CMD ["google.com"]
ENTRYPOINT ["ping"]

# When we run the container then it will run the ping command with the argument google.com because the ENTRYPOINT instruction will run the ping command and the CMD instruction will provide the default argument google.com to the ping command. 
# If we want to override the default argument then we can provide the argument in the docker run command. 
# For example, if we want to ping yahoo.com instead of google.com then we can provide yahoo.com in the docker run command and it will override the default argument provided by the CMD instruction.