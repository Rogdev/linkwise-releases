# Linkwise

Linkwise verbindt je computer met je Homey. Deze pagina bevat alleen de installers van de Linkwise-computer-app.
*Linkwise connects your computer to Homey. This repository only contains the installers of the Linkwise computer app.*

## Downloaden · Download

Ga naar **[de nieuwste release](https://github.com/Rogdev/linkwise-releases/releases/latest)** en kies het bestand voor jouw computer:

| Computer | Bestand |
| --- | --- |
| Windows 10/11 (64-bit) | `Linkwise-Setup-<versie>.exe` |
| Mac met Apple-chip (M1 of nieuwer) | `Linkwise-<versie>-mac-arm64.dmg` |
| Mac met Intel-chip | `Linkwise-<versie>-mac-x64.dmg` |
| Linux | `.AppImage` (alle distributies), `.deb` (Ubuntu/Debian) of `.rpm` (Fedora) |

> De bestanden "Source code (zip/tar.gz)" die GitHub bij elke release toont, bevatten alleen deze README, geen app.
> *The "Source code" files GitHub adds to every release only contain this README.*

## Bèta · Beta

Wil je nieuwe functies eerder proberen? Bètaversies (zoals `0.4.0-beta.1`) staan bij de [releases](https://github.com/Rogdev/linkwise-releases/releases) met het label *Pre-release*. Of zet in Linkwise **Instellingen → Updates → Bètaversies ontvangen** aan: dan krijg je ze vanzelf. Bètaversies kunnen fouten bevatten.

*Want new features earlier? Beta versions are marked Pre-release on the releases page, or turn on Settings → Updates → Receive beta versions in Linkwise.*

## Installeren · Install

1. Installeer en open de Linkwise-app op je computer.
2. Installeer de **Linkwise**-app op je Homey Pro en voeg een apparaat toe: *Apparaten → + → Linkwise → Computer*.
3. Kies je computer en vul de koppelcode in die de app op je computer toont.

De installers zijn (nog) niet digitaal ondertekend:
- **Windows:** klik bij "Windows heeft uw pc beschermd" op *Meer info → Toch uitvoeren*.
- **macOS:** open de app de eerste keer met rechtermuisklik → *Open*.
- **Linux (AppImage):** maak het bestand uitvoerbaar (`chmod +x Linkwise-*.AppImage`) en start het.

*The installers are not code-signed yet. Windows: "More info → Run anyway". macOS: right-click → Open the first time. Linux: `chmod +x` the AppImage.*

## Wat kan Linkwise? · Features

- Meldingen en vragen van Homey op je scherm, en meldingen van je computer naar Homey
- Vergrendelen, slaapstand, herstarten, afsluiten en wakker maken (Wake-on-LAN) vanuit Homey
- Volume en media bedienen
- Status van je computer in Flows: vergrendeld, inactief, actieve app, microfoon en camera in gebruik
- Homey-apparaten en Flows bedienen vanaf je computer (snelpaneel en zoekbalk)
- Automatisch acties uitvoeren als een programma start of naar voren komt

De verbinding loopt via je eigen netwerk, beveiligd met een koppelcode en ondertekende berichten. Buitenshuis kan Linkwise verbonden blijven via je Homey-account.

## Hulp · Support

Problemen of ideeën? Maak een [issue](https://github.com/Rogdev/linkwise-releases/issues) aan.

© Rogdev
