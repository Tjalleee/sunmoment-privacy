# Privacyverklaring SunMoment

*Laatst bijgewerkt: 26 oktober 2026*

SunMoment is een app voor huishoudens met zonnepanelen. De app vertelt wanneer je dak genoeg stroom levert voor je apparaten. Het korte antwoord: **de app gebruikt bijna geen gegevens, en wij kunnen niets ervan lezen, behalve wat je ons zelf stuurt.** Koppel je huisgenoten, dan bewaart een klein script van ons jullie logboek, versleuteld. Wij kunnen dat niet lezen.

## Wie is verantwoordelijk?
Gala Apps, eenmanszaak in Nederland, KvK-nummer 87752131, Keurenplein 41 Box C9874, 1069CD Amsterdam.
E-mail voor vragen over privacy: gala.apps11@gmail.com.

## Wat blijft op je telefoon?
- je taal en land, de plaats die je kiest, je panelen, de richting en helling van je dak;
- je apparaten en timerinstellingen;
- je antwoorden op "Klopte de voorspelling van gisteren?", de dagopbrengsten die je zelf invoert en je "Aangezet"-vinkjes (behalve als je huisgenoten koppelt, zie hieronder);
- de laatst opgehaalde weersverwachting (zodat de app ook zonder internet werkt).

Er is **geen account**. De app vraagt geen naam, e-mailadres, adres of telefoonnummer, gebruikt geen GPS, en bevat geen advertenties en geen volg- of analysesoftware. Back-up in de cloud en overzetten naar een nieuwe telefoon staan voor deze app **uit**. Nieuwe telefoon? Dan stel je de app in een minuut opnieuw in.

## Wat gaat er naar buiten, en waarom?

| Wat | Waarom | Naar wie | Grondslag (AVG) | Hoe lang |
|---|---|---|---|---|
| De **afgeronde** coördinaten van je gekozen plaats (een gebied van ongeveer 10 km, niet je adres), plus wat bij elk internetverzoek hoort: je **IP-adres**, het tijdstip en de naam van de app. Dit gebeurt eerst in de tien uitgewerkte landen (NL, BE, DE, AT, CH, LI, LU, GB, FR, DK); in andere landen alleen als onze eigen weerbestanden niet bereikbaar of ouder dan 48 uur zijn | De weersverwachting ophalen, zodat de app je dak kan uitrekenen | **Bright Sky** (api.brightsky.dev): een zelfstandige, gratis dienst van een particuliere ontwikkelaar in Duitsland, die de open data van de Duitse weerdienst DWD doorgeeft | Gerechtvaardigd belang: zonder weersverwachting werkt de app niet (art. 6 lid 1 sub f) | Dat bepaalt Bright Sky zelf; Bright Sky publiceert geen bewaartermijn. Bright Sky is zelf verantwoordelijk voor wat het met deze gegevens doet. Wij hebben geen afspraak met Bright Sky, kunnen hun logboeken niet inzien en krijgen niets van hen terug. |
| Alleen het **vak van ongeveer 1000 km** rond je plaats (bijvoorbeeld "50–60° noord, 0–10° oost"), plus je **IP-adres**, het tijdstip en de naam van de app. Dit gebeurt buiten de tien uitgewerkte landen (ook bijvoorbeeld in Italië of Spanje), of als Bright Sky geen verwachting heeft | De weersverwachting ophalen uit onze eigen weerbestanden (het ICON-model van de DWD) | **Bunny.net** (BunnyWay d.o.o., Slovenië), dat de bestanden voor ons bewaart en via zijn netwerk levert. Je telefoon krijgt ze van de dichtstbijzijnde server; in Europa is dat een server in Europa. Bunny.net werkt in onze opdracht (verwerkersovereenkomst van Bunny.net ⚖️) | Gerechtvaardigd belang: zonder weersverwachting werkt de app niet (art. 6 lid 1 sub f) | Wij zetten de logboeken van Bunny.net uit en bewaren niets. Wie buiten Europa woont, wordt bediend door een server in de eigen regio. |
| Een **feedbackbericht** dat je zelf verstuurt, eventueel met technische info: app- en Android-versie, toestelmodel, je gekozen plaats (naam en landcode), de tijdzone van plaats en telefoon, je instellingen in de app, of meldingen aan staan, of batterijbesparing de app beperkt, en wanneer de app het laatst het weer ophaalde en op de achtergrond draaide | Je vraag beantwoorden en de app verbeteren | Ons, via je **eigen** mail- of berichten-app (SunMoment verstuurt zelf niets) | Gerechtvaardigd belang: je hulpvraag afhandelen (art. 6 lid 1 sub f) | Tot uiterlijk 12 maanden nadat je vraag is afgehandeld; eerder als je daarom vraagt |
| Alleen als je zelf **huisgenoten koppelt** (Instellingen → Huisgenoten): je eigen beurten "op eigen zon" van de laatste 70 dagen (welke dag welk apparaat op de zon draaide, bijvoorbeeld "25-10 wasmachine"), en voor je eigen apparaten hoeveel kWh een beurt gebruikt. Je telefoon **versleutelt** dit eerst (AES-256-GCM). De sleutel zit alleen in de koppelcode en staat alleen op de gekoppelde telefoons. Verder een controlegetal, zodat alleen jullie telefoons het blok kunnen wijzigen, en zoals bij elk internetverzoek: je **IP-adres** en het tijdstip. Dit gebeurt als je de app opent of erin terugkomt, na "Aangezet" of "Ongedaan maken", op het scherm Huisgenoten, en bij de achtergrondtaken 's ochtends en 's avonds | Zodat jullie samen zien wat er op de zon draaide, en wat de ander al aanzette | Een klein script van SunMoment bij **Bunny.net** (BunnyWay d.o.o., Slovenië; Bunny Edge Scripting en Bunny Storage, opslag in de EU, in Frankfurt). Het bewaart per telefoon één versleuteld blok onder willekeurige nummers: geen naam, geen plaats, geen e-mail. Wij en Bunny.net kunnen het niet lezen; alleen de gekoppelde telefoons kunnen dat. Bunny.net werkt in onze opdracht (verwerkersovereenkomst van Bunny.net ⚖️) | Toestemming: je koppelt zelf (art. 6 lid 1 sub a). Ontkoppel je, dan stopt het | Tot je ontkoppelt; dan wordt het blok van je telefoon verwijderd. Is een blok 180 dagen niet bijgewerkt, dan wist het script het zodra een telefoon van jullie huishouden weer verbinding maakt. Gebruikt niemand het huishouden meer, dan blijft het versleutelde blok staan: ontkoppel daarom voordat je de app verwijdert. Het script logt zelf niets. Maximaal 8 telefoons per huishouden. Wie de koppelcode heeft, kan meekijken: deel hem alleen met je huisgenoten. |
| Je **beoordeling**, als je die geeft | Bij de 5e en 25e keer "Aangezet" kan Googles eigen beoordelingsvenster verschijnen | Google Play, rechtstreeks | De voorwaarden van Google Play | Volgens Google |

