---
title: "EmfPlgBlt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_PLGBLT‑Datensatz gibt einen Blocktransfer von Pixeln von einer Quell‑Bitmap zu einem Ziel‑Parallelogramm mit Anwendung einer Farbmasken‑Bitmap an."
type: docs
weight: 84
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

Der EMR\\_PLGBLT-Datensatz spezifiziert einen Blocktransfer von Pixeln von einer Quell-Bitmap zu einem Zielparallelogramm, unter Anwendung einer Farbmasken-Bitmap.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPlgBlt`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten für die Ausgabe zum Ziel definiert. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten für die Ausgabe zum Ziel definiert. |
| [getAptlDest()](#getAptlDest--) | Liest oder setzt ein Array von drei WMF PointL-Objekten ([MS-WMF] Abschnitt 2.2.2.15), das drei Ecken eines Parallelogramms für das Zielgebiet der Blockübertragung angibt. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | Liest oder setzt ein Array von drei WMF PointL-Objekten ([MS-WMF] Abschnitt 2.2.2.15), das drei Ecken eines Parallelogramms für das Zielgebiet der Blockübertragung angibt. |
| [getXSrc()](#getXSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [setXSrc(int value)](#setXSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [getYSrc()](#getYSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [setYSrc(int value)](#setYSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [getCxSrc()](#getCxSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Quellrechtecks angibt. |
| [setCxSrc(int value)](#setCxSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Quellrechtecks angibt. |
| [getCySrc()](#getCySrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Quellrechtecks angibt. |
| [setCySrc(int value)](#setCySrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Quellrechtecks angibt. |
| [getXFormSrc()](#getXFormSrc--) | Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Liest oder setzt ein WMF ColorRef-Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die Hintergrundfarbe der Quell-Bitmap angibt. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Liest oder setzt ein WMF ColorRef-Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die Hintergrundfarbe der Quell-Bitmap angibt. |
| [getUsageSrc()](#getUsageSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [getXMask()](#getXMask--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische X‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [setXMask(int value)](#setXMask-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische X‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [getYMask()](#getYMask--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [setYMask(int value)](#setYMask-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [getUsageMask()](#getUsageMask--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Masken‑Bitmap zu interpretieren sind. |
| [setUsageMask(int value)](#setUsageMask-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Masken‑Bitmap zu interpretieren sind. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder setzt einen Puffer, der die Quell-Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt einen Puffer, der die Quell-Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. |
| [getMaskBitmap()](#getMaskBitmap--) | Liest oder setzt einen Puffer, der die Masken-Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt einen Puffer, der die Masken-Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPlgBlt`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten für die Ausgabe zum Ziel definiert.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten für die Ausgabe zum Ziel definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


Liest oder setzt ein Array von drei WMF PointL-Objekten ([MS-WMF] Abschnitt 2.2.2.15), das drei Ecken eines Parallelogramms für das Zielgebiet der Blockübertragung angibt. Die obere linke Ecke des Quellrechtecks wird dem ersten Punkt dieses Arrays zugeordnet, die obere rechte Ecke dem zweiten Punkt und die untere linke Ecke dem dritten Punkt. Die untere rechte Ecke des Quellrechtecks wird dem impliziten vierten Punkt im Parallelogramm zugeordnet, der aus den ersten drei Punkten (A, B und C) als Vektoren berechnet wird. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


Liest oder setzt ein Array von drei WMF PointL-Objekten ([MS-WMF] Abschnitt 2.2.2.15), das drei Ecken eines Parallelogramms für das Zielgebiet der Blockübertragung angibt. Die obere linke Ecke des Quellrechtecks wird dem ersten Punkt dieses Arrays zugeordnet, die obere rechte Ecke dem zweiten Punkt und die untere linke Ecke dem dritten Punkt. Die untere rechte Ecke des Quellrechtecks wird dem impliziten vierten Punkt im Parallelogramm zugeordnet, der aus den ersten drei Punkten (A, B und C) als Vektoren berechnet wird. D = B + C A

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

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

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Quellrechtecks angibt.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Quellrechtecks angibt.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
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


Liest oder setzt ein WMF ColorRef-Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die Hintergrundfarbe der Quell-Bitmap angibt.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Liest oder setzt ein WMF ColorRef-Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die Hintergrundfarbe der Quell-Bitmap angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Quell‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung liegen.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Quell‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXMask() {#getXMask--}
```
public int getXMask()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische X‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische X‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Masken‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der Aufzählung DIBColors liegen.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Masken‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der Aufzählung DIBColors liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Liest oder setzt einen Puffer, der die Masken‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der die Masken‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_PLGBLT‑Datensatzes oder untereinander sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

