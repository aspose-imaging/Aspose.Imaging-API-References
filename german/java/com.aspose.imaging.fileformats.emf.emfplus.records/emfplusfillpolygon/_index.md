---
title: "EmfPlusFillPolygon"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusFillPolygon-Datensatz gibt das Füllen des Inneren eines Polygons an."
type: docs
weight: 36
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

Der EmfPlusFillPolygon-Datensatz gibt das Füllen des Inneren eines Polygons an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusFillPolygon`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [isCompressed()](#isCompressed--) | Liest oder schreibt einen Wert, der angibt, ob diese Instanz komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder schreibt einen Wert, der angibt, ob diese Instanz komprimiert ist. |
| [isRelative()](#isRelative--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz relativ ist. |
| [setRelative(boolean value)](#setRelative-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz relativ ist. |
| [getBrushId()](#getBrushId--) | Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
| [setBrushId(int value)](#setBrushId-int-) | Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
| [getPointData()](#getPointData--) | Liest oder setzt die Punktdaten, ein Array von Count‑Punkten, das die Eckpunkte des Polygons definiert. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Liest oder setzt die Punktdaten, ein Array von Count‑Punkten, das die Eckpunkte des Polygons definiert. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusFillPolygon`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. Ist er gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Ist er nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. Ist er gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Ist er nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz komprimiert ist. Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Wenn nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.

Wert: `true`, wenn diese Instanz komprimiert ist; andernfalls `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz komprimiert ist. Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Wenn nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.

Wert: `true`, wenn diese Instanz komprimiert ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz relativ ist. Wenn gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zum vom vorherigen Element im Array angegebenen Ort ist. Für das erste Element in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Wenn nicht gesetzt, gibt PointData absolute Positionen gemäß dem C‑Flag an.

Wert: `true`, wenn diese Instanz relativ ist; andernfalls `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz relativ ist. Wenn gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zum vom vorherigen Element im Array angegebenen Ort ist. Für das erste Element in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Wenn nicht gesetzt, gibt PointData absolute Positionen gemäß dem C‑Flag an.

Wert: `true`, wenn diese Instanz relativ ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Liest oder setzt die Punktdaten. Ein Array von Count‑Punkten, die die Eckpunkte des Polygons definieren. Die ersten beiden Punkte im Array geben die erste Seite des Polygons an. Jeder weitere Punkt definiert eine neue Seite, deren Eckpunkte der Punkt selbst und der vorherige Punkt sind. Stimmen der letzte und der erste Punkt nicht überein, geben sie die letzte Seite des Polygons an.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Liest oder setzt die Punktdaten. Ein Array von Count‑Punkten, die die Eckpunkte des Polygons definieren. Die ersten beiden Punkte im Array geben die erste Seite des Polygons an. Jeder weitere Punkt definiert eine neue Seite, deren Eckpunkte der Punkt selbst und der vorherige Punkt sind. Stimmen der letzte und der erste Punkt nicht überein, geben sie die letzte Seite des Polygons an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

