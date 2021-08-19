# Elektrik Wohnmobilausbau

********************************************
## Quellen
********************************************
- I: https://campofant.com/wohnmobil-elektrik-selbstausbau/
- I: https://outdoornomaden.de/camper-elektrik/
- I: 12V Laptop Laden: https://www.amumot.de/laptop-im-auto-laden-12v-netzteil/
- I: Doppelbatteriesystem: https://matsch-und-piste.de/doppelt-haelt-besser-doppelbatteriesystem-die-technik-im-ueberblick/
- I: Solaranlage: https://camperstyle.de/solaranlage-auf-dem-wohnmobil/#1-dach-vorreinigen

********************************************        
## Themen
********************************************

### Allgemeines:
- ? Sicherungskasten für feuchträume
- ? FI schutzschalter 230V
- I: 12V und 230V stets getrennt verlegen
- I: 12V und 230V innerhalb verschiedener Verteilerdose
- I: Solarregler sorgt dafür dass die Verbraucher direkt über die Sonne beliefert werden und nicht über die Batterie
- ?: Ist es Möglich den Landstrom und die Lima auf den solarregler zu legen
- ?: Ist die Starterbatterie nach hinten abgesichert?
- ?: Hat die Starterbatterie einen Entlüftungsschlauch
- I: XT60 stecker für viel strom
********************************************

### Anschluss:

#### Anschluss position:
1. Beleuchtung
    - !: Zwei Lichter am Bet
    - !: Ein Licht im Wohnraum
    - !: Drei Licht Bei küchenzeile 
    - !: Lichterkette
2. 12V- Anschlüsse
3. 230V~ Anschlüsse
    - !: 1 mal unterm Bett 
    - !: 1 mal in Küche
4. 5V- Anschlüsse usb oder usb-c
    - !: Sicherstellen, dass sie nur strom ziehen wenn sie angschlossen sind.
5. Gaswarner
    - ! 1mal decke einmal boden an belüfteter stelle

#### Kabel:
- !: Lieber ein Kabel mehr legen
- !: "Ölbeständige kabel" "Seekabel für feuchträume verwenden" mit verzinnten kupferlitzen
    - I: H07 V-K = Flexibel mit PVC ummantelung
    - I: H07 V-U = Starr mit PVC ummantelung
    - I: H07 V-R = Starres Seil mit PVC Ummantelung 
    - I verschiedene Kabelarten: https://elektricks.com/welche-kabelart-verwende-ich-wo/
- !: Kurze Strecken -> weniger Leitungsbfall -> geringere kabelquerschnitte
- ?: Querschnitt
- ?: Längen
- I: Verfügbare Querschnitte: 0,50 mm², 0,75 mm², 1,5 mm², 2,5 mm², 4 mm², 6 mm², 10 mm², 16 mm², 25 mm², 35 mm², 50 mm², 70 mm², 95 mm² und 120 mm².
- ?: Rückleitung oder Masse (mit Neutralleiter-Klemme)
1. Querschnitt
    1. 12 V
        - LED Lichter (~ 1mA)
        - ?: Vorschlag: 1,5 mm² LED Lampen; 2.5mm² Verbraucher bis 50 W; 6 mm² zum Hauptschalter
    2. 230 V
        - !: 1,5 mm2

#### Verbindungen:
- ? Keine Lüsterklemmen
- ! Nicht verlöten
- ! Krimpzange + aderendhülsen + 2 Kabel
- ! Wago klemmen 221 222 ohne aderendhülsen

#### Kabelrohr:
- I: Isolierrohr; Wellrohr; Leerrohr; kabekkanal; -> Christian fragen
- I: Stangenrohr
- !: Abzweigdose für Zugänge
********************************************

### Bedinung und Sicherheit

#### Sicherung:
1. Hauptsicherung 
    - I: So nahe wie möglich an den Stromquellen.
    - I: Stück zwischen sicherung und Quelle ist nicht geschützt
   1. 12V-Netz
       - I: Hauptsicherung an minus pol -> dann kein problem mit kurzschluss
       - !: 1 mal an der Steckdose
       - !: 1 mal nach Solarregler und Verbraucher
       - !: 1 mal dirket nach jeder Batterie vor Verteilter
    2. 230V-Netz
        - I: 13A LS Schalter
2. Verbraucher Sicherung
    1. 12V Netz
             - Grosverbraucher einzeln absichern, direkt von batterie
              - Kleinverbraucher sicherungsblock nach solarregler
3. Hauptschalter
- !: Für jede batterie vor Verteiler Hauptschalter

#### Schalter
- ?: Schalter für Kühlbox
- ?: Schalter für Standheizung
- ?: Schalter Umrichter
- !: Schalzer jeweilige lichtbereiche

********************************************
### Batterie

