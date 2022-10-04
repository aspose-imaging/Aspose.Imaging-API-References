---
title: EmfPolyBezier
second_title: Aspose.Imaging för .NET API-referens
description: EMR_POLYBEZIER-posten specificerar en eller flera Bezier-kurvor.
type: docs
weight: 3960
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
## EmfPolyBezier class

EMR_POLYBEZIER-posten specificerar en eller flera Bezier-kurvor.

```csharp
public sealed class EmfPolyBezier : EmfDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPolyBezier](emfpolybezier#constructor)() | Initierar en ny instans av[`EmfPolyBezier`](../emfpolybezier) class. |
| [EmfPolyBezier](emfpolybezier#constructor_1)(EmfRecord) | Initierar en ny instans av[`EmfPolyBezier`](../emfpolybezier) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezier/apoints) { get; set; } | Hämtar eller ställer in en Count length-array av WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar ändpunkterna och kontrollpunkterna för Bezier-kurvorna, i logiska enheter. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezier/bounds) { get; set; } | Hämtar eller ställer in ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den gränsande rektangeln i enhetsenheter. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Anmärkningar

Cubic Bezier-kurvor definieras med de ändpunkter och kontrollpunkter som anges i fältet aPoints . Den första kurvan ritas från den första punkten till den fjärde punkten, med de andra och tredje -punkterna som kontrollpunkter. Varje efterföljande kurva i sekvensen behöver exakt ytterligare tre punkter: slutpunkten för föregående kurva används som startpunkt, de följande två punkterna i sekvensen är kontrollpunkter och den tredje är slutpunkten. De kubiska Bezier-kurvorna SKA ritas med den nuvarande pennan

### Se även

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->