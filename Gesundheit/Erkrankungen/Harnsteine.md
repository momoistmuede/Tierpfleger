---
aliases:
  - "Urolithiasis"
  - "Blasensteine"
  - "Urolithen"
tierart:
  - "[[Hund]]"
  - "[[Katze]]"
organsystem: Harnwege
erblich: true
tags:
  - erkrankung
  - erkrankung/harnwege
  - hund
  - katze
  - erbkrankheit
  - notfall
---
# Harnsteine

> [!info] Steckbrief
> **Tierart:** [[Hund]] · [[Katze]] · **Organsystem:** Harnwege · **Erblich:** ja

Harnsteine entstehen, wenn sich Mineralien aus dem Urin als Kristalle absetzen und zu Steinen zusammenwachsen. Meist liegen sie in der Harnblase, seltener in Niere, Harnleiter oder Harnröhre. Man unterscheidet verschiedene Steinarten. Das ist wichtig, weil sich die Behandlung danach richtet:
- **Struvit** (Magnesium-Ammonium-Phosphat)
- **Calciumoxalat**
- **Urat** (Salz der Harnsäure)
- **Cystin**

Bei Katern kann ein Stein oder ein Harnröhrenpfropf die Harnröhre verschließen. Das ist ein **lebensbedrohlicher Notfall**.

## Ursache
Harnsteine haben mehrere Ursachen: Veranlagung, Fütterung, wenig Wasseraufnahme, Übergewicht, Harnwegsinfekte und Stoffwechselstörungen. Einige Formen sind eindeutig erblich.

**Hund:**
- **Struvit** entsteht meist durch eine Blasenentzündung mit Bakterien, die Harnstoff spalten. Hündinnen sind häufiger betroffen.
- **Calciumoxalat** betrifft vor allem ältere Rüden kleiner Rassen, z. B. Zwergschnauzer, Yorkshire Terrier, Shih Tzu, Bichon Frisé und Zwergpudel.
- **Urat:** Fast alle Dalmatiner scheiden wegen einer erblichen Variante im Gen *SLC2A9* sehr viel Harnsäure aus (Hyperurikosurie). Dieselbe Variante kommt u. a. bei der Englischen Bulldogge und beim Schwarzen Russischen Terrier vor. Uratsteine entstehen außerdem bei Hunden mit Lebershunt.
- **Cystin** entsteht bei der erblichen Cystinurie. Eine Form wird autosomal-rezessiv vererbt (*SLC3A1*-Gen), z. B. beim Neufundländer und beim Labrador Retriever. Bei einer anderen Form erkranken nur unkastrierte Rüden, z. B. bei Englischer und Französischer Bulldogge und beim Mastiff.

**Katze:**
- **Struvit** und **Calciumoxalat** sind etwa gleich häufig. Struvitsteine entstehen bei Katzen meist ohne Infektion. Jüngere Katzen haben eher Struvit, ältere eher Calciumoxalat.
- Burma, Perser und Himalaya-Katzen haben ein erhöhtes Risiko für Calciumoxalatsteine.
- Weitere Risikofaktoren sind Übergewicht, Bewegungsmangel, geringe Wasseraufnahme und Stress.

## Symptome
Viele Steine bleiben lange unbemerkt. Typische Zeichen sind:
- häufiger Harnabsatz in kleinen Mengen
- Pressen beim Urinieren
- Blut im Urin
- Urinieren an ungewohnten Stellen, bei Katzen z. B. neben dem Katzenklo
- häufiges Lecken im Genitalbereich

**Harnröhrenverschluss (Notfall):** Das Tier presst, aber es kommt kein oder kaum Urin. Kater gehen immer wieder zum Katzenklo, schreien dabei oder lecken am Penis. Dazu kommen Unruhe, Bauchschmerzen und Erbrechen. Später werden die Tiere matt und brechen zusammen. Kalium und Harnstoff reichern sich im Blut an, und das Herz kann versagen. Ohne Behandlung stirbt das Tier oft innerhalb weniger Tage.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt untersucht den Urin (Kristalle, pH-Wert, Bakterienkultur) und macht Röntgen- und Ultraschallaufnahmen. Struvit- und Calciumoxalatsteine sind im Röntgen gut sichtbar, Urat- und Cystinsteine oft nur im Ultraschall. Sicher bestimmt wird die Steinart erst durch eine Steinanalyse im Labor.

Die Behandlung richtet sich nach der Steinart:
- Struvit-, Urat- und Cystinsteine lassen sich oft mit Spezialfutter und Medikamenten auflösen. Bei einer Infektion kommen Antibiotika dazu.
- Calciumoxalatsteine lösen sich nicht auf. Sie werden operativ oder mit einer Blasenspiegelung entfernt.
- Bei der Cystinurie unkastrierter Rüden hilft oft eine Kastration.
- Für die Hyperurikosurie (*SLC2A9*) und einige Formen der Cystinurie gibt es Gentests.

Ein **Harnröhrenverschluss** wird sofort behandelt: Der Kreislauf wird stabilisiert, die Harnröhre unter Narkose freigespült und ein Blasenkatheter gelegt. Harnsteine kommen oft wieder. Deshalb sind Nachkontrollen wichtig.

## Hinweise für Tierpfleger
- **Ein Kater, der presst und keinen Urin absetzt, ist ein Notfall.** Sofort zur Tierärztin bzw. zum Tierarzt, nicht bis zum nächsten Tag warten.
- Den Harnabsatz beobachten: Bei Katzen das Katzenklo täglich kontrollieren (Anzahl und Größe der Urinklumpen, Blut). Bei Hunden auf häufiges Absetzen kleiner Mengen achten.
- Die Wasseraufnahme fördern: Nassfutter, mehrere Wassernäpfe, Trinkbrunnen. Siehe [[Ernährung Katze]] und [[Ernährung Hund]].
- Ein verordnetes Spezialfutter **strikt** füttern und nicht mit anderem Futter oder Leckerlis mischen, sonst wirkt es nicht.
- Bei Katzen Stress vermeiden und genug Katzenklos anbieten (Faustregel: Anzahl der Katzen plus eins).
- Hunden oft Gelegenheit zum Lösen geben. Langes Einhalten fördert Steine und Infekte.

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
[[Polyzystische Nierenerkrankung]] · [[Erkrankungen.base|Alle Erkrankungen]]
