# Welcome bij de Security workshop.

OWASP top 10 in het nederlands

#### A1-Injection

Injectiekwetsbaarheden zoals sql-, os commando- of ldap-injectie, ontstaan wanneer niet-geverifieerde data door een hacker wordt verzonden als onderdeel van een commando of query. Deze data kan onbedoelde commando’s uitvoeren of ongeautoriseerde toegang tot gegevens verschaffen.

  

#### A2-Broken Authentication

Authenticatiecontrole- en sessiebeheermechanismes worden vaak niet correct geïmplementeerd, waardoor aanvallers de identiteit van andere gebruikers aan kunnen nemen.

  

#### A3-Sensitive Data Exposure

Veel applicaties en API-endpoints beschermen gevoelige gegevens onvoldoende. Denk hierbij aan persoonsgegevens, documenten en autorisatiegegevens. Kwaadwillende kunnen deze dan stelen of wijzigen voor creditcardfraude, identiteitsdiefstal of andere misdrijven. Gevoelige gegevens moeten extra worden beschermd door middel van versleuteling of andere speciale voorzorgsmaatregelen.

  

#### A4-XML External Entities

Verouderde of slecht geconfigureerde xml-verwerkers staan vaak het laden van externe entiteiten toe. Aanvallers kunnen dit misbruiken om bijvoorbeeld toegang tot lokale bestanden te krijgen, os-commando’s uit te voeren of DoS-situaties te creëren om het systeem (tijdelijk) onbruikbaar te maken.

  

#### A5-Broken Access Control

Beperkingen wat een gebruiker wel of niet mag uitvoeren binnen een applicatie worden in veel gevallen niet correct afgedwongen. Aanvallers kunnen deze fouten misbruiken om toegang te krijgen tot functionaliteit en/of informatie zonder dat ze hiertoe geautoriseerd zijn.

  

#### A6-Security Misconfiguration

Goede beveiliging vereist een correcte configuratie die wordt afgestemd op de applicatie, frameworks, applicatieserver, webserver, databaseserver en platform. Beveiligingsinstellingen moeten worden gedefinieerd, geïmplementeerd en onderhouden omdat deze standaards vaak onveilig zijn. Daarnaast moet alle software up-to-date zijn.

  

#### A7-Cross-Site Scripting (XSS)

We spreken van xss-injectie als een applicatie gegevens zonder filtering en/of encodering naar een web browser zendt. xss-injectie stelt aanvallers in staat om scripts uit te voeren, gebruikerssessies te kapen, websites te beschadigen of de gebruiker naar andere sites te leiden. [Voorbeeld](https://www.whitehats.nl/owasp-a3-cross-site-scripting-xss-uitleg)

  

#### A8-Insecure Deserialization

Applicaties converteren objecten alvorens deze worden opgeslagen. Het terug converteren van deze objecten gebeurt vaak onveilig en kan worden misbruikt om os commando’s uit te voeren. In sommige gevallen stelt het de applicatie zelfs kwetsbaar op voor andere injectie aanvallen.

  

#### A9-Using Components with Known Vulnerabilities

Componenten zoals libraries, frameworks en andere software-modules draaien vaak met volledige autorisatie. Als een kwetsbaar onderdeel wordt geëxploiteerd kan dit tot dataverlies leiden of een overname van de server faciliteren. Componenten met reeds bekende kwetsbaarheden ondermijnen de beveiliging van de applicatie en faciliteren een scala aan mogelijke aanvallen.

  

#### A10-Insufficient Logging & Monitoring

Een tekort aan logging en monitoring kan aanvallers de tijd geven zich dieper in een systeem te nestelen en proberen zich permanent toegang te verschaffen. Gemiddeld wordt een lek pas na 200+ dagen gedetecteerd. Dit geeft aanvallers voldoende tijd om zelfs toegang te krijgen tot andere systemen en opgeslagen gegevens in te zien, wijzigen of zelfs te verwijderen.

# Webgoat project
Vandaag gebruiken we het webgoat project om te oefenen met OWASP Top 10 problemen.

https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project