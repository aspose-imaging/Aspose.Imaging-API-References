---
title: WmfLogColorSpace
second_title: Aspose.Imaging för .NET API-referens
description: LogColorSpace-objektet anger en logisk färgrymd för uppspelningsenhetskontexten vilket kan vara namnet på en färgprofil i ASCII-tecken.
type: docs
weight: 8750
url: /sv/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

LogColorSpace-objektet anger en logisk färgrymd för uppspelningsenhetskontexten, vilket kan vara namnet på en färgprofil i ASCII-tecken.

```csharp
public class WmfLogColorSpace : MetaObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger typen av färgrymd . Det MÅSTE definieras i LogicalColorSpace enumeration (avsnitt 2.1.1.14). Om detta värde är LCS_sRGB eller LCS_WINDOWS_COLOR_SPACE, MÅSTE sRGB-färgrymden användas. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | Hämtar eller ställer in ett CIEXYZTriple-objekt (avsnitt 2.2.2.7) som definierar CIE-kromaticiteten x, y och z-koordinater för de tre colors som motsvarar RGBendpoints för färgrymden logical som är associerad med bitmappen. Om [`ColorSpaceType`](./colorspacetype) fältet specificerar inte LCS_CALIBRATED_RGB, detta fält MÅSTE ignoreras. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Hämtar eller ställer in en valfri ASCII-teckensträng som anger namnet på en fil som innehåller en färgprofil. Om ett filnamn är specificerat, och[`ColorSpaceType`](./colorspacetype) fältet är satt till LCS_CALIBRATED_RGB, de andra fälten i denna struktur BÖR ignoreras. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Hämtar eller ställer in ett 32-bitars fast punktvärde som definierar toned svarskurvan för blått. Om[`ColorSpaceType`](./colorspacetype) field anger inte LCS_CALIBRATED_RGB, detta fält MÅSTE ignoreras. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Hämtar eller ställer in ett 32-bitars fast punktvärde som definierar toned svarskurvan för grönt. Om[`ColorSpaceType`](./colorspacetype) field anger inte LCS_CALIBRATED_RGB, detta fält MÅSTE ignoreras. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Hämtar eller ställer in ett 32-bitars fast punktvärde som definierar toned svarskurvan för rött. Om[`ColorSpaceType`](./colorspacetype) field anger inte LCS_CALIBRATED_RGB, detta fält MÅSTE ignoreras. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som definierar omfångsmapping avsikten. Det MÅSTE definieras i GamutMappingIntent enumeration (avsnitt 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger the signature av färgrymdsobjekt; den MÅSTE ställas in på värdet 0x50534F43, vilket är ASCII-kodningen för string "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som definierar size av detta objekt, i bytes. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som definierar a version siffra; det MÅSTE vara 0x00000400. |

### Anmärkningar

Fälten Endpoints, GammaRed, GammaGreen och GammaBlue används för att ange en logisk färgrymd. Fältet Endpoints är ett CIEXYZTriple -objekt som innehåller x-, y- och z-värdena för RGB-slutpunkten för färgrymden . Relationen mellan tri-stimulusvärdena X,Y,Z och kromaticitetsvärden x,y,z uttrycks enligt följande. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) Fälten GammaRed, GammaGreen och GammaBlue innehåller värden i "8.8 fixpunkt" format, vilket är en teknik för att representerar icke-heltal. Varje värde består av en zeroextended 8-bitars storlek följt av en 8-bitars bråkdel, med de kombinerade 16 bits vänsterförskjutna med 8 bitar. Sålunda, i 32-bitar, är det reella värdet NF 00000000nnnnnnffffffff00000000, där "nnnnnnnn" och "ffffffff" är binära representationer av N respektive F. For example, for the real number 10.5, nnnnnnnn would be 00001010 (binary 10) and ffffffff would be 00000101 (binary 5), and the complete 32-bit binary value would be 00000000000010100000010100000000, which is the hexadecimal value 0x0A50.

### Se även

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* namnutrymme [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
