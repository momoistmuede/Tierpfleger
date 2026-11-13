---
aliases:
  - "Magentorsion"
  - "GDV"
tierart:
  - "[[Hund]]"
organsystem: Verdauung
erblich: false
tags:
  - erkrankung
  - erkrankung/verdauung
  - hund
  - notfall
---
# Magendrehung

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Verdauung · **Erblich:** nein (Veranlagung möglich)

Die Magendrehung ist ein **lebensbedrohlicher Notfall**. Der Magen dreht sich um seine Achse, sodass Mageneingang und -ausgang verschlossen sind. Gas staut sich, und die Blutversorgung von Magen und Milz bricht zusammen. Es kommt zum Schock. Ohne Operation stirbt der Hund innerhalb weniger Stunden.

## Ursache
Betroffen sind vor allem große, tiefbrüstige Rassen. Risikofaktoren sind:
- nur eine große Mahlzeit am Tag
- hastiges Fressen
- Toben nach dem Fressen
- Stress
- höheres Alter
- Fälle von Magendrehung bei Verwandten

## Symptome
Erfolgloses Würgen bzw. Erbrechen (nur Schaum), aufgeblähter und harter Bauch, Unruhe, Speicheln, blasse Schleimhäute, Kollaps.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Röntgen. Dann folgt eine **Notoperation**: Der Magen wird zurückgedreht und an der Bauchwand angenäht (Gastropexie). Bei Risikohunden ist eine vorbeugende Gastropexie möglich, z. B. zusammen mit der Kastration.

## Hinweise für Tierpfleger
- **Notfall: sofort zur Tierärztin bzw. zum Tierarzt!** Jede Minute zählt.
- Vorbeugen: mehrere kleine Mahlzeiten, 1–2 Stunden Ruhe nach dem Fressen, Futterneid und Hektik bei der Fütterung vermeiden. Siehe [[Ernährung Hund]].
- Hunde nach dem Füttern nicht gleich ausführen oder in Spielgruppen lassen.

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
