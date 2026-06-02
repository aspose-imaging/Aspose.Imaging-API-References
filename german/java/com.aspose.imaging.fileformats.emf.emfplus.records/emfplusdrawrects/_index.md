---
title: "EmfPlusDrawRects"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawRects-Datensatz gibt das Zeichnen einer Reihe von Rechtecken an"
type: docs
weight: 27
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawRects extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawRects-Datensatz gibt das Zeichnen einer Reihe von Rechtecken an
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawRects(EmfPlusRecord source)](#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawRects`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getRectData()](#getRectData--) | Liest oder setzt die Rechteckdaten. Ein Array aus entweder EmfPlusRect‑ oder EmfPlusRectF‑Objekten der Länge Count, das die Rechteckdaten definiert. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Liest oder setzt die Rechteckdaten. Ein Array aus entweder EmfPlusRect‑ oder EmfPlusRectF‑Objekten der Länge Count, das die Rechteckdaten definiert. |
### EmfPlusDrawRects(EmfPlusRecord source) {#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawRects(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawRects`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder setzt den Objektbezeichner. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+ Object Table zum Zeichnen der Rechtecke. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt den Objektbezeichner. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+ Object Table zum Zeichnen der Rechtecke. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Liest oder setzt die Rechteckdaten. Ein Array aus entweder EmfPlusRect‑ oder EmfPlusRectF‑Objekten der Länge Count, das die Rechteckdaten definiert.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Liest oder setzt die Rechteckdaten. Ein Array aus entweder EmfPlusRect‑ oder EmfPlusRectF‑Objekten der Länge Count, das die Rechteckdaten definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

