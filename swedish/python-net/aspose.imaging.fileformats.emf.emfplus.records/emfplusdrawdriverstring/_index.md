---
title: "EmfPlusDrawDriverString klass"
type: docs
weight: 110
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Initierar en ny instans av [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Hämtar eller anger borstidentifieraren<br/> Ett 32-bitars osignerat heltal som specificerar antingen förgrundsfärgen för texten eller en grafikborste,<br/> beroende på värdet av S-flaggan i Flags. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Hämtar eller anger flaggorna för drivringssträngsalternativ<br/> Ett 32-bitars osignerat heltal som specificerar avstånd, orientering och renderingskvalitet för strängen. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| glyph_count | int | r/w | Hämtar eller anger antalet glyfer<br/> Ett 32-bitars osignerat heltal som specificerar antalet glyfer i strängen |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger arrayen med glyffpositioner<br/> En array av EmfPlusPointF-objekt (sektion 2.2.2.36) som specificerar utskriftspositionen för varje teckenglyf.<br/> Det MÅSTE finnas GlyphCount-element, som har en en-till-en korrespondens med elementen i Glyphs-arrayen.<br/> Glyffpositioner beräknas från positionen för den första glyfen om flaggan DriverStringOptionsRealizedAdvance<br/> i DriverStringOptions-flaggan är satt. I detta fall specificerar GlyphPos endast positionen för den första glyfen. |
| glyphs | int[] | r/w | Hämtar eller anger arrayen med glyfer<br/> En array av 16-bitars värden som definierar textsträngen att rita.<br/> Om flaggan DriverStringOptionsCmapLookup i DriverStringOptionsFlags-fältet är satt, specificerar varje värde i denna<br/> array ett Unicode-tecken. Annars specificerar varje värde ett index till en<br/> teckenglyf i EmfPlusFont-objektet som anges av ObjectId-värdet i Flags-fältet. |
| is_color | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är färg.<br/> Denna bit indikerar datatypen i BrushId-fältet.<br/> Om satt, specificerar BrushId färgvärdet i ett EmfPlusARGB-objekt<br/> (sektion 2.2.2.1). Om rensad, innehåller BrushId EMF+ Object<br/> Table-indexet för ett EmfPlusBrush-objekt (sektion 2.1.1). |
| matrix_present | int | r/w | Hämtar eller anger om matris‑present‑flaggan<br/> Ett 32-bitars osignerat heltal som specificerar om en transformmatris finns i TransformMatrix-fältet<br/> 0 - ingen matris närvarande. 1 - transformmatris finns i TransformMatrix-fältet |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/> EMF+ Object Table-indexet för ett ***EmfPlusFont***-objekt (sektion<br/> 2.2.1.3) för att rendera texten. Värdet MÅSTE vara mellan 0 och 63, inklusivt. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger transformmatrisen<br/> Ett valfritt EmfPlusTransformMatrix-objekt (sektion 2.2.2.47) som specificerar transformationen att tillämpa på<br/> varje värde i textarrayen. Förekomsten av dessa data bestäms av MatrixPresent-fältet. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Initierar en ny instans av [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

