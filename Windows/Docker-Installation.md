# Docker Installation on Windows

## Objective
Install Docker Desktop on Windows and verify the installation.

## Prerequisites
- Windows 10/11
- Internet connection

## Installation Steps

1. Download Docker Desktop from:
   https://www.docker.com/products/docker-desktop/

2. Run the installer.

3. Restart the computer if prompted.

4. Open Docker Desktop.

## Verification

Open Command Prompt or PowerShell and run:

```powershell
docker --version
docker run hello-world
docker ps
docker images
```

If the `hello-world` container runs successfully, Docker has been installed correctly.
