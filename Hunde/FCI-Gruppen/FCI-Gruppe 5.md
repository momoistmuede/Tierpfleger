---
aliases:
  - "Spitze und Hunde vom Urtyp"
fci_gruppe_nr: 5
tierart: "[[Hund]]"
tags:
  - hund
  - übersicht
  - fci/gruppe-5
---
# FCI-Gruppe 5: Spitze und Hunde vom Urtyp

← [[FCI-Gruppe 4]] · [[Hund]] · [[FCI-Gruppe 6]] →

Zu dieser Gruppe gehören nordische Schlitten- und Jagdhunde, europäische und asiatische Spitze sowie urtümliche Rassen. Sie sind meist eigenständig und haben einen starken eigenen Willen. Viele haben ein dichtes Doppelfell.

## Hinweise für Tierpfleger
- Sie sind weniger auf Gehorsam ausgerichtet. Die Erziehung braucht Geduld und Motivation statt Druck.
- Das Doppelfell wird **nicht geschoren**. Beim Fellwechsel ist intensives Auskämmen nötig, siehe [[Fellpflege]].
- Viele nordische Rassen haben einen starken Jagdtrieb und büxen gern aus.

## Rassen nach Sektionen
Die FCI führt in dieser Gruppe 48 Rassen:

### Sektion 1: Nordische Schlittenhunde
[[Alaskan Malamute]] · [[Grönlandhund]] · [[Jakutische Laika]] *(vorläufig)* · [[Kanadischer Eskimohund]] · [[Samojede]] · [[Siberian Husky]]

### Sektion 2: Nordische Jagdhunde
[[Finnenspitz]] · [[Jämthund]] · [[Karelischer Bärenhund]] · [[Norrbottenspitz]] · [[Norwegischer Elchhund]] · [[Norwegischer Lundehund]] · [[Ostsibirische Laika]] · [[Russisch-Europäische Laika]] · [[Schwarzer Norwegischer Elchhund]] · [[Westsibirische Laika]]

### Sektion 3: Nordische Wach- und Hütehunde
[[Finnischer Lapphund]] · [[Islandhund]] · [[Lapinporokoira]] · [[Norwegischer Buhund]] · [[Schwedischer Lapphund]] · [[Schwedischer Wallhund]]

### Sektion 4: Europäische Spitze
[[Deutscher Spitz]] · [[Volpino Italiano]]

### Sektion 5: Asiatische Spitze und verwandte Rassen
[[Akita Inu]] · [[American Akita]] · [[Chow-Chow]] · [[Eurasier]] · [[Hokkaido]] · [[Japan-Spitz]] · [[Kai]] · [[Kintamani-Bali-Hund]] *(vorläufig)* · [[Kishu]] · [[Korea Jindo]] · [[Shiba Inu]] · [[Shikoku]] · [[Thai Bangkaew]]

### Sektion 6: Urtyp
[[Basenji]] · [[Kanaan-Hund]] · [[Peruanischer Nackthund]] · [[Pharaonenhund]] · [[Xoloitzcuintle]]

### Sektion 7: Urtyp – Hunde zur jagdlichen Verwendung
[[Cirneco dell'Etna]] · [[Kanarischer Podenco]] · [[Podenco Ibicenco]] · [[Podengo Português]] · [[Taiwan-Hund]] · [[Thai Ridgeback]]

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
