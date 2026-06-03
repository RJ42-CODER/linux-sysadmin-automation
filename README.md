# Linux Sysadmin Automation Kit

## Overview

A Linux server monitoring script written in Bash that performs automated health checks and stores reports in a log file.

## Features

- Disk Usage Monitoring
- RAM Usage Monitoring
- System Uptime Monitoring
- Top Memory Consuming Processes
- Automated Logging
- Hourly Execution using Cron

## Project Structure

linux-sysadmin-kit/
├── health_check.sh
├── logs/
│   └── health_report.log
└── README.md

## Run Manually

```bash
./health_check.sh
