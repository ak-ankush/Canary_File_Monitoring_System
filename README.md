# Canary_File_Monitoring_System
This project is a security tool designed to detect insider threats and unauthorized file access within an organization.
It uses a layered monitoring system with three Python scripts: agent_monitor_backup.py, agent_monitor.py, and canary_file_monitoring.py. The system creates and tracks decoy files (file1.txt, file2.zip, file3.csv) embedded with trap links to lure potential intruders. It monitors these files for access, modification, deletion/movement and sends email alerts when suspicious activities, such as file openings or link clicks, are detected. Additionally, it ensures the integrity of the monitoring scripts themselves by alerting if they are deleted, with all activities logged and displayed on a web dashboard for real-time monitoring.
___________________________________________________________________
The project is currently under progress. Contributions and feedback are welcome to improve the system.

### Flow chart
![diagram](https://github.com/user-attachments/assets/1e9689f9-3f88-40a7-87f0-3ffce3fab100)
