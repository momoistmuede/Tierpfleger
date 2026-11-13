---
aliases:
  - "Atopie"
  - "Umweltallergie"
  - "CAD"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Haut
erblich: true
tags:
  - erkrankung
  - erkrankung/haut
  - hund
  - katze
  - erbkrankheit
---
# Atopische Dermatitis

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Haut · **Erblich:** ja

Die atopische Dermatitis ist eine chronisch-entzündliche, juckende Hauterkrankung. Sie entsteht durch eine Überreaktion auf Umweltallergene wie Hausstaubmilben, Pollen oder Schimmelpilze. Meist beginnt sie im Alter zwischen 6 Monaten und 3 Jahren. Bei Katzen gibt es ein ähnliches Krankheitsbild, das atopische Hautsyndrom.

## Ursache
Die Veranlagung ist erblich, die Hautbarriere ist gestört. Umweltallergene lösen die Beschwerden aus.

## Symptome
Juckreiz (Pfoten lecken, Gesicht reiben, Kratzen), Rötungen an Pfoten, Achseln, Bauch und Ohren, wiederkehrende Ohrentzündungen, Haarausfall. Oft kommen bakterielle Infektionen oder Hefepilze dazu.

## Diagnose & Behandlung
Die Diagnose ist eine **Ausschlussdiagnose**: Erst werden Parasiten und eine Futtermittelallergie ausgeschlossen, Letztere mit einer mindestens 8-wöchigen Ausschlussdiät. Ein Allergietest dient dazu, die Immuntherapie auszuwählen. Behandelt wird mit Juckreizhemmern, medizinischen Shampoos und Desensibilisierung. Das Management ist meist lebenslang.

## Hinweise für Tierpfleger
- Den Juckreiz täglich auf einer Skala dokumentieren.
- Die Parasitenprophylaxe konsequent durchführen, siehe [[Parasitenprophylaxe]].
- Eine Ausschlussdiät **strikt** einhalten, also keine Leckerlis. Siehe [[Ernährung Hund]] und [[Ernährung Katze]].
- Pfoten nach dem Spaziergang abwaschen und die Fellpflege anpassen, siehe [[Fellpflege]].

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
