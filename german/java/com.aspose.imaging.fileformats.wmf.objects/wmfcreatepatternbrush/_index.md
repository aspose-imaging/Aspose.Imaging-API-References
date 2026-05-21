---
title: "WmfCreatePatternBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_CREATEPATTERNBRUSH-Datensatz erstellt ein Pinselobjekt mit einem Muster, das durch ein Bitmap angegeben wird."
type: docs
weight: 23
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

Der META\_CREATEPATTERNBRUSH-Datensatz erstellt ein Pinselobjekt mit einem Muster, das durch eine Bitmap angegeben wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs der Datensatz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitmap()](#getBitmap--) | Liest oder setzt das Bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Liest oder setzt das Bitmap. |
| [getReserved()](#getReserved--) | Liest oder setzt das Reservierte. |
| [setReserved(byte[] value)](#setReserved-byte---) | Liest oder setzt das Reservierte. |
| [getPattern()](#getPattern--) | Liest oder setzt das Muster. |
| [setPattern(byte[] value)](#setPattern-byte---) | Liest oder setzt das Muster. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs der Datensatz.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Liest oder setzt das Bitmap.

Wert: Das Bitmap, das das Muster für den Pinsel angibt.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Liest oder setzt das Bitmap.

Wert: Das Bitmap, das das Muster für den Pinsel angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Liest oder setzt das Reservierte.

Wert: Der reservierte Teil. Dieses Feld MUSS ignoriert werden.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Liest oder setzt das Reservierte.

Wert: Der reservierte Teil. Dieses Feld MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Liest oder setzt das Muster.

Wert: Ein variabel langes Byte-Array, das die Bitmap-Pixeldaten definiert, aus denen das Pinsel-Muster besteht. Die Länge dieses Feldes in Bytes kann aus den Bitmap-Parametern wie folgt berechnet werden.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Liest oder setzt das Muster.

Wert: Ein variabel langes Byte-Array, das die Bitmap-Pixeldaten definiert, aus denen das Pinsel-Muster besteht. Die Länge dieses Feldes in Bytes kann aus den Bitmap-Parametern wie folgt berechnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

