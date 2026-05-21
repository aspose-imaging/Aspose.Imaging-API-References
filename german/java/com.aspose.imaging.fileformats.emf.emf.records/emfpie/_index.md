---
title: "EmfPie"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_PIE‑Datensatz definiert einen keilförmigen Abschnitt, der durch die Schnittmenge einer Ellipse und zweier Radien begrenzt wird."
type: docs
weight: 82
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

Der EMR\_PIE‑Datensatz definiert einen keilförmigen Abschnitt, der durch die Schnittmenge einer Ellipse und zweier Radien begrenzt wird. Der Keil wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPie`‑Klasse. |
| [EmfPie()](#EmfPie--) | Initialisiert eine neue Instanz der `EmfPie`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBox()](#getBox--) | Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert. |
| [getStart()](#getStart--) | Liest oder schreibt ein 64‑Bit‑WMF‑PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten (in logischen Einheiten) des Endpunkts des ersten Radius angibt. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Liest oder schreibt ein 64‑Bit‑WMF‑PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten (in logischen Einheiten) des Endpunkts des ersten Radius angibt. |
| [getEnd()](#getEnd--) | Liest oder schreibt ein 64‑Bit‑PointL‑Objekt, das die Koordinaten (in logischen Einheiten) des Endpunkts des zweiten Radius angibt. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Liest oder schreibt ein 64‑Bit‑PointL‑Objekt, das die Koordinaten (in logischen Einheiten) des Endpunkts des zweiten Radius angibt. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPie`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


Initialisiert eine neue Instanz der `EmfPie`‑Klasse.

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


Liest oder schreibt ein 64‑Bit‑WMF‑PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten (in logischen Einheiten) des Endpunkts des ersten Radius angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Liest oder schreibt ein 64‑Bit‑WMF‑PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten (in logischen Einheiten) des Endpunkts des ersten Radius angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Liest oder schreibt ein 64‑Bit‑PointL‑Objekt, das die Koordinaten (in logischen Einheiten) des Endpunkts des zweiten Radius angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Liest oder schreibt ein 64‑Bit‑PointL‑Objekt, das die Koordinaten (in logischen Einheiten) des Endpunkts des zweiten Radius angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

