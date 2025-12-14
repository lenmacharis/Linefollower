# Gebruiksaanwijzing


### 🔋 Voeding

Bij een lege batterij moet deze worden opgeladen.

Haal de batterij uit de houder

Laad de batterij extern op

Plaats de batterij opnieuw in de robot

### 📡 Draadloze communicatie
Verbinding maken

De ESP32 communiceert via Bluetooth.

Gebruik een Android smartphone

Verbind met een seriële Bluetooth-app

❌ iOS wordt niet ondersteund

### Beschikbare commando’s

Gebruik onderstaande commando’s in de Bluetooth-terminal:

debug [on/off]
start
stop
set cycle [µs]
set power [0..255]
set diff [0..1]
set kp [waarde]
set ki [waarde]
set kd [waarde]
calibrate black
calibrate white

### 🎯 Sensor kalibratie

Voor correcte metingen moet de sensor worden gekalibreerd:

Plaats de robot op een zwarte ondergrond

Verstuur:

calibrate black


Plaats de robot op een witte ondergrond

Verstuur:

calibrate white


Activeer debug-modus om de waarden te controleren:

debug on

### ⚙️ Aanbevolen instellingen

Met onderstaande parameters rijdt de robot stabiel:

Parameter	Waarde
Power	120
Diff	0.5
Kp	10
Ki	0
Kd	0.3
▶️ Start / Stop schakelaar

De robot wordt gestart of gestopt via een fysieke schakelaar.

Aangesloten op GPIO 17 van de ESP32

Activeert of pauzeert de hoofdloop van het programma

### 🧠 Hardware

ESP32

Lijnsensor (zwart/wit detectie)

DC-motoren + motor driver

Batterij + houder

Start/stop schakelaar

### 📱 Software

ESP32 (Arduino framework)

Seriële Bluetooth-app (Android)
