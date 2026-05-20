---
title: "EmfMaskBlt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_MASKBLT‑Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster und mit der Anwendung einer Farbmasken‑Bitmap gemäß den angegebenen Vorder‑ und Hintergrund‑Rasteroperationen."
type: docs
weight: 69
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

Der EMR\_MASKBLT-Datensatz gibt einen Blocktransfer von Pixeln von einer Quell-Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster und unter Anwendung einer Farbmasken-Bitmap, gemäß den angegebenen Vorder- und Hintergrundrasteroperationen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfMaskBlt`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [getXDest()](#getXDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setXDest(int value)](#setXDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getYDest()](#getYDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setYDest(int value)](#setYDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getCxDest()](#getCxDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Zielrechtecks angibt. |
| [setCxDest(int value)](#setCxDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Zielrechtecks angibt. |
| [getCyDest()](#getCyDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Zielrechtecks angibt. |
| [setCyDest(int value)](#setCyDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Zielrechtecks angibt. |
| [getRop4()](#getRop4--) | Liest oder setzt eine vierstufige Rasteroperation, die ternäre Rasteroperationen für die Vorder‑ und Hintergrundfarben einer Bitmap festlegt. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | Liest oder setzt eine vierstufige Rasteroperation, die ternäre Rasteroperationen für die Vorder‑ und Hintergrundfarben einer Bitmap festlegt. |
| [getXSrc()](#getXSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [setXSrc(int value)](#setXSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [getYSrc()](#getYSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [setYSrc(int value)](#setYSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Quellrechtecks angibt. |
| [getXformSrc()](#getXformSrc--) | Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Liest oder setzt ein XForm object (Abschnitt 2.2.28), das eine Welt‑zu‑Seiten‑Transformation für das Quell‑Bitmap angibt. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt. |
| [getUsageSrc()](#getUsageSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [getXMask()](#getXMask--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische X‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [setXMask(int value)](#setXMask-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische X‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [getYMask()](#getYMask--) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [setYMask(int value)](#setYMask-int-) | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die logische Y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| [getUsageMask()](#getUsageMask--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Masken‑Bitmap zu interpretieren sind. |
| [setUsageMask(int value)](#setUsageMask-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im Header der Masken‑Bitmap zu interpretieren sind. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder setzt einen Puffer, der die Quell‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt einen Puffer, der die Quell‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. |
| [getMaskBitmap()](#getMaskBitmap--) | Liest oder setzt einen Puffer, der die Masken‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt einen Puffer, der die Masken‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfMaskBlt`‑Klasse.

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


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Zielrechtecks angibt.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Zielrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Zielrechtecks angibt.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Zielrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


Liest oder setzt eine vierstufige Rasteroperation, die ternäre Rasteroperationen für die Vorder‑ und Hintergrundfarben einer Bitmap festlegt. Diese Werte definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks kombiniert werden.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


Liest oder setzt eine vierstufige Rasteroperation, die ternäre Rasteroperationen für die Vorder‑ und Hintergrundfarben einer Bitmap festlegt. Diese Werte definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks kombiniert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

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

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


Liest oder setzt ein WMF ColorRef object ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe des Quell‑Bitmaps angibt.

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


Liest oder setzt einen Puffer, der die Quell‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der die Quell‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Liest oder setzt einen Puffer, der die Masken‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der die Masken‑Bitmaps enthält, die nicht zwingend zusammenhängend mit dem festen Teil des EMR\\_MASKBLT‑Datensatzes oder untereinander sein müssen. Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

