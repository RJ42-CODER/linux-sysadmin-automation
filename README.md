# Linux Sysadmin Automation Kit

## Overview
A Bash script that performs automated server health checks and stores formatted reports in a log file.

## Features
- Disk space monitoring
- RAM usage tracking
- Running services check
- Formatted log report output
- Automated hourly execution via cron job

## Skills Applied
`Linux` `Bash` `Cron` `Logging`

## Usage

### Run manually
```bash
bash health_check.sh
```

### Set up cron job (runs every hour)
```bash
crontab -e
```
Add this line:
