---
aliases:
  - "BOAS"
  - "Brachyzephales Syndrom"
  - "Kurzköpfigkeit"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Atemwege
erblich: true
tags:
  - erkrankung
  - erkrankung/atemwege
  - hund
  - katze
  - erbkrankheit
  - qualzucht
  - notfall
---
# Brachyzephalie

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Atemwege · **Erblich:** ja

Brachyzephale (kurzköpfige) Rassen haben einen stark verkürzten Gesichtsschädel. Die Weichteile wie Gaumensegel, Zunge und Nasenmuscheln sind aber nicht entsprechend kleiner geworden. Dadurch sind die Atemwege eng. So entsteht das **brachyzephale obstruktive Atemwegssyndrom (BOAS)**. Dazu kommen Probleme an Augen, Zähnen und Haut. Betroffen sind Hunde **und** Katzen.

## Ursache
Die Ursache ist die Zucht auf extreme Kurzköpfigkeit. Sie gilt als [[Qualzucht]] nach § 11b TierSchG.

## Symptome
**Hund:**
- verengte Nasenlöcher, Schnarchen, Atemnot, Schlafapnoe
- Hitzeintoleranz, weil das Hecheln die Wärme nicht ausreichend abführt
- Hornhautverletzungen durch hervortretende Augen
- entzündete Hautfalten
- Zahnfehlstellungen
- Geburten oft nur per Kaiserschnitt

**Katze:**
- Tränenfluss durch verlegte Tränenkanäle
- Atemgeräusche
- Augenerkrankungen
- Probleme beim Fressen

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt beurteilt die Atmung mit einem Belastungstest und einer Endoskopie. Eine Operation (Nasenlöcher erweitern, Gaumensegel kürzen) verbessert die Atmung, heilt die Erkrankung aber nicht.

## Hinweise für Tierpfleger
- **Hitze ist lebensgefährlich:** an warmen Tagen nur kurze Runden am Morgen oder Abend, Schatten und Kühlmatte anbieten.
- Lautes Atmen, blaue Zunge oder Kollaps sind ein **Notfall**.
- Bei Narkosen ist das Risiko erhöht. Das Tier überwachen, bis es vollständig wach ist.
- Hautfalten und Augen pflegen, siehe [[Fellpflege]] und [[Zahnpflege]].
- Mit Brustgeschirr führen, nicht mit Halsband.

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
[[Trachealkollaps]], [[Syringomyelie]], [[Lidfehlstellungen]] · [[Erkrankungen.base|Alle Erkrankungen]]
