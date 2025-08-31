# Canary_File_Monitoring_System
This project is a security tool designed to detect insider threats and unauthorized file access within an organization.
It uses a layered monitoring system with three Python scripts: agent_monitor_backup.py, agent_monitor.py, and canary_file_monitoring.py. The system creates and tracks decoy files (file1.txt, file2.zip, file3.csv) embedded with trap links to lure potential intruders. It monitors these files for access, modification, deletion/movement and sends email alerts when suspicious activities, such as file openings or link clicks, are detected. Additionally, it ensures the integrity of the monitoring scripts themselves by alerting if they are deleted, with all activities logged and displayed on a web dashboard for real-time monitoring.
___________________________________________________________________
The project is currently under progress. Contributions and feedback are welcome to improve the system.

### Flow chart
![flow_diagram](https://github.com/user-attachments/assets/d7101d54-9ade-4414-90ba-b9a3507954db)

### Sample Dashboard
<img width="1898" height="761" alt="Screenshot 2025-08-31 214420" src="https://github.com/user-attachments/assets/cfaecf47-c318-4f0c-a0c5-3ce74bb7edda" />


### Email Alerts
<img width="879" height="610" alt="Screenshot 2025-08-31 215144" src="https://github.com/user-attachments/assets/343c9fa7-6a3f-4393-b919-82452f207b8c" />
