# virtualbox-docker
Docker Virtualbox Image

## Usage
> docker run --name rockstor -dit --privileged=true --net=host -v /dev/vboxdrv:/dev/vboxdrv -v /path/to/VirtualBox VMs/:/root/VirtualBox VMs --restart unless-stopped nandordocker/virtualbox /startvm VBoxImageName 
