---
title: "EmfPlusDrawBeziers"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawBeziers-Datensatz gibt das Zeichnen einer Sequenz verbundener Bézier‑Kurven an."
type: docs
weight: 17
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawBeziers‑Datensatz legt das Zeichnen einer Sequenz verbundener Bézier‑Kurven fest. Die Reihenfolge der Bézier‑Datenpunkte ist Startpunkt, Kontrollpunkt 1, Kontrollpunkt 2 und Endpunkt. Weitere Informationen siehe [MSDN-DrawBeziers].
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawBeziers`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [getRelative()](#getRelative--) | Liest oder schreibt einen Wert, der angibt, ob die PointData relativ ist. |
| [setRelative(boolean value)](#setRelative-boolean-) | Liest oder schreibt einen Wert, der angibt, ob die PointData relativ ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getPointData()](#getPointData--) | Liest oder schreibt die Punktdaten. Ein Array von Count‑Punkten, die die Start‑, End‑ und Kontrollpunkte der Bézier‑Kurven angeben. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Liest oder schreibt die Punktdaten. Ein Array von Count‑Punkten, die die Start‑, End‑ und Kontrollpunkte der Bézier‑Kurven angeben. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawBeziers`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Liest oder schreibt einen Wert, der angibt, ob die PointData komprimiert ist. Ist er gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Integer‑Koordinaten an. Ist er gelöscht, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob die PointData komprimiert ist. Ist er gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Integer‑Koordinaten an. Ist er gelöscht, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Liest oder schreibt einen Wert, der angibt, ob die PointData relativ ist. Ist er gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Für das erste Element in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Ist das Bit gelöscht, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob die PointData relativ ist. Ist er gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Für das erste Element in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Ist das Bit gelöscht, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest oder schreibt den Objekt‑Bezeichner. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+‑Objekttabelle zum Zeichnen der Bézier‑Kurven. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder schreibt den Objekt‑Bezeichner. Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+‑Objekttabelle zum Zeichnen der Bézier‑Kurven. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Liest oder schreibt die Punktdaten. Ein Array von Count‑Punkten, die die Start‑, End‑ und Kontrollpunkte der Bézier‑Kurven angeben. Die Endkoordinate einer Bézier‑Kurve ist die Startkoordinate der nächsten. Die Kontrollpunkte werden zur Erzeugung des Bézier‑Effekts verwendet. Der Datentyp in diesem Array wird durch das Flags‑Feld wie folgt bestimmt: Datentyp Bedeutung EmfPlusPointR‑Objekt (Abschnitt 2.2.2.37) – Wenn das P‑Flag im Flags gesetzt ist, geben die Punkte relative Positionen an. EmfPlusPointF‑Objekt (Abschnitt 2.2.2.36) – Wenn die P‑ und C‑Bits im Flags‑Feld gelöscht sind, geben die Punkte absolute Positionen an. EmfPlusPoint‑Objekt (Abschnitt 2.2.2.35) – Wenn das P‑Bit gelöscht und das C‑Bit im Flags‑Feld gesetzt ist, geben die Punkte relative Positionen an. Eine Bézier‑Kurve verläuft nicht durch ihre Kontrollpunkte. Die Kontrollpunkte dienen als

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Liest oder schreibt die Punktdaten. Ein Array von Count‑Punkten, die die Start‑, End‑ und Kontrollpunkte der Bézier‑Kurven angeben. Die Endkoordinate einer Bézier‑Kurve ist die Startkoordinate der nächsten. Die Kontrollpunkte werden zur Erzeugung des Bézier‑Effekts verwendet. Der Datentyp in diesem Array wird durch das Flags‑Feld wie folgt bestimmt: Datentyp Bedeutung EmfPlusPointR‑Objekt (Abschnitt 2.2.2.37) – Wenn das P‑Flag im Flags gesetzt ist, geben die Punkte relative Positionen an. EmfPlusPointF‑Objekt (Abschnitt 2.2.2.36) – Wenn die P‑ und C‑Bits im Flags‑Feld gelöscht sind, geben die Punkte absolute Positionen an. EmfPlusPoint‑Objekt (Abschnitt 2.2.2.35) – Wenn das P‑Bit gelöscht und das C‑Bit im Flags‑Feld gesetzt ist, geben die Punkte relative Positionen an. Eine Bézier‑Kurve verläuft nicht durch ihre Kontrollpunkte. Die Kontrollpunkte dienen als

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

