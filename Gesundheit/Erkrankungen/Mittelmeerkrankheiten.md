---
aliases:
  - "Reisekrankheiten"
  - "Vektorübertragene Krankheiten"
  - "Leishmaniose"
  - "Ehrlichiose"
  - "Babesiose"
  - "Hundemalaria"
  - "Anaplasmose"
  - "Dirofilariose"
  - "Herzwurm"
tierart:
  - "[[Hund]]"
organsystem: Infektion
erblich: false
tags:
  - erkrankung
  - erkrankung/infektion
  - hund
  - zoonose
---
# Mittelmeerkrankheiten

> [!info] Steckbrief
> **Tierart:** [[Hund]] · **Organsystem:** Infektion · **Erblich:** nein (Veranlagung möglich)

Als Mittelmeerkrankheiten bezeichnet man Infektionen, die von Sandmücken, Stechmücken oder Zecken übertragen werden. Sie sind in Süd- und Südosteuropa weit verbreitet. Betroffen sind vor allem Hunde aus dem Auslandstierschutz und Hunde, die mit auf Reisen waren. Die Krankheiten bleiben oft monatelang unbemerkt und brechen manchmal erst Jahre später aus. Häufig ist ein Hund mit mehreren Erregern gleichzeitig infiziert.

| Krankheit | Erreger | Überträger |
|---|---|---|
| **Leishmaniose** | *Leishmania infantum* (Einzeller) | Sandmücken |
| **Ehrlichiose** | *Ehrlichia canis* (Bakterium) | Braune Hundezecke |
| **Babesiose** ("Hundemalaria") | *Babesia* (Einzeller) | Auwaldzecke, Braune Hundezecke |
| **Anaplasmose** | *Anaplasma* (Bakterium) | Holzbock, Braune Hundezecke |
| **Dirofilariose** | Herzwurm *Dirofilaria immitis*, Hautwurm *Dirofilaria repens* | Stechmücken |

## Ursache
Die Erreger werden beim Stich infizierter Mücken oder beim Saugen infizierter Zecken übertragen. Leishmanien können außerdem über Bluttransfusionen, beim Deckakt und von der Mutter auf die Welpen übergehen. Einige Krankheiten breiten sich auch in Deutschland aus: Babesiose und Anaplasmose kommen hier bereits vor, und vereinzelt wurden Sandmücken nachgewiesen. Die Braune Hundezecke überlebt draußen den deutschen Winter nicht. In beheizten Räumen wie Wohnungen, Zwingern und Tierheimen kann sie sich aber vermehren.

**Zoonose:** Leishmaniose, Anaplasmose und der Hautwurm *D. repens* können auch Menschen infizieren. Die Übertragung erfolgt über Sandmücken, Zecken oder Stechmücken, nicht über den normalen Umgang mit dem Hund.

## Symptome
Die Symptome sind oft unspezifisch: Fieber, Mattigkeit, Gewichtsverlust, blasse Schleimhäute und vergrößerte Lymphknoten. Typische Zeichen der einzelnen Krankheiten:
- **Leishmaniose:** schuppige, haarlose Stellen um die Augen ("Brille"), an Ohrrändern und Nase, Hautgeschwüre, zu lange Krallen, Nasenbluten, Augen- und Gelenkentzündungen. Die häufigste Todesursache ist ein Nierenversagen.
- **Ehrlichiose:** Fieber und Blutungsneigung (Nasenbluten, punktförmige Blutungen), im chronischen Stadium eine schwere Blutarmut.
- **Babesiose:** hohes Fieber, Blutarmut, Gelbsucht und rot- bis kaffeebrauner Urin. Sie verläuft oft akut und ist ein **Notfall**.
- **Anaplasmose:** Fieber, Mattigkeit, Lahmheit, Gelenkschmerzen und Blutungsneigung.
- **Dirofilariose:** Herzwürmer verursachen Husten, Leistungsschwäche, Atemnot und später Herzversagen. Hautwürmer bilden Knoten unter der Haut.

## Diagnose & Behandlung
Die Tierärztin bzw. der Tierarzt untersucht Blut und, je nach Verdacht, Urin, Lymphknoten oder Knochenmark. Eingesetzt werden Antikörpertests, PCR, Blutausstriche und Antigentests. Viele Tests werden erst Wochen bis Monate nach der Ansteckung positiv:
- Leishmanien-Antikörper frühestens 6–8 Wochen nach der Infektion, oft erst viel später
- Herzwurm-Antigen erst 6–8 Monate nach der Infektion

Die ESCCAP empfiehlt deshalb, Importhunde bald nach der Ankunft zu untersuchen und die Tests nach einigen Monaten zu wiederholen, bei Leishmaniose z. B. im Abstand von 6 Monaten. Ein negativer Test schließt eine Infektion nicht aus.

**Behandlung:** Ehrlichiose und Anaplasmose werden mit dem Antibiotikum Doxycyclin behandelt, Babesiose z. B. mit Imidocarb. Leishmaniose ist nicht heilbar. Mit Medikamenten wie Allopurinol lässt sie sich aber oft lange kontrollieren, häufig lebenslang. Herzwürmer werden in mehreren Schritten über Monate behandelt.

## Hinweise für Tierpfleger
- Neuzugänge aus dem Ausland bei der Aufnahme gründlich auf Zecken absuchen und Zecken sofort entfernen. Zeckenschutz konsequent einsetzen, damit sich die Braune Hundezecke nicht im Tierheim festsetzt. Siehe [[Parasitenprophylaxe]].
- Herkunftsland, Einreisedatum und Testergebnisse in der Tierakte vermerken und Nachtests einplanen.
- Fieber, Mattigkeit, Nasenbluten, blasse Schleimhäute, dunklen Urin und Hautveränderungen sofort melden.
- Bei offenen Hautstellen, Blut und Ausfluss Handschuhe tragen und die Hygieneregeln einhalten.
- Hunde mit Leishmaniose mit einem Mittel gegen Sandmücken schützen, damit der Erreger nicht weiterverbreitet wird. **Mittel mit Permethrin oder Deltamethrin sind für Katzen giftig.** Behandelte Hunde nicht mit Katzen zusammen halten.
- Bei Hunden mit [[MDR1-Defekt]] auf die Medikamente gegen Herzwürmer achten, siehe dort.
- Bei Reisen in den Süden: Mückenschutz verwenden und den Hund in der Dämmerung und nachts drinnen lassen. Die Impfung gegen Leishmaniose senkt das Risiko, schützt aber nicht sicher. Siehe [[Impfungen Hund]].

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
[[MDR1-Defekt]] · [[Erkrankungen.base|Alle Erkrankungen]]
