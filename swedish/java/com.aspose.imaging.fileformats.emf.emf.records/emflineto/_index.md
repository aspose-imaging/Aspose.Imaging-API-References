---
title: "EmfLineTo"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_LINETO-posten specificerar en linje från den aktuella positionen upp till men utan att inkludera den angivna punkten. Den återställer den aktuella positionen till den angivna punkten."
type: docs
weight: 68
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emflineto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfLineTo extends EmfRecord
```

Den EMR_LINETO-posten specificerar en linje från den aktuella positionen upp till, men utan att inkludera, den angivna punkten. Den återställer den aktuella positionen till den angivna punkten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfLineTo(EmfRecord record)](#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfLineTo`. |
| [EmfLineTo()](#EmfLineTo--) | Initierar en ny instans av klassen `EmfLineTo`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPoint()](#getPoint--) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger koordinaterna för linjens slutpunkt. |
| [setPoint(Point value)](#setPoint-com.aspose.imaging.Point-) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger koordinaterna för linjens slutpunkt. |
### EmfLineTo(EmfRecord record) {#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfLineTo(EmfRecord record)
```


Initierar en ny instans av klassen `EmfLineTo`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Posten. |

### EmfLineTo() {#EmfLineTo--}
```
public EmfLineTo()
```


Initierar en ny instans av klassen `EmfLineTo`.

### getPoint() {#getPoint--}
```
public Point getPoint()
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger koordinaterna för linjens slutpunkt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPoint(Point value) {#setPoint-com.aspose.imaging.Point-}
```
public void setPoint(Point value)
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som anger koordinaterna för linjens slutpunkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

