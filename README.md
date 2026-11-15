# Glass Entity Grid

Eigenständige Home-Assistant-Lovelace-Karte im Frosted-Glass-Stil mit visuellem Konfigurationseditor.

## HACS-Installation

1. Die Dateien `hacs.json`, `glass-entity-grid.js`, `README.md` und `LICENSE` müssen direkt im Stammverzeichnis (Root) des GitHub-Repositories liegen.
2. In HACS **⋮ → Benutzerdefinierte Repositories** öffnen.
3. GitHub-Repository-URL eintragen und als Kategorie **Dashboard** auswählen.
4. Hinzufügen und anschließend in HACS nach „Glass Entity Grid“ suchen und installieren.
5. Falls die Ressource nicht automatisch angelegt wird, unter Einstellungen → Dashboards → Ressourcen hinzufügen:
   `/hacsfiles/glass-entity-grid/glass-entity-grid.js`
   Typ: **JavaScript-Modul**.

## YAML-Beispiel

```yaml
type: custom:glass-entity-grid
columns: 3
height: 52
radius: 18
gap: 10
entities:
  - entity: light.wohnzimmer_lampe
    name: Stehlampe
    icon: mdi:floor-lamp
```

## GitHub-Release

Für Version `2.0.0` zusätzlich einen GitHub-Release mit Tag `2.0.0` erstellen. Die Repository-Dateien müssen weiterhin im Root liegen.
