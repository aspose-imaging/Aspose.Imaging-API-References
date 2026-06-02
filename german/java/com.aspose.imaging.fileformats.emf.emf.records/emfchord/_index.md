---
title: "EmfChord"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CHORD‑Datensatz spezifiziert einen Akkord, der ein Gebiet ist, das durch die Schnittmenge einer Ellipse und eines Liniensegments, das Sekante genannt wird, begrenzt wird."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

Der EMR\_CHORD‑Datensatz spezifiziert einen Akkord, der ein Gebiet ist, das durch die Schnittmenge einer Ellipse und eines Liniensegments, genannt Sekante, begrenzt wird. Der Akkord wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel gefüllt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfChord` Klasse. |
| [EmfChord()](#EmfChord--) | Initialisiert eine neue Instanz der `EmfChord` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBox()](#getBox--) | Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ruft ein 128‑Bit‑WMF‑RectL‑Objekt ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und das inklusiv‑inklusiv begrenzende Rechteck definiert. |
| [getStart()](#getStart--) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Endpunkts des Strahls, der den Beginn des Akkords definiert, angibt. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Endpunkts des Strahls, der den Beginn des Akkords definiert, angibt. |
| [getEnd()](#getEnd--) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die logischen Koordinaten des Endpunkts des Strahls, der das Ende des Akkords definiert, angibt. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die logischen Koordinaten des Endpunkts des Strahls, der das Ende des Akkords definiert, angibt. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfChord` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


Initialisiert eine neue Instanz der `EmfChord` Klasse.

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


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Endpunkts des Strahls, der den Beginn des Akkords definiert, angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Endpunkts des Strahls, der den Beginn des Akkords definiert, angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die logischen Koordinaten des Endpunkts des Strahls, der das Ende des Akkords definiert, angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die logischen Koordinaten des Endpunkts des Strahls, der das Ende des Akkords definiert, angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

