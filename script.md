# Backup Script

## Purpose

This script creates a compressed backup of the website files stored in the Apache web directory.

## Script

```bash
#!/bin/bash

tar -czf website-backup.tar.gz /var/www/html

echo "Website backup completed successfully"
```

## Usage

Run the script using:

```bash
./backup.sh
```

## Outcome

The script generates a compressed backup file named:

```plaintext
website-backup.tar.gz
```

