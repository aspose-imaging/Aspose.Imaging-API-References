---
title: "EmfText-klass"
type: docs
weight: 260
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfText()](#EmfText__1) | Initierar en ny instans av klassen EmfText |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| chars | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen |
| dx_buffer | int[] | r/w | Hämtar eller anger den valfria teckenavståndsbuffern<br/>            UndefinedSpace2 (variabel): Ett valfritt antal oanvända byte. OutputDx-fältet krävs inte att <br/>            följa omedelbart den föregående delen av denna struktur.<br/>            OutputDx (variabel): En matris av 32-bitars osignerade heltal som specificerar utmatningsavståndet mellan <br/>            ursprungen för intilliggande teckenceller i logiska enheter. Placeringen av detta fält anges av <br/>            värdet av offDx i byte från början av denna post. Om avstånd är definierat innehåller detta fält <br/>            samma antal värden som tecken i utmatningssträngen. Om Options-fältet i EmrText-objektet <br/>            innehåller ETO_PDY-flaggan, innehåller denna buffer dubbelt så många värden som det finns tecken i <br/>            utmatningssträngen, ett horisontellt och ett vertikalt offset för varje, i den ordningen. Om ETO_RTLREADING är angivet, <br/>            läggs tecken från höger till vänster istället för från vänster till höger. Inga andra alternativ påverkar tolkningen av detta fält. |
| glyph_index_buffer | int[] | r/w | Hämtar eller anger den valfria glyph-indexbuffern.<br/>            Om alternativ har ETO_GLYPH_INDEX-flaggan så är koderna för tecken i en utmatningstextsträng faktiskt index<br/>            av teckenglyfer i ett TrueType-typsnitt (2.1.11 ExtTextOutOptions‑enumeration). Glyph-index är typsnittsspecifika,<br/>            så för att visa rätt tecken vid uppspelning måste det typsnitt som används vara IDENTISK med det typsnitt som användes för<br/>            att generera indexen. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur rektangeln som anges i <br/>            Rectangle-fältet ska användas. Detta fält kan vara en kombination av fler än ett ExtTextOutOptions-<br/>            enumerationsvärde (avsnitt 2.1.11). |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett valfritt WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en beskärnings- <br/>            och/eller opakiseringsrektangel i logiska enheter. Denna rektangel tillämpas på text-<br/>            utmatningen som utförs av den innehållande posten. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar koordinaterna för <br/>            referenspunkten som används för att positionera strängen. Referenspunkten definieras av det sista <br/>            EMR_SETTEXTALIGN-posten (avsnitt 2.3.11.25). Om ingen sådan post har satts, <br/>            är standardjusteringen TA_LEFT,TA_TOP. |
| string_buffer | string | r/w | Hämtar eller anger teckensträngbufferten<br/>            UndefinedSpace1 (variabel): Ett valfritt antal oanvända byte. <br/>            OutputString-fältet krävs inte att följa omedelbart den föregående delen av denna struktur.<br/>            OutputString (variabel): En matris av tecken som specificerar strängen att skriva ut. <br/>            Placeringen av detta fält anges av värdet av offString i byte från början av denna post. <br/>            Antalet tecken specificeras av värdet av Chars. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

Initierar en ny instans av klassen EmfText

