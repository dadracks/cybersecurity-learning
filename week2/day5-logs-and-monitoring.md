# Week 2 Day 5 - Logs & Monitoring 

## Tools & Concepts
- Windows Event Viewer
- Linux system logs

# Window Logs
- Security Log: login activity (Event IDs 4624, 4625)
- System Log: service and OS events 
- Application Log: application behavior 

## Linux Logs 
- /var/log/auth.log for authentication events
- /var/log/syslog for system activity 

## SOC Detection Focus 
- Brute force attempts 
- Abnormal login times
- Unauthorized process execution
- Suspicious patterns across logs

## Key Takeaway
SOC analysts detect threats by correlating log events and identifying abnormal behavior 
patterns rather than relying on single alers.
