## Referencias
- [CLI docker](https://docs.docker.com/reference/cli/docker/)
- [CLI dockerd](https://docs.docker.com/reference/cli/dockerd/)

## Comandos
- docker version
- systemctl enable docker
- systemctl start docker
- systemctl stop docker
- systemctl status docker
- dockerd / Ctr+C
- ps -ef | grep dockerd
- group add docker
  cat /etc/group | grep docker
  useradd dockeruser
  sudo useradd -s /bin/bash -d /home/dockeruser/ -m -G sudo dockeruser
  passwd dockeruser
  usermod -aG docker dockeruser
- docker ps
