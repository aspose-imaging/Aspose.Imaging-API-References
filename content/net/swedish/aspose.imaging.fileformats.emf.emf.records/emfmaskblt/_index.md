---
title: EmfMaskBlt
second_title: Aspose.Imaging för .NET API-referens
description: EMR_MASKBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel valfritt i kombination med ett penselmönster och med applicering av en färgmask bitmapp enligt specificerade förgrunds- och bakgrundsrasteroperationer.
type: docs
weight: 3800
url: /sv/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

EMR_MASKBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel, valfritt i kombination med ett penselmönster och med applicering av en färgmask bitmapp, enligt specificerade förgrunds- och bakgrundsrasteroperationer.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfMaskBlt](emfmaskblt)(EmfRecord) | Initierar en ny instans av[`EmfMaskBlt`](../emfmaskblt) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc) { get; set; } | Hämtar eller ställer in ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8 som anger bakgrundsfärgen för källbitmappen. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds) { get; set; } | Hämtar eller ställer in ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationsgränsrektangeln i enhetsenheter. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska bredden på destinationsrektangeln. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska höjden på destinationsrektangeln. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap) { get; set; } | Hämtar eller ställer in en buffert som innehåller maskbitmapparna, som inte krävs för att vara sammanhängande med den fasta delen av EMR_MASKBLT-posten eller med varandra . Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4) { get; set; } | Hämtar eller ställer in en kvartär rasteroperation, som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmapp. Dessa värden definierar hur färgdata för källrektangeln ska kombineras med färgdata för destinationsrektangeln. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap) { get; set; } | Hämtar eller ställer in en buffert som innehåller källbitmapparna, som inte krävs för att vara sammanhängande med den fasta delen av EMR_MASKBLT-posten eller med varandra . Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur värden ska tolkas i färgtabellen i maskens bitmappshuvud. Detta värde MÅSTE finnas i DIBColors-uppräkningen. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur värden ska tolkas i färgtabellen i källbitmappshuvudet. Detta värde MÅSTE finnas i DIBColors-uppräkningen (avsnitt 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc) { get; set; } | Hämtar eller ställer in ett XForm-objekt (avsnitt 2.2.28) som anger en transformation av världsutrymme till sidutrymme som ska tillämpas på källbitmappen. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska x-koordinaten för det övre vänstra hörnet av maskbitmappen. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av maskbitmappen. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |

### Se även

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
