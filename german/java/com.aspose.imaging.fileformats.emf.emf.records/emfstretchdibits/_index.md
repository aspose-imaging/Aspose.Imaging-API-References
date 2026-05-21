---
title: "EmfStretchDiBits"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_STRETCHDIBITS‑Datensatz gibt einen Blocktransfer von Pixeln von einem Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster gemäß einer angegebenen Rasteroperation, wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels anzupassen."
type: docs
weight: 150
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

Der EMR\_STRETCHDIBITS-Datensatz gibt eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation, wobei die Ausgabe gedehnt oder komprimiert wird, um die Abmessungen des Ziels zu passen, falls erforderlich.

Dieser Datensatz unterstützt Quellbilder im JPEG‑ und PNG‑Format. Das Feld Compression im Header des Quell‑Bitmaps gibt das Bildformat an. Wenn die Vorzeichen der Höhen‑ und Breitenfelder von Quelle und Ziel unterschiedlich sind, gibt dieser Datensatz eine spiegelverkehrte Kopie des Quell‑Bitmaps zum Ziel an. Das bedeutet, wenn cxSrc und cxDest unterschiedliche Vorzeichen haben, wird ein Spiegelbild des Quell‑Bitmaps entlang der x‑Achse angegeben. Wenn cySrc und cyDest unterschiedliche Vorzeichen haben, wird ein Spiegelbild des Quell‑Bitmaps entlang der y‑Achse angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfStretchDiBits`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [getXDest()](#getXDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setXDest(int value)](#setXDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getYDest()](#getYDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setYDest(int value)](#setYDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getXSrc()](#getXSrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt. |
| [setXSrc(int value)](#setXSrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt. |
| [getYSrc()](#getYSrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt. |
| [setYSrc(int value)](#setYSrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt. |
| [getCxSrc()](#getCxSrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Breite in Pixeln des Quellrechtecks angibt. |
| [setCxSrc(int value)](#setCxSrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Breite in Pixeln des Quellrechtecks angibt. |
| [getCySrc()](#getCySrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des Quellrechtecks angibt. |
| [setCySrc(int value)](#setCySrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des Quellrechtecks angibt. |
| [getUsageSrc()](#getUsageSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Rasteroperationscode angibt. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Rasteroperationscode angibt. |
| [getCxDest()](#getCxDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Zielrechtecks angibt. |
| [setCxDest(int value)](#setCxDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Breite des Zielrechtecks angibt. |
| [getCyDest()](#getCyDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Zielrechtecks angibt. |
| [setCyDest(int value)](#setCyDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische Höhe des Zielrechtecks angibt. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder setzt einen Puffer, der das Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_STRETCHDIBITS‑Datensatzes sein muss. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt einen Puffer, der das Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_STRETCHDIBITS‑Datensatzes sein muss. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfStretchDiBits`‑Klasse.

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

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der oberen linken Ecke des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Breite in Pixeln des Quellrechtecks angibt.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Breite in Pixeln des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des Quellrechtecks angibt.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des Quellrechtecks angibt.

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

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Rasteroperationscode angibt. Diese Codes definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinselmuster kombiniert werden, um die endgültige Farbe zu erhalten.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Rasteroperationscode angibt. Diese Codes definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinselmuster kombiniert werden, um die endgültige Farbe zu erhalten.

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Liest oder setzt einen Puffer, der das Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_STRETCHDIBITS‑Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der das Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_STRETCHDIBITS‑Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

