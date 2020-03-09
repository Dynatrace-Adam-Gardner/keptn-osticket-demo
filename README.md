# Keptn OS Ticket Service

## Create OSTicket MAchine

* Create a `t3.small Ubuntu Server 18.04` EC2 instance. Allow SSH and HTTP traffic.
* SSH into the instance and run:
```
cd ~
wget https://raw.githubusercontent.com/Dynatrace-Adam-Gardner/keptn-osticket-service/master/osTicketSetup.sh
chmod +x osTicketSetup.sh
./osTicketSetup.sh
````
