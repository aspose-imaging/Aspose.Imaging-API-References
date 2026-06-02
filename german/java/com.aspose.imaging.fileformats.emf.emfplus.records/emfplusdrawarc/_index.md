---
title: "EmfPlusDrawArc"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawArc-Datensatz gibt das Zeichnen des Bogens einer Ellipse an."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawArc-Datensatz gibt das Zeichnen des Bogens einer Ellipse an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawArc`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDataSize()](#getDataSize--) | Liest die Größe der Daten. |
| [setDataSize(int value)](#setDataSize-int-) | Setzt die Größe der Daten. |
| [getRectFloat()](#getRectFloat--) | Liest einen Wert, der angibt, ob die Daten EmfPlusRectF- oder EmfPlusRect‑Datensätze enthalten. Dieses Bit gibt an, ob die Daten im Feld RectData komprimiert sind. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Setzt einen Wert, der angibt, ob die Daten EmfPlusRectF- oder EmfPlusRect‑Datensätze enthalten. Dieses Bit gibt an, ob die Daten im Feld RectData komprimiert sind. |
| [getObjectId()](#getObjectId--) | Liest die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Schreibt die Objektkennung. |
| [getSize()](#getSize--) | Liest die Größe. |
| [setSize(int value)](#setSize-int-) | Setzt die Größe. |
| [getStartAngle()](#getStartAngle--) | Liest den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Bogens angibt. |
| [setStartAngle(float value)](#setStartAngle-float-) | Setzt den Startwinkel. Ein 32‑Bit‑nichtnegativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Bogens angibt. |
| [getSweepAngle()](#getSweepAngle--) | Liest den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des zu zeichnenden Bogens als Winkel in Grad angibt, gemessen vom Startpunkt, der durch den Startwinkel‑Wert definiert ist. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Setzt den Sweep‑Winkel. Ein 32‑Bit‑Gleitkommawert, der den Umfang des zu zeichnenden Bogens als Winkel in Grad angibt, gemessen vom Startpunkt, der durch den Startwinkel‑Wert definiert ist. |
| [getRectangleData()](#getRectangleData--) | Liest die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die mit dem Bogen kollinear ist. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Setzt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert, die mit dem Bogen kollinear ist. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawArc`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Liest die Größe der Daten. Eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes der nachfolgenden, recordspezifischen Daten angibt. Für diesen Record‑Typ MUSS der Wert einer der folgenden sein: 0x00000010, wenn das C‑Bit im Feld Flags gesetzt ist; 0x00000018, wenn das C‑Bit im Feld Flags gelöscht ist.

**Returns:**
int - Die Größe der Daten.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Setzt die Größe der Daten. Eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes der nachfolgenden, recordspezifischen Daten angibt. Für diesen Record‑Typ MUSS der Wert einer der folgenden sein: 0x00000010, wenn das C‑Bit im Feld Flags gesetzt ist; 0x00000018, wenn das C‑Bit im Feld Flags gelöscht ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Größe der Daten. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Liest einen Wert, der angibt, ob die Daten EmfPlusRectF- oder EmfPlusRect‑Datensätze enthalten. Dieses Bit gibt an, ob die Daten im Feld RectData komprimiert sind. Ist das Bit gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38). Ist das Bit gelöscht, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39).

**Returns:**
boolesch - `true`, wenn Fließkomma; andernfalls `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Legt einen Wert fest, der angibt, ob die Daten EmfPlusRectF- oder EmfPlusRect-Datensätze enthalten. Dieses Bit gibt an, ob die Daten im Feld RectData komprimiert sind. Wenn gesetzt, enthält RectData ein EmfPlusRect-Objekt (Abschnitt 2.2.2.38). Wenn gelöscht, enthält RectData ein EmfPlusRectF-Objekt (Abschnitt 2.2.2.39).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true` wenn float; andernfalls `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest die Objektkennung. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+ Objektetabelle zum Zeichnen des Bogens. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

**Returns:**
byte – Die Objektkennung.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Legt die Objektkennung fest. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+ Objektetabelle zum Zeichnen des Bogens. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Die Objektkennung. |

### getSize() {#getSize--}
```
public int getSize()
```


Liest die Größe. Ein 32‑Bit‑vorzeichenloser Integer, der die 32‑Bit‑ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der recordspezifischen Daten. Für diesen Datensatztyp MUSS der Wert einer der folgenden sein: 0x0000001C, wenn das C‑Bit im Flags‑Feld gesetzt ist. 0x00000024, wenn das C‑Bit im Flags‑Feld gelöscht ist.

**Returns:**
int - Die Größe.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Legt die Größe fest. Ein 32‑Bit‑vorzeichenloser Integer, der die 32‑Bit‑ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der recordspezifischen Daten. Für diesen Datensatztyp MUSS der Wert einer der folgenden sein: 0x0000001C, wenn das C‑Bit im Flags‑Feld gesetzt ist. 0x00000024, wenn das C‑Bit im Flags‑Feld gelöscht ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Größe. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Liest den Startwinkel. Ein 32‑Bit nicht‑negativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Bogens angibt. Jeder Wert ist zulässig, muss jedoch modulo 360 interpretiert werden, wobei das verwendete Ergebnis im Bereich 0,0 (einschließlich) bis 360,0 (ausschließlich) liegen muss.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Legt den Startwinkel fest. Ein 32‑Bit nicht‑negativer Gleitkommawert, der den Winkel zwischen der x‑Achse und dem Startpunkt des Bogens angibt. Jeder Wert ist zulässig, muss jedoch modulo 360 interpretiert werden, wobei das verwendete Ergebnis im Bereich 0,0 (einschließlich) bis 360,0 (ausschließlich) liegen muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Liest den Sweep‑Winkel. Ein 32‑Bit Gleitkommawert, der den Umfang des zu zeichnenden Bogens als Winkel in Grad angibt, gemessen vom Startpunkt, der durch den StartAngle‑Wert definiert ist. Jeder Wert ist zulässig, muss jedoch auf -360,0 bis 360,0 (einschließlich) begrenzt werden. Ein positiver Wert zeigt an, dass der Sweep im Uhrzeigersinn definiert ist, ein negativer Wert zeigt an, dass er gegen den Uhrzeigersinn definiert ist.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Legt den Sweep‑Winkel fest. Ein 32‑Bit Gleitkommawert, der den Umfang des zu zeichnenden Bogens als Winkel in Grad angibt, gemessen vom Startpunkt, der durch den StartAngle‑Wert definiert ist. Jeder Wert ist zulässig, muss jedoch auf -360,0 bis 360,0 (einschließlich) begrenzt werden. Ein positiver Wert zeigt an, dass der Sweep im Uhrzeigersinn definiert ist, ein negativer Wert zeigt an, dass er gegen den Uhrzeigersinn definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Liest die Rechteckdaten. Entweder ein EmfPlusRect- oder ein EmfPlusRectF-Objekt, das die Begrenzungsbox der Ellipse definiert, die mit dem Bogen kollinear ist. Dieses Rechteck definiert die Position, Größe und Form des Bogens. Der Objekttyp in diesem Feld wird durch den Wert des Flags‑Feldes angegeben.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Legt die Rechteckdaten fest. Entweder ein EmfPlusRect- oder ein EmfPlusRectF-Objekt, das die Begrenzungsbox der Ellipse definiert, die mit dem Bogen kollinear ist. Dieses Rechteck definiert die Position, Größe und Form des Bogens. Der Objekttyp in diesem Feld wird durch den Wert des Flags‑Feldes angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

