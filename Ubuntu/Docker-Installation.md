# Docker Installation on Ubuntu

## Objective

Install Docker Engine on Ubuntu and verify that it is working correctly.

## Installation Steps

1. Update the package list.

```bash
sudo apt update
```

2. Install Docker.

```bash
sudo apt install docker.io -y
```

3. Verify Docker installation.

```bash
docker --version
```

4. Run the Hello World container.

```bash
sudo docker run hello-world
```

5. Check running containers.

```bash
sudo docker ps
```

6. Run an Nginx container on port 8080.

```bash
sudo docker run -d -p 8080:80 --name webserver nginx
```

## Result

Docker was installed successfully and the Nginx container was running on port **8080**.
