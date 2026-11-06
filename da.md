[Other languages / andere talen](index.md)

# Privatlivspolitik for SunMoment (dansk)

*Senest opdateret: 7. november 2026*

SunMoment er en app til husstande med solceller. Den fortæller dig, hvornår dit tag producerer nok strøm til dine apparater. Det korte svar: **appen bruger næsten ingen data, og vi kan ikke læse noget af det, medmindre du selv sender det til os.** Forbinder du din husstand, gemmer et lille script fra os jeres fælles logbog, krypteret. Vi kan ikke læse den.

## Hvem er ansvarlig?
Gala Apps, enkeltmandsvirksomhed i Nederlandene, nr. i det nederlandske handelsregister (KvK) 87752131, Keurenplein 41 Box C9874, 1069CD Amsterdam.
Momsnummer (VAT): NL004472079B57.
Spørgsmål om privatliv: gala.apps11@gmail.com.

## Hvad bliver på din telefon
Dit sprog og land, den by, du har valgt, dine paneler, tagets retning og hældning, dine apparater og timerindstillinger, dine svar på »Passede gårsdagens vejrudsigt?«, den dagsproduktion, du selv skriver ind, dine »Startet«-flueben (undtagen hvis du forbinder din husstand, se nedenfor) og den senest hentede vejrudsigt. Er du off-grid, bliver dit batteri, dit forbrug pr. dag og den batteristand, du indtaster, også på din telefon. Der er **ingen konto**. Appen spørger ikke om navn, e-mail, adresse eller telefonnummer, bruger ikke GPS og indeholder ingen reklamer og ingen analyse- eller sporingssoftware. På Android er backup i skyen og overførsel fra telefon til telefon **slået fra** for denne app. På iPhone og iPad tager iOS appens data med i din egen backup (iCloud eller din computer), hvis du har slået den til. Den backup styrer du og Apple; vi har ikke adgang til den. Ny telefon? Så sætter du appen op igen på et minut.

**Kamera** (kun ved »Scan koden«): appen bruger kameraet til at læse koblingskoden fra en i din husstand. Det sker på din telefon; der bliver ikke gemt eller sendt noget foto.

## Hvad forlader din telefon, og hvorfor

