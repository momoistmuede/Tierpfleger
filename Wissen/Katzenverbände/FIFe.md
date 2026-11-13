---
aliases:
  - Fédération Internationale Féline
  - FIFE
tierart: "[[Katze]]"
gruendung: 1950
sitz: Schweiz
tags:
  - wissen
  - katze
  - verband
  - verband/fife
---
# FIFe – Fédération Internationale Féline

Die FIFe ist der **Dachverband nationaler Katzenzuchtverbände**, vor allem in Europa. Jedes Mitgliedsland hat in der Regel genau einen Mitgliedsverband. Sie ist einer der drei großen Verbände in Europa, siehe [[Katzenzuchtverbände]].

## Steckbrief
- **Gründung:** Inoffiziell 1949 in Paris, offiziell am 10.12.1950 mit der ersten Generalversammlung in Gent (Belgien). Bis 1973 hieß sie „Fédération Internationale Féline d'Europe“.
- **Sitz:** Schweiz. Amtssprachen sind Französisch, Deutsch und Englisch.
- **Mitglieder:** 42 Mitgliedsverbände in 41 Ländern.
- **Größe:** über 540 Ausstellungen pro Jahr mit mehr als 114.000 Katzen. 2025 wurden rund 97.000 Katzen registriert, am häufigsten [[Maine Coon]], [[Britisch Kurzhaar]] und [[Ragdoll]].
- **In Deutschland:** Mitglied ist der 1. Deutsche Edelkatzenzüchter-Verband e.V. (1. DEKZV).
- **Organisation:** ein Vorstand mit 6 Personen und 6 Kommissionen, u. a. für Zucht und Registrierung, Richter und Standards sowie Gesundheit und Tierschutz. Die Generalversammlung tagt jährlich, jedes Mitglied hat eine Stimme.

## Wie die FIFe eine Rasse anerkennt
1. **Breed Council gründen:** mindestens 3 Personen aus 3 Ländern. Er arbeitet mit drei Kommissionen zusammen: Zucht und Registrierung, Richter und Standards sowie Gesundheit und Tierschutz.
2. **Vorläufige Anerkennung beantragen.** Voraussetzungen:
   - mindestens 3 Züchter aus 3 Ländern mit je einem Wurf in den letzten 2 Jahren
   - Stammbäume über 5 Generationen bei 3 Katzen bzw. über 3 Generationen bei 15 Katzen
   - ein vorläufiger Standard, Zuchtregeln und Gesundheitsdaten
3. **Die Generalversammlung entscheidet.** Die vorläufige Phase beginnt am 1. Januar danach. Die Katzen werden ausgestellt und tragen Titel mit einem vorangestellten „P“.
4. **Volle Anerkennung** frühestens nach einem Jahr. Voraussetzungen:
   - mindestens 5 Züchter aus 3 Ländern mit zusammen mindestens 15 Würfen
   - mindestens 40 ausgestellte Katzen auf mindestens 3 Ausstellungen in 3 Ländern
   - jede Katze von 3 Richtern mit „Excellent“ bewertet
   - Danach stimmt die Generalversammlung erneut ab.
5. Ist eine Rasse nach **5 Jahren** noch nicht voll anerkannt, fällt sie automatisch zurück auf „nicht anerkannt“.

Derzeit vorläufig anerkannt sind [[Bombay]] und [[Lykoi]] (2023–2027).

## Codes und Kategorien
Die FIFe hat das **EMS-System** eingeführt (Easy Mind System, 1990). Ein Code beschreibt Rasse, Farbe und Muster. Ein Beispiel ist „BSH a“ für Britisch Kurzhaar in Blau. Die Rassen sind in 4 Kategorien eingeteilt:
1. Perser, Exotic und Verwandte
2. Halblanghaar
3. Kurzhaar und Somali
4. Siam, Orientalen und Verwandte

**Schwesterrassen** teilen einen Standard und unterscheiden sich nur in Felllänge oder Muster, z. B. [[Abessinier]] und [[Somali]] oder [[Sibirische Katze]] und [[Neva Masquerade]].

## Haltung zu umstrittenen Rassen
- **Keine Anerkennung** für Rassen, deren Merkmal Kurzbeinigkeit (Achondroplasie, z. B. [[Munchkin]]) oder Osteochondrodysplasie ist (z. B. [[Scottish Fold]]). Solche Katzen dürfen bei der FIFe weder gezüchtet noch registriert oder ausgestellt werden.
- **Haarlose Rassen:** keine neuen Anträge mehr. Anerkannt bleiben nur [[Sphynx]], [[Don Sphynx]] und [[Peterbald]].
- **Wildkatzenhybriden** der Generationen F1–F4 werden nicht anerkannt und nicht ausgestellt, z. B. [[Savannah]] und [[Chausie]].
- Von der Zucht ausgeschlossen sind u. a. taube Katzen, Katzen ohne Tasthaare und Verpaarungen weiß × weiß.

## Von der FIFe anerkannte Rassen in diesem Vault
```base
filters:
  and:
    - file.hasTag("rasse")
    - 'fife_status != "nicht anerkannt"'
properties:
  file.name:
    displayName: Rasse
  note.fife_status:
    displayName: Status
  note.fife_code:
    displayName: EMS-Code
views:
  - type: table
    name: FIFe-Rassen
    order:
      - file.name
      - fife_status
      - fife_code
      - felllaenge
    sort:
      - property: file.name
        direction: ASC
```

Quellen: [fifeweb.org](https://fifeweb.org/organisation/presentation/) · [Breeding & Registration Rules](https://fifeweb.org/wp-content/uploads/2023/11/br_reg_en.pdf) · Siehe auch [[TICA]] · [[WCF]]
