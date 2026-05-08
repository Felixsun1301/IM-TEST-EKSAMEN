# FX Studios – Bookingsystem

Et nettbasert bookingsystem for frisørsalong der kunder kan booke time på nett.

## Om prosjektet
FX Studios er en frisørsalong som trenger en enkel måte for kunder å booke time på nett. Brukeren velger dato og tid, fyller inn kontaktinfo og får en bekreftelse på bookingen.

## Teknologier brukt
- HTML
- CSS
- Python
- Flask
- MariaDB

## Funksjonalitet
- Velg dato og tid
- Fyll inn navn, telefon og e-post
- Bekreftelsesside med oppsummering

## Systemflyt
Bruker → Frontend (HTML/CSS) → Backend (Flask) → Database (MariaDB) → Bekreftelse til bruker

## Sikkerhet
- Parameterisert SQL for å beskytte mot SQL injection
- GDPR: brukeren informeres om hva dataene brukes til, data deles ikke med tredjeparter

## Videre utvikling
- Innlogging for administrator
- E-postbekreftelse til kunde
- HTTPS i produksjon
- Avbestilling og endring av booking

