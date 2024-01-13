docker client

docker host / daemon

docker hub
central repository like github to store public and private docker images

docker image
.dockerfile will be a file where you set up all the information for the docker image, e.g. what image / app to run, with what dependecies, what scripts to execute when it will first run etc, on what OS (which can be used for multiple containers with the same image)

dockar container
container is where an image runs in - it's the runtime, the os the kernel etc of each running image - you can run multiple containers for each image for scaling purposes

volume
shared storage between different containers 

network
shared network between different containers