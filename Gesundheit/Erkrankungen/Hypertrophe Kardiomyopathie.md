---
aliases:
  - "HCM"
  - "HKM"
tierart:
  - "[[Katze]]"
organsystem: Herz
erblich: true
tags:
  - erkrankung
  - erkrankung/herz
  - katze
  - erbkrankheit
  - notfall
---
# Hypertrophe Kardiomyopathie

> [!info] Steckbrief
> **Tierart:** [[Katze]] · **Organsystem:** Herz · **Erblich:** ja

Die hypertrophe Kardiomyopathie ist die **häufigste Herzerkrankung der Katze**. Der Herzmuskel der linken Kammer verdickt sich, wird steif und füllt sich schlecht. Dadurch vergrößert sich der Vorhof. Die Folgen sind Herzinsuffizienz und Blutgerinnsel.

## Ursache
Bei einigen Rassen ist die Erkrankung erblich. Für bestimmte Mutationen bei der [[Maine Coon]] und der [[Ragdoll]] gibt es Gentests (MYBPC3-Gen). Ein negativer Gentest schließt HCM aber nicht aus.

## Symptome
Die Erkrankung bleibt oft lange unauffällig. Dann treten schnelle oder angestrengte Atmung, Atmen mit offenem Maul und Mattigkeit auf.

**Aortenthrombose** (Notfall): plötzliche Lähmung der Hinterbeine, kalte Pfoten, starke Schmerzen, Schreien.

Auch ein plötzlicher Herztod ist möglich.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Herzultraschall. Zuchttiere sollten regelmäßig gescreent werden. Ergänzend gibt es einen NT-proBNP-Bluttest. Medikamente entwässern und hemmen die Blutgerinnung. Heilbar ist die Erkrankung nicht.

## Hinweise für Tierpfleger
- Die **Ruheatemfrequenz** im Schlaf zählen. Mehr als 30 Atemzüge pro Minute ist ein Warnsignal.
- Stress vermeiden.
- Bei plötzlicher Lähmung der Hinterbeine **sofort** zur Tierärztin bzw. zum Tierarzt.

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
[[Dilatative Kardiomyopathie]] · [[Erkrankungen.base|Alle Erkrankungen]]