### Batterie Anschluss
- I: Polklemmen
#### Trennrelais auslegung
- I: LiMa ~ 14,4V
- I: Solarregler ~ 
    - Erhaltungsladung 13.8V
    - Volllafung 14,4V

- I Schaltspannunh 13,8V

#### Verteiler
- I: Anzahl der Anschlüsse pro Batterie (  2*(Solar + Lictmaschiene + Landstrom )+ direltanschluss umrichter + direktanschluss standheizung+ direktanschluss kühlbox)
********************************************
### Verbraucher:
1. Kleinverbraucher
    - ? Mit sicherungsblock
2. Großverbraucher
    - ? Mit glassicherun
    - ? Wechselrichter seperat absichern +80 A
3. Zu erwartende Leistung
    1. 12 V
        - X Lampen a 5W 
        - Tauchpumpe 15-24W
        - Kühlschrank 100 W -> an 12V steckdose
        - X Steckdosen a X W
        - Lautsprecher
        - Luftdetektoren

********************************************

### Laden

#### Landstrom
- !: Converter 230V~/12V-
- ?: Umschalter für Batterien
- !: Sicherung (2 mal?)
- !: Kabel + Kabelschuhe

#### Solarstrom
- !: Kabel Solaranalge
- !: Kabel Solarregler
- ?: Sicherung

#### Lichtmaschiene
- !: Schaltrelais
- ?: Sicherung
- ?: Umschalter mit neutral 
- ?: Relais überbrückungsschalter
*******************************************
### Finale Auslegung
1. 12V-Netz
   - I: 12V Hauptsicherung pro Batterie: 120A
   - I: 12V Spannungsgesteueretes Trennrelais 140A 
   - I: 12V Sicherung summe Direktverbraucher: 75A
   - I: 12V Kabelquerschnitt Direktverbraucher: 6mm³
   - I: 12V Kabelquerschnitt Kleinverbraucher: 1.5mm²
   - I: 12V Ladekabel 35 mm²
2. 230V-Netz
   - I: 230V Hauptsicherung 13A LS un 0.03A FI
   - I: 230V 1.5mm² Leitungsquerschnitt
********************************************
### Bauteile 

