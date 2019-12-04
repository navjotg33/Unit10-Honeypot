# Unit10-Honeypot
Unit 10 Honeypot Assignment

Deployed Honeypot:
  Dionaea over HTTP
  
Issues encountered:
  1. I let the honeypot run for about 10 days before I decided to export the log.  I was unable to access the web page with the IP from the GCP external IP, and I couldn't ssh into the console either.  I restarted the console and honeypot after messing around with ssh settings and still couldn't get in.  The main page display with basic info of total attacks in the past 24 hours as well as top 5 attacking IPs and other info was blank and didn't actually display anything.  Luckily the logs of the past ~3 million logged attacks was still there and I could export it.
  2. Github has a file upload size limit of 25 mb, so I couldn't upload the full ~1 gb of logged data and had to cut it down to size.

Summary:
  Total attacks over ~10 days came out to over 3 million.  Can't grab information from mhn-admin page for number of malware samples since the page kind of died after restarting the instances, as mentioned above in issues.
