---
aliases:
  - "MDR1"
  - "Ivermectin-Empfindlichkeit"
  - "ABCB1-Defekt"
tierart:
  - "[[Hund]]"
organsystem: Nervensystem
erblich: true
tags:
  - erkrankung
  - erkrankung/nervensystem
  - hund
  - erbkrankheit
---
# MDR1-Defekt

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Nervensystem · **Erblich:** ja

Beim MDR1-Defekt ist das Gen *ABCB1* (MDR1) verändert. Dadurch fehlt ein funktionierendes P-Glykoprotein. Dieses Transportprotein sitzt in der Blut-Hirn-Schranke und pumpt bestimmte Arzneistoffe zurück ins Blut. So hält es sie vom Gehirn fern. Fehlt es, reichern sich die Wirkstoffe im Gehirn an und verursachen neurologische Vergiftungserscheinungen.

## Ursache
Der Defekt wird erblich weitergegeben:
- Hunde mit zwei defekten Genkopien (-/-) sind stark empfindlich.
- Mischerbige Hunde (+/-) sind teilweise empfindlich.

Der Defekt ist häufig bei Collie-artigen Hütehunden und ihren Mischlingen, er kommt aber auch bei manchen Windhunden vor.

## Symptome
Nach Gabe kritischer Wirkstoffe zeigt der Hund Speicheln, Zittern, Taumeln, erweiterte Pupillen, Blindheit und kann ins Koma fallen.

**Kritische Wirkstoffe (Auswahl):**
- makrozyklische Laktone wie Ivermectin, Doramectin, Moxidectin oder Milbemycinoxim in hoher Dosis, z. B. zur Räudebehandlung
- Emodepsid (Wurmmittel)
- Loperamid (Durchfallmittel)
- Acepromazin (Beruhigungsmittel) und Butorphanol (Schmerz- und Hustenmittel): nur in verringerter Dosis, auch bei mischerbigen Hunden
- einige Zytostatika, z. B. Vincristin, Vinblastin und Doxorubicin

Die Liste ist nicht vollständig. Vor jeder Behandlung die Tierärztin bzw. den Tierarzt auf den MDR1-Status hinweisen.

## Diagnose & Behandlung
Die Diagnose stellt ein **Gentest** aus Blut oder Backenabstrich. Heilbar ist der Defekt nicht. Die Medikation wird stattdessen angepasst.

## Hinweise für Tierpfleger
- Hunde betroffener Rassen und Mischlinge mit unbekanntem Status vorsorglich als empfindlich behandeln.
- Den MDR1-Status in der Tierakte vermerken.
- Pferdemist nach einer Pferdeentwurmung (z. B. Ivermectin- oder Moxidectin-Paste) kann für MDR1-Hunde gefährlich sein. Siehe [[Parasitenprophylaxe]].

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
