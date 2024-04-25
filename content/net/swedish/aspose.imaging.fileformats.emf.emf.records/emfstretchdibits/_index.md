---
title: EmfStretchDiBits
second_title: Aspose.Imaging för .NET API-referens
description: EMR_STRETCHDIBITS-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel valfritt i kombination med ett penselmönster enligt en specificerad raster operation sträckning eller komprimering av utdata för att passa destinationens dimensioner om nödvändig.
type: docs
weight: 4600
url: /sv/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

EMR_STRETCHDIBITS-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, valfritt i kombination med ett penselmönster, enligt en specificerad raster operation, sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändig.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits)(EmfRecord) | Initierar en ny instans av[`EmfStretchDiBits`](../emfstretchdibits) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger en rasteroperationskod . Dessa koder definierar hur färgdata för källrektangeln ska kombineras med färgdata för destinationsrektangeln och eventuellt ett penselmönster, för att uppnå den slutliga färgen. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds) { get; set; } | Hämtar eller ställer in ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationsgränsrektangeln i enhetsenheter. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska bredden på destinationsrektangeln. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger bredden i pixlar för källrektangeln. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska höjden på destinationsrektangeln. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger höjden i pixlar för källrektangeln. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap) { get; set; } | Hämtar eller ställer in en buffert som innehåller källbitmappen, som inte behöver vara sammanhängande med den fasta delen av EMR_STRETCHDIBITS-posten. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur värden ska tolkas i färgtabellen i källbitmappshuvudet. Detta värde MÅSTE finnas i DIBColors-uppräkningen (avsnitt 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger x-koordinaten i pixlar i det övre vänstra hörnet av källrektangeln. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger y-koordinaten i pixlar i det övre vänstra hörnet av källrektangeln. |

### Anmärkningar

Den här posten stöder källbilder i JPEG- och PNG-format. Komprimeringsfältet i källhuvudet bitmappshuvud anger bildformatet. Om tecknen för käll- och destinationshöjd- och breddfälten skiljer sig, specificerar denna post en spegelbildskopia av källbitmappen till destinationen. Det vill säga, om cxSrc och cxDest har olika tecken, specificeras en spegelbild av källbitmappen längs x-axeln. Om cySrc och cyDest har olika tecken, anges en spegelbild av källbitmappen längs y-axeln.

### Se även

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
