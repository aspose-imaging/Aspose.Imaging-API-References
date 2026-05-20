---
title: "EmfPlusDrawImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawImage-Datensatz gibt das Zeichnen eines skalierten Bildes an."
type: docs
weight: 22
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawImage-Datensatz gibt das Zeichnen eines skalierten Bildes an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawImage`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getImageAttributesId()](#getImageAttributesId--) | Liest oder setzt die Bildattribute‑Kennung. Ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusImageAttributes-Objekts (Abschnitt 2.2.1.5) in der EMF+-Objekttabelle angibt. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Liest oder setzt die Bildattribute‑Kennung. Ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusImageAttributes-Objekts (Abschnitt 2.2.1.5) in der EMF+-Objekttabelle angibt. |
| [getRectData()](#getRectData--) | Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect- oder ein EmfPlusRectF-Objekt, das die Begrenzungsbox des Bildes definiert. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect- oder ein EmfPlusRectF-Objekt, das die Begrenzungsbox des Bildes definiert. |
| [getSrcRect()](#getSrcRect--) | Liest oder setzt das Quellrechteck. Ein EmfPlusRectF-Objekt, das einen Teil des zu rendernden Bildes angibt. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Liest oder setzt das Quellrechteck. Ein EmfPlusRectF-Objekt, das einen Teil des zu rendernden Bildes angibt. |
| [getSrcUnit()](#getSrcUnit--) | Liest oder setzt die Quell‑Einheit. Ein 32‑Bit‑vorzeichenbehafteter Integer, der die Einheiten des SrcRect-Feldes angibt. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Liest oder setzt die Quell‑Einheit. Ein 32‑Bit‑vorzeichenbehafteter Integer, der die Einheiten des SrcRect-Feldes angibt. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawImage`-Klasse.

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


Liest oder setzt die Objektkennung. Der Index eines EmfPlusImage‑Objekts (Abschnitt 2.2.1.4) in der EMF+‑Objekttabelle, das das zu rendernde Bild angibt. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Liest oder setzt die Objektkennung. Der Index eines EmfPlusImage‑Objekts (Abschnitt 2.2.1.4) in der EMF+‑Objekttabelle, das das zu rendernde Bild angibt. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Liest oder setzt die Bildattribute‑Kennung. Ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusImageAttributes-Objekts (Abschnitt 2.2.1.5) in der EMF+-Objekttabelle angibt.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Liest oder setzt die Bildattribute‑Kennung. Ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusImageAttributes-Objekts (Abschnitt 2.2.1.5) in der EMF+-Objekttabelle angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect- oder ein EmfPlusRectF-Objekt, das die Begrenzungsbox des Bildes definiert. Der durch das SrcRect-Feld angegebene Bildteil wird skaliert, um in dieses Rechteck zu passen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Liest oder setzt die Rechteckdaten. Entweder ein EmfPlusRect- oder ein EmfPlusRectF-Objekt, das die Begrenzungsbox des Bildes definiert. Der durch das SrcRect-Feld angegebene Bildteil wird skaliert, um in dieses Rechteck zu passen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Liest oder setzt das Quellrechteck. Ein EmfPlusRectF-Objekt, das einen Teil des zu rendernden Bildes angibt. Der durch dieses Rechteck angegebene Bildteil wird skaliert, um in das Zielrechteck zu passen, das durch das RectData-Feld angegeben ist.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Liest oder setzt das Quellrechteck. Ein EmfPlusRectF-Objekt, das einen Teil des zu rendernden Bildes angibt. Der durch dieses Rechteck angegebene Bildteil wird skaliert, um in das Zielrechteck zu passen, das durch das RectData-Feld angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Liest oder setzt die Quell‑Einheit. Ein 32‑Bit‑vorzeichenbehafteter Integer, der die Einheiten des SrcRect-Feldes angibt. Er MUSS das Mitglied UnitTypePixel der Aufzählung UnitType sein (Abschnitt 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Liest oder setzt die Quell‑Einheit. Ein 32‑Bit‑vorzeichenbehafteter Integer, der die Einheiten des SrcRect-Feldes angibt. Er MUSS das Mitglied UnitTypePixel der Aufzählung UnitType sein (Abschnitt 2.1.1.33).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

