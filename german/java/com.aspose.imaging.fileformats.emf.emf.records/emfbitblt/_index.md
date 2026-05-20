---
title: "EmfBitBlt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_BITBLT‑Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinsel‑Muster gemäß einer angegebenen Rasteroperation."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfBitBlt extends EmfBitmapRecordType
```

Der EMR\_BITBLT-Datensatz gibt eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfBitBlt(EmfRecord source)](#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfBitBlt`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [getXDest()](#getXDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setXDest(int value)](#setXDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getYDest()](#getYDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setYDest(int value)](#setYDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getCxDest()](#getCxDest--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Breite der Quell‑ und Zielrechtecke angibt. |
| [setCxDest(int value)](#setCxDest-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Breite der Quell‑ und Zielrechtecke angibt. |
| [getCyDest()](#getCyDest--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Höhe der Quell‑ und Zielrechtecke angibt. |
| [setCyDest(int value)](#setCyDest-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Höhe der Quell‑ und Zielrechtecke angibt. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Rasteroperationscode angibt. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Rasteroperationscode angibt. |
| [getXSrc()](#getXSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [setXSrc(int value)](#setXSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [getYSrc()](#getYSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [setYSrc(int value)](#setYSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [getXformSrc()](#getXformSrc--) | Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt. |
| [getUsageSrc()](#getUsageSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_BITBLT‑Datensatzes sein muss. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_BITBLT‑Datensatzes sein muss. |
### EmfBitBlt(EmfRecord source) {#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfBitBlt(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfBitBlt`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Breite der Quell‑ und Zielrechtecke angibt.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Breite der Quell‑ und Zielrechtecke angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Höhe der Quell‑ und Zielrechtecke angibt.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Höhe der Quell‑ und Zielrechtecke angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Rasteroperationscode angibt. Dieser Code definiert, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinsel‑Muster kombiniert werden, um die endgültige Farbe zu erzeugen.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Rasteroperationscode angibt. Dieser Code definiert, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinsel‑Muster kombiniert werden, um die endgültige Farbe zu erzeugen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt.

Wert: Die 32‑Bit‑ARGB‑Farbe

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_BITBLT‑Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_BITBLT‑Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

