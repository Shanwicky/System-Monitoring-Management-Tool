# IT Support System

A comprehensive CLI-based system management and monitoring tool for IT professionals.

## Features

### 1. System Monitoring
- Real-time CPU, RAM, and disk usage monitoring
- Process monitoring and management
- Network statistics
- System health scoring
- Full system reports

### 2. Network Tools
- Internet speed testing
- Port scanning
- WiFi network analysis
- DNS resolution testing
- Bandwidth monitoring

### 3. Security Audit
- Comprehensive security scanning
- Firewall status checking
- Open port detection
- Antivirus verification
- Security recommendations

### 4. User Management
- List system users
- Create new user accounts
- Delete user accounts
- Reset passwords
- Lock/unlock accounts

### 5. System Cleanup
- Clean temporary files
- Clear browser cache
- Empty recycle bin/trash
- Clean package manager cache
- Remove old log files
- View disk space usage

### 6. Backup Operations
- Backup directories
- Backup specific files
- Database backup
- Restore from backup
- List and manage backups
- Windows registry backup

### 7. Password Generator
- Generate secure passwords
- Check password strength
- Generate random PINs

### 8. Alert Management
- View active alerts
- Alert history
- Resolve alerts
- Alert statistics

### 9. Reports
- Generate system reports
- Generate alert reports
- List and manage reports

### 10. Database Operations
- Backup database
- View statistics
- Cleanup old data
- Optimize database
- View action log

## Installation

1. Clone or download the repository
2. Install dependencies (optional):
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Requirements

- Python 3.7+
- Windows or Linux operating system
- Administrator/root privileges (for some features)

## Usage

Launch the application and use the numbered menu to navigate:

```
1. System Monitoring
2. Network Tools
3. Security Audit
4. User Management
5. System Cleanup
6. Backup Operations
7. Password Generator
8. Alert Management
9. Reports
10. Database Operations
0. Exit
```

## Database

The system uses SQLite for data storage:
- `it_support.db` - Main database file
- Stores metrics, alerts, user actions, and more
- Automatic backup functionality included

## Reports

Generated reports are saved in the `reports/` directory:
- System reports (TXT format)
- Alert reports (TXT format)
- Security audit reports (TXT format)

## Backups

Backups are stored in the `backups/` directory:
- Directory backups (ZIP/TAR.GZ)
- File backups (ZIP)
- Database backups (.db)
- Registry backups (Windows)

## Security

- All user actions are logged
- Database encryption not included (use OS-level encryption)
- Passwords are never stored in plain text

## License

MIT License - Free for personal and commercial use

## Support

For issues or feature requests, please create an issue in the repository.
