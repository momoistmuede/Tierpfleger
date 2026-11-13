---
aliases:
  - The International Cat Association
tierart: "[[Katze]]"
gruendung: 1979
sitz: USA
tags:
  - wissen
  - katze
  - verband
  - verband/tica
---
# TICA – The International Cat Association

Die TICA bezeichnet sich selbst als **größtes genetisches Zuchtbuch** für Rassekatzen und Hauskatzen. Sie ist außerdem einer der größten Ausstellungsverbände der Welt. Anders als die [[FIFe]] ist sie kein Dachverband nationaler Vereine, sondern ein Verband mit **Einzelmitgliedern**, die abstimmen dürfen. Überblick über alle Verbände: [[Katzenzuchtverbände]].

## Steckbrief
- **Gründung:** 1979 in den USA. Laut Wikipedia am 22.06.1979 in Branson, Missouri.
- **Sitz:** USA. Laut Wikipedia liegt das Büro in Harlingen, Texas.
- **Organisation:** Über Rassen entscheidet der **Board of Directors**. Er hört dazu das Genetics Committee und das Rules Committee an. Die Mitglieder können sich in **Breed Sections** für einzelne Rassen engagieren.
- **Regionen:** 15 Regionen weltweit, Deutschland gehört zur Region **Europe North**.
- **In Deutschland:** z. B. TICACats e.V., der TICA-Ausstellungen veranstaltet.
- **Besonderheit:** Bei der TICA können auch kastrierte **Hauskatzen ohne Stammbaum** (Household Pets) ausgestellt werden und eigene Titel erringen.

## Wie die TICA eine Rasse anerkennt
Zuerst wird die Rasse eingeordnet, z. B. als Kreuzung von Hauskatzenrassen, als Hybrid mit einer Wildkatze, als natürliche Rasse oder als Mutationsrasse. Dann durchläuft sie mehrere Stufen:
1. **Experimental New Breed:** Die Katzen werden im Experimentalregister geführt. Dafür ist noch kein Board-Beschluss nötig.
2. **Registration Only (RE):** Die TICA registriert die Rasse, sie kann aber noch keine Titel holen. Voraussetzungen sind mindestens 10 Katzen, 5 Würfe und 3 Mitglieder aus 2 Regionen. Der Board entscheidet.
3. **Preliminary New Breed (PNB):** frühestens 2 Jahre nach RE. Voraussetzungen: mindestens 15 Katzen, 10 Würfe, 5 Züchter in 3 Regionen sowie ein Standardentwurf.
4. **Advanced New Breed (ANB):** frühestens 1 Jahr später. Voraussetzungen: mindestens 100 Katzen, 25 Würfe, 15 Züchter in 5 Regionen und 25 ausgestellte Katzen.
5. **Championship:** frühestens 1 Jahr später. Voraussetzungen u. a.: mindestens 200 registrierte Katzen, 35 Ausstellungen und 15 Züchter in 5 Regionen. Die Championship gilt ab dem 1. Mai des Folgejahres.

Vom Antrag bis zur Championship vergehen also mindestens etwa 4 Jahre. Danach muss die Rasse 3 Jahre lang Mindestzahlen erfüllen, sonst wird sie zurückgestuft. Rassen, die schon bei anderen großen Verbänden anerkannt sind, können verkürzte Fristen bekommen.

Derzeit sind [[Serengeti]] und [[Toybob]] **Advanced New Breed**.

## Codes
Jede Rasse hat eine Abkürzung aus 2–3 Buchstaben, z. B. MC für [[Maine Coon]] oder SB für [[Sibirische Katze]]. Lang- und Kurzhaarformen führt die TICA oft als eigene Rassen mit eigenem Code. Das EMS-System der FIFe nutzt die TICA nicht.

## Haltung zu umstrittenen Rassen
- Die TICA erkennt [[Scottish Fold]], [[Munchkin]], [[Minuet]], haarlose Rassen und Wildkatzenhybriden wie [[Bengal]], [[Savannah]] und [[Chausie]] als Championship-Rassen an.
- Merkmale wie Faltohren, kurze Beine oder fehlender Schwanz gelten als **Strukturmutationen**. Neue Rassen dürfen sie nur mit Zustimmung der Rasse nutzen, die das Merkmal zuerst hatte.
- Katzen mit einem Wildtier unter den Eltern, Großeltern oder Urgroßeltern dürfen nicht in Championship-Klassen ausgestellt werden.

Für die Haltung in Deutschland gilt unabhängig davon § 11b TierSchG, siehe [[Qualzucht]].

## Von der TICA anerkannte Rassen in diesem Vault
```base
filters:
  and:
    - file.hasTag("rasse")
    - 'tica_status != "nicht anerkannt"'
properties:
  file.name:
    displayName: Rasse
  note.tica_status:
    displayName: Status
  note.tica_code:
    displayName: TICA-Code
views:
  - type: table
    name: TICA-Rassen
    order:
      - file.name
      - tica_status
      - tica_code
      - felllaenge
    sort:
      - property: file.name
        direction: ASC
```

> [!note] Quellenlage
> tica.org blockiert automatische Abrufe. Die Angaben stammen aus offiziellen TICA-Seiten und -Regelwerken (Registration Rules 2024, Standing Rules 2025), die im Internet Archive gespeichert sind. Gründungsort und Sitz sind nur über Wikipedia belegt.

Siehe auch [[FIFe]] · [[WCF]]