De technische info in een feedbackbericht staat standaard aan. Je ziet hem vóór het versturen helemaal, en je kunt hem uitzetten of weghalen. Je bericht loopt via je eigen mail- of berichtendienst; daarvoor gelden de voorwaarden van die dienst.

Wij hebben **geen eigen server**, alleen een klein synchronisatiescript bij Bunny.net. Dat werkt alleen als je huisgenoten koppelt, en bewaart alleen versleutelde blokken die wij niet kunnen lezen. Verder stuurt de app ons uit zichzelf niets.

## Jouw rechten
Je hebt recht op inzage, verbetering, verwijdering, beperking en overdracht van gegevens die wij van je hebben. Dat zijn alleen berichten die je ons zelf stuurde. Mail ons via [e-mailadres].

**Bezwaar:** je mag altijd bezwaar maken tegen het gebruik van je gegevens op grond van gerechtvaardigd belang. Wil je niet dat je IP-adres naar Bright Sky of Bunny.net gaat? Dan kan de app helaas geen verwachting ophalen. Verwijder de app; dan stopt het meteen. Wil je je logboek niet meer delen met huisgenoten? Ontkoppel dan.

Al je gegevens op je telefoon wis je zelf: verwijder de app, of kies Instellingen → Apps → SunMoment → Opslag → Gegevens wissen.

