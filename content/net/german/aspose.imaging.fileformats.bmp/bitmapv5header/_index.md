---
title: BitmapV5Header
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die BitmapV5Header-Struktur ist die Bitmap-Informations-Header-Datei. Es ist eine erweiterte Version der BITMAPINFOHEADER-Struktur. Wenn bV5Height negativ ist was auf eine Top-down-DIB hinweist muss bV5Compression entweder BI_RGB oder BI_BITFIELDS sein. Top-Down-DIBs können nicht komprimiert werden. Das Independent Color Management Interface ICM 2.0 ermöglicht das Verknüpfen oder Einbetten von Farbprofilen des International Color Consortium ICC in DIBs DIBs. Weitere Informationen finden Sie unter Strukturen verwenden. Wenn eine DIB in den Speicher geladen wird sollten die Profildaten falls vorhanden der Farbtabelle folgen und die bV5ProfileData sollten den Offset der Profildaten vom Beginn der BITMAPV5HEADER-Struktur bereitstellen. Der in bV5ProfileData gespeicherte Wert unterscheidet sich von dem Wert der vom sizeof-Operator mit dem BITMAPV5HEADER-Argument zurückgegeben wird  da bV5ProfileData der Offset in Bytes vom Beginn der BITMAPV5HEADER-Struktur bis zum Beginn der Profildaten ist. Bitmap-Bits folgen nicht der Farbtabelle im Speicher. Anwendungen sollten das bV5ProfileData-Member ändern nachdem sie die DIB in den Speicher geladen haben. Für gepackte DIBs sollten die Profildaten den Bitmap-Bits ähnlich dem Dateiformat folgen. Das Mitglied bV5ProfileData sollte weiterhin den Versatz der Profildaten vom Anfang des BITMAPV5HEADER angeben. Anwendungen sollten nur dann auf die Profildaten zugreifen wenn bV5Size gleich der Größe des BITMAPV5HEADER und bV5CSType gleich PROFILE_EMBEDDED oder PROFILE_LINKED ist.
type: docs
weight: 1370
url: /de/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

Die BitmapV5Header-Struktur ist die Bitmap-Informations-Header-Datei. Es ist eine erweiterte Version der BITMAPINFOHEADER-Struktur. Wenn bV5Height negativ ist, was auf eine Top-down-DIB hinweist, muss bV5Compression entweder BI_RGB oder BI_BITFIELDS sein. Top-Down-DIBs können nicht komprimiert werden. Das Independent Color Management Interface (ICM) 2.0 ermöglicht das Verknüpfen oder Einbetten von Farbprofilen des International Color Consortium (ICC) in DIBs (DIBs). Weitere Informationen finden Sie unter Strukturen verwenden. Wenn eine DIB in den Speicher geladen wird, sollten die Profildaten (falls vorhanden) der Farbtabelle folgen, und die bV5ProfileData sollten den Offset der Profildaten vom Beginn der BITMAPV5HEADER-Struktur bereitstellen. Der in bV5ProfileData gespeicherte Wert unterscheidet sich von dem Wert, der vom sizeof-Operator mit dem BITMAPV5HEADER-Argument zurückgegeben wird, , da bV5ProfileData der Offset in Bytes vom Beginn der BITMAPV5HEADER-Struktur bis zum Beginn der Profildaten ist. (Bitmap-Bits folgen nicht der Farbtabelle im Speicher). Anwendungen sollten das bV5ProfileData-Member ändern, nachdem sie die DIB in den Speicher geladen haben. Für gepackte DIBs sollten die Profildaten den Bitmap-Bits ähnlich dem Dateiformat folgen. Das Mitglied bV5ProfileData sollte weiterhin den Versatz der Profildaten vom Anfang des BITMAPV5HEADER angeben. Anwendungen sollten nur dann auf die Profildaten zugreifen, wenn bV5Size gleich der Größe des BITMAPV5HEADER und bV5CSType gleich PROFILE_EMBEDDED oder PROFILE_LINKED ist.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Ruft die Farbmaske ab oder legt sie fest, die die Alpha-Komponente jedes Pixels angibt. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Ruft die Anzahl wichtiger Palettenfarben ab oder legt sie fest. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Ruft die Anzahl der verwendeten Palettenfarben ab oder legt sie fest. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Ruft die Bitmap-Komprimierung ab oder legt sie fest. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Ruft die Bitmap-Höhe ab oder legt sie fest. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Ruft ab oder legt die Bitmap-Rohdatengröße in Byte fest. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Ruft die Anzahl der Ebenen ab oder legt sie fest. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Liest oder setzt Bitmap-Breite. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Ruft die horizontale Pixelauflösung ab oder legt sie fest. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Ruft die vertikale Pixelauflösung ab oder legt sie fest. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Ruft die Anzahl der Bits pro Pixel ab oder setzt sie. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Ruft die Farbmaske ab oder legt sie fest, die die blaue Komponente jedes Pixels angibt, nur gültig, wenn bV4Compression auf BI_BITFIELDS gesetzt ist. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | Ruft den Farbraum der DIB ab oder setzt ihn. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | Ruft die CoordinatesTriple-Klasse ab oder legt sie fest. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Ruft die zusätzlichen Bitmasken ab oder setzt sie. Nur vorhanden, wenn der DIB-Header der BITMAPINFOHEADER ist und der[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) ist auf beides eingestelltBitfields (RGB) bzwAlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Ruft das Gamma-Blau ab oder legt es fest. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Ruft das Gamma-Grün ab oder legt es fest. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Ruft das Gamma-Rot ab oder legt es fest. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Ruft die Farbmaske ab oder legt sie fest, die die grüne Komponente jedes Pixels angibt, nur gültig, wenn bV4Compression auf BI_BITFIELDS gesetzt ist. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Ruft die Größe dieser Struktur in Bytes ab oder legt sie fest. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Ruft die Wiedergabeart für Bitmap ab oder legt sie fest. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Holt oder setzt die Profildaten. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Ruft die Größe des Profils ab oder legt sie fest. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Ruft die Farbmaske ab oder legt sie fest, die die Rotkomponente jedes Pixels angibt, nur gültig, wenn bV4Compression auf BI_BITFIELDS gesetzt ist. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Ruft das reservierte Mitglied ab oder legt es fest. |

### Siehe auch

* class [BitmapV4Header](../bitmapv4header)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
