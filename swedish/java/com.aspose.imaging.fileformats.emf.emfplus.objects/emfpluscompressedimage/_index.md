---
title: "EmfPlusCompressedImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusCompressedImage-objektet specificerar en bild med komprimerad data."
type: docs
weight: 31
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

EmfPlusCompressedImage-objektet specificerar en bild med komprimerad data.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Hämtar eller anger en bytearray som specificerar den komprimerade bilden. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Hämtar eller anger en bytearray som specificerar den komprimerade bilden. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Hämtar eller anger en bytearray som specificerar den komprimerade bilden. Kompressionstypen MÅSTE bestämmas från själva datan.

Bitmaps specificeras av EmfPlusBitmap-objekt (sektion 2.2.2.2). Ett EmfPlusCompressedImage-objekt MÅSTE finnas i BitmapData‑fältet för ett EmfPlusBitmap‑objekt om BitmapDataTypeCompressed anges i dess Type‑fält. Detta objekt är generiskt och används för olika typer av komprimerad data, inklusive: \\uf0a7 Exchangeable Image File Format (EXIF), enligt [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), enligt [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), enligt [JFIF]; \\uf0a7 Portable Network Graphics (PNG), enligt [RFC2083] och [W3C - PNG]; och \\uf0a7 Tag Image File Format (TIFF), enligt [RFC3302] och [TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Hämtar eller anger en bytearray som specificerar den komprimerade bilden. Kompressionstypen MÅSTE bestämmas från själva datan.

Bitmaps specificeras av EmfPlusBitmap-objekt (sektion 2.2.2.2). Ett EmfPlusCompressedImage-objekt MÅSTE finnas i BitmapData‑fältet för ett EmfPlusBitmap‑objekt om BitmapDataTypeCompressed anges i dess Type‑fält. Detta objekt är generiskt och används för olika typer av komprimerad data, inklusive: \\uf0a7 Exchangeable Image File Format (EXIF), enligt [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), enligt [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), enligt [JFIF]; \\uf0a7 Portable Network Graphics (PNG), enligt [RFC2083] och [W3C - PNG]; och \\uf0a7 Tag Image File Format (TIFF), enligt [RFC3302] och [TIFF].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

