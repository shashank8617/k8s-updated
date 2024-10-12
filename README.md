```bash
yum install git -y
yum install docker -y
systemctl start docker
systemctl status docker
sudo curl -L "https://github.com/docker/compose/releases/download/v2.20.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
git clone https://github.com/shashank8617/k8s-updated.git
cd k8s-updated
docker-compose up --build
```

