---
title: "EmfPlusDrawLines"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawlLines-Datensatz gibt das Zeichnen einer Reihe verbundener Linien an"
type: docs
weight: 24
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawlLines-Datensatz gibt das Zeichnen einer Reihe verbundener Linien an
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawLines`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` komprimiert ist. |
| [getRelative()](#getRelative--) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` relativ ist. |
| [setRelative(boolean value)](#setRelative-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawClosedCurve` relativ ist. |
| [getClosedShape()](#getClosedShape--) | Liest oder setzt einen Wert, der angibt, ob [geschlossene Form]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | Liest oder setzt einen Wert, der angibt, ob [geschlossene Form]. |
| [getPointData()](#getPointData--) | Liest oder setzt die Punktdaten. Ein Array von Count‑Punkten, das die Start‑ und Endpunkte der zu zeichnenden Linien angibt. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Liest oder setzt die Punktdaten. Ein Array von Count‑Punkten, das die Start‑ und Endpunkte der zu zeichnenden Linien angibt. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawLines`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder setzt die Objektkennung. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+‑Objekttabelle zum Zeichnen der Linien. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt die Objektkennung. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+‑Objekttabelle zum Zeichnen der Linien. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

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

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


Liest oder setzt einen Wert, der angibt, ob [geschlossene Form].

Wert: `true` wenn [closed shape]; andernfalls `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [geschlossene Form].

Wert: `true` wenn [closed shape]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Liest oder setzt die Punktdaten. Ein Array von Count‑Punkten, das die Start‑ und Endpunkte der zu zeichnenden Linien angibt.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Liest oder setzt die Punktdaten. Ein Array von Count‑Punkten, das die Start‑ und Endpunkte der zu zeichnenden Linien angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

