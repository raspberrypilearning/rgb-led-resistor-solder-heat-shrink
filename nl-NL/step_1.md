## Verzamel onderdelen

Je hebt nodig:
+ 4 x bus-bus jumperdraden, liefst ook rood, groen en blauw
+ 3 weerstanden van dezelfde waarde, ongeveer 70 Ohm of hoger
+ 1× RGB-led met gemeenschappelijke kathode
+ Soldeerbout en krimpkous
+ tang om draad te knippen of te strippen

![4 bus-bus jumperdraden, 3 75ohm weerstanden, krimpkous en een RGB LED](images/kit.jpg)
## Zoek de rode poot van de RGB-led

Een gewone kathode RGB-led heeft één langere poot, de kathode en moet worden aangesloten op aarde (GND). Controleer de specificatie van je RGB-led, maar de volgorde van de poten is meestal rood, kathode (langere poot), groen, blauw.

![Een RGB LED met vier poten, de tweede is langer.](images/rgb-led-legs.png)

Spreid de pootjes van de LED voorzichtig uit en zet de LED vast met behulp van een soldeerhulp of een krokodillenklem.

![Een RGB LED met de poten uit elkaar](images/spread-legs.jpg)
## Vertin de poten van de LED

Gebruik voor elk van de led-poten een soldeerbout om ze een paar seconden te verwarmen en breng vervolgens soldeer aan zodat elke poot is bedekt met een gelijkmatige laag soldeer.

--- no-print ---

![De poten van de RGB-LED zijn bedekt met soldeer.](images/tin_rgb.gif)


--- /no-print ---

--- print-only ---

![De poten van de RGB-LED zijn bedekt met soldeer.](images/tinned-legs.jpg)

--- /print-only ---

## Vertin de weerstanden

Herhaal deze procedure met alle draden van de drie weerstanden.

--- no-print ---

![weerstand met zijn draad vertind met soldeer.](images/tin_resistor.gif)

--- /no-print ---

--- print-only ---

![afbeelding van een weerstand met zijn draad vertind met soldeer.](images/tinned-resistor.png)

--- /print-only ---
## Soldeer de weerstanden aan de pootjes van de LED

Houd de draad van de weerstand naast een van de anode-pootjes van de LED.

![led-poot naast een van de led-pootjes van de RGB-led](images/adjacent-legs.jpg)

Gebruik vervolgens de soldeerbout om beide pootjes te verwarmen, zodat het soldeer smelt en ze aan elkaar hechten.

--- no-print ---

![poot van RGB LED gesoldeerd aan de weerstand](images/bond_resistor.gif)

--- /no-print ---

--- print-only ---

![poot van RGB LED gesoldeerd aan de weerstand](images/bonded-legs.jpg)

--- /print-only ---

## Herhaal dit voor de overige pootjes

Herhaal deze procedure voor alle LED-poten, behalve de kathode (de langste poot).

![drie weerstanden gesoldeerd aan de anodes van de RGB LED](images/led-three-resistors.jpg)

## Bevestig de vier jumperdraden

Knip je jumperdraden op de gewenste lengte en strip ongeveer 1 cm isolatie van het uiteinde van de draden.

Omhul de jumperdraden met de krimpkous.

![Afgeknipte en gestripte jumperdraad met losse krimpkous over het grootste deel van de lengte](images/jumper-lead.jpg)


Vertin de gestripte uiteinden van de jumperdraden en plak ze vervolgens vast aan de pootjes van de LED. Als je een zwarte jumperdraad hebt, moet deze worden bevestigd aan de kathode van de LED (het langste been).

--- no-print ---

![het gestripte uiteinde van een jumperdraad die wordt vertind](images/tin_jumper.gif) ![de jumperdraad wordt verbonden met een weerstand](images/bond_jumpers.gif)

--- /no-print ---

![Vier jumperdraden zijn bevestigd aan een LED en een weerstand.](images/soldered-jumper-leads.jpg)

Schuif de krimpkous omhoog, zodat deze de basis van de LED raakt en de weerstanden en alle soldeerverbindingen bedekt.

Gebruik vervolgens de rand van de soldeerbout (niet de punt) en wrijf deze zachtjes op en neer over de krimpkous, waardoor deze rond de verbindingen krimpt en voor een geïsoleerde afdekking zorgt.

--- no-print ---

![krimpkous die over de weerstanden en poten wordt geschoven](images/position_heat_shrink.gif) ![rand van soldeerbout die in de buurt van de krimpkous wordt gehouden](images/shrink_heat_shrink.gif)

--- /no-print ---

--- print-only ---

![rand van soldeerbout die in de buurt van de krimpkous wordt gehouden](images/shrinking-heat-shrink.jpg)

--- /print-only ---

Zodra alle vier delen van de krimpkous rond de verbindingen zijn bevestigd is je voltooide RGB-LED klaar om rechtstreeks op je GPIO-pinnen aan te sluiten.

![RGB LED met weerstanden en vier jumperdraden, gewikkeld in de krimpkous.](images/rgb-led-finished.jpg)