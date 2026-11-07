[Other languages / andere talen](index.md)

# Integritetspolicy för SunMoment (svenska)

*Senast uppdaterad: 7 november 2026*

SunMoment är en app för hushåll, med eller utan solceller. Den talar om när dina apparater helst ska gå: på din egen solel eller under de billiga timmarna i ditt elavtal. Det korta svaret: **appen använder nästan inga uppgifter, och vi kan inte läsa något av dem, om du inte själv skickar dem till oss.** Kopplar du ihop ditt hushåll sparar ett litet skript från oss er gemensamma logg, krypterad. Vi kan inte läsa den.

## Vem är personuppgiftsansvarig?
Gala Apps, enskild firma i Nederländerna, nummer i det nederländska handelsregistret (KvK) 87752131, Keurenplein 41 Box C9874, 1069CD Amsterdam.
Momsregistreringsnummer: NL004472079B57.
Frågor om integritet: gala.apps11@gmail.com.

## Vad stannar på din telefon
Ditt språk och land, orten du har valt, dina paneler, takets riktning och lutning, dina apparater och timerinställningar, dina svar på ”Stämde gårdagens väderprognos?”, den dagsproduktion du själv fyller i, dina markeringar ”Startad” (utom om du kopplar ihop ditt hushåll, se nedan) och den senast hämtade väderprognosen. Är du off-grid stannar också ditt batteri, din förbrukning per dag och den batterinivå du fyller i på din telefon. Det finns **inget konto**. Appen frågar inte efter namn, e-postadress, adress eller telefonnummer, använder inte GPS och innehåller ingen reklam och ingen analys- eller spårningsprogramvara. På Android är säkerhetskopiering i molnet och överföring från telefon till telefon **avstängda** för den här appen. På iPhone och iPad tar iOS med appens data i din egen säkerhetskopia (iCloud eller din dator), om du har den påslagen. Den säkerhetskopian hanteras av dig och Apple; vi kommer inte åt den. Ny telefon? Då ställer du in appen igen på en minut.

På din telefon stannar också: hur du betalar för elen (ditt avtal, dina priser och billiga timmar, och i Danmark ditt nätbolag), körningarna du startade under de billiga timmarna och tipsen du bockar av, och för provperioden och köpkortet: vilka dagar appen kunde hjälpa dig och vad du betalade.

**Kamera** (bara vid ”Skanna koden”): appen använder kameran för att läsa kopplingskoden från någon i ditt hushåll. Det sker på din telefon; inget foto sparas eller skickas.

## Vad lämnar din telefon, och varför

