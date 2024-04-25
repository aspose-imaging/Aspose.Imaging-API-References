---
title: EmfTransparentBlt
second_title: Aspose.Imaging för .NET API-referens
description: EMR_TRANSPARENTBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel behandlar en specificerad färg som transparent sträcker ut eller komprimerar utdata för att passa dimensionerna på destinationen om nödvändigt
type: docs
weight: 4640
url: /sv/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

EMR_TRANSPARENTBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, behandlar en specificerad färg som transparent, sträcker ut eller komprimerar utdata för att passa dimensionerna på destinationen, om nödvändigt

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt)(EmfRecord) | Initierar en ny instans av[`EmfTransparentBlt`](../emftransparentblt) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds) { get; set; } | Hämtar eller ställer in ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationsgränsrektangeln i enhetsenheter. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska bredden på destinationsrektangeln. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger källrektangelns logiska bredd. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska höjden på destinationsrektangeln. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska höjden på källrektangeln. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap) { get; set; } | Hämtar eller ställer in en buffert som innehåller källbitmappen, som inte behöver vara sammanhängande med den fasta delen av EMR_TRANSPARENTBLT-posten. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color) { get; set; } | Hämtar eller ställer in ett WMF ColorRef-objekt som anger bakgrundsfärgen för källbitmappen. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color) { get; set; } | Hämtar eller ställer in ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som anger färgen i källbitmappen som ska behandlas som transparent. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur värden ska tolkas i färgtabellen i källbitmappshuvudet. Detta värde MÅSTE finnas i DIBColors-uppräkningen (avsnitt 2.1.9) |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc) { get; set; } | Hämtar eller ställer in ett XForm-objekt (avsnitt 2.2.28) som anger en transformation av världsutrymme till sidutrymme som ska tillämpas på källbitmappen. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |

### Se även

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
