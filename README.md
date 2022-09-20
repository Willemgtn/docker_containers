# How to install docker and docker-compose on the raspberry pi
```
sudo apt install docker docker-compose
or
curl -fsSL <https://get.docker.com> -o get-docker.sh
sh get-docker.sh
sudo systemctl enable docker
sudo usermod -aG docker {username}
sudo reboot

create docker-compose.yml and
docker-compose up -d
docker-compose down
docker-compose pause|unpause

docker ps
docker port
```
