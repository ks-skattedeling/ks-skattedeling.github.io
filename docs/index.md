## KS Skattedeling Dokumentasjon

Her finner du dokumentasjon for hvordan kommunal sektor går fram for å gjøre en oppkobling til Skatteetatens APIer. API-et eller det tekniske grensesnittet «Summert skattegrunnlag» er tilgjengeliggjort av Skatteetaten, og har rettighetspakken «kommuneforeldrebetaling».

Se mer informasjon om prosjektet her: 
- KS sin informasjonsside for prosjektet: [KS Skattedeling](https://www.ks.no/skattedeling)

### Redusert foreldrebetaling barnehage og skolefritidsordning AKS/SFO
API-et eller det tekniske grensesnittet [Summert skattegrunnlag API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_summertskattegrunnlag.html) er tilgjengeliggjort av Skatteetaten, og har rettighetspakken «kommuneforeldrebetaling». Dette er et ferdig dataminimert datasett med de nødvendige opplysningene kommuner trenger for å gjøre et vedtak for denne tjenesten.   

For dokumentasjon av Skatteetatens API: 
- [Skatteetatens delingstjenester](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/index.html)
- [Summert skattegrunnlag API](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/reference_summertskattegrunnlag.html)
- [Skatteetatens informasjonsmodell for "Summert skattegrunnlag API" 2020](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/data_summertskattegrunnlag2020)

For veiledning for å delegere rettigheter i Altinn:

- Digitaliseringsdirektoratet: [Hvordan delegere rettigheter til leverandør i Altinn](https://vimeo.com/533856189)


For dokumentasjon av øvrige tjenester for autentisering for oppkobling til Skatteetatens API: 

- Digitaliseringsdirektoratets [Maskinporten](https://docs.digdir.no/docs/Maskinporten/maskinporten_guide_apikonsument.html)
- [Virksomhetssertifikat](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/about_virksomhetssertifikat.html)

Scope i Maskinporten som skal benyttes har navnet **Skatteetaten:summertskattegrunnlag**

Det finnes flere alternativer for å gjøre en oppkobling mot Skatteetatens API. Kommuner kan eksempelvis velge om de ønsker å koble seg direkte på Skatteetatens API, via en fagsystemleverandør eller via KS Fiks (er under utarbeiding). KS eller prosjektet har ikke tatt stilling til eller gjort en vurdering for hvilken alternativ for oppkobling til Skatteetatens API som er å foretrekke.  

### Hvordan komme i gang
**Steg 1: Avtaleinngåelse (for alle)**

For å få tilgang til API må hver enkelt kommune signere Skatteetatens egenerklæring med tilhørende bruks- og delingsvilkår. Avtalen må signeres av en person i kommunen som kan forplikte kommunen til det som står skrevet i avtalen.


Ta kontakt med ***skattedeling@ks.no*** for å få tilsendt avtale. 

Avtalen må fylles ut med følgende informasjon:

- Kommunens hovedorganisasjonsnummer (og er samme org.nr. som brukes i avtalen og i delegering i Altinn). 
- Kontaktinformasjon til kommunen (kommunens epostadresse)
- Kontaktinformasjon til en kontaktperson i kommunen
- Skriv i emnefeltet på epost navnet på kommunen som ønsker å gjøre oppkobling og for hvilken tjeneste. For eksempel for redusert foreldrebetaling barnehage og skolefritidsordning (SFO).
- Om kommunen skal gjøre en oppkobling til API gjennom en fagsystemleverandør, opplys i samme epost om hvem som er leverandøren.


Send deretter signert og utfylt avtale tilbake til ***skattedeling@ks.no*** 


KS brukerstøtte videresender signert avtale til Skatteetaten, som gir kommunen tilgang til API. KS brukerstøtte gir beskjed til den aktuelle kommune når tilgang er gitt hos Skatteetaten. Selv om Skatteetaten har gitt tilgang til en kommune, og denne er aktiv, så må kommune som gjør påkobling gjennom fagsystemleverandør delegere rettighet i Altinn.  

**Steg 2: Delegere rettighet til fagsystemleverandør i Altinn (For kommuner som gjør påkobling gjennom fagsystemleverandør)**

Siden det er fagsystemleverandøren som gjør påkoblingen til Skatteetatens API på vegne av den enkelte kommunen, må kommunen delegere myndighet eller autorisasjon til fagsystemleverandøren i Altinn for å kunne gjøre påkoblingen. 

***Huskeliste:*** 
- Bruk kommunens hovedorganisasjonnummer, og bruk det samme org.nr. kommunen har oppgitt i signert og tilsendt avtale (Skatteetaten gir tilgang på dette org.nr.).
- Kommunen må også bruke riktig org.nr. til fagsystemleverandør.
- Du finner rettigheten som skal delegeres gjennom å søke: "Summert skattegrunnlag - På vegne av". Det er denne som skal delegeres videre.

For veiledning for å delegere rettigheter i Altinn:

- Digitaliseringsdirektoratet: [Hvordan delegere rettigheter til leverandør i Altinn](https://vimeo.com/533856189)

### Kontakt og brukerstøtte
KS og Skatteetaten har signert en avtale om segmentsamarbeid som utpeker KS som segmentansvarlig. Rollen som segmentansvarlig innebærer at KS er kontaktpunkt og koordinator mellom kommunal sektor og Skatteetaten (single point of contact). 

Derfor skal alle henvendelser, spørsmål og avvik/feilmeldinger fra kommunal sektor sendes til ***skattedeling@ks.no.***
Ved feil er det viktig at følgende informasjon er inkludert i henvendelsen til KS brukerstøtte: 


### Abonnere på nyheter og driftsvarsel fra Skatteetaten
Ved å abonnere på driftsvarsel fra Skatteetaten får du raskest mulig beskjed om endringer i dokumentasjon, tekniske løsninger eller andre nyheter om [Skatteetatens delingstjenester](https://skatteetaten.github.io/datasamarbeid-api-dokumentasjon/tag_news.html)





