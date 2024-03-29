---
title: EmfPlusDrawRects
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusDrawRects-posten anger att rita en serie rektanglar
type: docs
weight: 6010
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
## EmfPlusDrawRects class

EmfPlusDrawRects-posten anger att rita en serie rektanglar

```csharp
public sealed class EmfPlusDrawRects : EmfPlusDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusDrawRects](emfplusdrawrects)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusDrawRects`](../emfplusdrawrects) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/compressed) { get; set; } | Hämtar eller ställer in ett värde som indikerar om PointData är komprimerad. Om angivet innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38). Om det är klart innehåller RectData ett EmfPlusRectF-objekt._2.02d._section 2.02d. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/objectid) { get; set; } | Hämtar eller ställer in objektidentifieraren. Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Objekttabellen för att rita rektanglarna. Värdet MÅSTE vara noll till 63, inklusive. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/rectdata) { get; set; } | Hämtar eller ställer in rect data En array av antingen ett EmfPlusRect- eller EmfPlusRectF-objekt med Count-längd som definierar rektangeldata. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