Een klacht kun je indienen bij de privacytoezichthouder in je land:
- Nederland: [Autoriteit Persoonsgegevens](https://www.autoriteitpersoonsgegevens.nl/)
- België: [Gegevensbeschermingsautoriteit](https://www.gegevensbeschermingsautoriteit.be/)
- Duitsland: de toezichthouder van je deelstaat, of de [BfDI](https://www.bfdi.bund.de/)
- Oostenrijk: [Datenschutzbehörde](https://www.dsb.gv.at/)
- Zwitserland: [EDÖB](https://www.edoeb.admin.ch/) (voor jou geldt ook de Zwitserse privacywet; je rechten zijn vergelijkbaar)
- Liechtenstein: [Datenschutzstelle](https://www.datenschutzstelle.li/)
- Luxemburg: [CNPD](https://cnpd.public.lu/)
- Verenigd Koninkrijk: [ICO](https://ico.org.uk/) (voor jou geldt de Britse AVG, de UK GDPR)
- Frankrijk: [CNIL](https://www.cnil.fr/)
- Denemarken: [Datatilsynet](https://www.datatilsynet.dk/)
- Een ander land: de privacytoezichthouder van je eigen land, als die er is. Daar kan ook een eigen privacywet gelden. De rechten hierboven geven we iedereen, waar je ook woont.

## Aankopen
Na 21 dagen proef kun je SunMoment één keer kopen. Dat loopt helemaal via Google Play; daarvoor gelden de voorwaarden en de privacyverklaring van Google. Wij krijgen geen betaalgegevens. Google laat ons alleen gegevens over de bestelling zien, zoals het bestelnummer, het land en het bedrag. Die bewaren we zolang de belastingwet dat vraagt. De app vraagt Google Play bij elke start of je SunMoment hebt gekocht, en of kopen op deze telefoon kan. Kan dat duidelijk niet (bijvoorbeeld in een land zonder betaalde apps), dan blijft de app gratis. Beide antwoorden blijven op je telefoon. Wanneer je proef begon, staat ook alleen op je telefoon.

## Links naar bronnen
Tik je in de app op een bron (bijvoorbeeld bij de weetjes), dan opent je browser die website. Die website ziet dan je IP-adres, zoals bij elk bezoek. Dat gebeurt alleen als je zelf tikt.

## Kinderen
SunMoment is niet gemaakt voor kinderen en vraagt niemand naar zijn leeftijd.

## Wijzigingen
Verandert er iets aan welke gegevens de app gebruikt, dan passen we deze verklaring aan. Je ziet dat aan de datum bovenaan.

---

# Privacy Policy SunMoment (English)

*Last updated: 26 October 2026*

SunMoment is an app for households with solar panels. It tells you when your roof produces enough power for your appliances. Short answer: **the app uses almost no data, and we cannot read any of it unless you send it to us yourself.** If you link your household, a small script of ours keeps your shared log, encrypted. We cannot read it.

## Who is responsible?
Gala Apps, sole proprietorship in the Netherlands, Chamber of Commerce (KvK) number 87752131, Keurenplein 41 Box C9874, 1069CD Amsterdam.
Privacy questions: gala.apps11@gmail.com.

## What stays on your phone
Your language and country, chosen town, panels, roof direction and tilt, appliances and timer settings, your answers to "Was yesterday's forecast right?", the daily yields you enter, your "Started" ticks (unless you link your household, see below), and the last downloaded forecast. There is **no account**; the app asks no name, email, address or phone number, uses no GPS, and contains no ads and no analytics or tracking software. Cloud backup and phone-to-phone transfer are **switched off** for this app. New phone? Setting the app up again takes a minute.

## What leaves your phone, and why

| What | Why | To whom | Legal basis (GDPR) | How long |
|---|---|---|---|---|
| The **rounded** coordinates of your chosen town (an area of about 10 km, not your address), plus what every internet request carries: your **IP address**, the time and the app's name. This happens first in the ten fully supported countries (NL, BE, DE, AT, CH, LI, LU, GB, FR, DK); in other countries only when our own weather files cannot be reached or are more than 48 hours old | To fetch the weather forecast the app needs | **Bright Sky** (api.brightsky.dev): an independent, free service run by a private developer in Germany, serving the open data of the German weather service DWD | Legitimate interest: the app cannot work without a forecast (Art. 6(1)(f)) | Up to Bright Sky; it publishes no retention period. Bright Sky is itself responsible for what it does with this data. We have no agreement with Bright Sky, cannot see its logs and receive nothing from it. |
| Only the **block of about 1000 km** around your town (for example "50–60° north, 0–10° east"), plus your **IP address**, the time and the app's name. This happens outside the ten fully supported countries (also, for example, in Italy or Spain), or when Bright Sky has no forecast | Fetching the forecast from our own weather files (the DWD ICON model) | **Bunny.net** (BunnyWay d.o.o., Slovenia), which stores the files for us and delivers them through its network. Your phone gets them from the nearest server; in Europe that is a server in Europe. Bunny.net acts on our behalf (Bunny.net's data processing agreement) | Legitimate interest: without a forecast the app does not work (Art. 6(1)(f)) | We switch off Bunny.net's logging and keep nothing. People outside Europe are served by a server in their own region. |
| A **feedback message** you send yourself, optionally with technical info: app and Android version, device model, your chosen town (name and country code), the time zone of the town and of your phone, your in-app settings, whether notifications are on, whether battery saving restricts the app, and when the app last fetched the weather and last ran in the background | To answer you and improve the app | Us, through your **own** mail or messaging app (SunMoment sends nothing itself) | Legitimate interest: handling your request (Art. 6(1)(f)) | Until at most 12 months after your question is resolved; earlier on request |
| Only if you **link your household** yourself (Settings → Household): your own runs "on solar power" from the last 70 days (which day which appliance ran on the sun, for example "25-10 washing machine"), and for your own appliances how many kWh one run uses. Your phone **encrypts** this first (AES-256-GCM). The key is only in the pairing code and only on the linked phones. Plus a check number, so that only your household's phones can change the block, and, as with any internet request, your **IP address** and the time. This happens when you open the app or return to it, after "Started" or "Undo", on the Household screen, and during the background tasks in the morning and evening | So you can see together what ran on the sun, and what the others already started | A small SunMoment script at **Bunny.net** (BunnyWay d.o.o., Slovenia; Bunny Edge Scripting and Bunny Storage, stored in the EU, in Frankfurt). It keeps one encrypted block per phone under random numbers: no name, no town, no email. We and Bunny.net cannot read it; only the linked phones can. Bunny.net acts on our behalf (Bunny.net's data processing agreement) | Consent: you link yourself (Art. 6(1)(a)). Unlink and it stops | Until you unlink; then your phone's block is deleted. A block not updated for 180 days is deleted by the script the next time a phone of your household connects. If nobody uses the household any more, the encrypted block stays: so unlink before you uninstall the app. The script itself logs nothing. At most 8 phones per household. Anyone with the pairing code can see along: share it only within your household. |
| Your **rating**, if you give one | At your 5th and 25th "Started", Google's own rating dialog may appear | Google Play, directly | Google Play's terms | As set by Google |

The technical info is on by default. You see it in full before sending and can switch it off or delete it. We run **no server of our own**, only a small sync script at Bunny.net. It works only if you link your household, and it keeps only encrypted blocks that we cannot read. Apart from that, the app sends us nothing by itself.

## Your rights
You can ask for access to, correction, deletion, restriction or transfer of the data we hold about you (only messages you sent us). Contact: [e-mail address].

**Right to object:** you can always object to processing based on legitimate interest. If you do not want your IP address to reach Bright Sky or Bunny.net, the app cannot fetch a forecast; uninstalling the app stops it at once. No longer want to share your log with your household? Then unlink.

Delete everything on your phone yourself: uninstall the app, or choose Settings → Apps → SunMoment → Storage → Clear data. You can complain to the data protection authority in your country: Netherlands – Autoriteit Persoonsgegevens; Belgium – Gegevensbeschermingsautoriteit / Autorité de protection des données; Germany – your state's authority or the BfDI; Austria – Datenschutzbehörde; Switzerland – EDÖB (the Swiss data protection act also applies to you; your rights are similar); Liechtenstein – Datenschutzstelle; Luxembourg – CNPD; United Kingdom – ICO (the UK GDPR applies to you); France – CNIL; Denmark – Datatilsynet; other countries – the data protection authority of your country, if there is one. Your own country's privacy law may also apply; we give everyone the rights above, wherever you live.

## Purchases
After a 21-day trial you can buy SunMoment once. This runs entirely through Google Play; Google's terms and privacy policy apply. We receive no payment details. Google only shows us order details, such as the order number, the country and the amount. We keep those as long as tax law requires. At every start, the app asks Google Play whether you bought SunMoment, and whether buying is possible on this phone. If it clearly is not (for example in a country without paid apps), the app stays free. Both answers stay on your phone. When your trial started is also stored only on your phone.

## Links to sources
If you tap a source in the app (for example under the tips), your browser opens that website. The website then sees your IP address, as with any visit. This only happens when you tap.

## Children
SunMoment is not made for children and does not ask anyone's age.

## Changes
If anything changes in the data the app uses, we update this policy. You can see that from the date at the top.

---

# Datenschutzerklärung SunMoment (Deutsch)

*Zuletzt aktualisiert: 26. Oktober 2026*

SunMoment ist eine App für Haushalte mit Solaranlage oder Balkonkraftwerk. Sie zeigt, wann dein Dach genug Strom für deine Geräte liefert. Kurz gesagt: **Die App nutzt fast keine Daten, und wir können keine davon lesen, außer du schickst sie uns selbst.** Verbindest du deinen Haushalt, speichert ein kleines Skript von uns euer gemeinsames Protokoll, verschlüsselt. Wir können es nicht lesen.

## Verantwortlich
Gala Apps, Einzelunternehmen in den Niederlanden, Handelsregister KvK Nr. 87752131, Keurenplein 41 Box C9874, 1069CD Amsterdam.
Fragen zum Datenschutz: gala.apps11@gmail.com.

## Was auf deinem Handy bleibt
Sprache und Land, der gewählte Ort, deine Module, Ausrichtung und Neigung, deine Geräte und Timer-Einstellungen, deine Antworten auf „Hat die Vorhersage gestern gestimmt?“, selbst eingetragene Tageserträge, deine „Gestartet“-Häkchen (außer du verbindest deinen Haushalt, siehe unten) und die zuletzt geladene Vorhersage. Es gibt **kein Konto**. Die App fragt nicht nach Name, E-Mail-Adresse, Adresse oder Telefonnummer, nutzt kein GPS und enthält keine Werbung und keine Analyse- oder Tracking-Software. Cloud-Sicherung und Übertragung auf ein neues Handy sind für diese App **ausgeschaltet**. Neues Handy? Dann richtest du die App in einer Minute neu ein.

## Was dein Handy verlässt, und warum

| Was | Warum | An wen | Rechtsgrundlage (DSGVO) | Wie lange |
|---|---|---|---|---|
| Die **gerundeten** Koordinaten deines Ortes (ein Gebiet von etwa 10 km, nicht deine Adresse), dazu, was jede Internetanfrage enthält: deine **IP-Adresse**, die Uhrzeit und der Name der App. Das passiert zuerst in den zehn ausführlich unterstützten Ländern (NL, BE, DE, AT, CH, LI, LU, GB, FR, DK); in anderen Ländern nur, wenn unsere eigenen Wetterdateien nicht erreichbar oder älter als 48 Stunden sind | Die Wettervorhersage laden, die die App braucht | **Bright Sky** (api.brightsky.dev): ein eigenständiger, kostenloser Dienst eines privaten Entwicklers in Deutschland, der die offenen Daten des Deutschen Wetterdienstes (DWD) bereitstellt | Berechtigtes Interesse: Ohne Vorhersage funktioniert die App nicht (Art. 6 Abs. 1 lit. f) | Das bestimmt Bright Sky selbst; Bright Sky veröffentlicht keine Speicherdauer. Für den Umgang mit diesen Daten ist Bright Sky selbst verantwortlich. Wir haben keine Vereinbarung mit Bright Sky, sehen dessen Logs nicht ein und erhalten von dort nichts. |
| Nur das **Feld von etwa 1000 km** um deinen Ort (zum Beispiel „50–60° Nord, 0–10° Ost“), dazu deine **IP-Adresse**, die Uhrzeit und der Name der App. Das passiert außerhalb der zehn ausführlich unterstützten Länder (auch zum Beispiel in Italien oder Spanien) oder wenn Bright Sky keine Vorhersage hat | Die Vorhersage aus unseren eigenen Wetterdateien abrufen (das ICON-Modell des DWD) | **Bunny.net** (BunnyWay d.o.o., Slowenien), das die Dateien für uns speichert und über sein Netz ausliefert. Dein Handy bekommt sie vom nächstgelegenen Server; in Europa ist das ein Server in Europa. Bunny.net arbeitet in unserem Auftrag (Auftragsverarbeitungsvertrag von Bunny.net) | Berechtigtes Interesse: ohne Vorhersage funktioniert die App nicht (Art. 6 Abs. 1 lit. f) | Wir schalten die Protokolle von Bunny.net aus und speichern nichts. Wer außerhalb Europas wohnt, wird von einem Server in der eigenen Region bedient. |
| Eine **Feedback-Nachricht**, die du selbst schickst, wahlweise mit technischen Infos: App- und Android-Version, Gerätemodell, dein gewählter Ort (Name und Ländercode), die Zeitzone von Ort und Handy, deine Einstellungen in der App, ob Benachrichtigungen an sind, ob Energiesparen die App einschränkt, und wann die App zuletzt das Wetter geladen hat und im Hintergrund lief | Dir antworten und die App verbessern | Uns, über deine **eigene** Mail- oder Messenger-App (SunMoment selbst sendet nichts) | Berechtigtes Interesse: deine Anfrage bearbeiten (Art. 6 Abs. 1 lit. f) | Höchstens 12 Monate nach Erledigung deiner Frage; auf Wunsch früher |
| Nur wenn du selbst **deinen Haushalt verbindest** (Einstellungen → Haushalt): deine eigenen Durchgänge „mit eigener Sonne“ der letzten 70 Tage (an welchem Tag welches Gerät mit Sonnenstrom lief, zum Beispiel „25-10 Waschmaschine“), und für deine eigenen Geräte, wie viele kWh ein Durchgang braucht. Dein Handy **verschlüsselt** das vorher (AES-256-GCM). Der Schlüssel steckt nur im Kopplungscode und liegt nur auf den gekoppelten Handys. Dazu eine Prüfzahl, damit nur eure Handys den Block ändern können, und, wie bei jeder Internetanfrage, deine **IP-Adresse** und die Uhrzeit. Das passiert, wenn du die App öffnest oder zu ihr zurückkehrst, nach „Gestartet“ oder „Rückgängig“, auf dem Bildschirm Haushalt und bei den Hintergrundaufgaben morgens und abends | Damit ihr zusammen seht, was mit Sonnenstrom lief und was die anderen schon eingeschaltet haben | Ein kleines Skript von SunMoment bei **Bunny.net** (BunnyWay d.o.o., Slowenien; Bunny Edge Scripting und Bunny Storage, Speicherung in der EU, in Frankfurt). Es speichert pro Handy einen verschlüsselten Block unter zufälligen Nummern: kein Name, kein Ort, keine E-Mail. Wir und Bunny.net können ihn nicht lesen; nur die gekoppelten Handys können das. Bunny.net arbeitet in unserem Auftrag (Auftragsverarbeitungsvertrag von Bunny.net) | Einwilligung: Du koppelst selbst (Art. 6 Abs. 1 lit. a). Entkoppelst du, endet es | Bis du entkoppelst; dann wird der Block deines Handys gelöscht. Ein Block, der 180 Tage nicht aktualisiert wurde, wird vom Skript gelöscht, sobald sich ein Handy eures Haushalts wieder verbindet. Nutzt niemand den Haushalt mehr, bleibt der verschlüsselte Block liegen: Entkopple deshalb, bevor du die App löschst. Das Skript selbst protokolliert nichts. Höchstens 8 Handys pro Haushalt. Wer den Kopplungscode hat, kann mitlesen: Teile ihn nur in deinem Haushalt. |
| Deine **Bewertung**, wenn du eine abgibst | Beim 5. und 25. „Gestartet“ kann das Bewertungsfenster von Google erscheinen | Google Play, direkt | Bedingungen von Google Play | Nach Google |

Die technischen Infos sind standardmäßig an. Du siehst sie vor dem Senden vollständig und kannst sie ausschalten oder löschen. Wir betreiben **keinen eigenen Server**, nur ein kleines Synchronisations-Skript bei Bunny.net. Es arbeitet nur, wenn du deinen Haushalt verbindest, und speichert nur verschlüsselte Blöcke, die wir nicht lesen können. Sonst sendet uns die App von sich aus nichts.

## Deine Rechte
Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung und Datenübertragbarkeit für die Daten, die wir von dir haben (nur Nachrichten, die du uns geschickt hast). Kontakt: [E-Mail-Adresse].

**Widerspruchsrecht:** Du kannst jederzeit der Verarbeitung auf Grundlage berechtigter Interessen widersprechen. Möchtest du nicht, dass deine IP-Adresse an Bright Sky oder Bunny.net geht, kann die App keine Vorhersage laden; deinstallierst du die App, endet es sofort. Willst du dein Protokoll nicht mehr mit deinem Haushalt teilen? Dann entkopple.

Alle Daten auf deinem Handy löschst du selbst: Deinstalliere die App, oder wähle Einstellungen → Apps → SunMoment → Speicher → Daten löschen. Beschwerden kannst du bei der Datenschutzbehörde in deinem Land einreichen: in Deutschland bei der Aufsichtsbehörde deines Bundeslandes oder beim BfDI, in Österreich bei der Datenschutzbehörde (dsb.gv.at), in den Niederlanden bei der Autoriteit Persoonsgegevens, in Belgien bei der Datenschutzbehörde (GBA/APD), in der Schweiz beim EDÖB (für dich gilt auch das Schweizer Datenschutzgesetz; deine Rechte sind ähnlich), in Liechtenstein bei der Datenschutzstelle, in Luxemburg bei der CNPD, im Vereinigten Königreich beim ICO (für dich gilt die UK GDPR), in Frankreich bei der CNIL, in Dänemark beim Datatilsynet, in anderen Ländern bei der Datenschutzbehörde deines Landes, falls es eine gibt. Dort kann auch ein eigenes Datenschutzgesetz gelten; die Rechte oben geben wir allen, egal wo du wohnst.

## Käufe
Nach 21 Tagen Test kannst du SunMoment einmal kaufen. Das läuft vollständig über Google Play; dafür gelten die Bedingungen und die Datenschutzerklärung von Google. Wir erhalten keine Zahlungsdaten. Google zeigt uns nur Angaben zur Bestellung, etwa die Bestellnummer, das Land und den Betrag. Diese bewahren wir so lange auf, wie das Steuerrecht es verlangt. Die App fragt Google Play bei jedem Start, ob du SunMoment gekauft hast und ob Kaufen auf diesem Handy möglich ist. Geht das eindeutig nicht (zum Beispiel in einem Land ohne kostenpflichtige Apps), bleibt die App kostenlos. Beide Antworten bleiben auf deinem Handy. Wann dein Test begann, steht ebenfalls nur auf deinem Handy.

## Links zu Quellen
Tippst du in der App auf eine Quelle (zum Beispiel bei den Tipps), öffnet dein Browser diese Website. Die Website sieht dann deine IP-Adresse, wie bei jedem Besuch. Das passiert nur, wenn du selbst tippst.

## Kinder
SunMoment ist nicht für Kinder gemacht und fragt niemanden nach seinem Alter.

## Änderungen
Ändert sich etwas daran, welche Daten die App nutzt, passen wir diese Erklärung an. Das siehst du am Datum oben.

---

# Privatlivspolitik for SunMoment (dansk)

*Senest opdateret: 26. oktober 2026*

SunMoment er en app til husstande med solceller. Den fortæller dig, hvornår dit tag producerer nok strøm til dine apparater. Det korte svar: **appen bruger næsten ingen data, og vi kan ikke læse noget af det, medmindre du selv sender det til os.** Forbinder du din husstand, gemmer et lille script fra os jeres fælles logbog, krypteret. Vi kan ikke læse den.

## Hvem er ansvarlig?
Gala Apps, enkeltmandsvirksomhed i Nederlandene, nr. i det nederlandske handelsregister (KvK) 87752131, Keurenplein 41 Box C9874, 1069CD Amsterdam.
Spørgsmål om privatliv: gala.apps11@gmail.com.

## Hvad bliver på din telefon
Dit sprog og land, den by, du har valgt, dine paneler, tagets retning og hældning, dine apparater og timerindstillinger, dine svar på »Passede gårsdagens vejrudsigt?«, den dagsproduktion, du selv skriver ind, dine »Startet«-flueben (undtagen hvis du forbinder din husstand, se nedenfor) og den senest hentede vejrudsigt. Der er **ingen konto**. Appen spørger ikke om navn, e-mail, adresse eller telefonnummer, bruger ikke GPS og indeholder ingen reklamer og ingen analyse- eller sporingssoftware. Backup i skyen og overførsel fra telefon til telefon er **slået fra** for denne app. Ny telefon? Så sætter du appen op igen på et minut.

## Hvad forlader din telefon, og hvorfor

| Hvad | Hvorfor | Til hvem | Retsgrundlag (GDPR) | Hvor længe |
|---|---|---|---|---|
| De **afrundede** koordinater for den by, du har valgt (et område på ca. 10 km, ikke din adresse), plus det, som enhver forespørgsel på internettet indeholder: din **IP-adresse**, tidspunktet og appens navn. Det sker først i de ti udførligt understøttede lande (NL, BE, DE, AT, CH, LI, LU, GB, FR, DK); i andre lande kun, når vores egne vejrfiler ikke kan nås eller er over 48 timer gamle | For at hente den vejrudsigt, appen har brug for | **Bright Sky** (api.brightsky.dev): en selvstændig, gratis tjeneste, som drives af en privat udvikler i Tyskland, og som videregiver de åbne data fra den tyske vejrtjeneste DWD | Legitim interesse: appen kan ikke fungere uden en vejrudsigt (art. 6, stk. 1, litra f) | Det bestemmer Bright Sky selv; Bright Sky offentliggør ingen opbevaringsperiode. Bright Sky er selv ansvarlig for, hvad tjenesten gør med disse data. Vi har ingen aftale med Bright Sky, kan ikke se tjenestens logfiler og modtager intet fra den. |
| Kun **feltet på ca. 1000 km** omkring din by (for eksempel "50–60° nord, 0–10° øst"), plus din **IP-adresse**, tidspunktet og appens navn. Det sker uden for de ti udførligt understøttede lande (også for eksempel i Italien eller Spanien), eller når Bright Sky ikke har en vejrudsigt | Hente vejrudsigten fra vores egne vejrfiler (DWD's ICON-model) | **Bunny.net** (BunnyWay d.o.o., Slovenien), der gemmer filerne for os og leverer dem via sit netværk. Din telefon får dem fra den nærmeste server; i Europa er det en server i Europa. Bunny.net handler på vores vegne (Bunny.nets databehandleraftale) | Legitim interesse: uden vejrudsigt virker appen ikke (art. 6, stk. 1, litra f) | Vi slår Bunny.nets logning fra og gemmer intet. Den, der bor uden for Europa, betjenes af en server i sin egen region. |
| En **feedbackbesked**, som du selv sender, eventuelt med teknisk info: app- og Android-version, telefonmodel, den by, du har valgt (navn og landekode), tidszonen for byen og telefonen, dine indstillinger i appen, om notifikationer er slået til, om batterisparing begrænser appen, og hvornår appen sidst hentede vejret og sidst kørte i baggrunden | For at svare dig og forbedre appen | Os, via din **egen** mail- eller beskedapp (SunMoment sender ikke selv noget) | Legitim interesse: at behandle din henvendelse (art. 6, stk. 1, litra f) | Højst 12 måneder, efter at dit spørgsmål er besvaret; før, hvis du beder om det |
| Kun hvis du selv **forbinder din husstand** (Indstillinger → Husstand): dine egne omgange »på egen sol« fra de sidste 70 dage (hvilken dag hvilket apparat kørte på solen, for eksempel »25-10 vaskemaskine«), og for dine egne apparater, hvor mange kWh én omgang bruger. Din telefon **krypterer** det først (AES-256-GCM). Nøglen findes kun i koblingskoden og kun på de koblede telefoner. Desuden et kontroltal, så kun jeres telefoner kan ændre blokken, og, som ved enhver forespørgsel på internettet, din **IP-adresse** og tidspunktet. Det sker, når du åbner appen eller vender tilbage til den, efter »Startet« eller »Fortryd«, på skærmen Husstand og ved baggrundsopgaverne om morgenen og om aftenen | Så I sammen kan se, hvad der kørte på solen, og hvad de andre allerede har tændt | Et lille script fra SunMoment hos **Bunny.net** (BunnyWay d.o.o., Slovenien; Bunny Edge Scripting og Bunny Storage, opbevaring i EU, i Frankfurt). Det gemmer én krypteret blok pr. telefon under tilfældige numre: intet navn, ingen by, ingen e-mail. Hverken vi eller Bunny.net kan læse den; det kan kun de koblede telefoner. Bunny.net handler på vores vegne (Bunny.nets databehandleraftale) | Samtykke: du kobler selv (art. 6, stk. 1, litra a). Kobler du fra, stopper det | Indtil du kobler fra; så slettes din telefons blok. En blok, der ikke er opdateret i 180 dage, slettes af scriptet, næste gang en telefon i jeres husstand forbinder sig. Bruger ingen husstanden mere, bliver den krypterede blok liggende: kobl derfor fra, før du sletter appen. Scriptet logger ikke selv noget. Højst 8 telefoner pr. husstand. Den, der har koblingskoden, kan se med: del den kun med din husstand. |
| Din **bedømmelse**, hvis du giver en | Når du har trykket »Startet« for 5. og 25. gang, kan Googles eget bedømmelsesvindue blive vist | Google Play, direkte | Google Plays vilkår | Som Google bestemmer |

Den tekniske info er slået til som standard. Du ser den i sin helhed, før du sender, og du kan slå den fra eller slette den. Vi har **ingen egen server**, kun et lille synkroniseringsscript hos Bunny.net. Det virker kun, hvis du forbinder din husstand, og det gemmer kun krypterede blokke, som vi ikke kan læse. Ellers sender appen ikke os noget af sig selv.

## Dine rettigheder
Du kan bede om indsigt i, berigtigelse, sletning, begrænsning eller overførsel af de data, vi har om dig (det er kun beskeder, du selv har sendt os). Kontakt: [e-mailadresse].

**Ret til indsigelse:** du kan altid gøre indsigelse mod behandling, der bygger på legitim interesse. Vil du ikke have, at din IP-adresse sendes til Bright Sky eller Bunny.net, kan appen ikke hente en vejrudsigt; afinstallerer du appen, stopper det med det samme. Vil du ikke længere dele din logbog med din husstand? Så kobl fra.

Du sletter selv alt på din telefon: afinstaller appen, eller vælg Indstillinger → Apps → SunMoment → Lagerplads → Ryd data. Du kan klage til datatilsynet i dit land:
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
Efter 21 dages prøveperiode kan du købe SunMoment én gang. Det foregår helt via Google Play; Googles vilkår og privatlivspolitik gælder. Vi modtager ingen betalingsoplysninger. Google viser os kun oplysninger om ordren, som ordrenummer, land og beløb. Dem gemmer vi så længe, som skattereglerne kræver. Appen spørger Google Play ved hver start, om du har købt SunMoment, og om det er muligt at købe på denne telefon. Kan det tydeligvis ikke lade sig gøre (for eksempel i et land uden betalte apps), forbliver appen gratis. Begge svar bliver på din telefon. Hvornår din prøveperiode begyndte, gemmes også kun på din telefon.

## Links til kilder
Trykker du på en kilde i appen (for eksempel under tipsene), åbner din browser den hjemmeside. Hjemmesiden ser så din IP-adresse, som ved ethvert besøg. Det sker kun, når du selv trykker.

## Børn
SunMoment er ikke lavet til børn og spørger ingen om deres alder.

## Ændringer
Ændres der noget i, hvilke data appen bruger, opdaterer vi denne politik. Det kan du se på datoen øverst.

---

# Politique de confidentialité SunMoment (français)

*Dernière mise à jour : 26 octobre 2026*

SunMoment est une appli pour les foyers équipés de panneaux solaires. Elle vous indique quand votre toit produit assez d’électricité pour vos appareils. En bref : **l’appli n’utilise presque aucune donnée, et nous ne pouvons rien en lire, sauf ce que vous nous envoyez vous-même.** Si vous reliez votre foyer, un petit script à nous garde votre journal commun, chiffré. Nous ne pouvons pas le lire.

## Qui est responsable ?
Gala Apps, entreprise individuelle aux Pays-Bas, numéro à la Chambre de commerce (KvK) 87752131, Keurenplein 41 Box C9874, 1069CD Amsterdam.
Questions sur la confidentialité : gala.apps11@gmail.com.

## Ce qui reste sur votre téléphone
Votre langue et votre pays, la ville choisie, vos panneaux, l’orientation et l’inclinaison de votre toit, vos appareils et vos réglages de départ différé, vos réponses à « La prévision d’hier était-elle juste ? », les productions du jour que vous saisissez, vos coches « Lancé » (sauf si vous reliez votre foyer, voir plus bas) et la dernière prévision téléchargée. Il n’y a **pas de compte** : l’appli ne demande ni nom, ni e-mail, ni adresse, ni numéro de téléphone, n’utilise pas le GPS, et ne contient ni publicité ni logiciel d’analyse ou de suivi. La sauvegarde dans le cloud et le transfert vers un autre téléphone sont **désactivés** pour cette appli. Nouveau téléphone ? Vous configurez l’appli à nouveau en une minute.

## Ce qui quitte votre téléphone, et pourquoi

| Quoi | Pourquoi | À qui | Base légale (RGPD) | Combien de temps |
|---|---|---|---|---|
| Les coordonnées **arrondies** de la ville choisie (une zone d’environ 10 km, pas votre adresse), plus ce que contient toute requête Internet : votre **adresse IP**, l’heure et le nom de l’appli. Cela se produit d’abord dans les dix pays détaillés (NL, BE, DE, AT, CH, LI, LU, GB, FR, DK) ; dans les autres pays, seulement quand nos propres fichiers météo sont inaccessibles ou datent de plus de 48 heures | Récupérer la prévision météo dont l’appli a besoin | **Bright Sky** (api.brightsky.dev) : un service indépendant et gratuit géré par un développeur privé en Allemagne, qui diffuse les données ouvertes du service météo allemand DWD | Intérêt légitime : l’appli ne peut pas fonctionner sans prévision (art. 6, par. 1, point f) | C’est Bright Sky qui décide ; il ne publie pas de durée de conservation. Bright Sky est lui-même responsable de ce qu’il fait de ces données. Nous n’avons pas d’accord avec Bright Sky, ne pouvons pas voir ses journaux et ne recevons rien de lui. |
| Seulement le **carré d’environ 1000 km** autour de votre ville (par exemple « 50–60° nord, 0–10° est »), plus votre **adresse IP**, l’heure et le nom de l’appli. Cela se produit hors des dix pays détaillés (aussi par exemple en Italie ou en Espagne), ou quand Bright Sky n’a pas de prévision | Obtenir la prévision depuis nos propres fichiers météo (le modèle ICON du DWD) | **Bunny.net** (BunnyWay d.o.o., Slovénie), qui stocke les fichiers pour nous et les fournit via son réseau. Votre téléphone les reçoit du serveur le plus proche ; en Europe, c’est un serveur en Europe. Bunny.net agit pour notre compte (accord de traitement de Bunny.net) | Intérêt légitime : sans prévision, l’appli ne fonctionne pas (art. 6, par. 1, point f) | Nous désactivons les journaux de Bunny.net et ne gardons rien. Hors d’Europe, un serveur de votre région vous sert. |
| Un **message de retour** que vous envoyez vous-même, avec si vous le souhaitez des infos techniques : version de l’appli et d’Android, modèle de l’appareil, la ville choisie (nom et code pays), le fuseau horaire de la ville et du téléphone, vos réglages dans l’appli, si les notifications sont activées, si l’économie de batterie limite l’appli, et quand l’appli a récupéré la météo et tourné en arrière-plan pour la dernière fois | Vous répondre et améliorer l’appli | Nous, via **votre propre** appli de mail ou de messagerie (SunMoment n’envoie rien lui-même) | Intérêt légitime : traiter votre demande (art. 6, par. 1, point f) | Au plus 12 mois après le traitement de votre question ; plus tôt sur demande |
| Seulement si vous **reliez vous-même votre foyer** (Paramètres → Foyer) : vos propres cycles « au soleil » des 70 derniers jours (quel jour quel appareil a tourné au soleil, par exemple « 25-10 lave-linge »), et pour vos propres appareils, combien de kWh consomme un cycle. Votre téléphone **chiffre** cela d’abord (AES-256-GCM). La clé se trouve seulement dans le code de liaison et seulement sur les téléphones reliés. En plus, un nombre de contrôle, pour que seuls les téléphones de votre foyer puissent modifier le bloc, et, comme pour toute requête Internet, votre **adresse IP** et l’heure. Cela se produit quand vous ouvrez l’appli ou y revenez, après « Lancé » ou « Annuler », sur l’écran Foyer, et lors des tâches en arrière-plan du matin et du soir | Pour voir ensemble ce qui a tourné au soleil, et ce que les autres ont déjà lancé | Un petit script de SunMoment chez **Bunny.net** (BunnyWay d.o.o., Slovénie ; Bunny Edge Scripting et Bunny Storage, stockage dans l’UE, à Francfort). Il garde un bloc chiffré par téléphone sous des numéros aléatoires : pas de nom, pas de ville, pas d’e-mail. Ni nous ni Bunny.net ne pouvons le lire ; seuls les téléphones reliés le peuvent. Bunny.net agit pour notre compte (accord de traitement de Bunny.net) | Consentement : vous reliez vous-même (art. 6, par. 1, point a). Si vous déliez, cela s’arrête | Jusqu’à ce que vous déliiez ; le bloc de votre téléphone est alors supprimé. Un bloc non mis à jour depuis 180 jours est supprimé par le script dès qu’un téléphone de votre foyer se reconnecte. Si plus personne n’utilise le foyer, le bloc chiffré reste : déliez donc avant de désinstaller l’appli. Le script lui-même ne journalise rien. Au plus 8 téléphones par foyer. Toute personne qui a le code de liaison peut voir le journal : partagez-le seulement au sein de votre foyer. |
| Votre **note**, si vous en donnez une | À votre 5e et à votre 25e « Lancé », la fenêtre de notation de Google peut apparaître | Google Play, directement | Conditions de Google Play | Selon Google |

Les infos techniques sont activées par défaut. Vous les voyez en entier avant l’envoi et pouvez les désactiver ou les supprimer. Nous n’avons **pas de serveur à nous**, seulement un petit script de synchronisation chez Bunny.net. Il ne fonctionne que si vous reliez votre foyer, et ne garde que des blocs chiffrés que nous ne pouvons pas lire. Sinon, l’appli ne nous envoie rien d’elle-même.

## Vos droits
Vous pouvez demander l’accès, la rectification, l’effacement, la limitation ou la portabilité des données que nous avons sur vous (uniquement les messages que vous nous avez envoyés). Contact : [adresse e-mail].

**Droit d’opposition :** vous pouvez toujours vous opposer à un traitement fondé sur l’intérêt légitime. Si vous ne voulez pas que votre adresse IP parvienne à Bright Sky ou à Bunny.net, l’appli ne peut pas récupérer de prévision ; désinstaller l’appli y met fin aussitôt. Vous ne voulez plus partager votre journal avec votre foyer ? Déliez alors les téléphones.

Pour effacer vous-même tout ce qui est sur votre téléphone, désinstallez l’appli, ou choisissez Paramètres → Applications → SunMoment → Stockage → Effacer les données. Vous pouvez porter plainte auprès de l’autorité de protection des données de votre pays : Pays-Bas – Autoriteit Persoonsgegevens ; Belgique – Autorité de protection des données / Gegevensbeschermingsautoriteit ; Allemagne – l’autorité de votre Land ou le BfDI ; Autriche – Datenschutzbehörde ; Suisse – PFPDT / EDÖB (la loi suisse sur la protection des données s’applique aussi à vous ; vos droits sont comparables) ; Liechtenstein – Datenschutzstelle ; Luxembourg – CNPD ; Royaume-Uni – ICO (le UK GDPR s’applique à vous) ; France – CNIL (https://www.cnil.fr/) ; Danemark – Datatilsynet ; autres pays – l’autorité de protection des données de votre pays, s’il y en a une. La loi de votre pays peut aussi s’appliquer ; nous accordons à tous les droits ci-dessus, où que vous viviez.

## Achats
Après un essai de 21 jours, vous pouvez acheter SunMoment une seule fois. Cela passe entièrement par Google Play ; les conditions et la politique de confidentialité de Google s’appliquent. Nous ne recevons aucune donnée de paiement. Google nous montre seulement des informations sur la commande, comme le numéro de commande, le pays et le montant. Nous les conservons aussi longtemps que la loi fiscale l’exige. À chaque démarrage, l’appli demande à Google Play si vous avez acheté SunMoment, et si l’achat est possible sur ce téléphone. Si ce n’est clairement pas le cas (par exemple dans un pays sans applis payantes), l’appli reste gratuite. Les deux réponses restent sur votre téléphone. La date de début de votre essai est elle aussi enregistrée uniquement sur votre téléphone.

## Liens vers les sources
Si vous touchez une source dans l’appli (par exemple sous les conseils), votre navigateur ouvre ce site. Le site voit alors votre adresse IP, comme pour toute visite. Cela n’arrive que si vous touchez vous-même.

## Enfants
SunMoment n’est pas conçu pour les enfants et ne demande l’âge de personne.

## Modifications
Si les données utilisées par l’appli changent, nous mettons à jour cette politique. Vous le voyez à la date en haut.
