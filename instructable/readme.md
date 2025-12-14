# Instructable

## 🛠️ Instructable: Maak je eigen Line-Follower Robot

Met deze gids bouw je stap voor stap een eenvoudige line-following robot op basis van een ESP32.
Je start met het 3D-printen van de mechanische onderdelen, monteert vervolgens de hardware en laadt tot slot de software op de ESP32 om je robot tot leven te brengen.

## 📦 Benodigdheden
Elektronica

ESP32

QTR-8A Reflectance Sensor Array (Pololu)

DRV8833 motor driver

DIP-schakelaar

2× DC-motoren

Batterijhouder

Elektronische bedrading

Mechanica

3D-geprinte onderdelen (chassis, wielhouders)
→ te vinden in de GitHub-repository

T-strip of sterke lijm

Dubbelzijdige tape

## 🧩 Stappenplan
# 🔹 Stap 1: Print de mechanische onderdelen

Download de STL-bestanden uit de map Mechanische Onderdelen in de GitHub-repository.

Print de onderdelen met een 3D-printer.

Controleer of het chassis en de wielhouders correct zijn geprint en de juiste afmetingen hebben.

# 🔹 Stap 2: Monteer de mechanische onderdelen
2.1 Wielhouders plaatsen

Bevestig de wielhouders aan de achterkant van het chassis.

Gebruik T-strip of sterke lijm voor een stevige montage.

Laat de lijm volledig uitharden voordat je verdergaat.

2.2 Motoren monteren

Schuif de DC-motoren in de wielhouders.

Controleer of de motorassen vrij kunnen draaien en correct zijn uitgelijnd.

2.3 Batterijhouder bevestigen

Bevestig de batterijhouder bovenop het chassis.

Gebruik T-strip of sterke lijm.

Zorg ervoor dat de houder stevig vastzit.

# 🔹 Stap 3: Plaatsen van de elektronica
3.1 QTR-8A sensor bevestigen

Bevestig de QTR-8A reflectiesensor aan de voorkant van het chassis met dubbelzijdige tape.

Richt de sensoren naar beneden.

Houd enkele millimeters afstand tot de ondergrond voor optimale metingen.

3.2 DIP-schakelaar

Monteer de DIP-schakelaar op een breadboard.

Verbind deze met de ESP32 volgens het schema in de GitHub-repository.

# 🔹 Stap 4: Aansluiten van de bedrading
4.1 Motoren aansluiten

Verbind de DC-motoren met de juiste uitgangen van de DRV8833 motor driver.

Volg het bedradingsschema uit de GitHub-repository om fouten te voorkomen.

4.2 DRV8833 verbinden met ESP32

Sluit de motor driver aan op de ESP32 volgens het schema.

Verbind de voedingsdraden van de DRV8833 met de batterijhouder.

# 🔹 Stap 5: Controleer de assemblage

Vergelijk je robot met de foto’s in de GitHub-repository.

Controleer of:

alle draden correct zijn aangesloten

niets loszit

motoren vrij kunnen draaien

# 🔹 Stap 6: Laat je robot tot leven komen 🚀

Upload de software naar de ESP32 volgens de instructies in de GitHub-repository.

Controleer of de instellingen van de QTR-8A sensor correct zijn afgestemd op jouw omgeving.

Zet de robot aan en test of hij de lijn correct volgt.


Je hebt nu een volledig functionele line-following robot gebouwd 🚗💨

Veel succes en plezier met je project! 🙌
