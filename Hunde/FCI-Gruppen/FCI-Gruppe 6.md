---
aliases:
  - "Lauf- und Schweißhunde"
fci_gruppe_nr: 6
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-6
---
# FCI-Gruppe 6: Laufhunde, Schweißhunde und verwandte Rassen

← [[FCI-Gruppe 5]] · [[Hund]] · [[FCI-Gruppe 7]] →

Laufhunde verfolgen Wild selbstständig und laut auf der Spur. Schweißhunde suchen verletztes Wild nach. Zu den verwandten Rassen zählt der Rhodesian Ridgeback. Typisch für die Gruppe ist eine hervorragende Nase.

## Hinweise für Tierpfleger
- Der Jagdtrieb ist ausgeprägt, Freilauf ist deshalb oft nur mit sehr gutem Rückruf oder an der Schleppleine möglich.
- Nasenarbeit lastet diese Hunde am besten aus, zum Beispiel Mantrailing oder Fährtensuche. Siehe [[Bewegung und Beschäftigung Hund]].

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 75 Rassen:

### Sektion 1: Laufhunde
[[American Foxhound]] · [[Anglo-Français de Petite Vénerie]] · [[Ariégeois]] · [[Barak]] · [[Basset Artésien Normand]] · [[Basset Bleu de Gascogne]] · [[Basset Fauve de Bretagne]] · [[Basset Hound]] · [[Beagle]] · [[Beagle-Harrier]] · [[Billy]] · [[Black and Tan Coonhound]] · [[Bluthund]] · [[Brandlbracke]] · [[Briquet Griffon Vendéen]] · [[Chien d'Artois]] · [[Crnogorski Planinski Gonič]] · [[Deutsche Bracke]] · [[Dunkerbracke]] · [[English Foxhound]] · [[Erdélyi Kopó]] · [[Estnische Bracke]] *(vorläufig)* · [[Finnischer Laufhund]] · [[Français Blanc et Noir]] · [[Français Blanc et Orange]] · [[Français Tricolore]] · [[Gascon Saintongeois]] · [[Gończy Polski]] · [[Grand Anglo-Français Blanc et Noir]] · [[Grand Anglo-Français Blanc et Orange]] · [[Grand Anglo-Français Tricolore]] · [[Grand Basset Griffon Vendéen]] · [[Grand Bleu de Gascogne]] · [[Grand Griffon Vendéen]] · [[Griechischer Laufhund]] · [[Griffon Bleu de Gascogne]] · [[Griffon Fauve de Bretagne]] · [[Griffon Nivernais]] · [[Haldenstøver]] · [[Hamiltonstövare]] · [[Harrier]] · [[Hygenhund]] · [[Kurzhaarige Istrianer Bracke]] · [[Otterhound]] · [[Petit Basset Griffon Vendéen]] · [[Petit Bleu de Gascogne]] · [[Poitevin]] · [[Polnische Bracke]] · [[Porcelaine]] · [[Posavatz-Bracke]] · [[Rastreador Brasileiro]] · [[Rauhhaarige Istrianer Bracke]] · [[Sabueso Español]] · [[Sabueso Fino Colombiano]] *(vorläufig)* · [[Schillerstövare]] · [[Schwedische Dachsbracke]] · [[Schweizer Laufhund]] · [[Schweizer Niederlaufhund]] · [[Segugio dell'Appennino]] *(vorläufig)* · [[Segugio Italiano a pelo forte]] · [[Segugio Italiano a pelo raso]] · [[Segugio Maremmano]] *(vorläufig)* · [[Serbischer Laufhund]] · [[Slovenský Kopov]] · [[Smålandstövare]] · [[Srpski Trobojni Gonič]] · [[Steirische Rauhhaarbracke]] · [[Tiroler Bracke]] · [[Westfälische Dachsbracke]]

### Sektion 2: Schweißhunde
[[Alpenländische Dachsbracke]] · [[Bayerischer Gebirgsschweißhund]] · [[Hannoverscher Schweißhund]] · [[Tatranský Durič]] *(vorläufig)*

### Sektion 3: Verwandte Rassen
[[Dalmatiner]] · [[Rhodesian Ridgeback]]

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
