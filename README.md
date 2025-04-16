# OpenELIS3-OpenMRS3-HIE SETUP

Spin up the services

```
docker-compose up -d
```

Acces the services at 

| Instance  |     URL       | credentials (user : password)|
|---------- |:-------------:|------:                       |
| OpenMRS3   |  http://localhost/openmrs/spa | admin : Admin123 |
| OpenELIS3 | https://localhost/ |    admin : adminADMIN!| 
| SHR      | https://localhost:8090/fhir  |   | 
<!-- | OpenHIM   |    http://localhost:9000/  |  root@openhim.org : admin | -->

## Instructions 
1. Enable Importing electronic orders       
On the new UI , go to
 `Admin -> General Configurations ->  Order Entry Configuration -> Select "external orders" -> Click "Modify" -> select "True"`

1. Add the Right Test Catalogue ie tests with `Loinc Codes`

see [more](https://i-tech-uw.github.io/healthinformationexchange/lis-workflows/lis-workflows.html#tutorial-lab-order-communication-between-openmrs-and-openelis) for the EMR-LIS communication
