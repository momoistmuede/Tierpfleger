---
aliases:
  - "Windhunde"
fci_gruppe_nr: 10
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-10
---
# FCI-Gruppe 10: Windhunde

← [[FCI-Gruppe 9]] · [[Hund]]

Windhunde jagen auf Sicht (Sichtjäger) und erreichen enorme Sprintgeschwindigkeiten. Im Haus sind sie meist ruhig und sanft. Sie haben wenig Körperfett und ein dünnes Fell.

## Hinweise für Tierpfleger
- Ihr Hetztrieb wird durch Bewegung ausgelöst. Freilauf deshalb nur in eingezäuntem Gelände, zum Beispiel auf einer Coursing- oder Rennbahn.
- Sie frieren leicht und brauchen im Winter einen Mantel und weiche Liegeplätze.
- Bei Narkosen ist Vorsicht geboten: Sie haben wenig Körperfett und bauen manche Narkosemittel langsamer ab.

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 14 Rassen:

### Sektion 1: Langhaarige oder befederte Windhunde
[[Afghanischer Windhund]] · [[Barsoi]] · [[Kazakh Tazy]] *(vorläufig)* · [[Saluki]]

### Sektion 2: Rauhhaarige Windhunde
[[Deerhound]] · [[Irischer Wolfshund]]

### Sektion 3: Kurzhaarige Windhunde
[[Azawakh]] · [[Galgo Español]] · [[Greyhound]] · [[Italienisches Windspiel]] · [[Magyar Agar]] · [[Polnischer Windhund]] · [[Sloughi]] · [[Whippet]]

## Rassen in dieser Gruppe (Tabelle)
```base
filters:
  and:
    - file.hasTag("rasse")
    - file.hasLink(this.file)
formulas:
  gewicht: 'gewicht_min_kg.toString() + "–" + gewicht_max_kg.toString() + " kg"'
properties:
  file.name:
    displayName: Rasse
  formula.gewicht:
    displayName: Gewicht
  note.fci_sektion:
    displayName: Sektion
  note.fci_status:
    displayName: Anerkennung
views:
  - type: table
    name: Rassen
    groupBy:
      property: fci_sektion
      direction: ASC
    order:
      - file.name
      - fci_standard
      - fci_status
      - herkunft
      - groesse
      - formula.gewicht
      - bewegungsbedarf
    sort:
      - property: file.name
        direction: ASC
```
