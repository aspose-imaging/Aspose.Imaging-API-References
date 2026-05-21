---
title: "WmfScanObject"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Scan-Objekt gibt eine Sammlung von Scanlines an."
type: docs
weight: 69
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

Das Scan-Objekt gibt eine Sammlung von Scanlines an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Liest oder setzt die Anzahl. |
| [setCount(int value)](#setCount-int-) | Liest oder setzt die Anzahl. |
| [getTop()](#getTop--) | Liest oder setzt den oberen Wert. |
| [setTop(int value)](#setTop-int-) | Liest oder setzt den oberen Wert. |
| [getBottom()](#getBottom--) | Liest oder setzt den unteren Wert. |
| [setBottom(int value)](#setBottom-int-) | Liest oder setzt den unteren Wert. |
| [getScanLines()](#getScanLines--) | Liest oder setzt die Scan‑Zeilen. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | Liest oder setzt die Scan‑Zeilen. |
| [getCount2()](#getCount2--) | Liest oder setzt die count2. |
| [setCount2(int value)](#setCount2-int-) | Liest oder setzt die count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


Liest oder setzt die Anzahl.

Wert: Die Anzahl der horizontalen (x‑Achsen‑)Koordinaten im `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`‑Array. Dieser Wert MUSS ein Vielfaches von 2 sein, da linke und rechte Endpunkte für jede Scan‑Zeile angegeben werden müssen.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Liest oder setzt die Anzahl.

Wert: Die Anzahl der horizontalen (x‑Achsen‑)Koordinaten im `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`‑Array. Dieser Wert MUSS ein Vielfaches von 2 sein, da linke und rechte Endpunkte für jede Scan‑Zeile angegeben werden müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Liest oder setzt den oberen Wert.

Wert: Die vertikale (y‑Achsen‑)Koordinate in logischen Einheiten der oberen Scan‑Zeile.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Liest oder setzt den oberen Wert.

Wert: Die vertikale (y‑Achsen‑)Koordinate in logischen Einheiten der oberen Scan‑Zeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Liest oder setzt den unteren Wert.

Wert: Die vertikale (y‑Achsen‑)Koordinate in logischen Einheiten der unteren Scan‑Zeile.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Liest oder setzt den unteren Wert.

Wert: Die vertikale (y‑Achsen‑)Koordinate in logischen Einheiten der unteren Scan‑Zeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


Liest oder setzt die Scan‑Zeilen.

Wert: Ein Array von Scan‑Zeilen, von denen jede durch linke und rechte horizontale (x‑Achsen‑)Koordinaten ihrer Endpunkte angegeben wird.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


Liest oder setzt die Scan‑Zeilen.

Wert: Ein Array von Scan‑Zeilen, von denen jede durch linke und rechte horizontale (x‑Achsen‑)Koordinaten ihrer Endpunkte angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


Liest oder setzt die count2.

Wert: Der gleiche wie der Wert des Feldes `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; er ist vorhanden, um eine Aufwärtsnavigation in der Struktur zu ermöglichen.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


Liest oder setzt die count2.

Wert: Der gleiche wie der Wert des Feldes `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; er ist vorhanden, um eine Aufwärtsnavigation in der Struktur zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

