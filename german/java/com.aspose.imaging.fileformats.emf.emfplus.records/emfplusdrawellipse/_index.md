---
title: "EmfPlusDrawEllipse"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawEllipse-Datensatz gibt das Zeichnen einer Ellipse an."
type: docs
weight: 21
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawEllipse extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawEllipse-Datensatz gibt das Zeichnen einer Ellipse an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawEllipse(EmfPlusRecord source)](#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawEllipse`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [getRectData()](#getRectData--) | Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert. |
### EmfPlusDrawEllipse(EmfPlusRecord source) {#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawEllipse(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawEllipse`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder setzt die Objektkennung. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+‑Objekttabelle zum Zeichnen der Ellipse. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt die Objektkennung. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+‑Objekttabelle zum Zeichnen der Ellipse. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38). Wenn nicht gesetzt, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39).

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38). Wenn nicht gesetzt, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39).

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

