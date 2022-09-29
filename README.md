# web_manager
```bash
cd ~
docker network create web.io --subnet 172.18.0.0/16
docker network create spack.io --subnet 172.32.0.0/16

git clone https://github.com/Axaxin/web_manager.git
docker-compose -f ~/web_manager/docker-compose.yml up -d
```
