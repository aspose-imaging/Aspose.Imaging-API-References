---
title: BitmapV5Header
second_title: Aspose.Imaging för .NET API-referens
description: BitmapV5Header-strukturen är bitmappsinformationshuvudfilen. Det är en utökad version av BITMAPINFOHEADER-strukturen. Om bV5Height är negativ vilket indikerar en top-down DIB måste bV5Compression vara antingen BI_RGB eller BI_BITFIELDS. Top-down DIBer kan inte komprimeras. Independent Color Management Interface ICM 2.0 tillåter att färgprofiler för International Color Consortium ICC länkas eller bäddas in i DIBer DIB. Se Använda strukturer för mer information. När en DIB laddas in i minnet bör profildata om sådan finns följa färgtabellen och bV5ProfileData bör tillhandahålla offset för profildata från början av BITMAPV5HEADER-strukturen. Värdet som lagras i bV5ProfileData kommer att skilja sig från värdet som returneras av operatorn sizeof givet BITMAPV5HEADER-argumentet eftersom bV5ProfileData är förskjutningen i byte från början av BITMAPV5HEADER-strukturen till början av profildata. Bitmappsbitar följer inte färgtabellen i minnet. Applikationer bör modifiera bV5ProfileData-medlemmen efter att ha laddat in DIB i minnet. För packade DIBer bör profildata följa bitmappsbitarna som liknar filformatet. bV5ProfileData-medlemmen bör fortfarande ge förskjutningen av profildata från början av BITMAPV5HEADER. Applikationer bör endast komma åt profildata när bV5Size är lika med storleken på BITMAPV5HEADER och bV5CSType är lika med PROFILE_EMBEDDED eller PRO.
type: docs
weight: 1370
url: /sv/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

BitmapV5Header-strukturen är bitmappsinformationshuvudfilen. Det är en utökad version av BITMAPINFOHEADER-strukturen. Om bV5Height är negativ, vilket indikerar en top-down DIB, måste bV5Compression vara antingen BI_RGB eller BI_BITFIELDS. Top-down DIB:er kan inte komprimeras. Independent Color Management Interface (ICM) 2.0 tillåter att färgprofiler för International Color Consortium (ICC) länkas eller bäddas in i DIB:er (DIB). Se Använda strukturer för mer information. När en DIB laddas in i minnet bör profildata (om sådan finns) följa färgtabellen, och bV5ProfileData bör tillhandahålla offset för profildata från början av BITMAPV5HEADER-strukturen. Värdet som lagras i bV5ProfileData kommer att skilja sig från värdet som returneras av operatorn sizeof givet BITMAPV5HEADER-argumentet, eftersom bV5ProfileData är förskjutningen i byte från början av BITMAPV5HEADER-strukturen till början av profildata. (Bitmappsbitar följer inte färgtabellen i minnet). Applikationer bör modifiera bV5ProfileData-medlemmen efter att ha laddat in DIB i minnet. För packade DIB:er bör profildata följa bitmappsbitarna som liknar filformatet. bV5ProfileData-medlemmen bör fortfarande ge förskjutningen av profildata från början av BITMAPV5HEADER. Applikationer bör endast komma åt profildata när bV5Size är lika med storleken på BITMAPV5HEADER och bV5CSType är lika med PROFILE_EMBEDDED eller PRO.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Hämtar eller ställer in färgmasken som anger alfakomponenten för varje pixel. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Hämtar eller ställer in antal viktiga palettfärger. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Hämtar eller ställer in antalet palettfärger som används. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Hämtar eller ställer in bitmappskomprimering. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Hämtar eller ställer in bitmappshöjd. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Gets eller sets specificerar bitmappsrådatastorlek i byte. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Hämtar eller ställer in antal plan. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Hämtar eller ställer in bitmappsbredd. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Får eller ställer in horisontell pixelupplösning. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Hämtar eller ställer in vertikala pixlars upplösning. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Hämtar eller ställer in bitar per pixelantal. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Hämtar eller ställer in färgmasken som anger den blå komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | Hämtar eller ställer in färgrymden för DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | Hämtar eller ställer in klassen CoordinatesTriple. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Hämtar eller ställer in de extra bitmaskerna. Finns endast om DIB-huvudet är BITMAPINFOHEADER och[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) är inställd på antingenBitfields (RGB) ellerAlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Får eller ställer in gammablått. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Får eller ställer in gammagrönt. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Får eller ställer in gammaröd. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Hämtar eller ställer in färgmasken som anger den gröna komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Hämtar eller ställer in storleken på denna struktur i byte. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Hämtar eller ställer in renderingsavsikten för bitmapp. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Hämtar eller ställer in profildata. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Hämtar eller ställer in storleken på profilen. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Hämtar eller ställer in färgmasken som anger den röda komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Hämtar eller ställer in den reserverade medlemmen. |

### Se även

* class [BitmapV4Header](../bitmapv4header)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
