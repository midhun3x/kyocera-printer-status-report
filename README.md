# Kyocera Printer Status Report Tool

A Python-based SNMP monitoring script that collects Kyocera printer information,
generates an HTML status report, logs the output, and sends it via email.

## Features
- SNMP (v2c) based data collection
- Printer reachability check (ping)
- HTML formatted report
- Daily log files
- Email notifications with retry logic
- XML-based configuration

## Files
- printer_report.py → main script
- config.xml → printer & SMTP settings
- logs/ → auto-created daily logs

## Run
python printer_report.py
