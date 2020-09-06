# VLMCSD for Docker

Deploy vlmcsd service on Docker container

```bash
git clone https://github.com/yuyangame/vlmcsd-docker.git vlmcsd
cd vlmcsd

# Use docker-compose service
docker-compose up -d

# or docker build image
docker build -t vlmcsd .
docker run -idt -p 1688:1688 vlmcsd
```
