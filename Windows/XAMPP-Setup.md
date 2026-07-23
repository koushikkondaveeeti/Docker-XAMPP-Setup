# XAMPP Setup on Windows

## Objective

Install XAMPP on Windows and configure Apache to run on port **8080**.

## Installation Steps

1. Download XAMPP from:
   https://www.apachefriends.org/

2. Install XAMPP.

3. Open the XAMPP Control Panel.

4. Stop Apache if it is running.

5. Open the file:

```
C:\xampp\apache\conf\httpd.conf
```

6. Change

```
Listen 80
```

to

```
Listen 8080
```

7. Change

```
ServerName localhost:80
```

to

```
ServerName localhost:8080
```

8. Save the file.

9. Start Apache.

10. Open a browser and visit:

```
http://localhost:8080
```

## Result

Apache was successfully configured to run on port **8080**.
