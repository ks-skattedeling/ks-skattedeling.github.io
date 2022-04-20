## KS Skattedeling Dokumentasjon

Her finner du dokumentasjon for hvordan kommunal sektor går fram for å gjøre en påkobling til Skatteetatens API-er. 
Se mer informasjon på KS sin informasjonsside: [KS Skattedeling](https://www.ks.no/skattedeling)

Det er Skatteetaten som utvikler, forvalter og eier API-ene gjennom Skatteetatens delingstjenester. Det har egen kanal for teknisk dokumentasjon av alle deres API-er samt driftsmeldinger knyttet til disse: [Skatteetatens delingstjenester](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/index.html)

**Redusert foreldrebetaling barnehage og skolefritidsordning AKS/SFO (Er tilgjengelig for påkobling)**

API-et/delingtjenesten for redusert foreldrebetaling  er nå tilgjengeliggjort av Skatteetaten. Dette er et ferdig dataminimert datasett med de nødvendige skatte- og innntektsopplysninger kommunal sektor trenger for å gjøre et vedtak for tjenesten redusert foreldrebetaling barnehage og SFO/AKS.Se mer informasjon om: [Redusert foreldrebetaling barnehage og SFO](https://www.ks.no/fagomrader/digitalisering/felleslosninger/deling-av-opplysninger-fra-skatteetaten/barnehage-og-skolefritidsordning/)    

- Navnet på API-et som benyttes er: [Summert skattegrunnlag API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_summertskattegrunnlag.html)
- Navnet på rettighetspakken er ***kommuneforeldrebetaling***
- Navnet på scope i Maskinporten er ***skatteetaten:summerskattegrunnlag***
- Skatteetatens dokumentasjon av [Summert skattegrunnlag API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_summertskattegrunnlag.html)
- Skatteetatens [informasjonsmodell for Summert skattegrunnlag API 2021](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/data_summertskattegrunnlag2021)

**Kommunal boligsosial støtte (Er i pilot)**

API-et/delingstjenesten for vedtak om tildeling av behovsprøvet kommunal boligsosial støtte er nå i pilotprosjekt med KOBO (digitalt system for kommunale utleieboliger) og Oslo kommunes Kombo-prosjekt. For behovsprøvet boligsosial støtte trenger saksbehandler løpende inntektsopplysninger fra a-ordninger, opplysninger fra skattemelding og skatteoppgjør. API-et vil derfor dele siste tilgjengelige informasjon om en innbygger fra både a-meldingen, skattemelding og skatteoppgjør. Til dette benyttes to API-er. Se mer informasjon: [Kommunal boligsosial støtte](https://www.ks.no/fagomrader/digitalisering/felleslosninger/deling-av-opplysninger-fra-skatteetaten/kommunal-bolig-og-kommunal-bostotte/)

- Navnet på på API-ene som benyttes er: [Summert skattegrunnlag API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_summertskattegrunnlag.html) og [Inntektsmottaker API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_inntektsmottaker.html)
- Navnet på rettighetspakken er ***kommuneboligsosialeformaal***
- Navnet på scopene i Maskinporten er ***skatteetaten:summerskattegrunnlag*** og ***skatteetaten:inntekt***
- Rettighetene som skal delegeres i Altinn er ***Summert skattegrunnlag - På vegne av*** og ***Inntekt API*** OBS: Begge rettighetene må delegeres!

### Alternativer for å gjøre en påkobling mot Skatteetatens API-er
Det finnes flere alternativer for å gjøre en påkobling mot Skatteetatens API-er:
- kommuner kan koble seg til direkte på Skatteetatens API, og bygge sine egne tjenester selv
- kommuner kobler seg opp via en leverandør (databehandler)
- KS tilrettellegger for påkobling til API-ene via den kommunale samhandlingsplattformen Fiks (er under utarbeiding). 

KS eller prosjektet har hverken tatt stilling til eller gjort en vurdering av hvilket alternativ for påkobling til Skatteetatens API som er å foretrekke for den enkelte kommune.  


### Hvordan komme i gang med påkobling til Skatteetatens API
For å ta i bruk et API må kommunen: 
1. signere ***tilslutningserklæring***, dette gjøres én gang for alle API-er til Skatteetaten
2. sende ***påkoblingsforespørsel*** til KS for tilgang til det enkelte API-et: dvs. det skal gjøres en påkoblingsforespørsel per API
3. kommunen må ***delegere rettigheter via Altinn*** per API ved påkobling via leverandør

Se mer informasjon om [hvordan koble seg til Skatteetatens API-er/delingstjenester](https://www.ks.no/fagomrader/digitalisering/felleslosninger/deling-av-opplysninger-fra-skatteetaten/hvordan-koble-seg-til-skatteetatens-delingslosninger/) 

**Steg 1: Avtaleinngåelse - Signere tilslutningserklæring (gjelder for alle, og gjøres én gang)**

Før tilgang gis til Skatteetatens API, må den enkelt kommune signere Skatteetatens tilslutningserklæring for Skatteetatens delingstjenester for kommunene. Avtalen må signeres av Ordfører eller annen med tildelt myndighet, jf. kommuneloven § 6-1 annet ledd. 

Avtalen og informasjon om hvordan gjøre en påkobling til Skatteetatens API-er finner du her: [Hvordan koble seg til Skatteetatens delingsløsninger (API-er)](https://www.ks.no/fagomrader/digitalisering/felleslosninger/deling-av-opplysninger-fra-skatteetaten/hvordan-koble-seg-til-skatteetatens-delingslosninger/)

Du kan også ta kontakt med ***skattedeling@ks.no*** for å få tilsendt avtale. 

Avtalen må fylles ut med følgende informasjon:

- Kommunens hovedorganisasjonsnummer (og er samme org.nr. som brukes i avtalen og i delegering i Altinn). 
- Kontaktinformasjon til kommunen (kommunens e-postadresse)
- Kontaktinformasjon til en kontaktperson i kommunen
- Skriv kommunenavnet i emnefeltet på epost. For eksempel: X kommune ønsker å gjøre påkobling til Skatteetatens API for redusert foreldrebetaling barnehage og skolefritidsordning (SFO).
- Om kommunen skal gjøre en påkobling til API gjennom en fagsystemleverandør, opplys i samme epost om hvem som er leverandøren.

**Husk!** Om avtalen ikke fylles ut digitalt, skriv tydelig med blokkbokstaver.

Send signert og utfylt avtale tilbake til ***skattedeling@ks.no***. KS brukerstøtte arkiverer avtalen, og videresender signert avtale til Skatteetaten. 

**Steg 2: Sende påkoblingsforespørsel til KS (gjøres for påkobling til det enkelte API)**

Dersom kommunen allerde har signert tilslutningserklæringen, må kommunen sende påkoblingsforespørsel for hvert enkelt API det ønskes å ta i bruk. Det kreves én påkoblingsforespørsel per API/delingstjeneste. Kommuner som har tok i bruk API-et for tjenesten redusert foreldrebetaling barnehage og SFO i pilotperioden, behøver ikke å sende påkoblingsforespørsel for dette API-et.   

Påkoblingsforespørselen kan lastes ned [**HER**](https://www.ks.no/fagomrader/digitalisering/felleslosninger/deling-av-opplysninger-fra-skatteetaten/hvordan-koble-seg-til-skatteetatens-delingslosninger/)

Fremgangsmåte: 
1. kommune sender utfylt påkoblingsforespørsel om tilgang til den konkrete API-et/delingstjenesten til KS: skattedeling@ks.no
2. KS kontrollerer at kommunen har signert tilslutningserklæring. KS sender deretter en påkoblingsforespørsel til Skatteetaten om at det gis tilgang til et spesifikt      API.
3. KS gir beskjed til den kommunen når tilgang er gitt for test og produksjon hos Skatteetaten. 


**Steg 3: Delegere rettighet til leverandør i Altinn (For kommuner som gjør påkobling gjennom leverandør, og må gjøres for påkobling til hvert enkelte API fra Skatteetaten)**

Dersom det er leverandøren som gjør påkoblingen til Skatteetatens API på vegne av en enkelt kommune, må kommunen selv delegere rettighet/myndighet til leverandøren i Altinn for å hente opplysninger på vegne av kommunen. 

***Huskeliste:*** 
- Bruk kommunens hovedorganisasjonnummer, og bruk det samme org.nr. kommunen har oppgitt i signert og tilsendt avtale (Skatteetaten gir tilgang på dette org.nr.).
- Kommunen må også bruke riktig org.nr. til leverandør.
- For tjenesten Redusert foreldrebetaling barnehage og SFO, skal følgende rettighet søkes opp: **"Summert skattegrunnlag - På vegne av"**. Det er denne som skal delegeres videre leverandør.

For veiledning for å delegere rettigheter i Altinn:

- Digitaliseringsdirektoratet: [Hvordan delegere rettigheter til leverandør i Altinn](https://vimeo.com/533856189)

**Maskinporten (For leverandører eller kommuner som gjør direkte påkobling til Skatteetatens API)**
- [Slik bruker du Maskinporten som API-konsument](https://docs.digdir.no/docs/Maskinporten/maskinporten_guide_apikonsument.html)
- Dokumentasjon av [Virksomhetssertifikat](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/about_virksomhetssertifikat.html)

### Kontakt og brukerstøtte
KS og Skatteetaten har signert en avtale om segmentsamarbeid som utpeker KS som segmentansvarlig. Rollen som segmentansvarlig innebærer at KS er kontaktpunkt og koordinator mellom kommunal sektor og Skatteetaten (single point of contact). 

Derfor skal alle henvendelser, spørsmål og avvik/feilmeldinger fra kommunal sektor sendes til ***skattedeling@ks.no.***

**Venter du på svar fra oss?** 
Gjerne sjekk først om henvendelsen vår på epost ligger som søppelpost hos deg før du tar kontakt med oss. 

### Feil og avvik ###

Dersom det oppstår feil i tilgangen eller feilmelding, er det viktig at følgende informasjon er inkludert i henvendelsen til KS brukerstøtte:
- Dokumentasjon av feilen eller problemet (tekstbeskrivelse og bilde). 
- Hvilket tidspunkt oppstod feilen.
- Har kommunen på noen tidspunkt kunne hente ned skatte- og inntektsopplysninger gjennom API-et? 
- Om fagsystemleverandøre gjør påkobling på vegne av kommunen, har kommunen delegert rettighet til fagsystemleverandøren? 

### Abonnere på nyheter og driftsvarsel fra Skatteetaten ###
I henhold til Skatteetatens bruks- og delingsvilkår må deres datakonsumenter abonnere på [driftsvarsel fra Skatteetatens delingstjenester](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/tag_news.html). På denne måten får du raskest mulig beskjed om endringer i API, dokumentasjon, feil eller nedetid hos Skatteetaten. Vi ber derfor alle kommuner som har signert tilslutningserklæring og tatt i bruk et av Skatteetatens API-er om å abonnere driftsvarsel fra Skatteetatens Delingstjenester. 





