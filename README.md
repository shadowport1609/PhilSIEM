# PhilSIEM 🛡️
### A Home-Built Security Information & Event Management System

Built by Philip O'Malley as part of a cybersecurity career transition 
from Jarrow, North East England.

## What It Does
- Collects and parses security logs from multiple sources
- Detects brute force attacks, SYN floods, port scans and auth failures
- Stores events in SQLite database
- Visualises threats in real-time Kibana dashboard
- Sends instant Telegram alerts to phone when threats detected

## Tech Stack
- Python 3 — core detection engine
- Elasticsearch + Kibana — ELK Stack SIEM
- Docker — containerised deployment
- SQLite — event storage
- Telegram Bot API — mobile alerting
- Filebeat — log ingestion

## Features
- Real-time threat detection
- Live Kibana dashboard with severity breakdowns
- Instant mobile alerts via Telegram
- 680+ security events logged
- Brute force, SYN flood, port scan detection

## Architecture

