---
aliases:
  - "Kongenitale Taubheit"
  - "Angeborene Taubheit"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Ohren
erblich: true
tags:
  - erkrankung
  - erkrankung/ohren
  - hund
  - katze
  - erbkrankheit
---
# Erbliche Taubheit

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Ohren · **Erblich:** ja

Angeborene Taubheit hängt eng mit **weißer Fellfarbe bzw. Pigmentmangel** zusammen. Im Innenohr fehlen dann pigmentbildende Zellen (Melanozyten), die für das Hören nötig sind.

**Hund:**
- Ein besonders hohes Risiko haben Hunde aus **Merle × Merle-Verpaarungen** ("Double Merle"). Sie können außerdem Augenmissbildungen haben, siehe [[Qualzucht]].
- Auch Hunde mit sehr viel Weiß sind betroffen, z. B. Dalmatiner oder weiße Bullterrier. Beim Dalmatiner ist etwa jeder fünfte bis dritte Hund ein- oder beidseitig taub.

**Katze:**
- Weiße Katzen mit zwei blauen Augen sind häufig taub. Verantwortlich ist das dominante Weiß-Gen (W).
- Bei einem blauen Auge ist die Katze oft auf dieser Seite taub.

## Ursache
Die Ursache ist erblich und hängt direkt mit bestimmten Farbgenen zusammen: Merle, Extremscheckung (Piebald) und dominantes Weiß. Fehlen in der Stria vascularis des Innenohrs die Melanozyten, geht das Innenohr in den ersten 2–4 Lebenswochen zugrunde. Selten gibt es auch erbliche Taubheit ohne Bezug zur Fellfarbe, z. B. beim Dobermann.

## Symptome
Das Tier reagiert nicht auf Rufen oder Geräusche, schläft sehr tief und erschrickt bei Berührung. Einseitige Taubheit fällt oft gar nicht auf.

## Diagnose & Behandlung
Die Diagnose stellt ein **BAER-Test** (Hörtest über Hirnströme), möglich ab etwa 6 Wochen. Eine Behandlung gibt es nicht.

## Hinweise für Tierpfleger
- Taube Tiere nicht von hinten berühren, sonst erschrecken sie. Am besten vorher durch Vibration ankündigen, z. B. auf den Boden klopfen.
- Taube Hunde lernen über Handzeichen und Lichtsignale.
- Freigang ist für taube Katzen wegen des Verkehrs gefährlich.
- Die Taubheit in der Tierakte und im Vermittlungsprofil vermerken.

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
[[Progressive Retinaatrophie]] · [[Erkrankungen.base|Alle Erkrankungen]]
