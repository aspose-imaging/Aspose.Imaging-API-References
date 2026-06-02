---
title: "EmfPlusDrawCurve"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawCurve-Datensatz gibt das Zeichnen einer Kardinalspline an HINWEIS ObjectID 1 Byte Der Index eines EmfPlusPen-Objekts Abschnitt 2.2.1.7 in der EMF-Objekttabelle zum Zeichnen der Kurve."
type: docs
weight: 19
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawCurve-Datensatz gibt das Zeichnen einer Kardinalspline an HINWEIS: ObjectID (1 Byte): Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+-Objekttabelle zum Zeichnen der Kurve. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawCurve`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getTension()](#getTension--) | Ruft die Spannung ab oder legt sie fest, eine 32‑Bit-Gleitkommazahl, die angibt, wie stark die Spline sich beim Durchlaufen der Punkte biegt. |
| [setTension(float value)](#setTension-float-) | Ruft die Spannung ab oder legt sie fest, eine 32‑Bit-Gleitkommazahl, die angibt, wie stark die Spline sich beim Durchlaufen der Punkte biegt. |
| [getNumSegments()](#getNumSegments--) | Liest oder setzt die Segmentanzahl. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Liniensegmente angibt, aus denen die Spline besteht. |
| [setNumSegments(int value)](#setNumSegments-int-) | Liest oder setzt die Segmentanzahl. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Liniensegmente angibt, aus denen die Spline besteht. |
| [getPointData()](#getPointData--) | Liest oder setzt ein Array aus entweder 32‑Bit‑vorzeichenbehafteten Ganzzahlen oder 32‑Bit‑Gleitkommazahlen der Länge Count, das die Koordinatenwerte der Endpunkte der zu zeichnenden Linien definiert. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Liest oder setzt ein Array aus entweder 32‑Bit‑vorzeichenbehafteten Ganzzahlen oder 32‑Bit‑Gleitkommazahlen der Länge Count, das die Koordinatenwerte der Endpunkte der zu zeichnenden Linien definiert. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawCurve`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. Dieses Bit gibt an, ob das Feld PointData komprimierte Daten enthält. Ist das Bit gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. Dieses Bit gibt an, ob das Feld PointData komprimierte Daten enthält. Ist das Bit gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder setzt die Objektkennung. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+-Objekttabelle zum Zeichnen der Kurve. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt die Objektkennung. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+-Objekttabelle zum Zeichnen der Kurve. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


Liest oder schreibt die Spannung. Eine 32‑Bit-Gleitkommazahl, die angibt, wie stark die Spline beim Durchlaufen der Punkte gebogen wird. Ein Wert von 0 bedeutet, dass die Spline eine Folge von Geraden ist. Mit zunehmendem Wert wird die Kurve runder. Weitere Informationen finden Sie unter [SPLINE77] und [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Liest oder schreibt die Spannung. Eine 32‑Bit-Gleitkommazahl, die angibt, wie stark die Spline beim Durchlaufen der Punkte gebogen wird. Ein Wert von 0 bedeutet, dass die Spline eine Folge von Geraden ist. Mit zunehmendem Wert wird die Kurve runder. Weitere Informationen finden Sie unter [SPLINE77] und [PETZOLD].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Liest oder setzt die Segmentanzahl. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Liniensegmente angibt, aus denen die Spline besteht.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Liest oder setzt die Segmentanzahl. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Liniensegmente angibt, aus denen die Spline besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Liest oder setzt ein Array aus entweder 32‑Bit‑vorzeichenbehafteten Ganzzahlen oder 32‑Bit‑Gleitkommazahlen der Länge Count, das die Koordinatenwerte der Endpunkte der zu zeichnenden Linien definiert.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Liest oder setzt ein Array aus entweder 32‑Bit‑vorzeichenbehafteten Ganzzahlen oder 32‑Bit‑Gleitkommazahlen der Länge Count, das die Koordinatenwerte der Endpunkte der zu zeichnenden Linien definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

