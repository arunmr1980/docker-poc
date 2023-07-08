# docker commands

###  Images

List images
> docker images

Remove an image
> docker rmi [Image Id]
Or
> docker rmi [name]:[tag]

Use --force option to force remove the image. This becomes necessary if the image being removed is used by a container, either running or stopped

### Containers

List running containers
> docker ps
