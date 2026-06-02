---
title: "WmfSetDibToDev"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_SETDIBTODEV-Datensatz setzt einen Block von Pixeln im Wiedergabe‑Geräte‑Kontext mithilfe von geräteunabhängigen Farbdaten."
type: docs
weight: 75
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

Der META\_SETDIBTODEV-Datensatz setzt einen Block von Pixeln im Wiedergabe‑Geräte‑Kontext mithilfe von geräteunabhängigen Farbdaten. Die Quelle der Farbdaten ist ein DIB.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Liest oder setzt die Farbnutzung. |
| [setColorUsage(int value)](#setColorUsage-int-) | Liest oder setzt die Farbnutzung. |
| [getScanCount()](#getScanCount--) | Liest oder setzt die Scan-Anzahl. |
| [setScanCount(int value)](#setScanCount-int-) | Liest oder setzt die Scan-Anzahl. |
| [getStartScan()](#getStartScan--) | Liest oder setzt den Start‑Scan. |
| [setStartScan(int value)](#setStartScan-int-) | Liest oder setzt den Start‑Scan. |
| [getDibPos()](#getDibPos--) | Liest oder setzt die DIB‑Position. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | Liest oder setzt die DIB‑Position. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt die Höhe. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite. |
| [setWidth(int value)](#setWidth-int-) | Liest oder setzt die Breite. |
| [getDestPos()](#getDestPos--) | Liest oder setzt die Ziel‑Position. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | Liest oder setzt die Ziel‑Position. |
| [getDib()](#getDib--) | Liest oder setzt die DIB. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt die DIB. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Liest oder setzt die Farbnutzung.

Wert: Das Colors‑Feld der DIB enthält explizite RGB‑Werte oder Indizes in eine Palette. Dies MUST einer der Werte in der `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage`‑Aufzählung (Abschnitt 2.1.1.6) sein.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Liest oder setzt die Farbnutzung.

Wert: Das Colors‑Feld der DIB enthält explizite RGB‑Werte oder Indizes in eine Palette. Dies MUST einer der Werte in der `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage`‑Aufzählung (Abschnitt 2.1.1.6) sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Liest oder setzt die Scan-Anzahl.

Wert: Die Anzahl der Scanlinien in der Quelle.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Liest oder setzt die Scan-Anzahl.

Wert: Die Anzahl der Scanlinien in der Quelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Liest oder setzt den Start‑Scan.

Wert: Die startende Scanlinie in der Quelle.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Liest oder setzt den Start‑Scan.

Wert: Die startende Scanlinie in der Quelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


Liest oder setzt die DIB‑Position.

Wert: Die Koordinaten des Quellrechtecks in logischen Einheiten.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


Liest oder setzt die DIB‑Position.

Wert: Die Koordinaten des Quellrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt die Höhe.

Wert: Die Höhe des Quell- und Zielrechtecks in logischen Einheiten.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt die Höhe.

Wert: Die Höhe des Quell- und Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder setzt die Breite.

Wert: Die Breite des Quell- und Zielrechtecks in logischen Einheiten.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder setzt die Breite.

Wert: Die Breite des Quell- und Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


Liest oder setzt die Ziel‑Position.

Wert: Die Koordinaten der oberen linken Ecke des Zielrechtecks in logischen Einheiten.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


Liest oder setzt die Ziel‑Position.

Wert: Die Koordinaten der oberen linken Ecke des Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


Liest oder setzt die DIB.

Wert: Die y‑Koordinate, in logischen Einheiten, der oberen linken Ecke des Zielrechtecks.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


Liest oder setzt die DIB.

Wert: Die y‑Koordinate, in logischen Einheiten, der oberen linken Ecke des Zielrechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

