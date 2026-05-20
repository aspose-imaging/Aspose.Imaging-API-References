---
title: "EmfExtFloodFill"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EXTFLOODFILL‑Datensatz füllt einen Bereich der Anzeigeoberfläche mit dem aktuellen Pinsel."
type: docs
weight: 54
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

Der EMR\_EXTFLOODFILL-Datensatz füllt einen Bereich der Anzeigefläche mit dem aktuellen Pinsel.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfExtFloodFill`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStart()](#getStart--) | Liest oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Koordinaten in logischen Einheiten angibt, an denen das Füllen beginnt. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Liest oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Koordinaten in logischen Einheiten angibt, an denen das Füllen beginnt. |
| [getArgb32Color()](#getArgb32Color--) | Liest oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8) fest, das zusammen mit dem FloodFillMode verwendet wird, um den zu füllenden Bereich zu bestimmen. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Liest oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8) fest, das zusammen mit dem FloodFillMode verwendet wird, um den zu füllenden Bereich zu bestimmen. |
| [getFloodFillMode()](#getFloodFillMode--) | Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die angibt, wie der Farbwert verwendet wird, um den Bereich für die Flood‑Fill‑Operation zu bestimmen. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die angibt, wie der Farbwert verwendet wird, um den Bereich für die Flood‑Fill‑Operation zu bestimmen. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfExtFloodFill`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getStart() {#getStart--}
```
public Point getStart()
```


Liest oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Koordinaten in logischen Einheiten angibt, an denen das Füllen beginnt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Liest oder legt ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) fest, das die Koordinaten in logischen Einheiten angibt, an denen das Füllen beginnt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Liest oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8) fest, das zusammen mit dem FloodFillMode verwendet wird, um den zu füllenden Bereich zu bestimmen.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Liest oder legt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8) fest, das zusammen mit dem FloodFillMode verwendet wird, um den zu füllenden Bereich zu bestimmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die angibt, wie der Farbwert verwendet wird, um den Bereich für die Flood‑Fill‑Operation zu bestimmen. Der Wert MUSS in der FloodFill‑Aufzählung (Abschnitt 2.1.13) enthalten sein.

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die angibt, wie der Farbwert verwendet wird, um den Bereich für die Flood‑Fill‑Operation zu bestimmen. Der Wert MUSS in der FloodFill‑Aufzählung (Abschnitt 2.1.13) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

