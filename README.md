Setup and Install Docker
Go to to https://docs.docker.com
On left Panel - go to Docker Engine --> Install --> Ubuntu
First Uninstall old versions using below command
for pkg in docker.io docker-doc docker-compose docker-compose-v2 podman-docker containerd runc; do sudo apt-get remove $pkg; done
Then go to - Install using the convenience script
Install using below commands
$ curl -fsSL https://get.docker.com -o get-docker.sh
$ sudo sh ./get-docker.sh
$ sudo docker version
Now go to hub.docker.com
Search for Whalesay image
Copy the below given command
$ docker run docker/whalesay cowsay Hello-World!
