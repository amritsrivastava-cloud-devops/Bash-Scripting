# Monitoring Disk Usage

## Question:
Our servers frequently face disk space issues. We need a script that monitors disk usage and sends an alert email when disk usage exceeds eighty percent.
How would you implement this?

## Answer:
This can be achieved by writing a shell script that regularly checks disk usage using the df command.
The script compares the current disk usage against a predefined threshold, such as eighty percent.
If the usage crosses this limit, the script automatically sends an alert email to the system administrator using tools like mail or sendmail.
This helps in proactively identifying disk space issues and prevents system failures caused by full disks.
