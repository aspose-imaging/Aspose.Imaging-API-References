---
title: "EmfRegionDataHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das RegionDataHeader-Objekt beschreibt die Eigenschaften eines RegionData-Objekts."
type: docs
weight: 34
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

Das RegionDataHeader-Objekt beschreibt die Eigenschaften eines RegionData-Objekts.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Liest eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes angibt. |
| [setSize(int value)](#setSize-int-) | Setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes angibt. |
| [getType()](#getType--) | Liest eine 32‑Bit vorzeichenlose Ganzzahl, die den Regionstyp angibt. |
| [setType(int value)](#setType-int-) | Setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Regionstyp angibt. |
| [getCountRects()](#getCountRects--) | Liest eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Rechtecke in dieser Region angibt. |
| [setCountRects(int value)](#setCountRects-int-) | Legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Anzahl der Rechtecke in diesem Bereich angibt. |
| [getRgnSize()](#getRgnSize--) | Liefert eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Rechteckpuffers in Bytes angibt. |
| [setRgnSize(int value)](#setRgnSize-int-) | Legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Größe des Rechteckpuffers in Bytes angibt. |
| [getBounds()](#getBounds--) | Liefert ein 128‑Bit‑WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das die Begrenzungen des Bereichs angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Legt ein 128‑Bit‑WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19) fest, das die Begrenzungen des Bereichs angibt. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Liefert eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes angibt. Dies MUSS 0x00000020 sein.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Größe dieses Objekts in Bytes angibt. Dies MUSS 0x00000020 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getType() {#getType--}
```
public int getType()
```


Liefert eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Regionstyp angibt. Dies SOLLTE RDH\_RECTANGLES (0x00000001) sein.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den Regionstyp angibt. Dies SOLLTE RDH\_RECTANGLES (0x00000001) sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Liest eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Rechtecke in dieser Region angibt.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Anzahl der Rechtecke in diesem Bereich angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Liefert eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Rechteckpuffers in Bytes angibt.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Größe des Rechteckpuffers in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liefert ein 128‑Bit‑WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das die Begrenzungen des Bereichs angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Legt ein 128‑Bit‑WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19) fest, das die Begrenzungen des Bereichs angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

