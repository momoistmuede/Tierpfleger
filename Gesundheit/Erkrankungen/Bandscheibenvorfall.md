---
aliases:
  - "Dackellähme"
  - "IVDD"
  - "Diskopathie"
tierart:
  - "[[Hund]]"
organsystem: Nervensystem
erblich: true
tags:
  - erkrankung
  - erkrankung/nervensystem
  - hund
  - erbkrankheit
  - notfall
---
# Bandscheibenvorfall

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Nervensystem · **Erblich:** ja

Bei einem Bandscheibenvorfall wölbt sich eine Bandscheibe vor, oder ihr Kern tritt aus. Sie drückt dann auf das Rückenmark. Die Folgen reichen von Schmerzen bis zur Lähmung. Kurzbeinige (chondrodystrophe) Rassen erkranken oft schon mit 3–7 Jahren, weil ihre Bandscheiben früh verkalken.

## Ursache
Erblich ist die Chondrodystrophie: Ein FGF4-Retrogen auf Chromosom 12 lässt die Bandscheiben früh degenerieren und verkalken und verkürzt zugleich die Beine. Dafür gibt es einen Gentest. Verstärkend wirken Übergewicht, Sprünge und Treppensteigen.

## Symptome
Rückenschmerzen (aufgekrümmter Rücken, Zittern, Aufschreien bei Berührung), Bewegungsunlust, schwankender Gang, Lähmung der Hinterbeine, Harn- und Kotinkontinenz.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt untersucht den Hund neurologisch und macht ein CT oder MRT. Leichte Fälle werden mit strenger Boxenruhe und Schmerzmitteln behandelt. Bei Lähmung ist eine schnelle Operation nötig: Ob das Tiefenschmerzempfinden erhalten ist, entscheidet über die Prognose.

## Hinweise für Tierpfleger
- **Plötzliche Lähmungserscheinungen sind ein Notfall.**
- Gelähmte Hunde: Blase nach tierärztlicher Anleitung manuell entleeren, regelmäßig umlagern, Druckstellen vorbeugen.
- Vorbeugen: Normalgewicht halten, Sprünge und Treppen vermeiden, Brustgeschirr statt Halsband.

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
[[Degenerative Myelopathie]] · [[Erkrankungen.base|Alle Erkrankungen]]
