# SSL Configuration

## HTTPS Setup

SSL/TLS was configured using Certbot and Let's Encrypt.

## Installation

Installed Certbot using:

```bash id="r3u0y2"
apt install certbot python3-certbot-apache -y
```

## SSL Certificate Configuration

Configured the SSL certificate using:

```bash id="jqewlq"
certbot --apache
```

HTTPS redirection was enabled to automatically redirect HTTP traffic to HTTPS.

## Result

The website is now securely accessible using:

```plaintext id="8d8wfg"
https://yasracyber.online
```

A secure SSL lock icon is displayed in the browser.


