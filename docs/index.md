## KS Skattedeling Dokumentasjon

Her finner du dokumentasjon for hvordan kommunal sektor går fram for å gjøre en påkobling til Skatteetatens API-er. 

Se mer informasjon om prosjektet her: 
- KS sin informasjonsside for prosjektet: [KS Skattedeling](https://www.ks.no/skattedeling)

### Redusert foreldrebetaling barnehage og skolefritidsordning AKS/SFO (Er tilgjengelig for påkobling)
API-et eller det tekniske grensesnittet [Summert skattegrunnlag API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_summertskattegrunnlag.html) er nå tilgjengeliggjort av Skatteetaten, og har rettighetspakken «kommuneforeldrebetaling». Dette er et ferdig dataminimert datasett med de nødvendige skatte- og innntektsopplysninger  kommunal sektor trenger for å gjøre et vedtak for tjenesten redusert foreldrebetaling barnehage og skolefritidsordning AKS/SFO.   

For dokumentasjon av Skatteetatens API: 
- [Skatteetatens delingstjenester](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/index.html)
- [Summert skattegrunnlag API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_summertskattegrunnlag.html)
- [Skatteetatens informasjonsmodell for "Summert skattegrunnlag API" 2021](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/data_summertskattegrunnlag2021)

### Hvordan komme i gang med påkobling til Skatteetatens API
Det finnes flere alternativer for å gjøre en påkobling mot Skatteetatens API. Kommuner kan eksempelvis velge om de ønsker å koble seg direkte på Skatteetatens API, via en fagsystemleverandør eller via KS Fiks (er under utarbeiding). KS eller prosjektet har hverken tatt stilling til eller gjort en vurdering av hvilket alternativ for påkobling til Skatteetatens API som er å foretrekke for den enkelte kommune.  


**Steg 1: Avtaleinngåelse (gjelder for alle)**

For å få tilgang til Skatteetatens API, må den enkelt kommune signere Skatteetatens egenerklæring med tilhørende bruks- og delingsvilkår. Avtalen må signeres av en person i kommunen som kan forplikte kommunen til det som står skrevet i avtalen.

Ta kontakt med ***skattedeling@ks.no*** for å få tilsendt avtale. 

**Husk!** Om avtalen ikke fylles ut digitalt, skriv tydelig med blokkbokstaver.

Avtalen må fylles ut med følgende informasjon:

- Kommunens hovedorganisasjonsnummer (og er samme org.nr. som brukes i avtalen og i delegering i Altinn). 
- Kontaktinformasjon til kommunen (kommunens epostadresse)
- Kontaktinformasjon til en kontaktperson i kommunen
- Skriv i emnefeltet på epost navnet på kommunen som ønsker å gjøre påkobling og for hvilken tjeneste. For eksempel: X kommune ønsker å gjøre påkobling til Skatteetatens API for redusert foreldrebetaling barnehage og skolefritidsordning (SFO).
- Om kommunen skal gjøre en påkobling til API gjennom en fagsystemleverandør, opplys i samme epost om hvem som er leverandøren.


Send deretter signert og utfylt avtale tilbake til ***skattedeling@ks.no*** 


KS brukerstøtte videresender signert avtale til Skatteetaten, som gir kommunen tilgang til API. KS brukerstøtte gir beskjed til den aktuelle kommune når tilgang er gitt hos Skatteetaten. Selv om Skatteetaten har gitt tilgang til en kommune, og denne er aktiv, så må kommune som gjør påkobling gjennom fagsystemleverandør delegere rettighet i Altinn.  

**Steg 2: Delegere rettighet til fagsystemleverandør i Altinn (For kommuner som gjør påkobling gjennom fagsystemleverandør, og må gjøres for påkobling til hvert enkelte API fra Skatteetaten)**

Dersom det er fagsystemleverandøren som gjør påkoblingen til Skatteetatens API på vegne av en enkelt kommune, må kommunen selv delegere myndighet eller autorisasjon til fagsystemleverandøren i Altinn. 

***Huskeliste:*** 
- Bruk kommunens hovedorganisasjonnummer, og bruk det samme org.nr. kommunen har oppgitt i signert og tilsendt avtale (Skatteetaten gir tilgang på dette org.nr.).
- Kommunen må også bruke riktig org.nr. til fagsystemleverandør.
- Du finner rettigheten som skal delegeres gjennom å søke: **"Summert skattegrunnlag - På vegne av"**. Det er denne som skal delegeres videre.

For veiledning for å delegere rettigheter i Altinn:

- Digitaliseringsdirektoratet: [Hvordan delegere rettigheter til leverandør i Altinn](https://vimeo.com/533856189)

**Maskinporten (For fagsystemleverandør og kommuner som gjøre direkte påkobling til Skatteetatens API)**
- Digitaliseringsdirektoratets [Maskinporten](https://docs.digdir.no/docs/Maskinporten/maskinporten_guide_apikonsument.html)
- [Virksomhetssertifikat](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/about_virksomhetssertifikat.html)

Scope i Maskinporten som skal benyttes har navnet **Skatteetaten:summertskattegrunnlag**

### Kontakt og brukerstøtte
KS og Skatteetaten har signert en avtale om segmentsamarbeid som utpeker KS som segmentansvarlig. Rollen som segmentansvarlig innebærer at KS er kontaktpunkt og koordinator mellom kommunal sektor og Skatteetaten (single point of contact). 

Derfor skal alle henvendelser, spørsmål og avvik/feilmeldinger fra kommunal sektor sendes til ***skattedeling@ks.no.***


**Feil og avvik**

Dersom det oppstår feil i tilgangen eller feilmelding, er det viktig at følgende informasjon er inkludert i henvendelsen til KS brukerstøtte:
- Dokumentasjon av feilen eller problemet (tekstbeskrivelse og bilde). 
- Hvilket tidspunkt oppstod feilen.
- Har kommunen på noen tidspunkt kunne hente ned skatte- og inntektsopplysninger gjennom API-et? 
- Om fagsystemleverandøre gjør påkobling på vegne av kommunen, har kommunen delegert rettighet til fagsystemleverandøren? 


### Abonnere på nyheter og driftsvarsel fra Skatteetaten
Ved å abonnere på [driftsvarsel fra Skatteetatens delingstjenester](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/tag_news.html) får du raskest mulig beskjed om endringer i API, dokumentasjon, feil eller nedetid hos Skatteetaten.





