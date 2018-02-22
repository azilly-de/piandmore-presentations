# piandmore-presentations
Vorträge (reveal.js) für [Pi and more 10.5](https://piandmore.de/ "Pi and more")

Uni Stuttgart
24. Februar 2018, 09:30—18:30

## Raspberry Pi Zero als USB Gadget

Der Raspberry Pi Zero bietet unter Raspian die Möglichkeit über den
USB-OTG-Port verschiedene USB-Geräte zu emulieren.

Zu den verfügbaren virtuellen USB-Geräten zählen unter anderem:

- serielle Schnittstelle
- Netzwerkschnittstelle
- USB-Speicher
- Eingabegeräte wie Maus oder Tastatur

Nach erfolgter Konfiguration erkennt der Host-Computer den
angeschlossenen Raspberry Pi Zero als das entsprechende virtuelle
USB-Gerät. Der Raspberry Pi Zero wird dann zum Beispiel als serielle
Schnittstelle erkannt und ermöglicht dem Host-Computer per Putty auf
den Raspberry Pi Zero zuzugreifen.

Der Vortrag erläutert wie verschiedene virtuelle USB-Geräte
konfiguriert werden und welche Möglichkeiten diese Vorgehensweise
bietet. Auf diese Weise kann man zum Beispiel den Pi Zero ohne weiteres
Zubehör (nur SDCard und microUSB-Kabel nötig) in Betrieb nehmen und
auf ihn zugreifen.

## Sprachsteuerung mit dem Raspberry Pi

Auf Grund der breiten Verfügbarkeit relativ kostengünstiger
sprachgesteuerter Geräte, wie Amazon Echo oder Google Home, ist das
Interesse an "smarten" Assistenten gestiegen. Möchte man keine
vorgefertigte Lösung einsetzen oder eigene Projekte um eine
Sprachsteuerung erweitern bietet sich der Raspberry Pi als Basis an.
Sowohl Amazon mit "Alexa Voice Services" als auch Google mit "Google
Assistant Service" stellen eine Programmierschnittstelle zum jeweiligen
Spracherkennungssystem zur Verfügung. Über diese Schnittstelle(n) kann
der Raspberry Pi als Basis für die Sprachsteuerung eigener Projekte
genutzt werden.

Der Vortrag gibt einen Überblick über die Möglichkeiten, die ein
Raspberry Pi als Basis zur Sprachsteuerung bietet. Zum Einstieg genügt
ein einfaches Mikrophon sowie ein Lautsprecher. Spezielle HATs mit
Mikrofon Arrays verbessern die Spracherfassung und mit dem Google Voice
AIY Kit steht sogar ein offiziell von Google herausgegebenes
Entwicklungskit, das den Raspberry Pi als Basis benutzt, zur Verfügung.
Die Einbindung einer Sprachsteuerung in eigene Projekte wird sowohl für
"Alexa Voice Services" als auch "Google Assistant Service" demonstriert.

Grundlegende Programmierkenntnisse sollten vorhanden sein.
