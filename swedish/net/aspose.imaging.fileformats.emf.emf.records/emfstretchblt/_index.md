---
title: EmfStretchBlt
second_title: Aspose.Imaging för .NET API-referens
description: EMR_STRETCHBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel valfritt i kombination med ett penselmönster enligt en specificerad raster -operation sträckning eller komprimering av utdata för att passa destinationens dimensioner om nödvändigt .
type: docs
weight: 4590
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

EMR_STRETCHBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, valfritt i kombination med ett penselmönster, enligt en specificerad raster -operation, sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändigt .

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfStretchBlt](emfstretchblt#constructor)() | Initierar en ny instans av[`EmfStretchBlt`](../emfstretchblt) class. |
| [EmfStretchBlt](emfstretchblt#constructor_1)(EmfRecord) | Initierar en ny instans av[`EmfStretchBlt`](../emfstretchblt) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc) { get; set; } | Hämtar eller ställer in ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8 som anger bakgrundsfärgen för källbitmappen. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som specificerar rasteroperationens kod. Denna kod definierar hur färgdata för källrektangeln ska kombineras med färgdata för destinationsrektangeln och eventuellt ett penselmönster, för att uppnå den slutliga color |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds) { get; set; } | Hämtar eller ställer in ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationsgränsrektangeln i enhetsenheter. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska bredden på destinationsrektangeln. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger källrektangelns logiska bredd. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska höjden på destinationsrektangeln. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska höjden på källrektangeln. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect) { get; set; } | Får eller ställer in den bästa riktningen. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap) { get; set; } | Hämtar eller ställer in en buffert som innehåller källbitmappen, som inte behöver vara sammanhängande med den fasta delen av EMR_STRETCHBLT-posten. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect) { get; set; } | Hämtar eller ställer in källkorrigeringen. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur värden ska tolkas i färgtabellen i källbitmappshuvudet. Detta värde MÅSTE finnas i DIBColors-uppräkningen (avsnitt 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc) { get; set; } | Hämtar eller ställer in ett XForm-objekt (avsnitt 2.2.28) som anger en transformation av världsutrymme till sidutrymme för att tillämpas på källbitmappen. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |

### Se även

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
