# Docker Create Container & Pull & Push image Commands Steps
```bash
docker run -itd --name cont1 ubuntu /bin/bash
docker ps
docker ps -a
docker images
docker exec -it cont1 /bin/bash/
apt update -y
apt install apache2 -y
apt install systenctl -y
systemctl start apache2
systemctl enable apache2
apt install iproute2 -y
apt install iputils-ping -y
docker commit cont1 image1
docker tag image1 kumarnishant7835@/chandan:tag1
docker login
docker push kumarnishant7835@/chandan:tag1
docker rm cont1
docker rmi image1
docker pull kumarnishant7835@/chandan:tag1
docker run -itd --name cont2 kumarnishant7835@/chandan:tag1 /bin/bash/
docker exec -it cont2 /bon/bash/
```
