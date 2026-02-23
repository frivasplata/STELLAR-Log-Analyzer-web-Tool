# STELLAR-Log-Analyzer-Web-Tool
Stellar Log analyzer is a real-time wireless diagnostics and RF analysis platform  designed specifically for senior wireless engineers, NOC teams, and escalation specialists.  The system enables deep inspection of WiFi client lifecycle events, RF channel utilization,  and other features.

Install:
docker run -d -p 3005:3005 --restart always --name log-viewer frivasplata/log-viewer:latest

Update:
docker pull frivasplata/log-viewer:latest
docker stop log-viewer
docker rm log-viewer
docker run -d -p 3005:3005 --restart always --name log-viewer frivasplata/log-viewer:latest
