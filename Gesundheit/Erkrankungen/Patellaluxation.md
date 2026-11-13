---
aliases:
  - "PL"
  - "Kniescheibenluxation"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Bewegungsapparat
erblich: true
tags:
  - erkrankung
  - erkrankung/bewegungsapparat
  - hund
  - katze
  - erbkrankheit
---
# Patellaluxation

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Bewegungsapparat · **Erblich:** ja

Bei der Patellaluxation springt die Kniescheibe (Patella) aus ihrer Führungsrinne, meist nach innen (medial). Sie ist sehr häufig bei kleinen Hunderassen und kommt auch bei Katzen vor, z. B. bei [[Abessinier]] und [[Devon Rex]].

## Ursache
Meist ist die Ursache erblich: Die Führungsrinne ist zu flach, oder die Gliedmaßen stehen fehlerhaft. Seltener ist ein Unfall die Ursache.

## Symptome
Das Tier hüpft zeitweise auf drei Beinen, hält das Bein kurz hoch und schüttelt es dann aus. Später entwickeln sich dauerhafte Lahmheit und Arthrose, und das Risiko für einen Kreuzbandriss steigt.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt tastet das Knie ab und stuft die Luxation in Grad 1–4 ein, ergänzt durch Röntgen. Bei leichten Graden helfen Muskelaufbau und Gewichtskontrolle, bei höheren Graden eine Operation.

## Hinweise für Tierpfleger
- Für rutschfeste Böden sorgen, das Gewicht halten und die Muskulatur aufbauen.
- Lahmheitsepisoden mit Datum notieren.

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
