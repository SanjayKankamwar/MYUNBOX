# Log Pipeline Project


Install Docker & Git On EC2 instance
sudo apt update && sudo apt install -y docker.io git
sudo usermod -aG docker $USER && newgrp docker

Clone repo & deploy
git clone https://github.com/SanjayKankamwar/MYUNBOX.git
cd MYUNBOX
docker-compose up -d
