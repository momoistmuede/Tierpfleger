---
aliases:
  - "PKD"
  - "Zystennieren"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Niere
erblich: true
tags:
  - erkrankung
  - erkrankung/niere
  - hund
  - katze
  - erbkrankheit
---
# Polyzystische Nierenerkrankung

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Niere · **Erblich:** ja

Bei dieser erblichen Erkrankung bilden sich von Geburt an flüssigkeitsgefüllte Zysten in den Nieren. Die Zysten wachsen und verdrängen gesundes Gewebe. Daraus entwickelt sich eine chronische Niereninsuffizienz, bei Katzen meist zwischen 3 und 10 Jahren. Die Erkrankung kommt bei Katzen und Hunden vor. Beim Hund ist vor allem der Bullterrier betroffen. Dort ist der Verlauf sehr unterschiedlich.

## Ursache
Die Erkrankung wird autosomal-dominant vererbt und geht bei Katze und Hund auf Veränderungen im PKD1-Gen zurück. Schon eine Genkopie führt zur Erkrankung.
- **Katze:** verbreitet beim [[Perser]] und bei Rassen, in die Perser eingekreuzt wurden
- **Hund:** beim Bullterrier und Miniatur Bullterrier

Für beide Tierarten gibt es Gentests. Selten gibt es beim Hund auch andere, rezessiv vererbte Formen mit Zysten in Nieren und Leber, z. B. bei Welpen von Cairn Terrier und West Highland White Terrier.

## Symptome
Das Tier trinkt und uriniert mehr, verliert Gewicht und erbricht. Das Fell wird stumpf, und es kommt zu Mundgeruch durch Harnvergiftung (Urämie).

## Diagnose & Behandlung
Die Diagnose stellen ein Gentest und eine Ultraschalluntersuchung. Behandelt wird mit Nierendiät, Flüssigkeitstherapie und Blutdruckkontrolle. Heilbar ist die Erkrankung nicht.

## Hinweise für Tierpfleger
- Trinkmenge und Urinmenge beobachten. Bei Katzen ist die Größe der Klumpen im Katzenklo ein Hinweis.
- Nassfutter und frisches Wasser anbieten, Katzen auch einen Trinkbrunnen. Siehe [[Ernährung Katze]] und [[Ernährung Hund]].
- Zuchttiere sollten PKD-negativ getestet sein.

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
[[Hypokaliämie]], [[Harnsteine]] · [[Erkrankungen.base|Alle Erkrankungen]]
