---
aliases:
  - "GSD IV"
  - "Glykogenose Typ IV"
tierart:
  - "[[Katze]]"
organsystem: Stoffwechsel
erblich: true
tags:
  - erkrankung
  - erkrankung/stoffwechsel
  - katze
  - erbkrankheit
---
# Glykogenspeicherkrankheit Typ IV

> [!info] Steckbrief
> **Tierart:** [[Katze]] · **Organsystem:** Stoffwechsel · **Erblich:** ja

Die Glykogenspeicherkrankheit Typ IV ist eine seltene, erbliche Stoffwechselkrankheit der [[Norwegische Waldkatze|Norwegischen Waldkatze]]. Den Tieren fehlt das Glykogen-Verzweigungsenzym (GBE1-Gen). Dadurch wird Glykogen fehlerhaft gespeichert und lagert sich in Muskeln, Leber und Nerven ab.

## Ursache
Die Erkrankung wird autosomal-rezessiv vererbt. Ein Gentest ist verfügbar.

## Symptome
Viele betroffene Kitten werden tot geboren oder sterben kurz nach der Geburt, oft durch Unterzuckerung. Überlebende Tiere entwickeln ab etwa 5 Monaten Muskelzittern, Schwäche und Muskelschwund und sterben meist früh.

## Diagnose & Behandlung
Die Diagnose stellt ein Gentest. Eine Behandlung gibt es nicht. Zuchttiere müssen getestet werden.

## Hinweise für Tierpfleger
- Bei Kitten dieser Rasse auf Trinkschwäche, Schwäche und Zittern achten.
- Nach den Gentest-Ergebnissen der Elterntiere fragen.

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
