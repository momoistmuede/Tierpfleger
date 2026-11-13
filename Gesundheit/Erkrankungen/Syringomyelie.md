---
aliases:
  - "SM"
  - "Chiari-ähnliche Malformation"
  - "CM/SM"
tierart:
  - "[[Hund]]"
organsystem: Nervensystem
erblich: true
tags:
  - erkrankung
  - erkrankung/nervensystem
  - hund
  - erbkrankheit
  - qualzucht
---
# Syringomyelie

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Nervensystem · **Erblich:** ja

Bei der Syringomyelie bilden sich flüssigkeitsgefüllte Hohlräume (Syrinx) im Rückenmark. Meist ist sie die Folge einer **Chiari-ähnlichen Malformation**: Der hintere Schädel ist zu klein für das Gehirn, das Kleinhirn wird ins Hinterhauptsloch gedrückt, und das Hirnwasser kann nicht mehr frei fließen.

## Ursache
Die Erkrankung ist erblich und wird durch die Zucht auf kleine, runde Köpfe gefördert. Sie gilt als [[Qualzucht]]-Merkmal.

## Symptome
Typisch ist das **Phantomkratzen**: Der Hund kratzt am Hals in die Luft, oft beim Gehen an der Leine. Weitere Zeichen sind Schmerzen bei Berührung von Kopf und Hals, Aufschreien, eine verkrümmte Wirbelsäule (Skoliose) und Schwäche.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per MRT. Behandelt wird mit Schmerzmitteln wie Gabapentin und mit Medikamenten, die die Liquorproduktion senken. Eine Operation ist selten.

## Hinweise für Tierpfleger
- Brustgeschirr statt Halsband verwenden.
- Phantomkratzen und Schmerzäußerungen dokumentieren, ein Video hilft der Tierärztin bzw. dem Tierarzt.
- Auf Kälte und Wetterwechsel achten, weil sich die Symptome dann oft verstärken.

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
[[Mitralklappenendokardiose]], [[Brachyzephalie]] · [[Erkrankungen.base|Alle Erkrankungen]]
