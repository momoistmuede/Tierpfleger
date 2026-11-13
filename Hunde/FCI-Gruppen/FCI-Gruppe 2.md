---
aliases:
  - "Pinscher, Schnauzer, Molosser, Sennenhunde"
fci_gruppe_nr: 2
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-2
---
# FCI-Gruppe 2: Pinscher und Schnauzer – Molossoide – Schweizer Sennenhunde

← [[FCI-Gruppe 1]] · [[Hund]] · [[FCI-Gruppe 3]] →

Eine sehr vielfältige Gruppe: von kleinen Schnauzern über Wach- und Schutzhunde wie Rottweiler und Dobermann bis zu großen Molossern wie der Deutschen Dogge. Dazu kommen die Schweizer Sennenhunde, die eine eigene Sektion bilden.

## Hinweise für Tierpfleger
- Große, kräftige Rassen brauchen eine konsequente und souveräne Führung sowie früh eine gute Sozialisierung.
- Bei großen, tiefbrüstigen Rassen ist das Risiko einer [[Magendrehung]] erhöht.
- Einige Rassen dieser Gruppe stehen in manchen Bundesländern auf [[Listenhunde|Rasselisten]].

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 58 Rassen:

### Sektion 1: Pinscher und Schnauzer
[[Affenpinscher]] · [[Dänisch-Schwedischer Farmhund]] · [[Deutscher Pinscher]] · [[Dobermann]] · [[Holländischer Smoushond]] · [[Mittelschnauzer]] · [[Österreichischer Pinscher]] · [[Riesenschnauzer]] · [[Russischer Schwarzer Terrier]] · [[Zwergpinscher]] · [[Zwergschnauzer]]

### Sektion 2: Molossoide
[[Atlas-Berghund]] · [[Bernhardiner]] · [[Bordeauxdogge]] · [[Broholmer]] · [[Buldogue Campeiro]] *(vorläufig)* · [[Bullmastiff]] · [[Cane Corso]] · [[Cão da Serra da Estrela]] · [[Cão de Castro Laboreiro]] · [[Cão de Gado Transmontano]] *(vorläufig)* · [[Cão Fila de São Miguel]] · [[Cimarrón Uruguayo]] · [[Ciobănesc Românesc Corb]] *(vorläufig)* · [[Continental Bulldog]] *(vorläufig)* · [[Deutsche Dogge]] · [[Deutscher Boxer]] · [[Do Khyi]] · [[Dogo Argentino]] · [[Englische Bulldogge]] · [[Fila Brasileiro]] · [[Hovawart]] · [[Kangal-Hirtenhund]] · [[Karst-Schäferhund]] · [[Kaukasischer Schäferhund]] · [[Landseer]] · [[Leonberger]] · [[Macedonian Shepherd Dog Karaman]] *(vorläufig)* · [[Mallorca-Dogge]] · [[Mastiff]] · [[Mastín Español]] · [[Mastino Napoletano]] · [[Mittelasiatischer Schäferhund]] · [[Neufundländer]] · [[Presa Canario]] · [[Pyrenäen-Mastiff]] · [[Pyrenäenberghund]] · [[Rafeiro do Alentejo]] · [[Rottweiler]] · [[Rumänischer Bukowina-Schäferhund]] · [[Sarplaninac]] · [[Shar Pei]] · [[Tornjak]] · [[Tosa]]

### Sektion 3: Schweizer Sennenhunde
[[Appenzeller Sennenhund]] · [[Berner Sennenhund]] · [[Entlebucher Sennenhund]] · [[Großer Schweizer Sennenhund]]

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
