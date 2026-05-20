---
title: "EmfPlusFillRects"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusFillRects-Datensatz gibt das Füllen der Innenbereiche einer Reihe von Rechtecken an."
type: docs
weight: 37
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

Der EmfPlusFillRects-Datensatz gibt das Füllen der Innenbereiche einer Reihe von Rechtecken an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusFillRects`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [getCompressed()](#getCompressed--) | Liest oder legt einen Wert fest, der angibt, ob dieses `EmfPlusFillRects` komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder legt einen Wert fest, der angibt, ob dieses `EmfPlusFillRects` komprimiert ist. |
| [getBrushId()](#getBrushId--) | Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
| [setBrushId(int value)](#setBrushId-int-) | Liest oder setzt die Pinsel‑Kennung, einen 32‑Bit‑vorzeichenlosen Integer, der den Pinsel definiert; dessen Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
| [getRectData()](#getRectData--) | Liest oder legt die Rechteckdaten fest. Ein Array aus entweder EmfPlusRect- oder EmfPlusRectF-Objekten der Länge Count, das die Rechteckdaten definiert. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Liest oder legt die Rechteckdaten fest. Ein Array aus entweder EmfPlusRect- oder EmfPlusRectF-Objekten der Länge Count, das die Rechteckdaten definiert. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusFillRects`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist. Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist. Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Liest oder legt einen Wert fest, der angibt, ob dieses `EmfPlusFillRects` komprimiert ist. Wenn gesetzt, enthält RectData ein EmfPlusRect-Objekt (Abschnitt 2.2.2.38). Wenn gelöscht, enthält RectData ein EmfPlusRectF-Objekt (Abschnitt 2.2.2.39) Objekt.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob dieses `EmfPlusFillRects` komprimiert ist. Wenn gesetzt, enthält RectData ein EmfPlusRect-Objekt (Abschnitt 2.2.2.38). Wenn gelöscht, enthält RectData ein EmfPlusRectF-Objekt (Abschnitt 2.2.2.39) Objekt.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Liest oder legt die Rechteckdaten fest. Ein Array aus entweder EmfPlusRect- oder EmfPlusRectF-Objekten der Länge Count, das die Rechteckdaten definiert.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Liest oder legt die Rechteckdaten fest. Ein Array aus entweder EmfPlusRect- oder EmfPlusRectF-Objekten der Länge Count, das die Rechteckdaten definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

