---
aliases:
  - "PK-Defizienz"
  - "PK-Mangel"
tierart:
  - "[[Katze]]"
organsystem: Blut
erblich: true
tags:
  - erkrankung
  - erkrankung/blut
  - katze
  - erbkrankheit
---
# Pyruvatkinase-Defizienz

> [!info] Steckbrief
> **Tierart:** [[Katze]] · **Organsystem:** Blut · **Erblich:** ja

Bei der Pyruvatkinase-Defizienz fehlt den roten Blutkörperchen ein Enzym. Ohne Pyruvatkinase gewinnen sie zu wenig Energie und werden vorzeitig abgebaut. Die Folge ist eine wiederkehrende **hämolytische Anämie**. Auch beim Hund gibt es PK-Defizienzen, z. B. beim Basenji.

## Ursache
Die Erkrankung wird autosomal-rezessiv vererbt (PKLR-Gen). Betroffen sind u. a. [[Abessinier]], Somali und [[Bengal]].

## Symptome
Die Symptome schwanken: Müdigkeit, blasse Schleimhäute, Gewichtsverlust, Gelbsucht, vergrößerte Milz. Manche Tiere bleiben lange symptomlos.

## Diagnose & Behandlung
Die Diagnose stellen Blutbild und Gentest. In schweren Krisen hilft eine Bluttransfusion, gegebenenfalls wird die Milz entfernt.

## Hinweise für Tierpfleger
- Die Farbe der Schleimhäute kontrollieren. Blasse Schleimhäute sind ein Warnsignal.
- Stress und Infektionen möglichst vermeiden.

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
