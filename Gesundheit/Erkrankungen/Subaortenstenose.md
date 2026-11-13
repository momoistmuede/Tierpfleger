---
aliases:
  - "SAS"
  - "Aortenstenose"
  - "Subvalvuläre Aortenstenose"
tierart:
  - "[[Hund]]"
organsystem: Herz
erblich: true
tags:
  - erkrankung
  - erkrankung/herz
  - hund
  - erbkrankheit
---
# Subaortenstenose

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Herz · **Erblich:** ja

Bei der Subaortenstenose ist der Ausflusstrakt der linken Herzkammer direkt unterhalb der Aortenklappe verengt. Meist ist das ein Ring oder Wulst aus Bindegewebe. Das Herz muss gegen einen erhöhten Widerstand pumpen. Dadurch verdickt sich die Wand der linken Kammer, und es können gefährliche Herzrhythmusstörungen entstehen. Die SAS ist einer der häufigsten angeborenen Herzfehler großer Hunderassen.

## Ursache
Die Erkrankung ist erblich. Der genaue Erbgang ist nicht vollständig geklärt, vermutlich sind mehrere Gene beteiligt. Häufig betroffen sind Neufundländer, Boxer, Golden Retriever, Rottweiler und Deutscher Schäferhund. Die Verengung ist bei der Geburt oft noch nicht vorhanden. Sie entsteht in den ersten Lebenswochen und kann bis zum Ende des Wachstums zunehmen. Ein verlässlicher Gentest existiert nicht.

## Symptome
Leicht betroffene Hunde zeigen oft keine Symptome, auffällig ist nur ein Herzgeräusch. Bei schwerer SAS kommen dazu:
- schnelle Ermüdung und Leistungsschwäche
- Ohnmachtsanfälle (Synkopen), besonders bei Belastung
- Atemnot und Husten bei Herzinsuffizienz
- plötzlicher Herztod, oft schon im jungen oder mittleren Alter

Die veränderte Klappe kann sich außerdem leichter mit Bakterien infizieren (Endokarditis).

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt hört das Herz ab. Die Diagnose stellt ein Herzultraschall mit Doppler. Dabei wird die Strömungsgeschwindigkeit in der Aorta gemessen und daraus der Druckunterschied berechnet:
- leicht: unter 50 mmHg
- mittelgradig: 50–80 mmHg
- schwer: über 80 mmHg

Welpen ohne Herzgeräusch gelten erst mit etwa einem Jahr als sicher frei. Zuchttiere werden deshalb frühestens in diesem Alter untersucht. Leichte und mittelgradige Formen werden meist nicht behandelt, solange keine Symptome auftreten. Bei schwerer SAS werden oft Betablocker gegeben. Sie entlasten das Herz, verhindern einen plötzlichen Herztod aber nicht sicher. Eine Ballonaufdehnung ist nur in ausgewählten Fällen sinnvoll. Heilbar ist die Erkrankung nicht.

## Hinweise für Tierpfleger
- Bei mittelgradiger oder schwerer SAS starke Belastung vermeiden: kein Ballspiel bis zur Erschöpfung, kein Laufen am Fahrrad, keine Hitze. Siehe [[Bewegung und Beschäftigung Hund]].
- Ohnmachtsanfälle, Atemnot und Leistungsschwäche sofort melden.
- Die **Ruheatemfrequenz** im Schlaf zählen. Mehr als 30–35 Atemzüge pro Minute oder ein deutlicher Anstieg gegenüber dem eigenen Normalwert ist ein Warnsignal.
- Zähne pflegen und Entzündungen früh behandeln lassen, um einer Endokarditis vorzubeugen. Siehe [[Zahnpflege]].
- Medikamente pünktlich geben und nicht eigenmächtig absetzen.
- Bei Welpen gefährdeter Rassen nach dem Herzbefund der Elterntiere fragen.

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
[[Dilatative Kardiomyopathie]], [[Mitralklappenendokardiose]] · [[Erkrankungen.base|Alle Erkrankungen]]
