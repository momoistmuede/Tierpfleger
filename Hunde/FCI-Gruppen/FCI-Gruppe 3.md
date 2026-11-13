---
aliases:
  - "Terrier"
fci_gruppe_nr: 3
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-3
---
# FCI-Gruppe 3: Terrier

← [[FCI-Gruppe 2]] · [[Hund]] · [[FCI-Gruppe 4]] →

Terrier (lat. *terra* = Erde) wurden für die Jagd auf Fuchs, Dachs und Ratten im Bau gezüchtet. Später kamen auch Rassen für Hundekämpfe dazu, aus denen die bullartigen Terrier hervorgingen. Typisch sind Mut, Selbstständigkeit, Temperament und ein ausgeprägter Jagdtrieb.

## Hinweise für Tierpfleger
- Terrier sind oft dickköpfig. Sie brauchen konsequente, abwechslungsreiche Erziehung und Beschäftigung.
- Rauhaarige Terrier werden getrimmt, nicht geschoren. Siehe [[Fellpflege]].
- Bullartige Terrier sind in vielen Bundesländern [[Listenhunde]].

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 36 Rassen:

### Sektion 1: Hochläufige Terrier
[[Airedale Terrier]] · [[Bedlington Terrier]] · [[Border Terrier]] · [[Brasilianischer Terrier]] · [[Deutscher Jagdterrier]] · [[Foxterrier Drahthaar]] · [[Foxterrier Glatthaar]] · [[Gos Rater Valencià]] *(vorläufig)* · [[Irish Glen of Imaal Terrier]] · [[Irish Soft Coated Wheaten Terrier]] · [[Irish Terrier]] · [[Kerry Blue Terrier]] · [[Lakeland Terrier]] · [[Manchester Terrier]] · [[Parson Russell Terrier]] · [[Ratonero Bodeguero Andaluz]] *(vorläufig)* · [[Welsh Terrier]]

### Sektion 2: Niederläufige Terrier
[[Australian Terrier]] · [[Cairn Terrier]] · [[Dandie Dinmont Terrier]] · [[Jack Russell Terrier]] · [[Japanischer Terrier]] · [[Norfolk Terrier]] · [[Norwich Terrier]] · [[Scottish Terrier]] · [[Sealyham Terrier]] · [[Skye Terrier]] · [[Tschechischer Terrier]] · [[West Highland White Terrier]]

### Sektion 3: Bullartige Terrier
[[American Staffordshire Terrier]] · [[Bullterrier]] · [[Miniature Bull Terrier]] · [[Staffordshire Bullterrier]]

### Sektion 4: Zwerg-Terrier
[[Australian Silky Terrier]] · [[English Toy Terrier]] · [[Yorkshire Terrier]]

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
