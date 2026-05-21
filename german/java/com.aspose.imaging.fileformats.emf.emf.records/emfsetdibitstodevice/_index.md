---
title: "EmfSetDiBitsToDevice"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETDIBITSTODEVICE-Datensatz gibt einen Blocktransfer von Pixeln von angegebenen Scanlinien einer Quell‑Bitmap zu einem Zielrechteck an."
type: docs
weight: 124
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

Der EMR\_SETDIBITSTODEVICE-Datensatz spezifiziert einen Blocktransfer von Pixeln von angegebenen Scan‑Zeilen einer Quell‑Bitmap zu einem Ziel‑Rechteck.

Dieser Datensatz unterstützt Quellbilder im JPEG‑ und PNG‑Format. Das Kompressionsfeld im Header der Quell‑Bitmap gibt das Bildformat an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetDiBitsToDevice`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL object ([MS-WMF] Abschnitt 2.2.2.19), das das Zielbegrenzungsrechteck in Geräte‑Einheiten definiert. |
| [getXDest()](#getXDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setXDest(int value)](#setXDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getYDest()](#getYDest--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [setYDest(int value)](#setYDest-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [getXSrc()](#getXSrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt. |
| [setXSrc(int value)](#setXSrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt. |
| [getYSrc()](#getYSrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt. |
| [setYSrc(int value)](#setYSrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt. |
| [getCxSrc()](#getCxSrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Breite in Pixeln des Quellrechtecks angibt. |
| [setCxSrc(int value)](#setCxSrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Breite in Pixeln des Quellrechtecks angibt. |
| [getCySrc()](#getCySrc--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des Quellrechtecks angibt. |
| [setCySrc(int value)](#setCySrc-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des Quellrechtecks angibt. |
| [getUsageSrc()](#getUsageSrc--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der angibt, wie Werte in der Farbtafel des Quell‑Bitmap‑Headers zu interpretieren sind. |
| [getIStartScan()](#getIStartScan--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die erste Scanlinie im Array angibt. |
| [setIStartScan(int value)](#setIStartScan-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die erste Scanlinie im Array angibt. |
| [getCScans()](#getCScans--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scanlinien angibt. |
| [setCScans(int value)](#setCScans-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scanlinien angibt. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_SETDIBITSTODEVICE-Datensatzes sein muss. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_SETDIBITSTODEVICE-Datensatzes sein muss. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetDiBitsToDevice`‑Klasse.

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


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der linken unteren Ecke des Quellrechtecks angibt.

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

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die erste Scanlinie im Array angibt.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die erste Scanlinie im Array angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scanlinien angibt.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Scanlinien angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_SETDIBITSTODEVICE-Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_SETDIBITSTODEVICE-Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

