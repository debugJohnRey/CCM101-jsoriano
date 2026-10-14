# Checkpoint 6 - Technical Documentation

## 1. Automation Script
```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

# Create the backup directory if it does not exist
mkdir -p $BACKUP_DIR

# Compress the source directory into a tarball (.tar.gz)
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR

echo "Backup completed successfully at $TIMESTAMP!"
```

## 2. File Permissions
The command `chmod +x backup.sh` modifies the file permissions to make the script executable[cite: 3]. By default, Linux protects the system by preventing text files from running as programs[cite: 3]. This command explicitly grants the execution rights needed to run the script[cite: 3].

## 3. Cron Schedule Breakdown
The cron expression `0 2 * * * /root/backup.sh` tells the system to run the backup script every night at exactly 2:00 AM[cite: 4]. Here is the breakdown of the five time-fields[cite: 4]:
* **Minute (0):** Runs at the 0th minute.
* **Hour (2):** Runs at 2:00 AM.
* **Day of Month (*):** Runs every day of the month.
* **Month (*):** Runs every month.
* **Day of Week (*):** Runs every day of the week.