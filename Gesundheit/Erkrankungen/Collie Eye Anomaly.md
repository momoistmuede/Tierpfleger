---
aliases:
  - "CEA"
  - "Collie-Augen-Anomalie"
tierart:
  - "[[Hund]]"
organsystem: Augen
erblich: true
tags:
  - erkrankung
  - erkrankung/augen
  - hund
  - erbkrankheit
---
# Collie Eye Anomaly

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Augen · **Erblich:** ja

Bei der Collie Eye Anomaly hat sich der hintere Augenabschnitt angeboren fehlentwickelt. Die Aderhaut ist unterentwickelt (Hypoplasie). Teilweise kommen Kolobome (Spaltbildungen) und Netzhautablösungen dazu. Betroffen sind vor allem Collie-artige Hütehunde wie Collie, Sheltie, Border Collie und Australian Shepherd, aber z. B. auch der Nova Scotia Duck Tolling Retriever. Die meisten betroffenen Hunde sehen ihr Leben lang normal.

## Ursache
Die Erkrankung wird autosomal-rezessiv vererbt (NHEJ1-Gen). Ein Gentest ist verfügbar.

## Symptome
Meist zeigt der Hund keine sichtbaren Symptome. In schweren Fällen kommt es durch Netzhautablösung oder Blutungen zu Sehstörungen bis zur Blindheit.

## Diagnose & Behandlung
Die Diagnose stellt eine Fachtierärztin bzw. ein Fachtierarzt für Augenheilkunde, möglich schon bei Welpen ab 6–7 Wochen. Ergänzend gibt es einen Gentest. Behandeln lässt sich die Erkrankung nicht. In der Zucht hilft der Gentest, Verpaarungen so zu planen, dass keine betroffenen Welpen entstehen.

## Hinweise für Tierpfleger
- Bei sehbehinderten Hunden die Umgebung gleich lassen und keine Möbel verstellen.
- Den Hund ansprechen, bevor man ihn berührt.

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
[[Progressive Retinaatrophie]], [[MDR1-Defekt]] · [[Erkrankungen.base|Alle Erkrankungen]]
