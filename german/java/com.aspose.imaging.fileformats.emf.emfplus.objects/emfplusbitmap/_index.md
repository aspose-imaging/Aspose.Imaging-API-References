---
title: "EmfPlusBitmap"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusBitmap-Objekt gibt ein Bitmap an, das ein Grafikbild enthält."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

Das EmfPlusBitmap-Objekt gibt ein Bitmap an, das ein Grafikbild enthält.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Liest oder setzt Bitmap‑Daten BitmapData (variabel): Variable‑Länge‑Daten, die das im Feld Type angegebene Bitmap‑Datenobjekt definieren. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Liest oder setzt Bitmap‑Daten BitmapData (variabel): Variable‑Länge‑Daten, die das im Feld Type angegebene Bitmap‑Datenobjekt definieren. |
| [getHeight()](#getHeight--) | Liest oder setzt die Bitmap‑Höhe Height (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Höhe in Pixeln des von der Bitmap belegten Bereichs angibt. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt die Bitmap‑Höhe Height (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Höhe in Pixeln des von der Bitmap belegten Bereichs angibt. |
| [getPixelFormat()](#getPixelFormat--) | Liest oder setzt das Pixel‑Format PixelFormat (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die das Format der Pixel angibt, aus denen das Bitmap‑Bild besteht. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Liest oder setzt das Pixel‑Format PixelFormat (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die das Format der Pixel angibt, aus denen das Bitmap‑Bild besteht. |
| [getStride()](#getStride--) | Liest oder setzt die Zeilenlänge (Stride) des Bildes (4 Byte): Eine 32‑Bit‑signed‑Integer, die den Byte‑Versatz zwischen dem Beginn einer Scan‑Zeile und der nächsten angibt. |
| [setStride(int value)](#setStride-int-) | Liest oder setzt die Zeilenlänge (Stride) des Bildes (4 Byte): Eine 32‑Bit‑signed‑Integer, die den Byte‑Versatz zwischen dem Beginn einer Scan‑Zeile und der nächsten angibt. |
| [getType()](#getType--) | Liest oder setzt den Bildtyp Type (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die den Datentyp im Feld BitmapData angibt. |
| [setType(int value)](#setType-int-) | Liest oder setzt den Bildtyp Type (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die den Datentyp im Feld BitmapData angibt. |
| [getWidth()](#getWidth--) | Liest oder setzt die Bildbreite Width (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Breite in Pixeln des von der Bitmap belegten Bereichs angibt. |
| [setWidth(int value)](#setWidth-int-) | Liest oder setzt die Bildbreite Width (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Breite in Pixeln des von der Bitmap belegten Bereichs angibt. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Liest oder setzt Bitmap‑Daten BitmapData (variabel): Variable‑Länge‑Daten, die das im Feld Type angegebene Bitmap‑Datenobjekt definieren. Inhalt und Format der Daten können für jeden Bitmap‑Typ unterschiedlich sein.

Wert: Die Bitmap‑Daten.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Liest oder setzt Bitmap‑Daten BitmapData (variabel): Variable‑Länge‑Daten, die das im Feld Type angegebene Bitmap‑Datenobjekt definieren. Inhalt und Format der Daten können für jeden Bitmap‑Typ unterschiedlich sein.

Wert: Die Bitmap‑Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt die Bitmap‑Höhe Height (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Höhe in Pixeln des von der Bitmap belegten Bereichs angibt. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Die Höhe.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt die Bitmap‑Höhe Height (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Höhe in Pixeln des von der Bitmap belegten Bereichs angibt. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Die Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Liest oder setzt das Pixel‑Format PixelFormat (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die das Format der Pixel angibt, aus denen das Bitmap‑Bild besteht. Die unterstützten Pixelformate sind in der `EmfPlusPixelFormat`‑Aufzählung (Abschnitt 2.1.1.25) angegeben. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Das Pixelformat.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Liest oder setzt das Pixel‑Format PixelFormat (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die das Format der Pixel angibt, aus denen das Bitmap‑Bild besteht. Die unterstützten Pixelformate sind in der `EmfPlusPixelFormat`‑Aufzählung (Abschnitt 2.1.1.25) angegeben. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Das Pixelformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Liest oder setzt die Zeilenlänge (Stride) des Bildes (4 Byte): Eine 32‑Bit‑signed‑Integer, die den Byte‑Versatz zwischen dem Beginn einer Scan‑Zeile und der nächsten angibt. Dieser Wert ist die Anzahl der Bytes pro Pixel, die im Feld PixelFormat angegeben ist, multipliziert mit der Breite in Pixeln, die im Feld Width angegeben ist. Der Wert dieses Feldes MUSS ein Vielfaches von vier sein. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Die Zeilenlänge.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Liest oder setzt die Zeilenlänge (Stride) des Bildes (4 Byte): Eine 32‑Bit‑signed‑Integer, die den Byte‑Versatz zwischen dem Beginn einer Scan‑Zeile und der nächsten angibt. Dieser Wert ist die Anzahl der Bytes pro Pixel, die im Feld PixelFormat angegeben ist, multipliziert mit der Breite in Pixeln, die im Feld Width angegeben ist. Der Wert dieses Feldes MUSS ein Vielfaches von vier sein. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Die Zeilenlänge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getType() {#getType--}
```
public int getType()
```


Liest oder setzt den Bildtyp Type (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die den Datentyp im Feld BitmapData angibt. Dieser Wert MUSS in der `EmfPlusBitmapDataType`‑Aufzählung (Abschnitt 2.1.1.2) definiert sein.

Wert: Der Typ.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Liest oder setzt den Bildtyp Type (4 Byte): Eine 32‑Bit‑unsigned‑Integer, die den Datentyp im Feld BitmapData angibt. Dieser Wert MUSS in der `EmfPlusBitmapDataType`‑Aufzählung (Abschnitt 2.1.1.2) definiert sein.

Wert: Der Typ.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder setzt die Bildbreite Width (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Breite in Pixeln des von der Bitmap belegten Bereichs angibt. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Die Breite.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder setzt die Bildbreite Width (4 Byte): Eine 32‑Bit‑signed‑Integer, die die Breite in Pixeln des von der Bitmap belegten Bereichs angibt. Wenn das Bild gemäß dem Feld Type komprimiert ist, ist dieser Wert undefiniert und MUSS ignoriert werden.

Wert: Die Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

