---
title: EmfPlusPathPointTypeRle
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusPathPointTypeRle-objektet specificerar typvärden som är associerade med punkter på en grafikbana med RLE-komprimering. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 4 9 2 6 7 9 3 0 1 Bx7C1x7CRunCount x7C PointType x7C B 1 bit Om inställt är vägpunkterna på en Bezier-kurva. Om den är ren är vägpunkterna på en grafisk linje. RunCount 6 bitar Runcount vilket är antalet av sökvägspunkter som ska associeras med typen i PointType-fältet. PointType 1 byte Ett EmfPlusPathPointType-objekt avsnitt 2.2.2.31 som anger typen som ska associeras med sökvägspunkterna.
type: docs
weight: 5650
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
## EmfPlusPathPointTypeRle class

EmfPlusPathPointTypeRle-objektet specificerar typvärden som är associerade med punkter på en grafikbana med RLE-komprimering. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 4 9 2 6 7 9 3 0 1 B&#x7C;1&#x7C;RunCount &#x7C; PointType &#x7C; B (1 bit): Om inställt, är vägpunkterna på en Bezier-kurva. Om den är ren, är vägpunkterna på en grafisk linje. RunCount (6 bitar): Runcount, vilket är antalet av sökvägspunkter som ska associeras med typen i PointType-fältet. PointType (1 byte): Ett EmfPlusPathPointType-objekt (avsnitt 2.2.2.31) som anger typen som ska associeras med sökvägspunkterna.

```csharp
public sealed class EmfPlusPathPointTypeRle : EmfPlusBasePointType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusPathPointTypeRle](emfpluspathpointtyperle)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bezier](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/bezier) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`EmfPlusPathPointTypeRle`](../emfpluspathpointtyperle) är bezier. Om inställt är vägpunkterna på en Bezier-kurva. Om den är ren, är vägpunkterna på en grafisk linje. |
| [Data](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/data) { get; set; } | Hämtar eller ställer in data. |
| [PointType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/pointtype) { get; set; } | Hämtar eller ställer in typen av punkt. PointType (1 byte): Ett EmfPlusPathPointType-objekt (avsnitt 2.2.2.31) som anger typen som ska associeras med sökvägspunkterna. |
| [RunCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/runcount) { get; set; } | Hämtar eller ställer in antalet körningar. RunCount (6 bitar): Körantalet, vilket är antalet sökväg punkter som ska associeras med typen i PointType field |

### Se även

* class [EmfPlusBasePointType](../emfplusbasepointtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