#### Einlaufsliste
1. 12V- Netz
   1. Batterieanschluss
      - [x] Hauptschalter starterbatterie + Relais überbrückung
        - I Max:1000A Nenn 150A: https://www.amazon.de/ZHANChen-Batterieschalter-Trennschalter-Hauptschalter-Fahrzeuge/dp/B082SWCJVY/ref=sr_1_2?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=12V+Hauptschalter+400A&qid=1629128887&sr=8-2
      - [x] Hauptsicherung Batterie (120A) 
        - I: https://www.amazon.de/Mottdam-Schutzschalter-Leitungsschutzschalter-Sicherung-Leistungsschalter/dp/B087RBP72R/ref=sr_1_14?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=12V%2Bsicherungsautomat%2B50A&qid=1629115391&sr=8-14&th=1
        - I: https://www.amazon.de/Bestine-Schutzschalter-Sicherungshalter-Trolling-Inline-Wechselrichterrelais/dp/B08F1XQWB1/ref=sr_1_19?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=12V%2Bsicherungsautomat%2B50A&qid=1629115531&sr=8-19&th=1
      <!--- [ ] 12V Hauptschalter (~200A) -->
      - [ ] Batteriekabel Laden 35mm²
      - [ ] Batteriekabel Verbraucher 35mm² 
      - [x] Polklemmen
        - I: https://www.amazon.de/IWILCS-Batterieklemmen-Autobatterie-Schnellklemmen-Steckverbinder/dp/B08Y8CDKYR/ref=sr_1_16?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=33DWANXP3OBRG&dchild=1&keywords=polklemmen+autobatterie+12v&qid=1629115680&sprefix=Polklemmen%2Caps%2C191&sr=8-16
   2. Laden
      - [x] Trennrelias (~150A)
        - I: https://www.amazon.de/Spannungsgesteuertes-Trennrelais-140A-Wohnmobil-Boot/dp/B08HZ36V9T/ref=mp_s_a_1_11?adgrpid=77940202064&dchild=1&gclid=CjwKCAjw9uKIBhA8EiwAYPUS3DmWc9MyF2AEFwP8lVaHVYM3RjZ8xUxg8-IzMXiUYrtt92HUFh5J7hoCLlUQAvD_BwE&hvadid=482238871864&hvdev=m&hvlocphy=9041988&hvnetw=g&hvqmt=b&hvrand=15889686153418161721&hvtargid=kwd-301240286553&hydadcr=26544_2418474&keywords=autobatterie+trennrelais&qid=1629026534&sr=8-11
        - I 140A: https://www.amazon.de/Batterie-vollautomatisches-Trennrelais-Ampere-Drive/dp/B01G8ZVR16/ref=mp_s_a_1_6?adgrpid=77940202064&dchild=1&gclid=CjwKCAjw9uKIBhA8EiwAYPUS3DmWc9MyF2AEFwP8lVaHVYM3RjZ8xUxg8-IzMXiUYrtt92HUFh5J7hoCLlUQAvD_BwE&hvadid=482238871864&hvdev=m&hvlocphy=9041988&hvnetw=g&hvqmt=b&hvrand=15889686153418161721&hvtargid=kwd-301240286553&hydadcr=26544_2418474&keywords=autobatterie+trennrelais&qid=1629026624&sr=8-6
      - [x] Batteriewechselschalter
        - I: https://www.awn.de/products/batterie-umschalter-12v-100a?variant=31559123140743
        - I max 1000A, nenn 60A: https://www.ebay.de/itm/154291886548?hash=item23ec8359d4:g:uZkAAOSwmddf~-g6 
   3. Direktverbraucher
      - [x] Hauptsicherung 100A 
         - I: https://www.amazon.de/Mottdam-Schutzschalter-Leitungsschutzschalter-Sicherung-Leistungsschalter/dp/B087RBP72R/ref=sr_1_14?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=12V%2Bsicherungsautomat%2B50A&qid=1629115391&sr=8-14&th=1
         - I: https://www.amazon.de/Bestine-Schutzschalter-Sicherungshalter-Trolling-Inline-Wechselrichterrelais/dp/B08F1XQWB1/ref=sr_1_19?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=12V%2Bsicherungsautomat%2B50A&qid=1629115531&sr=8-19&th=1
      - [x] Verteilerblock 100A
         - I 100A pro panel 30A pro sicherung: https://www.amazon.de/Sicherungshalter-Sicherungskasten-Flachsicherungen-Wasserdicht-Sicherungsblock/dp/B08DHKNLLR/ref=sr_1_36?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=12V+Sicherungskasten+100A&qid=1629116776&sr=8-36 
      - [x] Batteriewahlschalter 100A
        - I: https://www.awn.de/products/batterie-umschalter-12v-100a?variant=31559123140743
        - I max 1000A, nenn 60A: https://www.ebay.de/itm/154291886548?hash=item23ec8359d4:g:uZkAAOSwmddf~-g6 
   4. Kabel 
      - [ ] 6mm² Kabel 17.5m
      - [ ] 1.5mm² Kabel 15m
   5. Verbraucher
      - [x] Steckdosen
        - I: https://www.amazon.de/SUSSURRO-Zigarettenanz%C3%BCnder-Wasserdicht-Motorradmit-Anschlusskabel/dp/B088NS5617/ref=sr_1_1_sspa?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=12V+Steckdose&qid=1629117342&sr=8-1-spons&psc=1&smid=A277SU4OWOR1LI&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyN1lCMVVVSlRBRjlCJmVuY3J5cHRlZElkPUEwODU5MjEzMUdKNE1ZRFNaQ1JNRSZlbmNyeXB0ZWRBZElkPUEwMTczOTk5MUZCM1JWNTg5UjU5VSZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=
      - [ ] Schalter
2. 230V~ Netz
   - [ ] Landstromkabel 1.5mm²
   - [ ] Verbraucherkabel 1.5mm²
   - [x] PE-Schiene
     - I: https://www.amazon.de/POLLMANN-2020303-Baderdungsschiene-PAS6-4025221120036/dp/B005I4GM8W/ref=sr_1_4?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2PBQ9FWK73J8A&dchild=1&keywords=potentialausgleichsschiene&qid=1629130182&sprefix=Potentialaus%2Caps%2C194&sr=8-4
   - [x] 220V FI Schalter + 220V Sicherungsautomat
   - [ ] Steckdosen
     - I: https://www.amazon.de/Doppelsteckdose-keramik-basis-250V-16A/dp/B07J442YQ1/ref=sr_1_16?dchild=1&keywords=230V+Steckdose&qid=1629117692&sr=8-16
3. Sonstiges
   - [ ] Kabelrohre 15m
     - I: https://www.amazon.de/AUPROTEC-Wellrohr-Kabelschutz-ungeschlitzt-Auswahl-2m-Meter/dp/B00VJYZ5N8/ref=sr_1_1_sspa?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=Kabelrohr&qid=1629117777&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExUUhQTDY4TDBBOVVNJmVuY3J5cHRlZElkPUEwMzMzNTgzMUZHMVVUVEZGTExYSCZlbmNyeXB0ZWRBZElkPUEwNDU5Mjk0M09CRE43TkdKVFNHTiZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=
   - [ ] Kabelschuhe
   - [ ] Kabelklemmen

********************************************










