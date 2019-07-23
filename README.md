# virtualbox-docker

Docker Virtualbox Image

## Usage

> docker run --name ImageName -dit --privileged=true --net=host -v /dev/vboxdrv:/dev/vboxdrv -v /path/to/VirtualBox VMs/:/root/VirtualBox VMs --restart unless-stopped nandordocker/virtualbox /startvm VBoxImageName 

## Details

I use this image to run RockStor NAS inside a docker container but you can adapt it to whatever image you want to run.
