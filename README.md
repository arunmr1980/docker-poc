# docker commands

###  Images

List images
> docker images

Remove an image
> docker rmi [Image Id]
Or
> docker rmi [name]:[tag]

Use --force option to force remove the image. This becomes necessary if the image being removed is used by a container, either running or stopped

Download an image
> docker pull [Image URL]

### Containers

List running containers
> docker ps

Run a container
> docker run --name [Custom Container Name] [Image Name]:[tag]
--name: Any name you want to give. Optional  
