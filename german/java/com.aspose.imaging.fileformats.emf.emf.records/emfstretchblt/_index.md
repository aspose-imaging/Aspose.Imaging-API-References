---
title: "EmfStretchBlt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_STRETCHBLT‑Datensatz definiert einen Blocktransfer von Pixeln von einem Quell‑Bitmap zu einem Zielrechteck, optional in Kombination mit einem Pinsel‑Muster gemäß einer angegebenen Rasteroperation, wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels anzupassen."
type: docs
weight: 149
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchBlt extends EmfBitmapRecordType
```

Der EMR\_STRETCHBLT-Datensatz gibt eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation, wobei die Ausgabe gedehnt oder komprimiert wird, um die Abmessungen des Ziels zu passen, falls erforderlich.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfStretchBlt(EmfRecord source)](#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfStretchBlt`‑Klasse. |
| [EmfStretchBlt()](#EmfStretchBlt--) | Initialisiert eine neue Instanz der `EmfStretchBlt`‑Klasse. |
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
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Rasteroperationscode angibt. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Rasteroperationscode angibt. |
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
| [getCxSrc()](#getCxSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Quellrechtecks angibt. |
| [setCxSrc(int value)](#setCxSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Quellrechtecks angibt. |
| [getCySrc()](#getCySrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Quellrechtecks angibt. |
| [setCySrc(int value)](#setCySrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Quellrechtecks angibt. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder schreibt einen Puffer, der das Quell‑Bitmap enthält, wobei er nicht zusammenhängend mit dem festen Teil des EMR\_STRETCHBLT‑Datensatzes sein muss. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder schreibt einen Puffer, der das Quell‑Bitmap enthält, wobei er nicht zusammenhängend mit dem festen Teil des EMR\_STRETCHBLT‑Datensatzes sein muss. |
| [getSrcRect()](#getSrcRect--) | Liest oder schreibt das Quell‑Rechteck. |
| [setSrcRect(Rectangle value)](#setSrcRect-com.aspose.imaging.Rectangle-) | Liest oder schreibt das Quell‑Rechteck. |
| [getDestRect()](#getDestRect--) | Liest oder schreibt das Ziel‑Rechteck. |
| [setDestRect(Rectangle value)](#setDestRect-com.aspose.imaging.Rectangle-) | Liest oder schreibt das Ziel‑Rechteck. |
### EmfStretchBlt(EmfRecord source) {#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchBlt(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfStretchBlt`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfStretchBlt() {#EmfStretchBlt--}
```
public EmfStretchBlt()
```


Initialisiert eine neue Instanz der `EmfStretchBlt`‑Klasse.

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

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Rasteroperation‑Code angibt. Dieser Code definiert, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinsel‑Muster kombiniert werden, um die endgültige Farbe zu erhalten.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Rasteroperation‑Code angibt. Dieser Code definiert, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinsel‑Muster kombiniert werden, um die endgültige Farbe zu erhalten.

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Liest oder schreibt einen Puffer, der das Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_STRETCHBLT‑Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder schreibt einen Puffer, der das Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_STRETCHBLT‑Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getSrcRect() {#getSrcRect--}
```
public Rectangle getSrcRect()
```


Liest oder schreibt das Quell‑Rechteck.

Wert: Das Quell‑Rechteck.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setSrcRect(Rectangle value) {#setSrcRect-com.aspose.imaging.Rectangle-}
```
public void setSrcRect(Rectangle value)
```


Liest oder schreibt das Quell‑Rechteck.

Wert: Das Quell‑Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getDestRect() {#getDestRect--}
```
public Rectangle getDestRect()
```


Liest oder schreibt das Ziel‑Rechteck.

Wert: Das Zielrechteck.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setDestRect(Rectangle value) {#setDestRect-com.aspose.imaging.Rectangle-}
```
public void setDestRect(Rectangle value)
```


Liest oder schreibt das Ziel‑Rechteck.

Wert: Das Zielrechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

