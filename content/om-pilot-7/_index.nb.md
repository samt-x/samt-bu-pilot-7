---
id: f8256f11-4edc-440a-b6cb-56ddb29e9d02
title: Om pilot 7
weight: 10
lastmod: 2026-10-29T21:17:36+01:00
last_editor: Erik Hagen

---
*Siden bygger på planutkastet «Gjennomføring av Pilot 7», versjon 0.1. Mye er ikke avklart ennå, og det står da på siden.*

## INNLEDNING

Dette er en beskrivelse av plan for gjennomføring av pilot 7 – Digital dialog mellom barnehage/skole og hjemmet. Selv om planen beskriver gjennomføringen som en fasedreven prosess, forutsettes det at vi arbeider iterativt, der enkelte faser gjentas ved behov.

Prosjekteier er Digitaliseringsdirektoratet (Digdir). Piloten ledes av Christiane Fröhlich (Digdir).

## OMFANG OG AVGRENSNING

### Bakgrunn

Arbeidet tar utgangspunkt i casebeskrivelsen [11. Digital dialog mellom barnehage/skole og hjemmet](https://docs.samt-bu.no/behov/use-cases/11-digital-dialog-hjem/).

Foresatte må ofte forholde seg til flere digitale løsninger for å kommunisere med barnehage, SFO og skole. Hvilke løsninger som brukes, varierer mellom kommuner og institusjoner. Det kan føre til at foresatte må bruke flere apper og brukerflater for å følge opp meldinger, kalenderinformasjon, aktiviteter og historikk. Informasjonen blir spredt, og det kan være krevende å få oversikt over kommunikasjonen som er viktig for barnas hverdag.

Samtidig har kommuner og utdanningsinstitusjoner allerede investert i eksisterende løsninger. Det er derfor lite hensiktsmessig å legge til grunn at utfordringen skal løses ved å utvikle enda en ny app eller erstatte alle eksisterende løsninger.

### Pilotens målsetning

Det sentrale spørsmålet for piloten er hvordan eksisterende løsninger kan samhandle bedre, slik at foresatte kan velge hvordan de vil motta og følge opp kommunikasjonen, uten at det går på bekostning av personvern, informasjonssikkerhet eller virksomhetenes ansvar. Piloten tar derfor utgangspunkt i gjenbruk, samhandling og åpne grensesnitt framfor å utvikle en ny app.

Målene er å:

- kartlegge hvilke løsninger, standarder og felleskomponenter som allerede finnes, og hva som kan gjenbrukes
- finne ut hvordan meldinger, kalenderinformasjon og historikk kan deles mellom ulike systemer og apper på en sikker måte
- avklare hva som må på plass når det gjelder personvern, tilgangsrettigheter og ansvar
- avklare hvordan elever og studenter kan kommunisere med hverandre om det som gjelder skolen
- lage et konkret forslag til hvordan løsningene kan samhandle (enkel teknisk prototype og arkitektur)
- utarbeide forslag til felles krav som kommunene og andre kan stille til leverandørene
- legge til rette for at frivillig sektor og innovatører kan følge samme tilnærming til mer sammenhengende kommunikasjon

### Pilotens produkter

Piloten har følgende produkter:

1. **Løsningsdesign:** en skisse av hvordan dagens systemer og fellesløsninger kan fungere sammen for å gi foresatte én samlet kanal
2. **Felles standarder og integrasjonsmodell:** et forslag til hvordan meldinger, kalenderinformasjon og historikk kan deles mellom ulike systemer på en standardisert måte
3. **Teknisk prototype:** en enkel demonstrasjon av hvordan informasjon fra ulike systemer kan samles i én brukerflate
4. **Juridiske avklaringer:** en oversikt over hva som må være på plass for personvern, tilgangsrettigheter og fordeling av ansvar. Det kan også være aktuelt å se på hvordan elevene selv kan bruke løsningen (innspill fra Demokratiløftet).
5. **Felles leverandørkrav:** et forslag til krav som gjør det enklere for ulike systemer å utveksle data, og som reduserer leverandørbinding
6. **Hackathon:** det er foreslått å gjennomføre et hackathon for å finne mulige løsninger og prototyper

Selve gjennomføringen av piloten skal også danne grunnlag for oppdatering av prosjektets «dreiebok» for gjennomføring av denne typen prosjekter.

### Avgrensning

Piloten skal konsentrere seg om å demonstrere hvordan eksisterende løsninger kan samhandle, ikke om å utvikle en ny tjeneste eller app. Piloten avgrenses til:

- kartlegging av relevante løsninger og gjenbrukbare komponenter
- utvikling av en enkel prototype for samlet visning av utvalgt informasjon
- utprøving av integrasjonsmønstre og standarder
- avklaring av juridiske, organisatoriske og sikkerhetsmessige forutsetninger
- forslag til felles krav og anbefalinger for leverandører

### Gevinsteiere

Gevinsteierne er ikke avklart ennå. De viktigste forventede gevinstene er enklere kommunikasjon for foresatte, mindre oppsplitting av informasjonen og bedre samhandling mellom eksisterende systemer:

- bedre samhandling og mindre behov for parallelle løsninger, for kommuner og systemleverandører
- bedre oversikt over meldinger, beskjeder og kalenderinformasjon for foresatte
- større valgfrihet for foresatte og elever
- felles krav og åpne grensesnitt kan gjøre det enklere for flere aktører å tilby løsninger (marked og innovatører)
- tryggere kommunikasjon for elever

## BEMANNING

Piloten har behov for følgende kompetanse:

- Piloteier og prosjektleder
- **Arkitektur og integrasjon:** hvordan ulike systemer kan kobles sammen og utveksle data
- **Standardisering:** felles formater, API-er og standarder for meldinger, protokoller og informasjon
- **Utvikling:** utviklere som kan lage og teste en enkel teknisk prototype
- **Jus og personvern:** tilgangsrettigheter, personvern, informasjonssikkerhet og arkivering
- **Brukerinnsikt:** kjennskap til foreldres behov og til skole og barnehage, gjerne gjennom en pilotkommune
- **Anskaffelser og leverandørdialog:** utforme felles krav og involvere leverandørene i arbeidet

Bemanningen er ikke avklart ennå. Det er arbeidspakke 1.

## GJENNOMFØRING

### Pilotens varighet

Varigheten er ikke avklart ennå.

### Pilotens arbeidspakker

Hver arbeidspakke følges opp som et issue i [samt-bu-pilot-7](https://github.com/samt-x/samt-bu-pilot-7/issues).

#### 1. Finne piloteier og sette sammen team

Aktiviteter:

- Utpeke piloteier
- Etablere et autonomt, tverrfaglig team
- Avklare ressursbehov
- Etablere mål

Leveranser:

- Navngitt team med forpliktet kapasitet
- Plan for gjennomføring og ressursbruk

#### 2. Kartlegging og brukerbehov

Aktiviteter:

- Kartlegge dagens kommunikasjon mellom hjem, barnehage, SFO og skole
- Samle innsikt fra foresatte, ansatte og kommuner
- Kartlegge eksisterende systemer, apper, API-er, standarder og felleskomponenter
- Identifisere aktuelle leverandører og tekniske begrensninger
- Avgrense hva som skal testes

Leveranser:

- Kartlegging av dagens løsninger og systemlandskap
- Beskrivelse av brukerbehov og problemstilling

#### 3. Arkitektur og standardisering

Aktiviteter:

- Foreslå målarkitektur og informasjonsflyt
- Definere hvordan meldinger, kalenderinformasjon og historikk kan utveksles og representeres
- Kartlegge relevante standarder og integrasjoner
- Beskrive hvordan foresatte kan få informasjonen samlet
- Avklare behov for autentisering, tilgangsstyring, sporbarhet og lignende

Leveranser:

- Løsningsdesign og arkitekturskisse
- Beskrivelse av grensesnitt og integrasjonsprinsipper

#### 4. Juridiske avklaringer

Aktiviteter:

- Avklare behandlingsgrunnlag, formål og behandlingsansvar
- Avklare tilgangsrettigheter, både for foresatte og elev
- Vurdere krav til arkivering
- Identifisere ansvar ved mulige feil, for eksempel manglende synkronisering

Leveranser:

- Dokumenterte juridiske vurderinger (personvern og lignende)
- Oversikt over sikkerhetskrav og tilgangsregler
- Beskrivelse av uavklarte forhold og nødvendige tiltak før en eventuell produksjonssetting

#### 5. Teknisk prototype og hackathon

Aktiviteter:

- Utvikle en enkel prototype som samler informasjon
- Demonstrere samlet visning av meldinger og kalenderinformasjon
- Teste mulige integrasjonsmønstre
- Gjennomføre hackathon med utviklere, leverandører og innovasjonsmiljøer

Leveranser:

- Fungerende prototype
- Oppsummering av hackathon og anbefalte løsninger

#### 6. Felles leverandørkrav

Aktiviteter:

- Utarbeide forslag til leverandørkrav
- Innhente innspill fra kommuner og relevante leverandører
- Dokumentere anbefalinger

Leveranser:

- Forslag til felles leverandørkrav
- Dokumenterte erfaringer til dreieboken

### Avhengigheter og milepæler

Avhengigheter og milepæler er ikke avklart ennå.

### Praktisk gjennomføring

Hvordan teamet skal arbeide, er ikke avklart ennå. Utgangspunktet i malen er det samme som for de andre pilotene: iterativt etter smidige prinsipper, i sprinter på to eller tre uker, med planleggingsmøte i starten og demo på slutten av hver sprint, og minst én retrospektiv i løpet av pilotperioden.

Pilotens oppgaver følges opp som issues i [samt-bu-pilot-7](https://github.com/samt-x/samt-bu-pilot-7/issues), på brettet [SAMT-BU Pilot 7](https://github.com/orgs/samt-x/projects/19).

### Ikke avklart ennå

Overordnet plan, mål (OKR), rammer (budsjett), usikkerhetsanalyse og kommunikasjon er ikke avklart ennå.
