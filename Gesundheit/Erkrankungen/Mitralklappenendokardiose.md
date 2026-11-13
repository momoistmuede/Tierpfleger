---
aliases:
  - "MMVD"
  - "Mitralklappeninsuffizienz"
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
# Mitralklappenendokardiose

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Herz · **Erblich:** ja

Die Mitralklappenendokardiose ist die häufigste Herzerkrankung des Hundes. Die Mitralklappe verändert sich krankhaft (myxomatöse Degeneration): Sie wird dick und verformt und schließt nicht mehr dicht. Blut fließt zurück, und der linke Vorhof vergrößert sich. Etwa ein Drittel der Hunde entwickelt mit der Zeit eine Linksherzinsuffizienz mit Lungenödem. Betroffen sind vor allem kleine, ältere Hunde.

## Ursache
Die Veranlagung ist erblich und beim [[Cavalier King Charles Spaniel]] extrem häufig, oft schon in jungen Jahren. Außerdem spielt das Alter eine Rolle.

## Symptome
Ein Herzgeräusch ist das früheste Zeichen. Später kommen Husten, Leistungsschwäche, erhöhte Atemfrequenz und nächtliche Atemnot dazu.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt hört das Herz ab und untersucht es per Herzultraschall und Röntgen. Die Erkrankung wird in Stadien eingeteilt (ACVIM A–D). Ab Stadium B2 wird Pimobendan gegeben, bei Lungenödem zusätzlich entwässernde Medikamente.

## Hinweise für Tierpfleger
- Die **Ruheatemfrequenz** im Schlaf zählen und dokumentieren.
- Übergewicht vermeiden.
- Husten und Atemnot notieren und melden.

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
[[Dilatative Kardiomyopathie]], [[Syringomyelie]] · [[Erkrankungen.base|Alle Erkrankungen]]
