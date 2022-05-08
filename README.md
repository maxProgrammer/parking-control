<h1>parking-control</h1>

> Status: Completed ✅

### It's a REST API responsible for controlling the parking spot of an apartment condominium.
<h1 align="center">
  <img alt="Readme" title="Readme" src="./github/Readme-gif.gif"/>
</h1>

## Fields of ParkingSpotModel are:
+ id
+ parkingSportNumber
+ licensePlareCar
+ brandCar
+ modelCar
+ colorCar
+ registrationDate
+ responsibleName
+ apartment
+ block

## Features
This API has only a feature that allows a parking spot CRUD.

## Business Rules
The user can't park in three situations:
+ The LicencePlateCar is already in use.
+ The Parking spot is alredy in use.
+ The number of apartment/block is already in use.

## Technologies
+ Java 11
+ Spring Boot
+ Maven
+ PostgreSQL

## Starters
+ Spring WEB
+ Spring Data JPA
+ Lombok
+ Spring Boot DevTools
+ Validation
+ PostgreSQL Driver
+ Swagger UI

## Patterns
+ MVC
+ IOC
+ DTO

