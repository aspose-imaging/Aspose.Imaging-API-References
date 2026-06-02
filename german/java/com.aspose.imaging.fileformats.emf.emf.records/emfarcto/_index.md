---
title: "EmfArcTo"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_ARCTO‑Datensatz spezifiziert einen elliptischen Bogen."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

Der EMR\_ARCTO‑Datensatz spezifiziert einen elliptischen Bogen. Er setzt die aktuelle Position auf den Endpunkt des Bogens zurück.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfArcTo` Klasse. |
| [EmfArcTo()](#EmfArcTo--) | Initialisiert eine neue Instanz der `EmfArcTo` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBox()](#getBox--) | Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt. |
| [getStart()](#getStart--) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten des ersten radialen Endpunkts in logischen Einheiten angibt. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten des ersten radialen Endpunkts in logischen Einheiten angibt. |
| [getEnd()](#getEnd--) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die Koordinaten des zweiten radialen Endpunkts in logischen Einheiten angibt. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die Koordinaten des zweiten radialen Endpunkts in logischen Einheiten angibt. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfArcTo` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


Initialisiert eine neue Instanz der `EmfArcTo` Klasse.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Liest oder setzt ein 128‑Bit‑WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das Begrenzungsrechteck angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten des ersten radialen Endpunkts in logischen Einheiten angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das die Koordinaten des ersten radialen Endpunkts in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die Koordinaten des zweiten radialen Endpunkts in logischen Einheiten angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die Koordinaten des zweiten radialen Endpunkts in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

