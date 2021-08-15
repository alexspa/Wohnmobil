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
        - ?: 1,5 mm2

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
    - I: Hauptsicherung an minus pol -> dann kein problem mit kurzschluss
    - !: 1 mal an der Steckdose
    - !: 1 mal nach Solarregler und Verbraucher
    - !: 1 mal dirket nach jeder Batterie vor Verteilter
    - ?: Wie viel Ampere
    - ?: 1 mal an Solaranlage bzw solarregler
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

### Bauteile 

#### Benötiogte Bauteile
1. 12V- Netz
   - [ ] Trennrelias 
   - [ ] Hauptsicherung (Sicherungsautomat 100A + 50A)
   - [ ] ?: 12V Hauptschalter
2. 230V~ Netz
   - [ ] 220V FI Schalter + 220V Sicherungsautomat
   - [ ] 220V Umschalter
   - [ ] Batteriepolklemmen mit Abzweigung
#### Einlaufsliste
1. 12V- Netz
   
   - [ ] Trennrelais:
     - I: https://www.amazon.de/Spannungsgesteuertes-Trennrelais-140A-Wohnmobil-Boot/dp/B08HZ36V9T/ref=mp_s_a_1_11?adgrpid=77940202064&dchild=1&gclid=CjwKCAjw9uKIBhA8EiwAYPUS3DmWc9MyF2AEFwP8lVaHVYM3RjZ8xUxg8-IzMXiUYrtt92HUFh5J7hoCLlUQAvD_BwE&hvadid=482238871864&hvdev=m&hvlocphy=9041988&hvnetw=g&hvqmt=b&hvrand=15889686153418161721&hvtargid=kwd-301240286553&hydadcr=26544_2418474&keywords=autobatterie+trennrelais&qid=1629026534&sr=8-11
        
      - I: https://www.amazon.de/Batterie-vollautomatisches-Trennrelais-Ampere-Drive/dp/B01G8ZVR16/ref=mp_s_a_1_6?adgrpid=77940202064&dchild=1&gclid=CjwKCAjw9uKIBhA8EiwAYPUS3DmWc9MyF2AEFwP8lVaHVYM3RjZ8xUxg8-IzMXiUYrtt92HUFh5J7hoCLlUQAvD_BwE&hvadid=482238871864&hvdev=m&hvlocphy=9041988&hvnetw=g&hvqmt=b&hvrand=15889686153418161721&hvtargid=kwd-301240286553&hydadcr=26544_2418474&keywords=autobatterie+trennrelais&qid=1629026624&sr=8-6
      
    - [ ] Mechanischer Umschalter
    - [ ] ?: 12V Hauptschalter 
    - [ ] Hauptsicherung (Sicherungsautomat 100A + 50A)
2. 230V~ Netz
********************************************










