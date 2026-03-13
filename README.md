# Automated Server Maintenance with Ansible

## Project Overview
This project automates routine Linux server maintenance tasks using Ansible.  
It performs system checks, backups, scheduled reboots, and logging to ensure reliable and secure server operations.

The automation runs weekly using a cron job and reduces the need for manual intervention.

---

## Features

- Dynamic Inventory Management
- Pre-Maintenance System Checks
- Automated Backup Creation
- Conditional Server Reboot
- Maintenance Logging
- Email Notification Support
- Weekly Cron Job Scheduling

---

## Architecture

Control Node:
- Ansible installed
- Runs playbooks

Managed Nodes:
- Linux servers managed through SSH

Communication:
- SSH key-based authentication

---

## Project Structure

```
ansible-server-maintenance/
│
├── inventory.ini
├── maintenance.yml
├── README.md
```

---

## Requirements

- Linux system
- Ansible installed
- SSH access to target servers
- Sudo privileges on managed nodes

---


## Example Tasks Performed

- Disk usage check
- System updates
- Backup important files
- Reboot server if required
- Store logs for maintenance operations

---

## Benefits

- Reduces manual maintenance work
- Improves system reliability
- Ensures regular backups
- Automates routine server operations

---

## Future Improvements

- Slack notifications
- Monitoring integration
- Docker container maintenance
- Integration with CI/CD pipelines

---

## Author
Hariom Tarakh  
