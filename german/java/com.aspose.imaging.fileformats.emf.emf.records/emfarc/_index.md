---
title: "EmfArc"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_ARC‑Datensatz gibt einen elliptischen Bogen an."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArc extends EmfDrawingRecordType
```

Der EMR\_ARC-Datensatz gibt einen elliptischen Bogen an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfArc(EmfRecord source)](#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfArc`‑Klasse. |
| [EmfArc()](#EmfArc--) | Initialisiert eine neue Instanz der `EmfArc`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBox()](#getBox--) | Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert. |
| [getStart()](#getStart--) | Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.15 angegeben ist und die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Startpunkt des Bogens definiert. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.15 angegeben ist und die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Startpunkt des Bogens definiert. |
| [getEnd()](#getEnd--) | Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Endpunkt des Bogens definiert. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Endpunkt des Bogens definiert. |
### EmfArc(EmfRecord source) {#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArc(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfArc`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfArc() {#EmfArc--}
```
public EmfArc()
```


Initialisiert eine neue Instanz der `EmfArc`‑Klasse.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.15 angegeben ist und die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Startpunkt des Bogens definiert.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.15 angegeben ist und die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Startpunkt des Bogens definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Endpunkt des Bogens definiert.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Ruft ein 64‑Bit‑WMF‑PointL‑Objekt ab oder legt es fest, das die Koordinaten (in logischen Einheiten) des Endpunkts der radialen Linie angibt, die den Endpunkt des Bogens definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

