---
title: "EmfFrameRgn"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_FRAMERGN-Datensatz zeichnet einen Rahmen um die angegebene Region mit dem angegebenen Pinsel."
type: docs
weight: 62
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

Der EMR\_FRAMERGN-Datensatz zeichnet einen Rahmen um die angegebene Region mit dem angegebenen Pinsel.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfFrameRgn`-Klasse. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Initialisiert eine neue Instanz der [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [getRgnDataSize()](#getRgnDataSize--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt. |
| [getIhBrush()](#getIhBrush--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Index des Pinsel‑EMF‑Objekttabellen‑Eintrags angibt. |
| [setIhBrush(int value)](#setIhBrush-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Index des Pinsel‑EMF‑Objekttabellen‑Eintrags angibt. |
| [getWidth()](#getWidth--) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Breite des vertikalen Pinselstrichs in logischen Einheiten angibt. |
| [setWidth(int value)](#setWidth-int-) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Breite des vertikalen Pinselstrichs in logischen Einheiten angibt. |
| [getHeight()](#getHeight--) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Höhe des horizontalen Pinselstrichs in logischen Einheiten angibt. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Höhe des horizontalen Pinselstrichs in logischen Einheiten angibt. |
| [getRgnData()](#getRgnData--) | Liest oder setzt ein RgnDataSize‑länges Byte‑Array, das ein RegionData‑Objekt in logischen Einheiten angibt |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Liest oder setzt ein RgnDataSize‑länges Byte‑Array, das ein RegionData‑Objekt in logischen Einheiten angibt |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfFrameRgn`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Initialisiert eine neue Instanz der [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn)-Klasse.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Index des Pinsel‑EMF‑Objekttabellen‑Eintrags angibt.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Index des Pinsel‑EMF‑Objekttabellen‑Eintrags angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Breite des vertikalen Pinselstrichs in logischen Einheiten angibt.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Breite des vertikalen Pinselstrichs in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Höhe des horizontalen Pinselstrichs in logischen Einheiten angibt.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Höhe des horizontalen Pinselstrichs in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Liest oder setzt ein RgnDataSize‑länges Byte‑Array, das ein RegionData‑Objekt in logischen Einheiten angibt

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Liest oder setzt ein RgnDataSize‑länges Byte‑Array, das ein RegionData‑Objekt in logischen Einheiten angibt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

