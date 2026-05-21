---
title: "EmfPlusFillPie"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusFillPie-Datensatz gibt das Füllen eines Abschnitts des Inneren einer Ellipse an."
type: docs
weight: 35
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

Der EmfPlusFillPie-Datensatz gibt das Füllen eines Abschnitts des Inneren einer Ellipse an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusFillPie`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [getStartAngle()](#getStartAngle--) | Liest oder schreibt den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Kuchenstücks angibt. |
| [setStartAngle(float value)](#setStartAngle-float-) | Liest oder schreibt den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Kuchenstücks angibt. |
| [getSweepAngle()](#getSweepAngle--) | Liest oder schreibt den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des Bogens angibt, der das zu zeichnende Kuchenstück definiert, gemessen in Grad vom durch den StartAngle‑Wert definierten Startpunkt. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Liest oder schreibt den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des Bogens angibt, der das zu zeichnende Kuchenstück definiert, gemessen in Grad vom durch den StartAngle‑Wert definierten Startpunkt. |
| [getRectData()](#getRectData--) | Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die das Kuchenstück enthält. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die das Kuchenstück enthält. |
| [getBrushId()](#getBrushId--) | Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
| [setBrushId(int value)](#setBrushId-int-) | Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusFillPie`‑Klasse.

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

