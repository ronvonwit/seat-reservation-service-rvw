# seat-reservation-service-rvw
Component behorende bij Ticket Booking Camunda demo opstelling, verantwoordelijk voor de reservering van een plek. Abonneert zich op events van het Camunda Ticket Booking proces en communiceert middels gRPC.

## Code gedeployed middels GitHub Actions
* Gebruikte Secrets: EC2 Instance public IP en EC2 SSH key

## Aanmaken instanties EC2 Linux 2
* geen bijzondere security rechten nodig.

## Installation Amazon EC2 Linux 2
* sudo yum update
* sudo curl -sL https://rpm.nodesource.com/setup_14.x | sudo bash -
* sudo yum install -y nodejs
* sudo npm install -g typescript
* sudo npm install -g ts-node

## Run NodeJs Fake Seat Reservation Service

If you want to understand the code, please have a look into this get started tutorial: https://github.com/camunda/camunda-platform-get-started/tree/main/nodejs

```
cd fake-services-nodejs
npm update
ts-node src/app.ts
```
