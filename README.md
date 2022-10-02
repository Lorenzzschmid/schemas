# Mongoose Schemas

This assignment will allow to practise building mongoose validation schemas

Schemas allow you to set rules for the type of data you will want to save in your collection

> Difficulty level: Beginner 🍵

## Tasks

### Task 1 - Installing Mongoose

Install mongoose
- `npm i mongoose`

### Task 2 - Writing a "Diagnosis" Schema

Consider the following raw `diagnosis` data:

```text
patientReference: 334bc0bdfc13ae6e09700889
diagnosisCode: T420X1
procedureCode: 1821
description: Poisoning by hydantoin derivatives accidental (unintentional)
```

- Write a Mongoose schema which correctly reflects this data

### Task 3 - Writing a "Car" Schema

Consider the following raw `car` data:

```text
ownerReference: 618bc0bdfc13ae6e07000640
vin: 1GYS4CEF0DR758251
manufacturer: Volvo
model: C940
year: 1994
```

- Write a Mongoose schema which correctly reflects this data

### Task 4 - Writing an "Order" Schema

Consider the following raw `order` data:

```text
orderReference: 618bbec2fc13ae6de4000433
cardNumber: 3576146186799481
cardType: jcb
value: 216293
currency: Euro
department: Sports
validated: true
```

### Task 5 - Writing a "User" Schema

Consider the following raw `user` data:

```text
id: 1
username: cscamaden0
firstname: Cale
lastname: Scamaden
email: cscamaden0@ezinearticles.com
confirmed: false
ip: 78.16.63.95
avatar: https://robohash.org/voluptatesuntrepudiandae.png?size=50x50&set=set1
dateOfBirth: 1628972562000
```

- Write a Mongoose schema which correctly reflects this data

### Task 6 - Writing a "Location" Schema

Consider the following raw `location` data:

```text
userReference: 413tted1fg09ae6de7000211
phone: 540-870-6446
street: Ridge Oak
streetNumber: 39760
postalCode: 2495-555
state: Santarém
city: Fátima
country: Portugal
latitude: 39.6208162
longitude: -8.6563967
timeZone: Europe/Lisbon
ip: 118.157.238.128/16
```

- Write a Mongoose schema which correctly reflects this data
