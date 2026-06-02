---
title: "EmfPlusCompressedImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusCompressedImage-Objekt gibt ein Bild mit komprimierten Daten an."
type: docs
weight: 31
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

Das EmfPlusCompressedImage-Objekt gibt ein Bild mit komprimierten Daten an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Ruft ein Byte‑Array ab oder legt es fest, das das komprimierte Bild angibt. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Ruft ein Byte‑Array ab oder legt es fest, das das komprimierte Bild angibt. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Ruft ein Byte‑Array ab oder legt es fest, das das komprimierte Bild angibt. Der Kompressionstyp MUSS aus den Daten selbst ermittelt werden.

Bitmaps werden durch EmfPlusBitmap‑Objekte (Abschnitt 2.2.2.2) spezifiziert. Ein EmfPlusCompressedImage‑Objekt MUSS im BitmapData‑Feld eines EmfPlusBitmap‑Objekts vorhanden sein, wenn BitmapDataTypeCompressed in dessen Typ‑Feld angegeben ist. Dieses Objekt ist generisch und wird für verschiedene Arten von komprimierten Daten verwendet, einschließlich: \\uf0a7 Exchangeable Image File Format (EXIF), wie in [EXIF] angegeben; \\uf0a7 Graphics Interchange Format (GIF), wie in [GIF] angegeben; \\uf0a7 Joint Photographic Experts Group (JPEG), wie in [JFIF] angegeben; \\uf0a7 Portable Network Graphics (PNG), wie in [RFC2083] und [W3C - PNG] angegeben; und \\uf0a7 Tag Image File Format (TIFF), wie in [RFC3302] und [TIFF] angegeben.

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Ruft ein Byte‑Array ab oder legt es fest, das das komprimierte Bild angibt. Der Kompressionstyp MUSS aus den Daten selbst ermittelt werden.

Bitmaps werden durch EmfPlusBitmap‑Objekte (Abschnitt 2.2.2.2) spezifiziert. Ein EmfPlusCompressedImage‑Objekt MUSS im BitmapData‑Feld eines EmfPlusBitmap‑Objekts vorhanden sein, wenn BitmapDataTypeCompressed in dessen Typ‑Feld angegeben ist. Dieses Objekt ist generisch und wird für verschiedene Arten von komprimierten Daten verwendet, einschließlich: \\uf0a7 Exchangeable Image File Format (EXIF), wie in [EXIF] angegeben; \\uf0a7 Graphics Interchange Format (GIF), wie in [GIF] angegeben; \\uf0a7 Joint Photographic Experts Group (JPEG), wie in [JFIF] angegeben; \\uf0a7 Portable Network Graphics (PNG), wie in [RFC2083] und [W3C - PNG] angegeben; und \\uf0a7 Tag Image File Format (TIFF), wie in [RFC3302] und [TIFF] angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

