---
title: EmfPlusBitmap
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusBitmap-objektet anger en bitmapp som innehåller en grafikbild.
type: docs
weight: 5170
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
## EmfPlusBitmap class

EmfPlusBitmap-objektet anger en bitmapp som innehåller en grafikbild.

```csharp
public sealed class EmfPlusBitmap : EmfPlusBaseImageData
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusBitmap](emfplusbitmap)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BitmapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/bitmapdata) { get; set; } | Hämtar eller ställer in bitmappsdata BitmapData (variabel): Data med variabel längd som definierar bitmappsdataobjektet som anges i fältet Typ. Innehållet och dataformatet kan vara olika för varje bitmappstyp. |
| [Height](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/height) { get; set; } | Hämtar eller ställer in bitmapp height Height (4 byte): Ett 32-bitars heltal med tecken som anger höjden i pixlar för området som upptas av bitmappen. Om bilden är komprimerad, enligt fältet Typ, är detta värde odefinierat och MÅSTE ignoreras. |
| [PixelFormat](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/pixelformat) { get; set; } | Hämtar eller ställer in pixelformat PixelFormat (4 byte): Ett 32-bitars heltal utan tecken som anger formatet på pixlarna som bildar bitmap . De pixelformat som stöds anges i[`EmfPlusPixelFormat`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat) uppräkning (section 2.1.1.25). Om bilden är komprimerad, enligt fältet Typ, är detta värde odefinierat och MÅSTE ignoreras. |
| [Stride](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/stride) { get; set; } | Hämtar eller ställer in steg för image Stride (4 byte): Ett 32-bitars heltal med tecken som anger byteförskjutningen mellan början av en skanningslinje och nästa. Detta värde är antalet byte per pixel, som anges i fältet PixelFormat, multiplicerat med bredden i pixlar, som anges i fältet Width. Värdet för detta fält MÅSTE vara en multipel av fyra. Om bilden är komprimerad, enligt fältet Typ, är detta värde odefinierat och MÅSTE ignoreras. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/type) { get; set; } | Hämtar eller ställer in typen av image Typ (4 byte): Ett 32-bitars osignerat heltal som anger typen av data i fältet BitmapData. Detta värde MUST definieras i[`EmfPlusBitmapDataType`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype) uppräkning (avsnitt 2.1.1.2). |
| [Width](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/width) { get; set; } | Hämtar eller ställer in bild Width Width (4 byte): Ett 32-bitars signerat heltal som anger bredden i pixlar för området som upptas av bitmappen. Om bilden är komprimerad, enligt fältet Typ, är detta värde odefinierat och MÅSTE ignoreras. |

### Se även

* class [EmfPlusBaseImageData](../emfplusbaseimagedata)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