| Vad | Varför | Till vem | Rättslig grund (GDPR) | Hur länge |
|---|---|---|---|---|
| De **avrundade** koordinaterna för orten du har valt (ett område på cirka 10 km, inte din adress), plus det som varje förfrågan på internet innehåller: din **IP-adress**, tidpunkten och appens namn. Det sker i första hand i de tio fullt stödda länderna (NL, BE, DE, AT, CH, LI, LU, GB, FR, DK); i andra länder bara när våra egna väderfiler inte kan nås eller är äldre än 48 timmar | För att hämta den väderprognos som appen behöver | **Bright Sky** (api.brightsky.dev): en fristående, kostnadsfri tjänst som drivs av en privat utvecklare i Tyskland och som tillhandahåller öppna data från den tyska vädertjänsten DWD | Berättigat intresse: appen kan inte fungera utan en väderprognos (art. 6.1 f) | Det bestämmer Bright Sky; tjänsten anger ingen lagringstid. Vi ansvarar för att skicka din förfrågan till Bright Sky; för vad Bright Sky gör sedan ansvarar Bright Sky själv. Vi har inget avtal med Bright Sky, kan inte se tjänstens loggar och får ingenting från den. |
| Bara **rutan på cirka 1000 km** runt din ort (till exempel ”50–60° nord, 0–10° öst”), plus din **IP-adress**, tidpunkten och appens namn. Det sker utanför de tio fullt stödda länderna (också till exempel i Italien eller Spanien), eller när Bright Sky inte har någon prognos | För att hämta väderprognosen från våra egna väderfiler (DWD:s ICON-modell) | **Bunny.net** (BunnyWay d.o.o., Slovenien), som lagrar filerna åt oss och levererar dem via sitt nätverk. Det sker bara från servrar i EU, även om du bor utanför Europa. Bunny.net är personuppgiftsbiträde åt oss (Bunny.nets personuppgiftsbiträdesavtal) | Berättigat intresse: utan väderprognos fungerar appen inte (art. 6.1 f) | Vi stänger av Bunny.nets loggning och sparar ingenting. |
| Ett **meddelande med feedback** som du själv skickar, om du vill med teknisk info: appversion, Android- eller iOS-version, telefonmodell, orten du har valt (namn och landskod), tidszonen för orten och för din telefon, dina inställningar i appen, om aviseringar är på, om batterisparläget begränsar appen (Android), när appen senast hämtade vädret och senast körde i bakgrunden, för varje dag om en morgonavisering kom (och om inte, varför), en lista över de senaste felen (utan webbadresser och siffror) och om du har köpt appen eller fortfarande är i provperioden | För att svara dig och förbättra appen | Oss, via din **egen** e-post- eller meddelandeapp (SunMoment skickar ingenting själv) | Berättigat intresse: att hantera din förfrågan (art. 6.1 f) | Högst 12 månader efter att din fråga är löst; tidigare om du ber om det |
| Bara om du själv **kopplar ihop ditt hushåll** (Inställningar → Hushåll): dina egna omgångar ”på egen solel” från de senaste 70 dagarna (vilken dag vilken apparat gick på solen, till exempel ”25-10 tvättmaskin”), och för dina egna apparater hur många kWh en omgång använder, när en omgång i dag eller i går startade, hur många kWh en omgång sparade och när din telefon skrev blocket. Din telefon **krypterar** detta först (AES-256-GCM). Nyckeln finns bara i kopplingskoden och bara på de kopplade telefonerna. Inte heller på iPhone och iPad finns den i din säkerhetskopia: om du återställer en säkerhetskopia kopplar du ihop igen. Dessutom ett kontrollnummer, så att bara ert hushålls telefoner kan ändra blocket, och, som vid varje förfrågan på internet, din **IP-adress** och tidpunkten. Det sker när du öppnar appen eller går tillbaka till den, efter ”Startad” eller ”Ångra”, på skärmen Hushåll och vid bakgrundsuppgifterna på morgonen och kvällen (på iPhone och iPad: när iOS låter appen köras i bakgrunden) | Så att ni tillsammans kan se vad som gick på solen, och vad de andra redan har startat | Ett litet SunMoment-skript hos **Bunny.net** (BunnyWay d.o.o., Slovenien; Bunny Edge Scripting och Bunny Storage, lagrat i EU, i Tyskland). Skriptet och lagringen körs bara på Bunny.net-servrar i EU (i Tyskland), även om du bor utanför Europa. Det sparar ett krypterat block per telefon under slumpmässiga nummer: inget namn, ingen ort, ingen e-postadress. Varken vi eller Bunny.net kan läsa det; bara de kopplade telefonerna kan det. Bunny.net är personuppgiftsbiträde åt oss (Bunny.nets personuppgiftsbiträdesavtal) | Samtycke: du kopplar själv (art. 6.1 a). Du kan när som helst återkalla ditt samtycke genom att koppla från; då upphör det. Det som skedde innan är fortfarande lagligt. | Tills du kopplar från; då raderas din telefons block. Ett block som inte har uppdaterats på 90 dagar raderas av skriptet, även om ingen använder hushållet längre. Skriptet rensar bort sådana block medan det ändå arbetar; oftast inom några dagar, men det har ingen fast klocka. Koppla helst från innan du avinstallerar appen. Om du skapar en ny kopplingskod finns bara en krypterad lapp om att du har bytt (utan omgångar) kvar i ditt gamla hushåll, tills den raderas efter 90 dagar. Skriptet loggar själv ingenting. Högst 8 telefoner per hushåll. Den som har kopplingskoden kan se med: dela den bara inom ditt hushåll. |
| Ditt **betyg**, om du ger ett | Vid din 5:e och 25:e ”Startad” kan betygsdialogen från Google Play eller App Store visas | Google Play eller Apple, direkt | Google Plays eller Apples villkor | Som Google eller Apple bestämmer |

**Elpriser** (bara om du slår på ”Jag har ett dynamiskt elavtal”; nu i Tyskland och Danmark): appen hämtar en gång om dagen prisfilen för ditt elområde (DK1, DK2 eller DE) hos Bunny.net. Filen är densamma för alla i det området. Bunny.net ser då bara din IP-adress och tidpunkten, precis som för vädret. Din ort skickas inte med; bara området står i filens namn. Ditt svar ”dynamiskt elavtal” stannar på din telefon. Priserna kommer från Energinet (Energi Data Service, Danmark, CC BY 4.0). Energinet får ingenting från dig: det är vi som hämtar priserna där, inte din telefon. Från kl. 15 hämtar appen även filen för i morgon. Berättigat intresse: du slår på det själv, och appen behöver filen för det (art. 6.1 f). Vi stänger av Bunny.nets loggning och sparar ingenting.

