---
aliases:
  - "DCM"
  - "DKM"
tierart:
  - "[[Hund]]"
organsystem: Herz
erblich: true
tags:
  - erkrankung
  - erkrankung/herz
  - hund
  - erbkrankheit
---
# Dilatative Kardiomyopathie

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Herz · **Erblich:** ja

Bei der dilatativen Kardiomyopathie erschlafft der Herzmuskel, und die Herzkammern erweitern sich. Das Herz pumpt schlechter. Die Folgen sind Herzinsuffizienz und gefährliche Herzrhythmusstörungen bis zum plötzlichen Herztod. DCM ist die häufigste Herzmuskelerkrankung großer Hunderassen.

## Ursache
Die Erkrankung ist erblich und beim [[Dobermann]] sehr häufig. Seltener ist sie ernährungsbedingt (Taurinmangel). Beim Boxer kommt zusätzlich die **ARVC** vor (arrhythmogene rechtsventrikuläre Kardiomyopathie, "Boxer-Kardiomyopathie"), bei der vor allem Rhythmusstörungen auftreten.

## Symptome
Die Erkrankung bleibt lange unbemerkt (okkulte Phase). Dann treten Leistungsschwäche, Husten, Atemnot, Ohnmachtsanfälle und Bauchwasser auf. Manche Hunde sterben plötzlich.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Herzultraschall und Langzeit-EKG (Holter). Bei Risikorassen wird jährlich gescreent. Medikamente wie Pimobendan verlangsamen das Fortschreiten.

## Hinweise für Tierpfleger
- Die **Ruheatemfrequenz** im Schlaf zählen. Mehr als 30–35 Atemzüge pro Minute oder ein deutlicher Anstieg gegenüber dem eigenen Normalwert ist ein Warnsignal.
- Die Belastung anpassen und Medikamente pünktlich geben.
- Ohnmachtsanfälle sofort melden.

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
[[Mitralklappenendokardiose]], [[Hypertrophe Kardiomyopathie]], [[Subaortenstenose]] · [[Erkrankungen.base|Alle Erkrankungen]]
