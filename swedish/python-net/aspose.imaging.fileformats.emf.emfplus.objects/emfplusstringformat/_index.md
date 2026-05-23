---
title: "EmfPlusStringFormat klass"
type: docs
weight: 650
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | Initierar en ny instans av EmfPlusStringFormat‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt som specificerar<br/>            språket som ska användas för numeriska siffror i strängen.<br/>            Till exempel, om denna sträng innehåller arabiska siffror,<br/>            måste detta fält innehålla en språkidentifierare som<br/>            specificerar ett arabiskt språk |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur numeriska siffror i strängen ska ersättas<br/>            enligt en lokal eller ett språk.<br/>            Detta värde MÅSTE definieras i StringDigitSubstitution‑enumerationen<br/>            (avsnitt 2.1.1.30). |
| first_tab_offset | float | r/w | Hämtar eller anger ett 32‑bit flyttal som specificerar antalet<br/>            mellanslag mellan början av en textrad och<br/>            den första tabbstoppet |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | Hämtar eller anger ett 32‑bit signerat heltal som specificerar typen av<br/>            bearbetning som utförs på en sträng när ett tangentbords‑snabbtangent‑prefix (det vill säga ett &‑tecken) påträffas.<br/>            I grund och botten anger detta fält huruvida tangentbords‑snabbtangent‑prefix som relaterar till text ska visas.<br/>            Värdet MÅSTE definieras i HotkeyPrefix‑enumerationen<br/>            (avsnitt 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt (avsnitt 2.2.2.23)<br/>            som specificerar språket som ska användas för strängen. |
| leading_margin | float | r/w | Hämtar eller anger ett 32‑bit flyttal som specificerar längden<br/>            på utrymmet som ska läggas till startpositionen för en sträng.<br/>            Standardvärdet är 1/6 tum; för typografiska typsnitt är<br/>            standardvärdet 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar hur strängen ska justeras vertikalt i layout‑rektangeln.<br/>            Detta värde MÅSTE definieras i StringAlignment‑enumerationen. |
| range_count | int | r/w | Hämtar eller anger ett 32‑bit signerat heltal som specificerar antalet EmfPlusCharacterRange‑objekt (avsnitt 2.2.2.8) som definieras i fältet StringFormatData. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar hur strängen ska justeras horisontellt i layout‑rektangeln.<br/>            Detta värde MÅSTE definieras i StringAlignment‑enumerationen<br/>            (avsnitt 2.1.1.29). |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Hämtar eller anger ett EmfPlusStringFormatData‑objekt (avsnitt 2.2.2.44)<br/>            som specificerar valfri textlayout‑data. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar textlayout‑alternativ<br/>            för formatering, beskärning och teckensnittshantering.<br/>            Detta värde MÅSTE bestå av StringFormat‑flaggor<br/>            (avsnitt 2.1.2.8). |
| tabstop_count | int | r/w | Hämtar eller anger ett 32‑bit signerat heltal som specificerar antalet tabbstopp<br/>            som definieras i fältet StringFormatData. |
| tracking | float | r/w | Hämtar eller anger ett 32‑bit flyttal som specificerar förhållandet<br/>            mellan det horisontella utrymmet som tilldelas varje tecken i<br/>            en angiven sträng och teckensnittets definierade bredd för<br/>            tecknet. Stora värden för denna egenskap anger gott om<br/>            utrymme mellan tecken; värden mindre än 1 kan leda till<br/>            teckenöverlappning. Standardvärdet är 1,03; för typografiska<br/>            teckensnitt är standardvärdet 1,00. |
| trailing_margin | float | r/w | Hämtar eller anger ett 32‑bit flyttal som specificerar längden<br/>            på utrymmet som ska lämnas efter en sträng. Standardvärdet<br/>            är 1/6 tum; för typografiska teckensnitt är standardvärdet 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Hämtar eller anger hur tecken ska trunkeras från en sträng som är<br/>            för stor för att få plats i en layout‑rektangel. Detta värde<br/>            MÅSTE definieras i StringTrimming‑enumerationen (avsnitt 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Hämtar eller anger versionen. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

Initierar en ny instans av EmfPlusStringFormat‑klassen

