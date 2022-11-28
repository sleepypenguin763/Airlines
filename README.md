## What is this
This make a virtual REST API server on GitHub repository.
By analyzing JSON files, the script makes directories and some files.
User can access datas of JSON file as if REST API server


## Directory Setup
```
main
├── aircrafts
│   ├── Folder name: First 3 character of ICAO aircraft number
|        ├── Folder name: ICAO aircraft number
|               ├── AirlineCode ── index.html
|               ├── ICAO ── index.html
|               ├── IsPrivateOperator ── index.html
|               ├── Manufacturer ── index.html
|               ├── ManufacturerAndModel ── index.html
|               ├── Model ── index.html
|               ├── ModelIcao ── index.html
|               ├── Operator ── index.html
|               ├── Registration ── index.html
|               ├── SerialNumber ── index.html
|               ├── YearBuilt ── index.html
|               ├── index.html
|        ├── index.html
├── airlines
│   ├── Folder name: ICAO airline code
|        ├── CharterFlightPattern ── index.html
|        ├── Code ── index.html
|        ├── IATA ── index.html
|        ├── ICAO ── index.html
|        ├── Name ── index.html
|        ├── PositioningFlightPattern ── index.html
|        ├── index.html
│   ├── index.html
├── airports
│   ├── Folder name: First 2 character of ICAO airport code
|        ├── Folder name: ICAO airport code
|               ├── AltitudeFeet ── index.html
|               ├── Code ── index.html
|               ├── CountryISO2 ── index.html
|               ├── IATA ── index.html
|               ├── ICAO ── index.html
|               ├── Latitude ── index.html
|               ├── Location ── index.html
|               ├── Logitude ── index.html
|               ├── Name ── index.html
|               ├── index.html
|        ├── index.html
├── countries
│   ├── Folder name: ISO2 country code
|        ├── ISO ── index.html
|        ├── Name ── index.html
|        ├── index.html
│   ├── index.html
```

|  data you want  |  REST API URL  |
| ---- | ---- |
|  Aircraft Data[First_Three_ICAO=00A]   |  https://sleepypenguin763.github.io/Airlines/aircrafts/00A/  |
|  Aircraft Data[ICAO=00AE3A]   |  https://sleepypenguin763.github.io/Airlines/aircrafts/00A/00AE3A  |
|  Airline Data   |  https://sleepypenguin763.github.io/Airlines/airlines/  |
|  Airline Data[Code=ANA]   |  https://sleepypenguin763.github.io/Airlines/airlines/ANA/  |
|  Airport Data[First_Two_ICAO=KL]   |  https://sleepypenguin763.github.io/Airlines/airports/KL/  |
|  Airport Data[ICAO=KLAX]   |  https://sleepypenguin763.github.io/Airlines/airports/KL/KLAX  |
|  Country Data   |  https://sleepypenguin763.github.io/Airlines/countries/  |
|  Country Data[ISO2=JP]   |  https://sleepypenguin763.github.io/Airlines/countries/JP  |

Note: Please view [this repo](https://github.com/sleepypenguin763/Flight-Routes/tree/main) to get the route information given a callsign.
