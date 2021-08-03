# Taxi-app

<p>We gaan een app schrijven voor een taxi-bedrijf. Dit bedrijf wil zijn taxi's beheren en aansturen via de app.
<i>Uiteindelijk is dit alleen mogelijk wanneer je bent ingelogd, maar het inlog systeem voegen we als laatste toe.</i></p>

## views

### View 1: Landing page
- Lijst met al je taxi's
- Optie om nieuwe taxi's aan te maken
- Optie om naar View 3 te gaan.

### View 2: Taxi beheren
- Wanneer je op een taxi in de lijst klikt, ga je naar je 2de view, waar je je taxi gegevens kan aanpassen, of de taxi verwijderen.

### View 3:
- Is een kaart waar je visueel kan zien waar je taxi's zich bevinden op het moment.
- Wanneer je op een taxi klikt ga je terug naar view 2, waar je deze taxi weer kan aanpassen.

## Classes

### Taxi class
- id
- taxinummer
- kenteken
- kilometerstand
- benzinestand

### User class(admin login)
- id
- username / e-mailadres
- password