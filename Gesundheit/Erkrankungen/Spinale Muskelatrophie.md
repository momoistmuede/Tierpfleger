---
aliases:
  - "SMA"
tierart:
  - "[[Katze]]"
organsystem: Nervensystem
erblich: true
tags:
  - erkrankung
  - erkrankung/nervensystem
  - katze
  - erbkrankheit
---
# Spinale Muskelatrophie

> [!info] Steckbrief
> **Tierart:** [[Katze]] · **Organsystem:** Nervensystem · **Erblich:** ja

Die spinale Muskelatrophie ist eine erbliche Erkrankung der [[Maine Coon]]. Die motorischen Nervenzellen im Rückenmark sterben ab. Dadurch schwinden die Muskeln, vor allem an den Hinterbeinen.

## Ursache
Die Erkrankung wird autosomal-rezessiv vererbt. Ursache ist eine Deletion, bei der Teile der Gene LIX1 und LNPEP fehlen. Ein Gentest ist verfügbar. Träger erkranken nicht, geben die Veränderung aber an die Hälfte ihrer Nachkommen weiter.

## Symptome
Ab etwa 3–4 Monaten zeigen die Kitten einen schwankenden, watschelnden Gang, Zittern, schwache Hinterbeine und Probleme beim Springen. Schmerzhaft ist die Erkrankung nicht. In Wohnungshaltung ist die Lebensqualität oft gut.

## Diagnose & Behandlung
Die Diagnose stellt ein Gentest. Eine Behandlung gibt es nicht.

## Hinweise für Tierpfleger
- Die Umgebung anpassen: niedrige Kratzbäume, Rampen, ein Katzenklo mit niedrigem Einstieg.

## Betroffene Rassen
Diese Rassen verweisen auf diese Erkrankung:

```base
filters:
  and:
    - file.hasTag("rasse")
    - file.hasLink(this.file)
properties:
  file.name:
    displayName: Rasse
views:
  - type: table
    name: Betroffene Rassen
    order:
      - file.name
      - tierart
      - herkunft
    sort:
      - property: file.name
        direction: ASC
```

## Siehe auch
[[Erkrankungen.base|Alle Erkrankungen]]