| Hvad | Hvorfor | Til hvem | Retsgrundlag (GDPR) | Hvor længe |
|---|---|---|---|---|
| De **afrundede** koordinater for den by, du har valgt (et område på ca. 10 km, ikke din adresse), plus det, som enhver forespørgsel på internettet indeholder: din **IP-adresse**, tidspunktet og appens navn. Det sker først i de ti udførligt understøttede lande (NL, BE, DE, AT, CH, LI, LU, GB, FR, DK); i andre lande kun, når vores egne vejrfiler ikke kan nås eller er over 48 timer gamle | For at hente den vejrudsigt, appen har brug for | **Bright Sky** (api.brightsky.dev): en selvstændig, gratis tjeneste, som drives af en privat udvikler i Tyskland, og som videregiver de åbne data fra den tyske vejrtjeneste DWD | Legitim interesse: appen kan ikke fungere uden en vejrudsigt (art. 6, stk. 1, litra f) | Det bestemmer Bright Sky selv; Bright Sky offentliggør ingen opbevaringsperiode. Vi er ansvarlige for at sende din forespørgsel til Bright Sky; Bright Sky er selv ansvarlig for, hvad tjenesten gør derefter. Vi har ingen aftale med Bright Sky, kan ikke se tjenestens logfiler og modtager intet fra den. |
| Kun **feltet på ca. 1000 km** omkring din by (for eksempel "50–60° nord, 0–10° øst"), plus din **IP-adresse**, tidspunktet og appens navn. Det sker uden for de ti udførligt understøttede lande (også for eksempel i Italien eller Spanien), eller når Bright Sky ikke har en vejrudsigt | Hente vejrudsigten fra vores egne vejrfiler (DWD's ICON-model) | **Bunny.net** (BunnyWay d.o.o., Slovenien), der gemmer filerne for os og leverer dem via sit netværk. Det sker kun fra servere i EU, også hvis du bor uden for Europa. Bunny.net handler på vores vegne (Bunny.nets databehandleraftale) | Legitim interesse: uden vejrudsigt virker appen ikke (art. 6, stk. 1, litra f) | Vi slår Bunny.nets logning fra og gemmer intet. |
| En **feedbackbesked**, som du selv sender, eventuelt med teknisk info: app-version, Android- eller iOS-version, telefonmodel, den by, du har valgt (navn og landekode), tidszonen for byen og telefonen, dine indstillinger i appen, om notifikationer er slået til, om batterisparing begrænser appen (Android), hvornår appen sidst hentede vejret og sidst kørte i baggrunden, for hver dag om der kom en morgennotifikation (og hvis ikke, hvorfor), en liste over de seneste fejl (uden webadresser og tal), og om du har købt appen eller stadig er i prøveperioden | For at svare dig og forbedre appen | Os, via din **egen** mail- eller beskedapp (SunMoment sender ikke selv noget) | Legitim interesse: at behandle din henvendelse (art. 6, stk. 1, litra f) | Højst 12 måneder, efter at dit spørgsmål er besvaret; før, hvis du beder om det |
| Kun hvis du selv **forbinder din husstand** (Indstillinger → Husstand): dine egne omgange »på egen sol« fra de sidste 70 dage (hvilken dag hvilket apparat kørte på solen, for eksempel »25-10 vaskemaskine«), og for dine egne apparater, hvor mange kWh én omgang bruger, hvornår en omgang i dag eller i går begyndte, hvor mange kWh en omgang sparede, og hvornår din telefon skrev blokken. Din telefon **krypterer** det først (AES-256-GCM). Nøglen findes kun i koblingskoden og kun på de koblede telefoner. Heller ikke på iPhone og iPad er den med i din backup: gendanner du en backup, kobler du igen. Desuden et kontroltal, så kun jeres telefoner kan ændre blokken, og, som ved enhver forespørgsel på internettet, din **IP-adresse** og tidspunktet. Det sker, når du åbner appen eller vender tilbage til den, efter »Startet« eller »Fortryd«, på skærmen Husstand og ved baggrundsopgaverne om morgenen og om aftenen (på iPhone og iPad: når iOS lader appen køre i baggrunden) | Så I sammen kan se, hvad der kørte på solen, og hvad de andre allerede har tændt | Et lille script fra SunMoment hos **Bunny.net** (BunnyWay d.o.o., Slovenien; Bunny Edge Scripting og Bunny Storage, opbevaring i EU, i Tyskland). Scriptet og opbevaringen kører kun på Bunny.net-servere i EU (i Tyskland), også hvis du bor uden for Europa. Det gemmer én krypteret blok pr. telefon under tilfældige numre: intet navn, ingen by, ingen e-mail. Hverken vi eller Bunny.net kan læse den; det kan kun de koblede telefoner. Bunny.net handler på vores vegne (Bunny.nets databehandleraftale) | Samtykke: du kobler selv (art. 6, stk. 1, litra a). Du kan altid trække dit samtykke tilbage ved at koble fra; så stopper det. Det, der skete før, forbliver lovligt. | Indtil du kobler fra; så slettes din telefons blok. En blok, der ikke er opdateret i 90 dage, slettes af scriptet, også selvom ingen bruger husstanden mere. Scriptet rydder op i sådanne blokke undervejs; som regel inden for få dage, men det har intet fast ur. Kobl helst fra, før du sletter appen. Laver du en ny koblingskode, bliver der i din gamle husstand kun en krypteret note om, at du er skiftet (uden omgange), indtil den slettes efter 90 dage. Scriptet logger ikke selv noget. Højst 8 telefoner pr. husstand. Den, der har koblingskoden, kan se med: del den kun med din husstand. |
| Din **bedømmelse**, hvis du giver en | Når du har trykket »Startet« for 5. og 25. gang, kan bedømmelsesvinduet fra Google Play eller App Store blive vist | Google Play eller Apple, direkte | Google Plays eller Apples vilkår | Som Google eller Apple bestemmer |

**Elpriser** (kun hvis du slår «Jeg har en dynamisk elaftale (spotpris)» til; nu i Tyskland og Danmark): appen henter én gang om dagen prisfilen for din priszone (DK1, DK2 eller DE) hos Bunny.net. Filen er den samme for alle i den zone. Bunny.net ser kun din IP-adresse og tidspunktet, ligesom ved vejret. Din by sendes ikke med; kun zonen står i filens navn. Dit svar «dynamisk elaftale» bliver på din telefon. Priserne kommer fra Energinet (Energi Data Service, Danmark, CC BY 4.0). Energinet får intet fra dig: vi henter priserne der, ikke din telefon.

**Nettarif (Danmark)** (kun hvis du vælger dit netselskab under Indstillinger): appen henter listen over netselskaber og derefter tarif-filen for dit netselskab hos Bunny.net, højst to gange om dagen. Filen er den samme for alle hos det netselskab; i navnet står kun netselskabets nummer. Bunny.net ser kun din IP-adresse og tidspunktet. Dit valg bliver på din telefon. Tarifferne kommer fra Energinet (DataHub, CC BY 4.0); Energinet får intet fra dig.

Den tekniske info er slået til som standard. Du ser den i sin helhed, før du sender, og du kan slå den fra eller slette den. Vi har **ingen egen server**, kun et lille synkroniseringsscript hos Bunny.net. Det virker kun, hvis du forbinder din husstand, og det gemmer kun krypterede blokke, som vi ikke kan læse. Ellers sender appen ikke os noget af sig selv.

**Uden for Europa:** også hvis du bor uden for Europa, bliver alle vejr-, pris- og nettarif-filer kun gemt på og leveret fra Bunny.net-servere i EU. Bunny.net (Slovenien) arbejder efter vores databehandleraftale.

## Dine rettigheder
Du kan bede om indsigt i, berigtigelse, sletning, begrænsning eller overførsel af de data, vi har om dig (det er kun beskeder, du selv har sendt os). Kontakt: gala.apps11@gmail.com.

**Ret til indsigelse:** du kan altid gøre indsigelse mod behandling, der bygger på legitim interesse. Vil du ikke have, at din IP-adresse sendes til Bright Sky eller Bunny.net, kan appen ikke hente en vejrudsigt; afinstallerer du appen, stopper det med det samme. Vil du ikke længere dele din logbog med din husstand? Så kobl fra.

Du behøver ikke give os noget. Uden vejrforespørgslen kan appen bare ikke vise en vejrudsigt. Appen træffer ingen afgørelser om dig og laver ingen profil.

Du sletter selv alt på din telefon: afinstaller appen, eller vælg Indstillinger → Apps → SunMoment → Lagerplads → Ryd data (Android). På iPhone og iPad sletter du appen; en gammel backup i iCloud sletter du i indstillingerne på din iPhone eller iPad. Du kan klage til datatilsynet i dit land:
- Danmark: [Datatilsynet](https://www.datatilsynet.dk)
- Nederlandene: Autoriteit Persoonsgegevens
- Belgien: Gegevensbeschermingsautoriteit / Autorité de protection des données
- Tyskland: tilsynsmyndigheden i din delstat eller BfDI
- Østrig: Datenschutzbehörde
- Schweiz: EDÖB (for dig gælder også den schweiziske databeskyttelseslov; dine rettigheder er de samme i store træk)
- Liechtenstein: Datenschutzstelle
- Luxembourg: CNPD
- Storbritannien: ICO (for dig gælder den britiske GDPR, UK GDPR)
- Frankrig: CNIL
- Andre lande: datatilsynet i dit land, hvis der er et. Der kan også gælde en egen lov om databeskyttelse; rettighederne ovenfor giver vi alle, uanset hvor du bor.

## Køb
Efter 21 dages prøveperiode kan du købe SunMoment én gang. På Android foregår det helt via Google Play, på iPhone og iPad helt via Apples App Store; Googles eller Apples vilkår og privatlivspolitik gælder. Google Plays købsfunktion i appen kan sende tekniske oplysninger om købet til Google; for det gælder Googles privatlivspolitik. Vi modtager ingen betalingsoplysninger. Google viser os kun oplysninger om ordren, som ordrenummer, land og beløb; Apple viser os kun salgstal, som antal pr. land og beløb, uden noget, der kan identificere dig (som dit navn eller din Apple-konto). Dem gemmer vi i 7 år, som den nederlandske skattelovgivning kræver (retsgrundlag: retlig forpligtelse, art. 6, stk. 1, litra c, i GDPR). Appen spørger butikken ved hver start, om du har købt SunMoment. På Android spørger den også Google Play, om det er muligt at købe på denne telefon. Kan det tydeligvis ikke lade sig gøre (for eksempel i et land uden betalte apps), forbliver appen gratis. Svarene bliver på din telefon. På iPhone og iPad starter prøveperioden med et gratis »køb« i App Store (»21-day Trial«). Appen gemmer kun den dato, App Store giver for det, på din telefon for at tælle de 21 dage; Apple sender os intet om det, der kan identificere dig. Hvornår din prøveperiode begyndte, gemmes altså også kun på din telefon.

## Links til kilder
Trykker du på en kilde i appen (for eksempel under tipsene), åbner din browser den hjemmeside. Hjemmesiden ser så din IP-adresse, som ved ethvert besøg. Det sker kun, når du selv trykker.

## Børn
SunMoment er ikke lavet til børn og spørger ingen om deres alder.

## Ændringer
Ændres der noget i, hvilke data appen bruger, opdaterer vi denne politik. Det kan du se på datoen øverst.
