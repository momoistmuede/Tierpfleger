---
aliases:
  - "Dermoidsinus"
  - "Sinus dermalis"
tierart:
  - "[[Hund]]"
organsystem: Haut
erblich: true
tags:
  - erkrankung
  - erkrankung/haut
  - hund
  - erbkrankheit
---
# Dermoid Sinus

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Haut · **Erblich:** ja

Ein Dermoid Sinus ist eine angeborene, röhrenförmige Einstülpung der Haut entlang der Rückenmitte. Sie kann bis zum Rückenmark reichen. Typisch ist er beim [[Rhodesian Ridgeback]]: Dieselbe Genveränderung, die den Ridge (Haarkamm) erzeugt, erhöht auch das Risiko für einen Dermoid Sinus. Vereinzelt kommt er auch bei anderen Rassen vor.

## Ursache
Die Ursache ist eine erbliche Entwicklungsstörung in der Embryonalzeit: Haut und Neuralrohr trennen sich nicht vollständig. Beim Ridgeback ist eine Verdopplung (Duplikation) mehrerer Wachstumsfaktor-Gene (u. a. FGF3, FGF4, FGF19) die Grundlage. Für den Ridge reicht eine Kopie. Hunde mit zwei Kopien haben ein deutlich höheres Risiko für einen Dermoid Sinus. Wahrscheinlich sind noch weitere Gene beteiligt. Folsäure für die Hündin vor und in der frühen Trächtigkeit senkt das Risiko möglicherweise.

## Symptome
Am Rücken lässt sich ein Strang oder eine kleine Öffnung mit Haarbüschel tasten. Es kann zu Entzündungen und Abszessen kommen. Reicht der Gang bis zum Rückenmark, drohen eine Hirnhaut- oder Rückenmarksentzündung mit neurologischen Ausfällen.

## Diagnose & Behandlung
Die Züchterin bzw. der Züchter tastet die Welpen ab, ergänzend wird per Bildgebung untersucht. Behandelt wird durch chirurgische Entfernung.

## Hinweise für Tierpfleger
- Bei Ridgebacks die Rückenlinie regelmäßig abtasten.
- Auf Schwellungen und Ausfluss achten.

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
[[Manx-Syndrom]] · [[Erkrankungen.base|Alle Erkrankungen]]
