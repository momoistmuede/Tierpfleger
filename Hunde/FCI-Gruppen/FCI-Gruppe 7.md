---
aliases:
  - "Vorstehhunde"
fci_gruppe_nr: 7
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-7
---
# FCI-Gruppe 7: Vorstehhunde

← [[FCI-Gruppe 6]] · [[Hund]] · [[FCI-Gruppe 8]] →

Vorstehhunde zeigen gefundenes Wild an, indem sie wie erstarrt stehen bleiben (das sogenannte Vorstehen). Kontinentale Vorstehhunde wie Deutsch Kurzhaar und Weimaraner sind vielseitige Jagdgebrauchshunde.

## Hinweise für Tierpfleger
- Sie haben einen sehr hohen Bewegungs- und Arbeitsbedarf. Viele Züchter geben Welpen bevorzugt an Jäger ab.
- Ohne Aufgabe neigen sie zu Unruhe und selbstständigem Jagen.

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 36 Rassen:

### Sektion 1: Kontinentale Vorstehhunde
[[Altdänischer Vorstehhund]] · [[Blauer Picardie-Spaniel]] · [[Bracco Italiano]] · [[Braque d'Auvergne]] · [[Braque de l'Ariège]] · [[Braque du Bourbonnais]] · [[Braque Français Typ Gascogne]] · [[Braque Français Typ Pyrenäen]] · [[Braque Saint-Germain]] · [[Český Fousek]] · [[Deutsch Drahthaar]] · [[Deutsch Kurzhaar]] · [[Deutsch Langhaar]] · [[Deutsch Stichelhaar]] · [[Drahthaariger Ungarischer Vorstehhund]] · [[Drentsche Patrijshond]] · [[Epagneul Breton]] · [[Französischer Spaniel]] · [[Griffon Korthals]] · [[Großer Münsterländer]] · [[Kleiner Münsterländer]] · [[Magyar Vizsla]] · [[Perdigueiro Português]] · [[Perdiguero de Burgos]] · [[Picardie-Spaniel]] · [[Pont-Audemer-Spaniel]] · [[Pudelpointer]] · [[Slowakischer Rauhbart]] · [[Spinone Italiano]] · [[Stabijhoun]] · [[Weimaraner]]

### Sektion 2: Britische und Irische Vorstehhunde
[[English Pointer]] · [[English Setter]] · [[Gordon Setter]] · [[Irish Red and White Setter]] · [[Irish Setter]]

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
