---
aliases:
  - "Krebs"
  - "Neoplasien"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Onkologie
erblich: false
tags:
  - erkrankung
  - erkrankung/onkologie
  - hund
  - katze
---
# Tumorerkrankungen

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Onkologie · **Erblich:** nein (Veranlagung möglich)

Tumoren gehören bei älteren Hunden und Katzen zu den häufigsten Todesursachen. Manche Rassen neigen deutlich stärker zu bestimmten Tumorarten:
- **Berner Sennenhund:** histiozytäres Sarkom
- **Golden Retriever:** Hämangiosarkom, Lymphom
- **Boxer:** Mastzelltumoren
- **Rottweiler, Deutsche Dogge:** Osteosarkom (Knochenkrebs)

Bei Katzen kommen u. a. Lymphome vor. Eine FeLV-Infektion erhöht das Risiko stark, heute sind die meisten Lymphome aber FeLV-negativ. Außerdem gibt es Fibrosarkome an Injektionsstellen und Plattenepithelkarzinome an weißen Ohren (durch Sonne).

## Ursache
Die Ursachen sind vielfältig: genetische Veranlagung, Alter, Viren (FeLV), UV-Strahlung und Hormone. Nicht kastrierte Hündinnen haben z. B. ein höheres Risiko für Gesäugetumoren.

## Symptome
Neue Knoten oder Umfangsvermehrungen, Lahmheit (bei Knochentumoren), Gewichtsverlust, Leistungsschwäche, blasse Schleimhäute, Blutungen.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt untersucht per Feinnadelaspiration, Biopsie und Bildgebung. Behandlungsmöglichkeiten sind Operation, Chemotherapie, Bestrahlung und palliative Therapie.

## Hinweise für Tierpfleger
- Beim Bürsten auf neue Knoten achten. Größe und Lage dokumentieren, am besten mit Körperskizze oder Foto mit Maßband.
- Das Tier regelmäßig wiegen.
- Bei Katzen die Injektionsstellen beobachten. Eine Schwellung, die 3 Monate nach der Injektion noch besteht, größer als 2 cm ist oder 1 Monat danach noch wächst, tierärztlich abklären lassen (3-2-1-Regel).

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
[[Erkrankungen.base|Alle Erkrankungen]]
