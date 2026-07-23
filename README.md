# Docker-XAMPP-Setup
# Docker Installation on Windows and Ubuntu with XAMPP Setup on Port 8080

## Objective

This project demonstrates the installation of Docker on both Windows and Ubuntu operating systems. It also includes the installation and configuration of XAMPP with Apache running on port **8080**.

---

## Software Used

- Windows 11
- Ubuntu (VMware)
- Docker Desktop
- Docker Engine
- XAMPP 8.2.12
- Apache Web Server
- Nginx Docker Image

---

## Windows Installation

### Docker

1. Download and install Docker Desktop.
2. Verify installation:

```powershell
docker --version
docker run hello-world
docker ps
docker images
```

### XAMPP

1. Install XAMPP.
2. Open:

```
C:\xampp\apache\conf\httpd.conf
```

3. Change

```
Listen 80
```

to

```
Listen 8080
```

4. Change

```
ServerName localhost:80
```

to

```
ServerName localhost:8080
```

5. Restart Apache.

6. Verify

```
http://localhost:8080
```

---

## Ubuntu Installation

### Install Docker

```bash
sudo apt update
sudo apt install docker.io -y
docker --version
sudo docker run hello-world
```

### Install XAMPP

```bash
chmod +x xampp-linux-x64-8.2.12-0-installer.run
sudo ./xampp-linux-x64-8.2.12-0-installer.run
```

### Start XAMPP

```bash
sudo /opt/lampp/lampp start
```

### Stop XAMPP

```bash
sudo /opt/lampp/lampp stop
```

### Run Nginx Container

```bash
sudo docker run -d -p 8080:80 --name webserver nginx
```

### Verify

```bash
sudo docker ps
```

---

## Screenshots

- Docker Desktop
- Docker Hello World
- XAMPP Control Panel
- Apache running on Port 8080
- Ubuntu Docker Installation
- Ubuntu XAMPP Setup
- Nginx Welcome Page

---

## Author

**Koushik Kondaveeti**
