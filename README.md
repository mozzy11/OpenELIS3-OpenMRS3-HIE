# OpenELIS3-OpenMRS3-HIE SETUP

Spin up the services

```
docker-compose up -d
```

Acces the services at 

| Instance  |     URL       | credentials (user : password)|
|---------- |:-------------:|------:                       |
| OpenMRS3   |  https://localhost/openmrs/spa | admin : Admin123 |
| OpenHIM   |    http://localhost:9000/  |  root@openhim.org : admin |
| OpenELIS3 | https://localhost/ |    admin : adminADMIN!| 

## Instructions 
1. Add the necesary Lab Unit permisions to the User      
Go To `Admin -> User Management -> Select User -> Under "Roles" ,Choose "ALL Lab Units" and select  "All Permissions"`

2. Enable Importing electronic orders       
Go To `Admin -> Order Entry Configuration -> Select "external orders" -> Click "Modify" -> select "True"`

3. Add the Right Test Catalogue ie tests with `Loinc Codes`

see [more](https://i-tech-uw.github.io/healthinformationexchange/lis-workflows/lis-workflows.html#tutorial-lab-order-communication-between-openmrs-and-openelis) for the EMR-LIS communication
