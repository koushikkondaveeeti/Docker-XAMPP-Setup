# XAMPP Setup on Ubuntu

## Objective

Install XAMPP on Ubuntu and configure Apache to run on port **8080**.

## Installation Steps

1. Make the installer executable.

```bash
chmod +x xampp-linux-x64-8.2.12-0-installer.run
```

2. Install XAMPP.

```bash
sudo ./xampp-linux-x64-8.2.12-0-installer.run
```

3. Start XAMPP.

```bash
sudo /opt/lampp/lampp start
```

4. Stop XAMPP.

```bash
sudo /opt/lampp/lampp stop
```

5. Edit the Apache configuration.

```bash
sudo nano /opt/lampp/etc/httpd.conf
```

6. Configure Apache to use port **8080** and restart XAMPP.

## Result

XAMPP was successfully installed and Apache was configured to use port **8080**.
