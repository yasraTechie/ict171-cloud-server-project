# Server Setup

## Cloud Server

Created an Ubuntu cloud server using DigitalOcean.

* Public IP Address: 134.199.175.47

---

## SSH Connection

Connected to the server using SSH from Windows PowerShell.

```bash
ssh root@134.199.175.47
```

---

## System Update

Updated the server packages using:

```bash
apt update
apt upgrade -y
```

---

## Apache Installation

Installed Apache web server using:

```bash
apt install apache2 -y
```

Started the Apache service using:

```bash
service apache2 start
```

---

## Website Deployment

Edited the default Apache web page directory using:

```bash
nano /var/www/html/index.html
```

Created and deployed a custom cybersecurity portfolio website using HTML and CSS.

The website was tested successfully through the server public IP address.



