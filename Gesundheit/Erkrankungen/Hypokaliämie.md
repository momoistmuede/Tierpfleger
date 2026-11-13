---
aliases:
  - "Kaliummangel"
  - "Hypokaliämische Polymyopathie"
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
# Hypokaliämie

> [!info] Steckbrief
> **Tierart:** [[Katze]] · **Organsystem:** Stoffwechsel · **Erblich:** ja

Bei einer Hypokaliämie ist der Kaliumspiegel im Blut zu niedrig. Das führt zu Muskelschwäche. Bei der [[Burma]] gibt es eine **erbliche Form** mit Schwächeanfällen, die schon bei jungen Katzen auftreten. Bei älteren Katzen ist eine Hypokaliämie häufig die Folge einer chronischen Nierenerkrankung.

## Ursache
Die erbliche Form bei der Burma wird autosomal-rezessiv vererbt (WNK4-Gen). Sie kommt auch bei verwandten Rassen vor, z. B. Tonkanese, Burmilla, Bombay und Singapura. Die erworbene Form entsteht vor allem durch eine chronische Nierenerkrankung, seltener durch eine Überfunktion der Nebenniere (Hyperaldosteronismus), langes Erbrechen oder kaliumarme Ernährung.

## Symptome
Typisch ist ein **nach unten hängender Kopf** (die Katze beugt den Hals nach unten). Dazu kommen steifer Gang, Muskelschwäche und Berührungsempfindlichkeit, oft in Episoden.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Blutuntersuchung (Kalium, CK) und Gentest. Behandelt wird mit Kalium zum Eingeben, oft lebenslang. Die Erkrankung ist gut behandelbar.

## Hinweise für Tierpfleger
- Medikamente zuverlässig geben.
- Kopfhaltung und Gang beobachten.
- Siehe [[Ernährung Katze]].

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
[[Polyzystische Nierenerkrankung]] · [[Erkrankungen.base|Alle Erkrankungen]]
