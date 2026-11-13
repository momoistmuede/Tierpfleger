---
aliases:
  - "Sakrokaudale Dysgenesie"
  - "Manx Syndrome"
tierart:
  - "[[Katze]]"
organsystem: Nervensystem
erblich: true
tags:
  - erkrankung
  - erkrankung/nervensystem
  - katze
  - erbkrankheit
  - qualzucht
---
# Manx-Syndrom

> [!info] Steckbrief
> **Tierart:** [[Katze]] · **Organsystem:** Nervensystem · **Erblich:** ja

Das Manx-Syndrom ist eine angeborene Fehlbildung von Wirbelsäule und Rückenmark bei schwanzlosen Katzen. Es kommt vor allem bei der Manx und ihrer Langhaarform, der Cymric, vor. Die Schwanzwirbel fehlen oder sind verkürzt. Oft sind auch Kreuzbein, Becken und das hintere Ende des Rückenmarks fehlgebildet. Typisch ist eine **Spina bifida**: Die Wirbelbögen sind nicht geschlossen, und Rückenmark oder Rückenmarkshäute können sich vorwölben.

Nach der Schwanzlänge unterscheidet man:
- **Rumpy:** völlig schwanzlos
- **Rumpy-Riser:** wenige, verwachsene Schwanzwirbel
- **Stumpy:** kurzer, oft geknickter Stummelschwanz
- **Longy:** fast normal langer Schwanz

Je kürzer der Schwanz, desto häufiger und schwerer sind die Fehlbildungen. Am häufigsten betroffen sind Rumpy-Katzen.

## Ursache
Ursache ist eine dominant vererbte Veränderung im Gen *TBXT* (T-Box-Gen, auch Brachyury genannt). Schon eine Genkopie verkürzt den Schwanz. Alle Manx-Katzen sind deshalb mischerbig. Embryonen mit zwei Kopien sterben früh im Mutterleib ab. Bei der Japanese Bobtail beruht der Kurzschwanz auf einem anderen Gen.

Die Zucht auf Schwanzlosigkeit gilt als [[Qualzucht]]. Das Qualzucht-Gutachten des Bundesministeriums empfiehlt für Manx und Cymric ein Zuchtverbot. Der Grund: Auch bei der Verpaarung mit geschwänzten Katzen kommen fehlgebildete Kitten zur Welt.

## Symptome
Die Zeichen sind oft schon bei der Geburt sichtbar oder zeigen sich in den ersten Lebenswochen bis -monaten:
- hoppelnder Gang, beide Hinterbeine springen gleichzeitig ab ("Hasenhoppeln")
- Schwäche oder Lähmung der Hinterbeine, Auftreten mit der ganzen Sohle
- Harn- und Kotinkontinenz, verschmutztes Fell und wunde Haut am Hinterteil
- Verstopfung bis zum Megakolon (stark erweiterter Dickdarm), Enddarmvorfall
- wiederkehrende Harnwegsinfekte
- fehlendes Gefühl am After und an den Hinterbeinen

Stumpy-Katzen können zusätzlich eine schmerzhafte Arthrose an den Gelenken des Stummelschwanzes entwickeln. Leicht betroffene Tiere leben oft ohne Einschränkungen.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt untersucht das Tier neurologisch und macht Röntgenaufnahmen. Die genaue Fehlbildung zeigt ein MRT. Heilbar ist das Manx-Syndrom nicht. Behandelt werden die Folgen: Diät und Abführmittel gegen Verstopfung, Entleeren der Blase von Hand, Behandlung von Harnwegsinfekten. Manchmal hilft eine Operation. Schwer betroffene Kitten werden oft eingeschläfert, weil ihre Lebensqualität sehr gering ist.

## Hinweise für Tierpfleger
- Manx-Kitten vor der Vermittlung tierärztlich untersuchen lassen. Manche Probleme zeigen sich erst nach einigen Wochen.
- Gang, Kot- und Harnabsatz beobachten und dokumentieren. Eine Verstopfung früh melden.
- Bei Inkontinenz das Hinterteil sauber und trocken halten und die Haut auf wunde Stellen kontrollieren, siehe [[Fellpflege]].
- Ein Katzenklo mit niedrigem Einstieg und weiche, gut waschbare Liegeplätze anbieten.
- Schwanzlose Katzen nur kastriert vermitteln und über die Qualzucht-Problematik aufklären.

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
[[Dermoid Sinus]], [[Osteochondrodysplasie]] · [[Erkrankungen.base|Alle Erkrankungen]]