**Nättariff (Danmark)** (bara om du väljer ditt nätbolag i Inställningar): appen hämtar listan över nätbolag och sedan tariffilen för ditt nätbolag hos Bunny.net, högst två gånger om dagen. Filen är densamma för alla hos det nätbolaget; i namnet står bara nätbolagets nummer. Bunny.net ser då bara din IP-adress och tidpunkten. Ditt val stannar på din telefon. Tarifferna kommer från Energinet (DataHub, CC BY 4.0); Energinet får ingenting från dig. Berättigat intresse: du väljer nätbolaget själv, och appen behöver filen för det (art. 6.1 f). Vi stänger av Bunny.nets loggning och sparar ingenting.

Den tekniska infon är på som standard. Du ser den i sin helhet innan du skickar och kan stänga av den eller radera den. Vi har **ingen egen server**, bara ett litet synkroniseringsskript hos Bunny.net. Det fungerar bara om du kopplar ihop ditt hushåll, och det sparar bara krypterade block som vi inte kan läsa. Utöver det skickar appen ingenting till oss av sig själv.

**Utanför Europa:** även om du bor utanför Europa lagras och levereras alla väder-, pris- och nättariffiler bara från Bunny.net-servrar i EU. Bunny.net (Slovenien) arbetar enligt vårt personuppgiftsbiträdesavtal.

## Dina rättigheter
Du kan begära tillgång till, rättelse, radering, begränsning eller överföring av de uppgifter vi har om dig (bara meddelanden som du har skickat till oss). Kontakt: gala.apps11@gmail.com.

**Rätt att invända:** du kan alltid invända mot behandling som grundar sig på berättigat intresse. Vill du inte att din IP-adress når Bright Sky eller Bunny.net kan appen inte hämta någon väderprognos; avinstallerar du appen upphör det direkt. Vill du inte längre dela din logg med ditt hushåll? Koppla då från.

Du behöver inte ge oss något. Utan väderförfrågan kan appen bara inte visa någon väderprognos. Appen fattar inga beslut om dig och skapar ingen profil.

Radera allt på din telefon själv: avinstallera appen, eller välj Inställningar → Appar → SunMoment → Lagring → Rensa data (Android). På iPhone och iPad raderar du appen; en gammal säkerhetskopia i iCloud raderar du i inställningarna på din iPhone eller iPad. Du kan klaga hos dataskyddsmyndigheten i ditt land:
- Sverige: Integritetsskyddsmyndigheten (IMY)
- Nederländerna: Autoriteit Persoonsgegevens
- Belgien: Gegevensbeschermingsautoriteit / Autorité de protection des données
- Tyskland: myndigheten i din delstat eller BfDI
- Österrike: Datenschutzbehörde
- Schweiz: EDÖB (för dig gäller också den schweiziska dataskyddslagen; dina rättigheter är liknande)
- Liechtenstein: Datenschutzstelle
- Luxemburg: CNPD
- Storbritannien: ICO (för dig gäller UK GDPR)
- Frankrike: CNIL
- Danmark: Datatilsynet
- Andra länder: dataskyddsmyndigheten i ditt land, om det finns en.

Även ditt eget lands integritetslagstiftning kan gälla; vi ger alla rättigheterna ovan, var du än bor.

## Köp
Efter provperioden (på Android minst 21 och högst 60 dagar, på iPhone och iPad 21 dagar) kan du köpa SunMoment en gång. På Android sker det helt via Google Play, på iPhone och iPad helt via Apples App Store; Googles eller Apples villkor och integritetspolicy gäller. Google Plays köpfunktion i appen kan skicka tekniska uppgifter om köpet till Google; för det gäller Googles integritetspolicy. Vi får inga betalningsuppgifter. Google visar oss bara uppgifter om ordern, som ordernummer, land och belopp; Apple visar oss bara försäljningssiffror, som antal per land och belopp, utan något som identifierar dig (som ditt namn eller ditt Apple-konto). Dem sparar vi i 7 år, som den nederländska skattelagstiftningen kräver (rättslig grund: rättslig förpliktelse, art. 6.1 c GDPR). Vid varje start frågar appen butiken om du har köpt SunMoment. På Android frågar den också Google Play om det går att köpa på den här telefonen. Om det tydligt inte går (till exempel i ett land utan betalappar) förblir appen gratis. Svaren stannar på din telefon. På iPhone och iPad börjar provperioden med ett gratis ”köp” i App Store (”21-day Trial”). Appen sparar bara det datum som App Store anger för det, på din telefon, för att räkna de 21 dagarna; Apple skickar inget om det till oss som identifierar dig. När din provperiod började sparas alltså också bara på din telefon.

## Länkar till källor
Om du trycker på en källa i appen (till exempel under tipsen) öppnar din webbläsare den webbplatsen. Webbplatsen ser då din IP-adress, som vid varje besök. Det sker bara när du trycker.

## Barn
SunMoment är inte gjord för barn och frågar ingen om ålder.

## Ändringar
Om något ändras i vilka uppgifter appen använder uppdaterar vi den här policyn. Det ser du på datumet överst.
