#docker
docker run --name shubham -it ubuntu /bin/bash  (--name shubham represent the name of container, ubuntu represent image name, /bin/bash use to lodin in that container)
now we go to /tmp here we create a file 
now we create an image from existing container by using this command 
docker commit shubham update  (here shubham is the existing container, update is the new image name)
docker run -it --name pandit update /bin/bash (by this command we create a container by using new image)
