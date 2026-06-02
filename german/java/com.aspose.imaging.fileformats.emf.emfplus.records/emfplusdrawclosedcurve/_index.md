---
title: "EmfPlusDrawClosedCurve"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawClosedCurve-Datensatz gibt das Zeichnen einer geschlossenen Kardinal‑Spline an."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawClosedCurve-Datensatz gibt das Zeichnen einer geschlossenen Kardinal‑Spline an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawClosedCurve`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. |
| [getRelative()](#getRelative--) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` relativ ist. |
| [setRelative(boolean value)](#setRelative-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` relativ ist. |
| [getTension()](#getTension--) | Ruft die Spannung ab oder legt sie fest, eine 32‑Bit-Gleitkommazahl, die angibt, wie stark die Spline sich beim Durchlaufen der Punkte biegt. |
| [setTension(float value)](#setTension-float-) | Ruft die Spannung ab oder legt sie fest, eine 32‑Bit-Gleitkommazahl, die angibt, wie stark die Spline sich beim Durchlaufen der Punkte biegt. |
| [getPointData()](#getPointData--) | Liest oder schreibt die Punktdaten – ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Liest oder schreibt die Punktdaten – ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawClosedCurve`-Klasse. RecordType – Eine 16‑Bit‑vorzeichenlose Ganzzahl, die diesen Datensatztyp als EmfPlusDrawClosedCurve aus der RecordType‑Aufzählung (Abschnitt 2.1.1.1) identifiziert. Der Wert MUSS 0x4017 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder schreibt die Objektkennung. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+-Objekttabelle zum Zeichnen der geschlossenen Kurve. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder schreibt die Objektkennung. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+-Objekttabelle zum Zeichnen der geschlossenen Kurve. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

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

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` relativ ist. Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt. Ist das Bit gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Im Fall des ersten Elements in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das Komprimiert‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` relativ ist. Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt. Ist das Bit gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Im Fall des ersten Elements in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das Komprimiert‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Liest oder schreibt die Punktdaten. Ein Array von Count‑Punkten, das die Endpunkte der Linien angibt, die die Spline definieren. Bei einer geschlossenen Kardinal‑Spline setzt sich die Kurve nach dem letzten Punkt im PointData‑Array fort und verbindet sich mit dem ersten Punkt des Arrays. Der Typ der Daten in diesem Array wird durch das Flags‑Feld wie folgt angegeben: Datentyp Bedeutung EmfPlusPointR‑Objekt (Abschnitt 2.2.2.37) Wenn das P‑Flag in den Flags gesetzt ist, geben die Punkte relative Positionen an. EmfPlusPointF‑Objekt (Abschnitt 2.2.2.36) Wenn die P‑ und C‑Bits im Flags‑Feld gesetzt sind, geben die Punkte absolute Positionen an. EmfPlusPoint‑Objekt (Abschnitt 2.2.2.35) Wenn das P‑Bit nicht gesetzt und das C‑Bit gesetzt ist, geben die Punkte relative Positionen an.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Liest oder schreibt die Punktdaten. Ein Array von Count‑Punkten, das die Endpunkte der Linien angibt, die die Spline definieren. Bei einer geschlossenen Kardinal‑Spline setzt sich die Kurve nach dem letzten Punkt im PointData‑Array fort und verbindet sich mit dem ersten Punkt des Arrays. Der Typ der Daten in diesem Array wird durch das Flags‑Feld wie folgt angegeben: Datentyp Bedeutung EmfPlusPointR‑Objekt (Abschnitt 2.2.2.37) Wenn das P‑Flag in den Flags gesetzt ist, geben die Punkte relative Positionen an. EmfPlusPointF‑Objekt (Abschnitt 2.2.2.36) Wenn die P‑ und C‑Bits im Flags‑Feld gesetzt sind, geben die Punkte absolute Positionen an. EmfPlusPoint‑Objekt (Abschnitt 2.2.2.35) Wenn das P‑Bit nicht gesetzt und das C‑Bit gesetzt ist, geben die Punkte relative Positionen an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

