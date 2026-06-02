---
title: "EmfPlusDrawString"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawString-Datensatz gibt die Textausgabe mit Zeichenkettenformatierung an"
type: docs
weight: 28
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawString-Datensatz gibt die Textausgabe mit Zeichenkettenformatierung an
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusDrawString`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getBrushId()](#getBrushId--) | Ruft die Pinselkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
| [setBrushId(int value)](#setBrushId-int-) | Ruft die Pinselkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
| [getFormatId()](#getFormatId--) | Ruft die Formatkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusStringFormat‑Objekts (Abschnitt 2.2.1.9) in der EMF+‑Objekttabelle angibt. |
| [setFormatId(int value)](#setFormatId-int-) | Ruft die Formatkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusStringFormat‑Objekts (Abschnitt 2.2.1.9) in der EMF+‑Objekttabelle angibt. |
| [getLength()](#getLength--) | Ruft die Länge ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Zeichen in der Zeichenkette angibt. |
| [setLength(int value)](#setLength-int-) | Ruft die Länge ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Zeichen in der Zeichenkette angibt. |
| [getLayoutRect()](#getLayoutRect--) | Ruft das Layout‑Rechteck ab oder legt es fest, ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das den Begrenzungsbereich des Ziels definiert, das die Zeichenkette erhalten wird. |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Ruft das Layout‑Rechteck ab oder legt es fest, ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das den Begrenzungsbereich des Ziels definiert, das die Zeichenkette erhalten wird. |
| [getStringData()](#getStringData--) | Ruft die Zeichenkettendaten ab oder legt sie fest, ein Array aus 16‑Bit‑Unicode‑Zeichen, das die zu zeichnende Zeichenkette angibt. |
| [setStringData(String value)](#setStringData-java.lang.String-) | Ruft die Zeichenkettendaten ab oder legt sie fest, ein Array aus 16‑Bit‑Unicode‑Zeichen, das die zu zeichnende Zeichenkette angibt. |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusDrawString`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ruft die Objektkennung ab oder legt sie fest. Der Index eines EmfPlusFont‑Objekts (Abschnitt 2.2.1.3) in der EMF+‑Objekttabelle, das zum Rendern des Textes verwendet wird. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ruft die Objektkennung ab oder legt sie fest. Der Index eines EmfPlusFont‑Objekts (Abschnitt 2.2.1.3) in der EMF+‑Objekttabelle, das zum Rendern des Textes verwendet wird. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Ruft die Pinselkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. Diese Definition wird verwendet, um die Vordergrund‑Textfarbe zu malen; das heißt, nur die Glyphen selbst.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Ruft die Pinselkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. Diese Definition wird verwendet, um die Vordergrund‑Textfarbe zu malen; das heißt, nur die Glyphen selbst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Ruft die Formatkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusStringFormat‑Objekts (Abschnitt 2.2.1.9) in der EMF+‑Objekttabelle angibt. Dieses Objekt definiert Textlayout‑Informationen und Anzeige­manipulationen, die auf eine Zeichenkette angewendet werden.

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Ruft die Formatkennung ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der den Index eines optionalen EmfPlusStringFormat‑Objekts (Abschnitt 2.2.1.9) in der EMF+‑Objekttabelle angibt. Dieses Objekt definiert Textlayout‑Informationen und Anzeige­manipulationen, die auf eine Zeichenkette angewendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Ruft die Länge ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Zeichen in der Zeichenkette angibt.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Ruft die Länge ab oder legt sie fest, ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Zeichen in der Zeichenkette angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Ruft das Layout‑Rechteck ab oder legt es fest, ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das den Begrenzungsbereich des Ziels definiert, das die Zeichenkette erhalten wird.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Ruft das Layout‑Rechteck ab oder legt es fest, ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das den Begrenzungsbereich des Ziels definiert, das die Zeichenkette erhalten wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Ruft die Zeichenkettendaten ab oder legt sie fest, ein Array aus 16‑Bit‑Unicode‑Zeichen, das die zu zeichnende Zeichenkette angibt.

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Ruft die Zeichenkettendaten ab oder legt sie fest, ein Array aus 16‑Bit‑Unicode‑Zeichen, das die zu zeichnende Zeichenkette angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

