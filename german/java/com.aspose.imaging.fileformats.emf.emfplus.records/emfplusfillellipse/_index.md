---
title: "EmfPlusFillEllipse"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusFillEllipse-Datensatz gibt das Füllen des Inneren einer Ellipse an."
type: docs
weight: 33
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

Der EmfPlusFillEllipse-Datensatz gibt das Füllen des Inneren einer Ellipse an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusFillEllipse`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [isCompressed()](#isCompressed--) | Liest oder schreibt einen Wert, der angibt, ob diese Instanz komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder schreibt einen Wert, der angibt, ob diese Instanz komprimiert ist. |
| [getBrushId()](#getBrushId--) | Ruft die Pinselkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
| [setBrushId(int value)](#setBrushId-int-) | Ruft die Pinselkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
| [getRectData()](#getRectData--) | Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert. |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusFillEllipse`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

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

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Liest oder schreibt einen Wert, der angibt, ob diese Instanz komprimiert ist. Ist er gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38). Ist er gelöscht, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39).

Wert: `true`, wenn diese Instanz komprimiert ist; andernfalls `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob diese Instanz komprimiert ist. Ist er gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38). Ist er gelöscht, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39).

Wert: `true`, wenn diese Instanz komprimiert ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Liest oder schreibt den Pinsel‑Bezeichner. Ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. Diese Definition wird verwendet, um das Innere der Ellipse zu füllen.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Liest oder schreibt den Pinsel‑Bezeichner. Ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. Diese Definition wird verwendet, um das Innere der Ellipse zu füllen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Liest oder schreibt die Rechteckdaten. Entweder ein EmfPlusRect‑ oder ein EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

