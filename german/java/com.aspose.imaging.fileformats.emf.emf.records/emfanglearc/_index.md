---
title: "EmfAngleArc"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_ANGLEARC-Datensatz gibt ein Liniensegment eines Bogens an."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

Der EMR\_ANGLEARC-Datensatz gibt ein Liniensegment eines Bogens an. Das Liniensegment wird von der aktuellen Position zum Beginn des Bogens gezeichnet. Der Bogen wird entlang des Umfangs eines Kreises mit dem angegebenen Radius und Zentrum gezeichnet. Die Länge des Bogens wird durch die angegebenen Start‑ und Sweep‑Winkel definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfAngleArc`-Klasse. |
| [EmfAngleArc()](#EmfAngleArc--) | Initialisiert eine neue Instanz der `EmfAngleArc`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCenter()](#getCenter--) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Kreismittelpunkts angibt. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Kreismittelpunkts angibt. |
| [getRadius()](#getRadius--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Radius des Kreises in logischen Einheiten angibt. |
| [setRadius(int value)](#setRadius-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Radius des Kreises in logischen Einheiten angibt. |
| [getStartAngle()](#getStartAngle--) | Liest oder setzt einen 32‑Bit‑Float, der den Startwinkel des Bogens in Grad angibt. |
| [setStartAngle(float value)](#setStartAngle-float-) | Liest oder setzt einen 32‑Bit‑Float, der den Startwinkel des Bogens in Grad angibt. |
| [getSweepAngle()](#getSweepAngle--) | Liest oder setzt einen 32‑Bit‑Float, der den Sweep‑Winkel des Bogens in Grad angibt. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Liest oder setzt einen 32‑Bit‑Float, der den Sweep‑Winkel des Bogens in Grad angibt. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfAngleArc`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Initialisiert eine neue Instanz der `EmfAngleArc`-Klasse.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Kreismittelpunkts angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die logischen Koordinaten des Kreismittelpunkts angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Radius des Kreises in logischen Einheiten angibt.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Radius des Kreises in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Liest oder setzt einen 32‑Bit‑Float, der den Startwinkel des Bogens in Grad angibt.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Liest oder setzt einen 32‑Bit‑Float, der den Startwinkel des Bogens in Grad angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Liest oder setzt einen 32‑Bit‑Float, der den Sweep‑Winkel des Bogens in Grad angibt.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Liest oder setzt einen 32‑Bit‑Float, der den Sweep‑Winkel des Bogens in Grad angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

