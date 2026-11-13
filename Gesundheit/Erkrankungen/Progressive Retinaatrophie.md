---
aliases:
  - "PRA"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Augen
erblich: true
tags:
  - erkrankung
  - erkrankung/augen
  - hund
  - katze
  - erbkrankheit
---
# Progressive Retinaatrophie

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Augen · **Erblich:** ja

Die progressive Retinaatrophie umfasst eine Gruppe erblicher Netzhauterkrankungen. Die Lichtsinneszellen gehen nach und nach zugrunde, zuerst die Stäbchen. Daraus entwickelt sich eine Nachtblindheit, die bis zur vollständigen Erblindung fortschreitet. **Schmerzhaft ist die Erkrankung nicht.** Sie betrifft Hunde und Katzen, wobei je nach Rasse verschiedene Genvarianten verantwortlich sind:
- Hund: z. B. *prcd*-PRA
- Katze: z. B. *rdAc* bei Abessinier und Siam

## Ursache
Die Erkrankung ist erblich, meist autosomal-rezessiv. Für viele Rassen gibt es Gentests.

## Symptome
Unsicherheit in der Dämmerung und im Dunkeln, Anstoßen an Gegenstände, weite Pupillen, auffällig reflektierende Augen. Später kann ein Grauer Star (Katarakt) hinzukommen.

## Diagnose & Behandlung
Die Diagnose stellt eine Fachtierärztin bzw. ein Fachtierarzt für Augenheilkunde, ergänzt durch Elektroretinografie und Gentest. Eine Behandlung gibt es nicht.

## Hinweise für Tierpfleger
- Blinde Tiere kommen meist erstaunlich gut zurecht, wenn die Umgebung **gleich bleibt**.
- Das Tier ansprechen, bevor man es berührt. Geräusch- und Duftmarken helfen bei der Orientierung.
- Bei Zuchttieren nach dem Gentest-Ergebnis fragen.

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
[[Collie Eye Anomaly]] · [[Erkrankungen.base|Alle Erkrankungen]]
