---
aliases:
  - "Hüte- und Treibhunde"
fci_gruppe_nr: 1
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-1
---
# FCI-Gruppe 1: Hütehunde und Treibhunde (ausgenommen Schweizer Sennenhunde)

[[Hund]] · [[FCI-Gruppe 2]] →

Hunde dieser Gruppe wurden gezüchtet, um Schafe oder Rinder zu hüten, zu treiben und zu bewachen. Sie arbeiten eng mit dem Menschen zusammen und sind meist sehr lernfähig, aufmerksam und bewegungsfreudig.

## Hinweise für Tierpfleger
- Sie brauchen körperliche **und** geistige Auslastung, zum Beispiel Hütearbeit, Unterordnung, Agility, Treibball oder Fährte.
- Werden sie unterfordert, zeigen sie oft Problemverhalten: Sie hüten Radfahrer, Kinder oder Autos, kläffen oder entwickeln Stereotypien.
- Einige Rassen tragen den [[MDR1-Defekt]]. Bei Medikamenten und Parasitenmitteln deshalb immer nachfragen.

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 47 Rassen:

### Sektion 1: Schäferhunde
[[Australian Kelpie]] · [[Australian Shepherd]] · [[Bearded Collie]] · [[Beauceron]] · [[Belgischer Schäferhund]] · [[Bergamasker]] · [[Berger Picard]] · [[Böhmischer Schäferhund]] *(vorläufig)* · [[Border Collie]] · [[Briard]] · [[Ca de Bestiar]] · [[Cão da Serra de Aires]] · [[Ciobănesc Românesc Carpatin]] · [[Ciobănesc Românesc Mioritic]] · [[Collie]] · [[Collie Kurzhaar]] · [[Deutscher Schäferhund]] · [[Holländischer Schäferhund]] · [[Katalanischer Schäferhund]] · [[Komondor]] · [[Kroatischer Schäferhund]] · [[Kuvasz]] · [[Lancashire Heeler]] *(vorläufig)* · [[Langhaariger Pyrenäenschäferhund]] · [[Maremmano-Abruzzese]] · [[Miniature American Shepherd]] *(vorläufig)* · [[Mudi]] · [[Old English Sheepdog]] · [[Polnischer Niederungshütehund]] · [[Polnischer Tatra-Schäferhund]] · [[Puli]] · [[Pumi]] · [[Pyrenäenschäferhund mit kurzhaarigem Gesicht]] · [[Saarloos-Wolfhund]] · [[Schapendoes]] · [[Schipperke]] · [[Shetland Sheepdog]] · [[Slowakischer Tschuvatsch]] · [[Südrussischer Owtscharka]] · [[Tschechoslowakischer Wolfhund]] · [[Weißer Schweizer Schäferhund]]

### Sektion 2: Treibhunde (ausgenommen Schweizer Sennenhunde)
[[Australian Cattle Dog]] · [[Australian Stumpy Tail Cattle Dog]] *(vorläufig)* · [[Bouvier des Ardennes]] · [[Bouvier des Flandres]] · [[Welsh Corgi Cardigan]] · [[Welsh Corgi Pembroke]]

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
