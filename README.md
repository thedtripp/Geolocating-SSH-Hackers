# Geolocating-SSH-Hackers
![Alt Text](Map-Demo.png)

## Intro:
As a system administrator, it's important to secure your servers from unauthorized access. One way hackers try to gain access is through Secure Shell (SSH) logins. To detect and prevent these attacks, consider using geolocation. This technique involves identifying the physical location of an IP address. By geolocating SSH hackers in real time, you can detect when an unauthorized user is attempting to log in and where they are located.

## Methods:
To geolocate SSH hackers in real time, you can use tools like rsyslog and an IP geolocation service. For example, you can use rsyslog to send log data to a Node TCP server, which can then use an IP geolocation service to look up the location of an incoming connection. The server can then store this information in a database like InfluxDB, and you can use a visualization tool like Grafana to create graphs and alerts based on the location data.

## Outcomes:
By integrating these tools into your server's SSH login process, you can automatically detect and block incoming connections from suspicious locations. This can help you track down the perpetrators of SSH attacks and improve the security of your servers.
