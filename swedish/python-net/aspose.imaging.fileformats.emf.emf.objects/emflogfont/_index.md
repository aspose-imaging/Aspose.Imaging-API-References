---
title: "EmfLogFont klass"
type: docs
weight: 130
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---

**Summary:** The LogFont object specifies the basic attributes of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFont

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogFont()](#EmfLogFont__1) | Initierar en ny instans av EmfLogFont‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar uppsättningen av teckenglyfer. Det MÅSTE <br/>            vara ett värde i WMF CharacterSet-uppräkningen ([MS-WMF] avsnitt 2.1.1.5). Om <br/>            teckenuppsättningen är okänd, bör metafilbearbetning INTE försöka översätta eller tolka <br/>            strängar som renderas med det teckensnittet. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar beskärningsprecisionen. Den <br/>            beskärningsprecisionen definierar hur man beskär tecken som delvis ligger utanför beskärningsregionen. <br/>            Den kan vara en eller flera av WMF ClipPrecision-flaggorna. |
| escapement | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, <br/>            mellan escapement-vektorn och enhetens x-axel. Escapement-vektorn är <br/>            parallell med baslinjen för en textrad. |
| teckensnittsnamn | string | r/w | Hämtar eller anger ett Facename (64 byte):  En sträng på högst 32 Unicode-tecken som specificerar <br/>            typsnittets namn. Om längden på denna sträng är mindre än 32 tecken, måste en avslutande <br/>            NULL vara närvarande, varefter resten av detta fält MÅSTE ignoreras. |
| height | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden, i logiska enheter, för teckensnittets <br/>            teckencell eller tecken. Värdet för teckenhöjd, även känt som em-storlek, är <br/>            teckencellens höjdvärde minus det interna ledningsvärdet. Teckensnittsmapparen SKA <br/>            tolka värdet som anges i Height-fältet på följande sätt. |
| kursiv | System.Byte | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar ett kursivt teckensnitt om det är satt till 0x01; annars <br/>            MÅSTE det vara satt till 0x00. |
| orientering | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, <br/>            mellan varje teckens baslinje och enhetens x-axel. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar utskriftsprecisionen. <br/>            Utskriftsprecisionen definierar hur nära teckensnittet måste matcha den begärda höjden, bredden, <br/>            teckenorienteringen, escapement, pitch och teckensnittstypen. Det MÅSTE vara ett värde från WMF <br/>            OutPrecision‑enumerationen. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Hämtar eller anger ett WMF PitchAndFamily‑objekt ([MS-WMF] avsnitt 2.2.2.14) som <br/>            specificerar teckensnittets pitch och familj. Teckensnittsfamiljer beskriver teckensnittets utseende på ett generellt <br/>            sätt. De är avsedda för att specificera ett teckensnitt när den angivna teckensnittsfamiljen inte är tillgänglig. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar utskriftskvaliteten. Utskriftskvaliteten <br/>            definierar hur nära man ska försöka matcha logiska teckensnittsattribut till ett faktiskt <br/>            fysiskt teckensnitt. Det MÅSTE vara ett av värdena i WMF FontQuality‑enumerationen ([MS-WMF] <br/>            avsnitt 2.1.1.10). |
| genomstruken | System.Byte | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar ett genomstruket teckensnitt om det är satt till 0x01; <br/>            annars MÅSTE det vara satt till 0x00. |
| understruken | System.Byte | r/w | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar ett understruket teckensnitt om det är satt till 0x01; <br/>            annars MÅSTE det vara satt till 0x00. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar teckensnittets tjocklek i intervallet <br/>            noll till 1000. Till exempel är 400 normal och 700 fet. Om detta värde är noll kan en standard‑<br/>            tjocklek användas. |
| width | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den genomsnittliga bredden, i logiska enheter, för <br/>            tecken i teckensnittet. Om Width‑fältets värde är noll SKA ett lämpligt värde <br/>            beräknas från andra LogFont‑värden för att hitta ett teckensnitt som har typografens avsedda <br/>            bildförhållande. |


### Constructor: EmfLogFont() {#EmfLogFont__1}


```
 EmfLogFont() 
```

Initierar en ny instans av EmfLogFont‑klassen

