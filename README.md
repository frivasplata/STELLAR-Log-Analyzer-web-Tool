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

V0.3.0-build-7
Channel utilization as a Gauge

V0.3.0-build-8
CCI logic improved and using a Gauge

V0.3.0-build-9
Network Events analysis improvements

Refetch logs button fix

V0.3.0-build-10
Tx Power obtained in real time from the 2.4, 5 or 6Ghz radio adapter when using the CCI function

From now on you can change the tx power on the radio adapter for troubleshooting purposes

V0.3.0-build-11
Split screen fullscreen

V0.3.0-build-12
Improved analysis logic

Network anbalysis page can be closed pressing the escape key
