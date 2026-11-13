---
aliases:
  - "DM"
tierart:
  - "[[Hund]]"
organsystem: Nervensystem
erblich: true
tags:
  - erkrankung
  - erkrankung/nervensystem
  - hund
  - erbkrankheit
---
# Degenerative Myelopathie

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Nervensystem · **Erblich:** ja

Die degenerative Myelopathie ist eine langsam fortschreitende, **nicht schmerzhafte** Degeneration des Rückenmarks. Sie betrifft ältere Hunde, meist ab 8 Jahren, und führt zur Lähmung, die an der Hinterhand beginnt. Sie ähnelt der ALS beim Menschen.

## Ursache
Ursache ist eine Mutation im SOD1-Gen, für die es einen Gentest gibt. Nicht jeder Hund mit zwei defekten Genkopien erkrankt jedoch.

## Symptome
Der Gang der Hinterhand wird schwankend, die Zehen schleifen (abgelaufene Krallen), die Beine überkreuzen sich. Später folgen Lähmung und Inkontinenz. Schmerzen hat der Hund nicht.

## Diagnose & Behandlung
Die Diagnose ist eine Ausschlussdiagnose: Ein [[Bandscheibenvorfall]] oder Tumoren werden per MRT ausgeschlossen. Ergänzend gibt es einen Gentest. Heilbar ist die Erkrankung nicht. Physiotherapie verlangsamt den Verlauf, Hilfsmittel wie Rollwagen und Pfotenschuhe erleichtern den Alltag.

## Hinweise für Tierpfleger
- Für rutschfeste Böden sorgen und die Pfoten mit Schuhen schützen.
- Regelmäßige Physiotherapie und Bewegung erhalten die Beweglichkeit.
- Die Lebensqualität regelmäßig einschätzen und mit der Tierärztin bzw. dem Tierarzt besprechen.

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
[[Bandscheibenvorfall]] · [[Erkrankungen.base|Alle Erkrankungen]]
