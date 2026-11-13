---
aliases:
  - World Cat Federation
tierart: "[[Katze]]"
gruendung: 1988
sitz: Essen
tags:
  - wissen
  - katze
  - verband
  - verband/wcf
---
# WCF – World Cat Federation

Die WCF ist ein **internationaler Dachverband von Katzenvereinen** mit Sitz in **Essen**. Sie ist als eingetragener Verein organisiert und hat besonders viele Mitglieder in Mittel- und Osteuropa. Überblick über alle Verbände: [[Katzenzuchtverbände]].

## Steckbrief
- **Gründung:** am 20.08.1988 in Petrópolis bei Rio de Janeiro (Brasilien).
- **Sitz:** Essen, eingetragen im Vereinsregister beim Amtsgericht Essen.
- **Mitglieder:** Nur Vereine und Verbände können Mitglied werden, keine Einzelpersonen. Weltweit sind rund 280 Vereinigungen angeschlossen:
  - 106 Vollmitglieder in 40 Ländern, die meisten in Russland, Italien, der Ukraine und Deutschland
  - 74 Patronatsvereine
  - 109 Vertragspartner
- **In Deutschland:** 5 Vollmitglieder, z. B. Deutsche Edelkatze e.V., und 3 Patronatsvereine.
- **Organisation:** Oberstes Organ ist die Generalversammlung, jedes Vollmitglied hat eine Stimme. Dazu kommen ein Vorstand und Kommissionen, u. a. die Richter- und Stammbuchkommission und eine Tierschutzkommission.
- **Aufgaben:** internationaler Zwingerschutz (Schutz der Zuchtstättennamen), Ausbildung der Richter, Rassestandards und Ausstellungsregeln.

## Wie die WCF eine Rasse anerkennt
1. **Voranerkennungsausstellung:** Die Züchter reichen einen Bericht über Ursprung, Geschichte und Genetik ein. Dazu kommen ein Standardentwurf, Stammbäume und Fotos. Auf einer Ausstellung werden 6–10 Katzen vorgestellt. Danach erhält die Rasse einen eigenen EMS-Code.
2. **Anerkennungsausstellung:** Zwei Richter bewerten **mindestens 15 Katzen** mit vollständigem 4-Generationen-Stammbaum. Mindestens 7 davon müssen 3 Generationen reiner Rasse haben.
3. **Entscheidung:** Die Richterkommission bestätigt den Standard, danach stimmt die **Generalversammlung** ab.

Eine Mindestdauer ist nicht festgelegt.

**Sonderfall:** Rassen, die nicht die WCF, aber ein anderer großer Verband anerkennt (z. B. FIFe, TICA, CFA oder LOOF), dürfen auf WCF-Ausstellungen starten. Sie erhalten aber nur Stammbäume aus dem Experimentalregister („RIEX“). Im Vault gelten sie bei der WCF als „nicht anerkannt“, ein Beispiel ist [[Sokoke]].

## Codes und Kategorien
Die WCF nutzt einen **eigenen EMS-Code**. Er ähnelt dem der FIFe, weicht aber teilweise ab: Britisch Kurzhaar heißt bei der WCF **BRI**, und **BSH** steht für [[Brasilianisch Kurzhaar]]. Die Rassen sind in 5 Kategorien eingeteilt:
1. Langhaar
2. Halblanghaar
3. Kurzhaar
4. Siam und Orientalen
5. Haarlos

## Haltung zu umstrittenen Rassen
- Laut den allgemeinen Zuchtregeln dürfen Katzen mit angeborenen Anomalien nicht gezüchtet werden. Außerdem dürfen nicht mehrere Mutationen in einer Katze kombiniert werden.
- Trotzdem erkennt die WCF [[Scottish Fold]], [[Munchkin]], [[Minuet]], [[Savannah]], [[Chausie]], [[Lykoi]] und haarlose Rassen an. Die Standards haben aber Auflagen:
  - Scottish Folds dürfen nur mit geradohrigen Katzen verpaart werden.
  - Katzen mit eingeschränkter Beweglichkeit erhalten keine Zertifikate.
  - Savannahs der Generationen F1–F3 sind nicht ausstellbar.
- Laut Ethikkodex sind höchstens 2 Würfe pro Jahr erlaubt, und Kitten werden nicht vor der 12. Woche abgegeben.

Für die Haltung in Deutschland gilt unabhängig davon § 11b TierSchG, siehe [[Qualzucht]].

## Von der WCF anerkannte Rassen in diesem Vault
```base
filters:
  and:
    - file.hasTag("rasse")
    - 'wcf_status != "nicht anerkannt"'
properties:
  file.name:
    displayName: Rasse
  note.wcf_status:
    displayName: Status
  note.wcf_code:
    displayName: WCF-Code
views:
  - type: table
    name: WCF-Rassen
    order:
      - file.name
      - wcf_status
      - wcf_code
      - felllaenge
    sort:
      - property: file.name
        direction: ASC
```

Quellen: [wcf.de](https://wcf.de/de/) · [WCF-EMS-Code](https://wcf.de/pdf-de/WCF-EMS_DE.pdf) · [Anerkennung neuer Rassen](https://wcf.de/de/anerkennung-neuer-rassen/) · Siehe auch [[FIFe]] · [[TICA]]
