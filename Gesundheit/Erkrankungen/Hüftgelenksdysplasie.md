---
aliases:
  - "HD"
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
# Hüftgelenksdysplasie

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Bewegungsapparat · **Erblich:** ja

Bei der Hüftgelenksdysplasie hat sich das Hüftgelenk fehlerhaft entwickelt: Gelenkpfanne und Oberschenkelkopf passen nicht richtig zusammen. Das Gelenk wird instabil und entwickelt mit der Zeit eine Arthrose. HD ist die häufigste Skeletterkrankung großer Hunderassen. Sie kommt aber auch bei Katzen vor, besonders bei der [[Maine Coon]].

## Ursache
Die Veranlagung wird polygen vererbt. Verstärkend wirken Umweltfaktoren: zu schnelles Wachstum durch energiereiches Futter, Übergewicht und Überlastung im Wachstum.

## Symptome
Lahmheit der Hinterhand, "Hasenhoppeln" (beide Hinterbeine springen gleichzeitig ab), Schwierigkeiten beim Aufstehen und Treppensteigen, Muskelabbau an der Hinterhand. Katzen zeigen oft nur, dass sie weniger springen.

## Diagnose & Behandlung
Die Diagnose stellt die Tierärztin bzw. der Tierarzt per Röntgen unter Sedation. In der Zucht wird HD offiziell von **A** (frei) bis **E** (schwer) eingestuft. Behandelt wird mit Gewichtsreduktion, gelenkschonender Bewegung (Schwimmen, Physiotherapie) und Schmerzmitteln. In schweren Fällen hilft eine Operation, z. B. ein künstliches Hüftgelenk.

## Hinweise für Tierpfleger
- Gelenkschonend bewegen, für rutschfeste Böden und weiche Liegeplätze sorgen.
- Das Gewicht konsequent kontrollieren, siehe [[Ernährung Hund]].
- Welpen und Junghunde großer Rassen nicht überlasten, siehe [[Bewegung und Beschäftigung Hund]].
- Bei der Abgabe von Rassehunden nach dem HD-Befund der Elterntiere fragen.

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
[[Ellbogendysplasie]], [[Patellaluxation]] · [[Erkrankungen.base|Alle Erkrankungen]]
