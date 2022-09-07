---
title: EmfPlgBlt
second_title: Aspose.Imaging för .NET API-referens
description: EMR_PLGBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till ett mål parallellogram med tillämpning av en färgmaskbitmapp.
type: docs
weight: 3950
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

EMR_PLGBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till ett mål parallellogram, med tillämpning av en färgmaskbitmapp.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlgBlt](emfplgblt)(EmfRecord) | Initierar en ny instans av[`EmfPlgBlt`](../emfplgblt) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest) { get; set; } | Hämtar eller ställer in en array med tre WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som anger tre hörn ett parallellogramdestinationsområde för blocköverföringen. Det övre vänstra hörnet av källrektangeln mappas till första punkten i denna array, det övre högra hörnet till den andra punkten och det nedre vänstra hörnet till den tredje punkten. Det nedre högra hörnet av källrektangeln mappas till den implicita fjärde punkten i parallellogrammet, som beräknas från de första tre punkterna (A, B och C) genom att behandla dem som vektorer. D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color) { get; set; } | Hämtar eller ställer in ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som anger bakgrundsfärgen för källbitmappen. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds) { get; set; } | Hämtar eller ställer in ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar den avgränsande rektangeln, i enhetsenheter, för utmatning till destinationen. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger källrektangelns logiska bredd. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska höjden på källrektangeln. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap) { get; set; } | Hämtar eller ställer in en buffert som innehåller maskbitmappen, som inte krävs för att vara sammanhängande med den fasta delen av EMR_PLGBLT-posten eller med varandra. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap) { get; set; } | Hämtar eller ställer in en buffert som innehåller källbitmappen, som inte krävs för att vara sammanhängande med den fasta delen av EMR_PLGBLT-posten eller med varandra. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur värden ska tolkas i färgtabellen i maskens bitmappshuvud. Detta värde MÅSTE finnas i DIBColors-uppräkningen. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur värden ska tolkas i färgtabellen i källbitmappshuvudet. Detta värde MÅSTE finnas i DIBColors enumeration |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc) { get; set; } | Hämtar eller ställer in ett XForm-objekt (avsnitt 2.2.28) som anger en transformation av världsutrymme till sidutrymme som ska tillämpas på källbitmappen. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska x-koordinaten för det övre vänstra hörnet av maskbitmappen. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av maskbitmappen. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |

### Se även

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
