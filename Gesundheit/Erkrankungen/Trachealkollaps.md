---
aliases:
  - "Luftröhrenkollaps"
tierart:
  - "[[Hund]]"
organsystem: Atemwege
erblich: false
tags:
  - erkrankung
  - erkrankung/atemwege
  - hund
---
# Trachealkollaps

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Atemwege · **Erblich:** nein (Veranlagung möglich)

Beim Trachealkollaps sind die Knorpelspangen der Luftröhre zu weich. Die Luftröhre flacht deshalb beim Atmen ab und fällt zusammen. Das ist typisch für Zwerg- und Toyrassen mittleren Alters.

## Ursache
Ursache ist eine angeborene Knorpelschwäche. Verstärkend wirken Übergewicht, Zug am Halsband, Rauch und Atemwegsinfekte.

## Symptome
Typisch ist ein trockener, "hupender" Husten (Gänsehusten), besonders bei Aufregung, beim Ziehen an der Leine oder beim Trinken. In schweren Fällen kommen Atemnot und eine blaue Zunge (Zyanose) dazu.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Röntgen, Durchleuchtung und Endoskopie. Behandelt wird mit Gewichtsreduktion, Hustenstillern und Entzündungshemmern. In schweren Fällen wird ein Stent eingesetzt oder operiert.

## Hinweise für Tierpfleger
- **Brustgeschirr statt Halsband** verwenden.
- Aufregung, Hitze und Rauch vermeiden.
- Hustenanfälle dokumentieren.

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
[[Brachyzephalie]] · [[Erkrankungen.base|Alle Erkrankungen]]
