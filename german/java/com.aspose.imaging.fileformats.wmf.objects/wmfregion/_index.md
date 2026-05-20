---
title: "WmfRegion"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Region-Objekt definiert eine potenziell nicht-rechtwinklige Form, die durch ein Array von Scanlines definiert wird."
type: docs
weight: 62
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

Das Region-Objekt definiert eine potenziell nicht-rechtwinklige Form, die durch ein Array von Scanlines definiert wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Liest oder setzt das nächste Element in der Kette. |
| [setNextInChain(short value)](#setNextInChain-short-) | Liest oder setzt das nächste Element in der Kette. |
| [getObjectType()](#getObjectType--) | Ruft den Typ des Objekts ab oder legt ihn fest. |
| [setObjectType(short value)](#setObjectType-short-) | Ruft den Typ des Objekts ab oder legt ihn fest. |
| [getObjectCount()](#getObjectCount--) | Liest oder setzt die Objektanzahl. |
| [setObjectCount(int value)](#setObjectCount-int-) | Liest oder setzt die Objektanzahl. |
| [getRegionSize()](#getRegionSize--) | Liest oder setzt die Größe der Region. |
| [setRegionSize(short value)](#setRegionSize-short-) | Liest oder setzt die Größe der Region. |
| [getScanCount()](#getScanCount--) | Liest oder setzt die Scan-Anzahl. |
| [setScanCount(short value)](#setScanCount-short-) | Liest oder setzt die Scan-Anzahl. |
| [getMaxScan()](#getMaxScan--) | Liest oder setzt den maximalen Scan. |
| [setMaxScan(short value)](#setMaxScan-short-) | Liest oder setzt den maximalen Scan. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Liest oder setzt das Begrenzungsrechteck. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Liest oder setzt das Begrenzungsrechteck. |
| [getAScans()](#getAScans--) | Liest oder setzt einen Scan. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Liest oder setzt einen Scan. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Liest oder setzt das nächste Element in der Kette.

Wert: Ein Wert, der MUST ignoriert werden muss.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Liest oder setzt das nächste Element in der Kette.

Wert: Ein Wert, der MUST ignoriert werden muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Ruft den Typ des Objekts ab oder legt ihn fest.

Wert: Der Regionsbezeichner. Er MUST 0x0006 sein.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Ruft den Typ des Objekts ab oder legt ihn fest.

Wert: Der Regionsbezeichner. Er MUST 0x0006 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Liest oder setzt die Objektanzahl.

Wert: Ein Wert, der MUST ignoriert werden muss.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Liest oder setzt die Objektanzahl.

Wert: Ein Wert, der MUST ignoriert werden muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Liest oder setzt die Größe der Region.

Wert: Die Größe der Region in Bytes plus die Größe von aScans in Bytes.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Liest oder setzt die Größe der Region.

Wert: Die Größe der Region in Bytes plus die Größe von aScans in Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Liest oder setzt die Scan-Anzahl.

Wert: Die Anzahl der Scanlinien, die die Region bilden.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Liest oder setzt die Scan-Anzahl.

Wert: Die Anzahl der Scanlinien, die die Region bilden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Liest oder setzt den maximalen Scan.

Wert: Die maximale Anzahl von Punkten in einem einzelnen Scan in dieser Region.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Liest oder setzt den maximalen Scan.

Wert: Die maximale Anzahl von Punkten in einem einzelnen Scan in dieser Region.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Liest oder setzt das Begrenzungsrechteck.

Wert: Ein Rect-Objekt (Abschnitt 2.2.2.18), das das Begrenzungsrechteck definiert.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Liest oder setzt das Begrenzungsrechteck.

Wert: Ein Rect-Objekt (Abschnitt 2.2.2.18), das das Begrenzungsrechteck definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Liest oder setzt einen Scan.

Wert: Ein Array von Scan-Objekten (Abschnitt 2.2.2.21), das die Scanlinien in der Region definiert.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Liest oder setzt einen Scan.

Wert: Ein Array von Scan-Objekten (Abschnitt 2.2.2.21), das die Scanlinien in der Region definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

