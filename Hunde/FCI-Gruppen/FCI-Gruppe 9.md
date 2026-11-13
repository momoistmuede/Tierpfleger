---
aliases:
  - "Gesellschafts- und Begleithunde"
fci_gruppe_nr: 9
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-9
---
# FCI-Gruppe 9: Gesellschafts- und Begleithunde

← [[FCI-Gruppe 8]] · [[Hund]] · [[FCI-Gruppe 10]] →

Diese Hunde wurden in erster Linie als Begleiter des Menschen gezüchtet. In der Gruppe finden sich viele Klein- und Zwergrassen, aber auch brachyzephale (kurzköpfige) Rassen mit erheblichen Gesundheitsproblemen.

## Hinweise für Tierpfleger
- Bei mehreren Rassen gibt es [[Qualzucht]]-Merkmale, besonders die [[Brachyzephalie]].
- Kleine Rassen sind häufig von [[Patellaluxation]], [[Trachealkollaps]] und Zahnproblemen betroffen, siehe [[Zahnpflege]].
- Auch kleine Hunde brauchen Erziehung und Auslastung. Das "Small-Dog-Syndrom" ist meist hausgemacht.

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 27 Rassen:

### Sektion 1: Bichons und verwandte Rassen
[[Bichon Frisé]] · [[Bologneser]] · [[Coton de Tuléar]] · [[Havaneser]] · [[Löwchen]] · [[Malteser]]

### Sektion 2: Pudel
[[Pudel]]

### Sektion 3: Kleine belgische Hunderassen
[[Belgischer Griffon]] · [[Brabanter Griffon]] · [[Brüsseler Griffon]]

### Sektion 4: Haarlose Hunde
[[Chinesischer Schopfhund]]

### Sektion 5: Tibetanische Hunderassen
[[Lhasa Apso]] · [[Shih Tzu]] · [[Tibet-Spaniel]] · [[Tibet-Terrier]]

### Sektion 6: Chihuahueno
[[Chihuahua]]

### Sektion 7: Englische Gesellschaftsspaniel
[[Cavalier King Charles Spaniel]] · [[King Charles Spaniel]]

### Sektion 8: Japanische Spaniel und Pekingesen
[[Japan Chin]] · [[Pekingese]]

### Sektion 9: Kontinentaler Zwergspaniel und andere
[[Kontinentaler Zwergspaniel]] · [[Prager Rattler]] *(vorläufig)* · [[Russischer Toy]]

### Sektion 10: Kromfohrländer
[[Kromfohrländer]]

### Sektion 11: Kleine doggenartige Hunde
[[Boston Terrier]] · [[Französische Bulldogge]] · [[Mops]]

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
