---
aliases:
  - "Faltohr-Osteochondrodysplasie"
  - "SFOCD"
tierart:
  - "[[Katze]]"
organsystem: Bewegungsapparat
erblich: true
tags:
  - erkrankung
  - erkrankung/bewegungsapparat
  - katze
  - erbkrankheit
  - qualzucht
---
# Osteochondrodysplasie

> [!info] Steckbrief
> **Tierart:** [[Katze]] · **Organsystem:** Bewegungsapparat · **Erblich:** ja

Die Osteochondrodysplasie ist eine erbliche Störung der Knorpel- und Knochenentwicklung. Sie wird durch dasselbe Gen verursacht (TRPV4-Mutation), das die gefalteten Ohren der [[Scottish Fold]] bewirkt. **Das Faltohr ist also selbst schon ein Symptom des Knorpeldefekts.** Alle Faltohrkatzen sind betroffen, allerdings unterschiedlich stark. Bei reinerbigen Tieren aus Fold × Fold-Verpaarungen ist die Erkrankung besonders schwer.

## Ursache
Die Ursache ist die Zucht auf das Faltohr-Merkmal. Sie gilt als [[Qualzucht]].

## Symptome
Schwanz und Gliedmaßen verdicken und versteifen sich, die Gliedmaßen bleiben kurz. An Pfoten und Gelenken bilden sich Knochenzubildungen. Es kommt zu schmerzhafter Arthrose, Lahmheit und Bewegungsunlust, die Katze springt nicht mehr.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Röntgen. Behandelt wird vor allem mit Schmerzmitteln. Heilbar ist die Erkrankung nicht.

## Hinweise für Tierpfleger
- Katzen zeigen Schmerzen kaum. Auf Hinweise achten: Die Katze springt nicht mehr, zieht sich zurück oder wird unsauber, weil der Einstieg ins Katzenklo schmerzt.
- Ein niedriges Katzenklo, Rampen und weiche Liegeplätze anbieten.

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
