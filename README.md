# FX Studios  - 

FX Studios – Bookingsystem
Et nettbasert bookingsystem for frisørsalong, der kunder kan velge dato, tid og fylle inn kontaktinformasjon for å bestille time.

## Om prosjektet
FX Studios er en frisørsalong som trenger en enkel og oversiktlig måte for kunder å booke time på nett. Systemet er bygget som en trinnvis bookingflyt der brukeren velger dato og tid, fyller inn navn, telefonnummer og e-post, og til slutt får en bekreftelse på bookingen.

## Teknologier brukt:
**HTML**\
**CSS**\
**Python**\
**Flask**\
**MariaDB** - enkel databaseløsning for lagring av bookinger

## Funksjonalitet:
Velg ønsket dato fra ukeskalender
Velg ledig tidspunkt (opptatte tider vises som utilgjengelige)
Fyll inn kontaktinformasjon (navn, telefon, e-post)
Bekreftelsesside med oppsummering av bookingen
Mulighet for å starte ny booking


## Systemflyt:
Bruker (klient)
    ↓ sender forespørsel via nettleser
Frontend (HTML/CSS/JS)
    ↓ sender data til backend
Backend (Flask)
    ↓ lagrer og henter data
Database (MariaDB)
    ↓ returnerer bekreftelse
Bruker får bekreftelse


## Sikkerhet:
SQL injection kan føre til datatap og uautorisert tilgang - et tiltak kan være parameterisert SQL (skiller kode fra inndata).
**GDPR**


## Forbredninger?
**Vipps** - Jeg vil at (client) skal kunne logge inn/lage bruker direkte med vipps, og dermed slippe å fylle det inn manuelt. 


