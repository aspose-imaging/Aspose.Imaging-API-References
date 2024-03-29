---
title: EmfPolygon
second_title: Aspose.Imaging för .NET API-referens
description: EMR_POLYGON-posten anger en polygon som består av två eller flera hörn sammankopplade med raka linjer.
type: docs
weight: 4080
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---
## EmfPolygon class

EMR_POLYGON-posten anger en polygon som består av två eller flera hörn sammankopplade med raka linjer.

```csharp
public sealed class EmfPolygon : EmfDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPolygon](emfpolygon#constructor)() | Initierar en ny instans av[`EmfPolygon`](../emfpolygon) class. |
| [EmfPolygon](emfpolygon#constructor_1)(EmfRecord) | Initierar en ny instans av[`EmfPolygon`](../emfpolygon) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon/apoints) { get; set; } | Hämtar eller ställer in en Count length-array av WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar polygonens hörn i logiska enheter. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon/bounds) { get; set; } | Hämtar eller ställer in ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den gränsande rektangeln i enhetsenheter. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Anmärkningar

Polygonen SKA kontureras med den aktuella pennan och fyllas med den aktuella penseln och polygonfyllningsläget. Polygonen SKA stängas automatiskt genom att dra en linje från den sista vertexen till den första

### Se även

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
