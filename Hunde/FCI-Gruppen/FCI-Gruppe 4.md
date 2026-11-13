---
aliases:
  - "Dachshunde"
fci_gruppe_nr: 4
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-4
---
# FCI-Gruppe 4: Dachshunde

← [[FCI-Gruppe 3]] · [[Hund]] · [[FCI-Gruppe 5]] →

Diese Gruppe umfasst nur eine Rasse, den Dachshund oder Dackel. Es gibt ihn in drei Größen (Normal-, Zwerg- und Kaninchenteckel) und drei Haararten (Kurz-, Rau- und Langhaar). Ursprünglich wurde er für die Jagd im Bau gezüchtet.

## Hinweise für Tierpfleger
- Die kurzen Beine und der lange Rücken entstehen durch Chondrodystrophie. Deshalb besteht ein hohes Risiko für einen [[Bandscheibenvorfall]].
- Treppen und Springen sollten möglichst vermieden werden. Normalgewicht ist wichtig, siehe [[Ernährung Hund]].

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 1 Rasse:

[[Dackel]]

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
