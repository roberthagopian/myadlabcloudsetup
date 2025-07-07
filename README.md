To begin I will be spinning up the 3 servers in the cloud. 2 windows machines, One being a domain controller and one being the test machine. I also deployed a ubuntu server and as noted in the diagram that one is going to be my splunk server.

![alt text](https://i.imgur.com/0nzYf5R.png)

After getting these up and running I made sure to create some firewall rules so only I can access these. As you can see below I made them IP based to my machine - 1 for SSH and 1 for RDP.

![alt text](https://i.imgur.com/iRgLotj.jpeg)

After some troubleshooting, I set some static ips for the VPC NICs and things are ready to go.
