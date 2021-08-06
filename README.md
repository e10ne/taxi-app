# Taxi-app

<p>We gaan een app schrijven voor een taxi-bedrijf. Dit bedrijf wil zijn taxi's beheren en aansturen via de app.
<i>Uiteindelijk is dit alleen mogelijk wanneer je bent ingelogd, maar het inlog systeem voegen we als laatste toe.</i></p>

## views

### View 1: Landing page
- Lijst met al je taxi's
- Als je op een taxi drukt, ga je naar view 2 -> update die taxi.
- Optie om nieuwe taxi's aan te maken. Dan verschijnt een modal.
- Optie om naar View 3 (locations) te gaan.

### View 2: Taxi beheren
- Wanneer je op een taxi in de lijst klikt, kun je de taxi gegevens aanpassen, of de taxi verwijderen.

### View 3 Locations:
- Lijst met al je locations
- Als je op een location drukt, ga je naar view 4 -> update die location.
- Optie om nieuwe locations aan te maken. Dan verschijnt een modal.

### View 4: Location beheren
- Wanneer je op een location in de lijst klikt, kun je de location gegevens aanpassen, of de taxi verwijderen.

## User Stories

### As: admin
- <b>Want</b>: al mijn taxi's/locations in een lijst zien.
- <b>Why</b>: zodat ik in 1 opslag overzich heb over mijn taxi's/locations.

### As: admin
- <b>Want</b>: door op een taxi/location in de lijst te klikken, de mogelijkheid krijgen deze aan te passen.
- <b>Why</b>: zodat ik makkelijk elke taxi/location kan beheren.

### As: admin
- <b>Want</b>: door op een knopje te drukken, wil ik de mogelijkheid krijgen een taxi/location toe te voegen.
- <i>Bij het aanmaken van een taxi. Is de location = station/base, mileage = 0, gas = 10. Je voert dus alleen de licence pate in.</i>
- <b>Why</b>: zodat ik makkelijk taxi's/locations kan aanpassen.

### As: Admin
- <b>Want</b>: wanneer ik de location van een taxi heb aangepast:
- <i>Wordt het verschil in values van de locaties bij de mileage opgeteld.</i>
- <i>Wordt het 10% van het verschil in values van de locaties bij de gass afgetrokken.</i>
- <b>Why</b>: zodat mileages en gas gelijk updaten.

## Classes

### Taxi class
- id
- location
- licence plate
- mileage
- gas

### Location class
- id
- name
- value