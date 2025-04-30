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
| OpenHIM   |    http://localhost:9000/  |  root@openhim.org : openhim-passoword |
| SHR      | https://localhost:8090/fhir  |   | 

## Instructions 

1. Login in to OpenHIM , Go To Import/Export and manually inport the [Config file here](./volumes/openhim/configs/openhim-config.json)

1. Ensure Add the Right Test Catalogue ie tests with `Loinc Codes`

see [more](https://i-tech-uw.github.io/healthinformationexchange/lis-workflows/lis-workflows.html#tutorial-lab-order-communication-between-openmrs-and-openelis) for the EMR-LIS communication
