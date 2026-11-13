---
aliases:
  - "Apportier-, Stöber- und Wasserhunde"
fci_gruppe_nr: 8
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-8
---
# FCI-Gruppe 8: Apportierhunde – Stöberhunde – Wasserhunde

← [[FCI-Gruppe 7]] · [[Hund]] · [[FCI-Gruppe 9]] →

Retriever bringen geschossenes Wild zurück, Stöberhunde wie der Spaniel treiben Wild aus dichtem Bewuchs. Wasserhunde arbeiten im Wasser. Die Hunde dieser Gruppe gelten als besonders kooperativ und "will to please".

## Hinweise für Tierpfleger
- Diese Rassen eignen sich gut für Anfänger und Familien, brauchen aber trotzdem Beschäftigung, zum Beispiel Dummy-Training oder Wasserarbeit.
- Sie neigen zu Übergewicht, siehe [[Ernährung Hund]]. Bei großen Rassen ist [[Hüftgelenksdysplasie]] verbreitet.

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 22 Rassen:

### Sektion 1: Apportierhunde
[[Chesapeake Bay Retriever]] · [[Curly Coated Retriever]] · [[Flat Coated Retriever]] · [[Golden Retriever]] · [[Labrador Retriever]] · [[Nova Scotia Duck Tolling Retriever]]

### Sektion 2: Stöberhunde
[[American Cocker Spaniel]] · [[Clumber Spaniel]] · [[Deutscher Wachtelhund]] · [[English Cocker Spaniel]] · [[English Springer Spaniel]] · [[Field Spaniel]] · [[Kooikerhondje]] · [[Sussex Spaniel]] · [[Welsh Springer Spaniel]]

### Sektion 3: Wasserhunde
[[American Water Spaniel]] · [[Barbet]] · [[Irish Water Spaniel]] · [[Lagotto Romagnolo]] · [[Portugiesischer Wasserhund]] · [[Spanischer Wasserhund]] · [[Wetterhoun]]

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
