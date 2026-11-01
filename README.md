# Nixo Express (Spigot-Plugin, Minecraft 1.21.11)

Spieler bestellen Kits/Blöcke und schreiben dazu, was sie dafür geben.
Admins sehen alle Bestellungen, sagen Deals zu und bearbeiten das Sortiment.

Installation: `NixoExpress.jar` in den Ordner `plugins` des Servers legen, Server neu starten.
Daten liegen in `plugins/NixoExpress/data.yml`.

## Spieler
- /express – Sortiment (klickbar)
- /express info <produkt>
- /express order <produkt> <was du dafür gibst>
- /express orders – eigene Bestellungen
- /express cancel <id>

## Admin (Permission: nixoexpress.admin, Standard: OP)
- /expressadmin orders [all]
- /expressadmin accept <id>   (Spieler bekommt Nachricht + Titel + Sound + Items, offline beim Login)
- /expressadmin deny <id> [grund]
- /expressadmin product list | add <id> <name> | remove <id> | toggle <id>
- /expressadmin product name|desc|price <id> <text>
- /expressadmin product additem <id>   (Item in der Hand, inkl. Verzauberungen/Namen)
- /expressadmin product clearitems <id>
