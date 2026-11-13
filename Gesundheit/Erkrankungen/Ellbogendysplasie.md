---
aliases:
  - "ED"
tierart:
  - "[[Hund]]"
organsystem: Bewegungsapparat
erblich: true
tags:
  - erkrankung
  - erkrankung/bewegungsapparat
  - hund
  - erbkrankheit
---
# Ellbogendysplasie

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Bewegungsapparat · **Erblich:** ja

Ellbogendysplasie ist ein Sammelbegriff für Entwicklungsstörungen des Ellbogengelenks. Dazu gehören:
- fragmentierter Processus coronoideus (FCP)
- isolierter Processus anconaeus (IPA)
- Osteochondrosis dissecans (OCD)
- Stufenbildung im Gelenk

Alle diese Formen führen früh zur Arthrose.

## Ursache
Die Veranlagung ist erblich. Fütterung und Wachstumsgeschwindigkeit spielen ebenfalls eine Rolle.

## Symptome
Die Vorhand lahmt, meist ab einem Alter von 4–8 Monaten. Nach Ruhephasen ist die Lahmheit deutlicher. Oft sind die Pfoten nach außen gedreht.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Röntgen und CT. In der Zucht wird ED in die Grade 0–3 eingeteilt. Behandelt wird mit Arthroskopie, Schmerztherapie, Gewichtskontrolle und Physiotherapie.

## Hinweise für Tierpfleger
- Kontrolliert bewegen, also keine abrupten Stopps und Sprünge.
- Normalgewicht halten.
- Lahmheiten im Verlauf dokumentieren, das hilft bei der Therapieplanung.

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
[[Hüftgelenksdysplasie]] · [[Erkrankungen.base|Alle Erkrankungen]]
