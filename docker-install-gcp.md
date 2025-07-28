sudo apt update && sudo apt upgrade -y

## Install Docker
curl -fsSL https://get.docker.com/ | sudo sh

## Tambahkan user ke group docker agar bisa run docker tanpa sudo (optional, but recommended)
sudo usermod -aG docker $USER

## Install Docker Compose
sudo apt install docker-compose -y

## check version
docker --version
docker compose version
