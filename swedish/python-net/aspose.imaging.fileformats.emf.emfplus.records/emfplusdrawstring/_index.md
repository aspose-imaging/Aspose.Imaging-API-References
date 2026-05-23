---
title: "EmfPlusDrawString klass"
type: docs
weight: 190
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Initierar en ny instans av klassen [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Hämtar eller anger borstidentifieraren<br/>            Ett 32-bitars osignerat heltal som specificerar borsten, vars innehåll <br/>            bestäms av S-bit i Flag-fältet. Denna definition används <br/>            för att måla förgrundens textfärg; det vill säga bara glyferna själva. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| format_id | int | r/w | Hämtar eller anger formatidentifieraren<br/>            Ett 32-bitars osignerat heltal som specificerar indexet för ett valfritt <br/>            EmfPlusStringFormat-objekt (avsnitt 2.2.1.9) i EMF+ objekt-tabellen. <br/>            Detta objekt specificerar information om textlayout och visningsmanipulationer <br/>            som ska tillämpas på en sträng. |
| is_color | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är färg.<br/>            Om satt, specificerar BrushId en färg som ett EmfPlusARGB-objekt (avsnitt 2.2.2.1).<br/>            Om rensad, innehåller BrushId indexet för ett EmfPlusBrush-objekt <br/>            (avsnitt 2.2.1.1) i EMF+ objekt-tabellen. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger layoutrektangeln<br/>            Ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) som definierar det omgivande området <br/>            för destinationen som ska ta emot strängen. |
| length | int | r/w | Hämtar eller anger längden<br/>            Ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet för ett EmfPlusFont-objekt (avsnitt 2.2.1.3) i EMF+<br/>            objekt-tabellen för att rendera texten. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| string_data | string | r/w | Hämtar eller anger strängdata<br/>            En array av 16-bitars Unicode-tecken som specificerar strängen som ska ritas. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Initierar en ny instans av klassen [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

