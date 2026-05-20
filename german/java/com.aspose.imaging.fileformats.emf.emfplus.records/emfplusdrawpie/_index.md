---
title: "EmfPlusDrawPie"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawPie-Datensatz gibt das Zeichnen eines Abschnitts des Inneren einer Ellipse an."
type: docs
weight: 26
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawPie-Datensatz gibt das Zeichnen eines Abschnitts des Inneren einer Ellipse an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawPie`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getStartAngle()](#getStartAngle--) | Liest oder schreibt den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Kuchenstücks angibt. |
| [setStartAngle(float value)](#setStartAngle-float-) | Liest oder schreibt den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Kuchenstücks angibt. |
| [getSweepAngle()](#getSweepAngle--) | Liest oder schreibt den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des Bogens angibt, der das zu zeichnende Kuchenstück definiert, gemessen in Grad vom durch den StartAngle‑Wert definierten Startpunkt. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Liest oder schreibt den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des Bogens angibt, der das zu zeichnende Kuchenstück definiert, gemessen in Grad vom durch den StartAngle‑Wert definierten Startpunkt. |
| [getRectData()](#getRectData--) | Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die das Kuchenstück enthält. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die das Kuchenstück enthält. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawPie`‑Klasse.

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


Liest oder legt die Objektkennung fest. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+ Objektetabelle zum Zeichnen des Kuchensegments. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder legt die Objektkennung fest. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+ Objektetabelle zum Zeichnen des Kuchensegments. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Liest oder schreibt den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Kuchenstücks angibt. Jeder Wert ist zulässig, muss jedoch modulo 360 interpretiert werden, wobei das Ergebnis im Bereich 0,0 (einschließlich) bis 360,0 (ausschließlich) liegen muss.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Liest oder schreibt den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Kuchenstücks angibt. Jeder Wert ist zulässig, muss jedoch modulo 360 interpretiert werden, wobei das Ergebnis im Bereich 0,0 (einschließlich) bis 360,0 (ausschließlich) liegen muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Liest oder schreibt den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des Bogens angibt, der das zu zeichnende Kuchenstück definiert, gemessen in Grad vom durch den StartAngle‑Wert definierten Startpunkt. Jeder Wert ist zulässig, muss jedoch auf -360,0 bis 360,0 (einschließlich) begrenzt werden. Ein positiver Wert bedeutet, dass der Sweep im Uhrzeigersinn definiert ist, ein negativer Wert bedeutet, dass er gegen den Uhrzeigersinn definiert ist.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Liest oder schreibt den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des Bogens angibt, der das zu zeichnende Kuchenstück definiert, gemessen in Grad vom durch den StartAngle‑Wert definierten Startpunkt. Jeder Wert ist zulässig, muss jedoch auf -360,0 bis 360,0 (einschließlich) begrenzt werden. Ein positiver Wert bedeutet, dass der Sweep im Uhrzeigersinn definiert ist, ein negativer Wert bedeutet, dass er gegen den Uhrzeigersinn definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die das Kuchenstück enthält. Dieses Rechteck definiert die Position, Größe und Form des Kuchens. Der Objekttyp in diesem Feld wird durch den Wert des Flags‑Feldes angegeben.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die das Kuchenstück enthält. Dieses Rechteck definiert die Position, Größe und Form des Kuchens. Der Objekttyp in diesem Feld wird durch den Wert des Flags‑Feldes angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

