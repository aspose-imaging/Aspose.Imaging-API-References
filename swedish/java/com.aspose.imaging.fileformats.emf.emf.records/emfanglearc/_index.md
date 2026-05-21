---
title: "EmfAngleArc"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_ANGLEARC‑posten specificerar ett linjesegment av en båge."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

EMR\_ANGLEARC‑posten specificerar ett linjesegment av en båge. Linjesegmentet ritas från den aktuella positionen till början av bågen. Bågen ritas längs omkretsen av en cirkel med den angivna radien och centrum. Bågens längd definieras av de angivna start‑ och svev‑vinklarna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfAngleArc`. |
| [EmfAngleArc()](#EmfAngleArc--) | Initierar en ny instans av klassen `EmfAngleArc`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCenter()](#getCenter--) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger de logiska koordinaterna för cirkelns centrum. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger de logiska koordinaterna för cirkelns centrum. |
| [getRadius()](#getRadius--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar cirkelns radie i logiska enheter. |
| [setRadius(int value)](#setRadius-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar cirkelns radie i logiska enheter. |
| [getStartAngle()](#getStartAngle--) | Hämtar eller anger ett 32-bitars flyttal som specificerar bågens startvinkel i grader. |
| [setStartAngle(float value)](#setStartAngle-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar bågens startvinkel i grader. |
| [getSweepAngle()](#getSweepAngle--) | Hämtar eller anger ett 32-bitars flyttal som specificerar bågens svepvinkel i grader. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar bågens svepvinkel i grader. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Initierar en ny instans av klassen `EmfAngleArc`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Initierar en ny instans av klassen `EmfAngleArc`.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger de logiska koordinaterna för cirkelns centrum.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger de logiska koordinaterna för cirkelns centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar cirkelns radie i logiska enheter.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar cirkelns radie i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar bågens startvinkel i grader.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar bågens startvinkel i grader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar bågens svepvinkel i grader.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar bågens svepvinkel i grader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

