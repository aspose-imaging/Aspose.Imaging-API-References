---
title: EmfPlusDrawDriverString
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusDrawDriverString-posten anger textutmatning med teckenpositioner.
type: docs
weight: 5940
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

EmfPlusDrawDriverString-posten anger textutmatning med teckenpositioner.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusDrawDriverString`](../emfplusdrawdriverstring) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid) { get; set; } | Hämtar eller ställer in penselidentifieraren Ett 32-bitars osignerat heltal som anger antingen förgrundsfärgen på texten eller en grafikpensel, beroende på värdet på S-flaggan i Flags |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags) { get; set; } | Hämtar eller ställer in alternativen för drivrutinssträngen flags Ett 32-bitars osignerat heltal som anger avstånd, orientering och renderingskvalitet för strängen. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount) { get; set; } | Hämtar eller ställer in glyph count Ett 32-bitars osignerat heltal som anger antalet glyphs i string |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos) { get; set; } | Hämtar eller ställer in glyphpositionerna array En array av EmfPlusPointF-objekt (avsnitt 2.2.2.36) som anger utdatapositionen för varje teckenglyph. Det MÅSTE finnas GlyphCount-element som har en en-till-en-överensstämmelse med elementet Glyphs array. Glyfpositioner beräknas från positionen för den första glyfen om flaggan DriverStringOptionsRealizedAdvance i DriverStringOptions-flaggor är inställd. I det här fallet anger GlyphPos endast den första glyfens position. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs) { get; set; } | Hämtar eller ställer in glyphs array En matris med 16-bitars värden som definierar textsträngen som ska ritas. Om flaggan DriverStringOptionsCmapLookup i fältet DriverStringOptionsFlags är inställd, anger varje värde i this_x000-tecken ett Unicode. Annars anger varje värde ett index till a teckenglyph i EmfPlusFont-objektet som anges av ObjectId-värdet i Flags-fältet. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor) { get; set; } | Hämtar eller ställer in ett värde som indikerar om denna instans är färg. Den här biten indikerar typen av data i BrushId-fältet. Om angivet anger BrushId färgvärdet i ett EmfPlusARGB-objekt (avsnitt 2.2.2.1). Om den är ren, innehåller BrushId EMF+ Object Tabellindex för ett EmfPlusBrush-objekt (avsnitt 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent) { get; set; } | Hämtar eller ställer in om matrisen presenterar flag Ett 32-bitars heltal utan tecken som anger om en transformationsmatris finns i fältet TransformMatrix 0 - ingen matris närvarande. 1 - transformationsmatris är i TransformMatrix field |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid) { get; set; } | Hämtar eller ställer in objektidentifieraren. EMF+ Objekttabellindex för en[EmfPlusFont](EmfPlusFont) objekt (section 2.2.1.3) för att återge texten. Värdet MÅSTE vara noll till 63, inklusive. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix) { get; set; } | Hämtar eller ställer in transformationen matrix Ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som anger transformationen som ska tillämpas på varje värde i textmatrisen. Förekomsten av dessa data bestäms från fältet MatrixPresent. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
