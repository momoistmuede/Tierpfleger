---
aliases:
  - "Entropium"
  - "Ektropium"
  - "Rolllid"
tierart:
  - "[[Hund]]"
organsystem: Augen
erblich: true
tags:
  - erkrankung
  - erkrankung/augen
  - hund
  - erbkrankheit
  - qualzucht
---
# Lidfehlstellungen

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Augen · **Erblich:** ja

Bei Lidfehlstellungen liegt der Rand des Augenlids nicht richtig am Auge an:
- **Entropium:** Der Lidrand rollt sich nach innen. Haare und Wimpern reiben auf der Hornhaut. Das ist sehr schmerzhaft und kann zu Hornhautgeschwüren führen.
- **Ektropium:** Der Lidrand, meist am Unterlid, hängt nach außen. Die Bindehaut liegt frei, trocknet aus und entzündet sich leicht.

Beide Formen können auch zusammen vorkommen, z. B. bei Rassen mit sehr großer Lidspalte und schwerer Kopfhaut ("Diamond Eye").

## Ursache
Die Veranlagung ist erblich, der Erbgang ist wahrscheinlich polygen. Entscheidend ist die Kopfform, auf die gezüchtet wird:
- viel lose Haut und tiefe Falten am Kopf, z. B. Shar-Pei, Chow-Chow und Bluthund
- große, schwere Köpfe mit lockeren Lidern, z. B. Neufundländer, Bernhardiner, Mastiff, Cane Corso und Basset Hound
- kurzköpfige Rassen: Beim Mops, Pekinesen und Shih Tzu rollt sich oft das Unterlid im inneren Augenwinkel ein (mediales Entropium). Bei der Englischen Bulldogge kommen Entropium und Ektropium vor.
- Ein Entropium tritt auch bei Rottweiler, Retrievern und Pudeln auf.

Das Qualzucht-Gutachten des Bundesministeriums empfiehlt ein Zuchtverbot für Tiere mit Entropium oder Ektropium, siehe [[Qualzucht]]. Seltener entsteht ein Entropium erst im Lauf des Lebens, z. B. durch Augenschmerzen mit Lidkrampf, Narben oder starken Gewichtsverlust.

## Symptome
**Entropium:** Das Auge tränt stark. Der Hund kneift das Auge zusammen (Lidkrampf) und reibt es. Die Bindehaut ist gerötet, oft mit schleimigem Ausfluss. Später entstehen Trübungen, Blutgefäße und dunkles Pigment auf der Hornhaut sowie Hornhautgeschwüre.

**Ektropium:** Das Unterlid hängt herab, und die rote Bindehaut ist sichtbar. Typisch sind wiederkehrende Bindehautentzündungen, Ausfluss und Tränenspuren im Fell.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt untersucht die Augen und färbt die Hornhaut an, um Verletzungen zu erkennen. Mit betäubenden Augentropfen lässt sich prüfen, ob die Fehlstellung bestehen bleibt oder nur durch den Schmerz entsteht. Ein Entropium wird meist operiert, z. B. indem ein schmaler Hautstreifen unter dem Lidrand entfernt wird (Hotz-Celsus-Methode). Bei Welpen, etwa beim Shar-Pei, werden die Lider oft zunächst nur vorübergehend nach außen geheftet, bis der Kopf ausgewachsen ist. Ein leichtes Ektropium wird mit Augensalben und Tränenersatz behandelt, ein starkes ebenfalls operiert.

## Hinweise für Tierpfleger
- Zusammengekniffene, tränende oder gerötete Augen bald tierärztlich abklären lassen. Hornhautgeschwüre verschlimmern sich schnell.
- Augen und Tränenrinnen täglich mit einem sauberen, feuchten Tuch reinigen. Für jedes Auge ein eigenes Tuch verwenden. Siehe [[Fellpflege]].
- Augentropfen und -salben genau nach Plan geben.
- Nach einer Lidoperation konsequent einen Halskragen tragen lassen, damit sich der Hund nicht kratzt oder reibt.
- Bei Zuchthunden nach Lidoperationen fragen. Operierte Lider sind später oft kaum noch zu erkennen.

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
