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
-  Logs → PhilSIEM Collector → SQLite → Detection Engine
↓
Elasticsearch → Kibana
↓
Telegram Alerts
↓
iPhone 📱


## Detection Rules
| Rule | Trigger | Severity |
|------|---------|----------|
| BRUTE_FORCE | 3+ failed passwords in 10 mins | CRITICAL |
| SYN_FLOOD | SYN flood detected | CRITICAL |
| PORT_SCAN | Port scan activity | HIGH |
| AUTH_FAILURE | Authentication failure | HIGH |
| SUDO_FAILURE | Sudo failure detected | HIGH |

## Results
- 9,000+ LinkedIn impressions when published
- Featured by cybersecurity professionals as industry-standard approach
- Validated as sellable product by multiple security experts

- ## Screenshots

### Kibana Dashboard
![Kibana](screenshots/kibana.png)

### Telegram Alerts
![Telegram](screenshots/telegram.png)

### Live Event Stream
![Terminal](screenshots/terminal.png)


## Author
Philip O'Malley | Breaking Into Cyber 🛡️
philsiem.com | LinkedIn: Philip John Omalley
CompTIA Security+ | CREST CPSA

*Breaking Into Cyber — so the hackers can't.*


