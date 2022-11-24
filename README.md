[[_TOC_]]


# Introduksjon
E-rapport er et verktøy for oppfølging av [avtaler](https://dev.azure.com/gk-devs/GKCloud/_wiki?pageId=46&friendlyName=Avtale#) mellom to parter (interne parter eller mellom GK og eksterne kunder). Avtalen knyttes mot en [bedrift](https://dev.azure.com/gk-devs/GKCloud/_wiki?pageId=50&friendlyName=Bedrift#).

Til hver avtale knyttes ett eller flere [bygg](https://dev.azure.com/gk-devs/GKCloud/_wiki?pageId=48&friendlyName=Bygg#).

Bygget og avtalen eier sammen en liste med tilstander, kalt [Avvik](/Funksjonell-beskrivelse/E%2Drapport/Avvik). 

```
Eksempel: 
GK har to avtaler med Stortinget:
- Avtale om snømåking
- Avtale om skifting av lyspærer

Under avtale om snømåking registreres avviket "mye snø i natt".
Under avtale om lyspære registreres avviket "lyspære i kantine må skiftes".
``` 

Hvert avvik kan inneholde en eller flere aksjoner. Disse beskriver oppgaver som må utføres.
``` 
Eksempel:
Under avvik "lyspære i kantine må skiftes" registreres følgende aksjoner:
- Bestille 40W lyspære
- Montere lyspære
- Rapportere at feil er utbedret
- Sende faktura
``` 

# Brukere
## Tiltenkte brukere
Verktøyet er tiltenkt fire forskjellige brukerkategorier:
- Brukere som registrerer feil og mangler (ansatt i GK eller hos kunder)
- Brukere som koordinerer aktiviteten (primært GK-ansatte)
- Brukere som utfører aksjoner (primært GK-ansatte)
- Brukere med behov for innsyn (primært eksternt ansatte)

## Pålogging
Brukere kan logge seg på med sin GK-adresse eller utdelt brukernavn og passord. En administrator må først sette nødvendige tilganger.

## Tilgang
Hver bruker blir tildelt ett eller flere selskaper av administrator. Dette styrer hva brukeren har mulighet for å se. 

``` 
Eksempel:
Bruker Arne Olsen har tilgang til bedriftene "Slottet" og "Stortinget"
Bruker Per Andersen har kun tilgang til "Slottet"

Arne Olsen kan se alle avtaler, avvik og aksjoner som er opprettet med Stortinget og Slottet.
Per Andersen kan kun se avtaler, avvik og aksjoner opprettet med Slottet.
``` 
[Tilgangsnivåene](/Funksjonell-beskrivelse/E%2Drapport/Tilgangsnivå) vil styre hvilke muligheter brukeren har til å se, endre, slette og opprette nye aksjoner, avvik og avtaler.

# Arbeidsflyt
## Hva E-rapport IKKE gjør
E-rapport er ikke en kommunikasjonsplattform som skal erstatte epost, telefon og chat. Det er ikke en plattform som vekker deg på morran, prioriterer oppgavene dine eller minner deg på alt du skal ha gjort. E-rapport sender ikke blomster til din svigermor på hennes bursdag.

## Hva E-rapport gjør
E-rapport sin startside viser deg aksjoner og avvik der du er innkoblet. De viktigste sakene kommer øverst. Startsiden viser deg aksjoner du må godkjenne eller utføre, samt tidsfrister som er i ferd med å løpe ut.

Fra startsiden kan du trykke deg inn i dine aktiviteter for å se detaljer og gjøre endringer.
