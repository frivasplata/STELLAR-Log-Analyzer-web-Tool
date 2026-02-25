# STELLAR-Log-Analyzer-Web-Tool
Stellar Log analyzer is a real-time wireless diagnostics and RF analysis platform  designed specifically for senior wireless engineers, NOC teams, and escalation specialists.  The system enables deep inspection of WiFi client lifecycle events, RF channel utilization,  and other features.

Install:
docker run -d -p 3005:3005 --restart always --name log-viewer frivasplata/log-viewer:latest

Update:

docker pull frivasplata/log-viewer:latest

docker stop log-viewer

docker rm log-viewer

docker run -d -p 3005:3005 --restart always --name log-viewer frivasplata/log-viewer:latest


Changes or Improvements

V0.3.0-build-3
Differentiating Radius Authentication than Radius Accounting

V0.3.0-build-4
Differentiating 4-Way-Handshake messages 1/1 to 1/4

V0.3.0-build-5
Analyze both Aps button added

V0.3.0-build-6
Time elapsed between Flows is calculated and shown
