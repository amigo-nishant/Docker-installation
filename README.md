# Docker-installation

### Docker Installation (AWS Linux Instance) via docker.io

``` bash
sudo apt-get update
sudo apt-get install docker.io -y
sudo apt-get install docker-compose -y
```

### Docker installation via apt repository (Recommended)
1. Install Docker -- https://docs.docker.com/engine/install/ubuntu/

2. Add user to the docker group - sudo usermod -aG docker $USER [ exit and ssh back to to apply the changes. This step is important as it refreshes your session and grants your user the new group permissions]
