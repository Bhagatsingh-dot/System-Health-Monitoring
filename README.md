📊 System Health Monitoring Script

📌 Overview

The System Health Monitoring script provides real-time information about CPU usage, memory usage, disk usage, logged-in users, and running processes. It helps system administrators monitor critical system metrics efficiently.

⚡ Features

Displays CPU Usage (Top 2 processes consuming the most CPU)

Displays Memory Usage (Total, Used, and Free memory)

Displays Disk Usage (All mounted disks)

Lists Currently Logged-in Users

Shows Top Running Processes

Sends Email Alerts with system status

🚀 Prerequisites

Ensure you have the following installed on your Linux system:

Bash (default in Linux)

mailx (for email alerts)

Postfix (configured for sending emails)

cron (for scheduling the script)

📂 Installation

Clone the repository:

git clone https://github.com/Bhagatsingh-dot/System-Health-Monitoring

Navigate to the script directory:

cd PS_monitoring

Give execution permissions to the script:

chmod +x system_health_monitor.sh

🛠️ Usage

Run the script manually:

./system_health_monitor.sh

Or schedule it using cron to run at regular intervals:

Open crontab:

crontab -e

Add a cron job (Example: Runs every 5 minutes):

*/5 * * * * /path/to/system-health-monitoring.sh | mail -s "System Health Report" your-email@example.com

📧 Contact

🌐 GitHub Issues: Submit an Issue📩 Email: b0900075@gmail.com

📜 License

This project is licensed under the MIT License – feel free to use and modify! 🎯
