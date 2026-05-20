---
title: "EmfPlusDrawDriverString"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawDriverString-Datensatz gibt die Textausgabe mit Zeichenpositionen an."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawDriverString-Datensatz gibt die Textausgabe mit Zeichenpositionen an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusDrawDriverString`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectId()](#getObjectId--) | Liest die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Schreibt die Objektkennung. |
| [getBrushId()](#getBrushId--) | Liest die Pinselkennung. Eine 32‑Bit‑vorzeichenlose Ganzzahl, die entweder die Vordergrundfarbe des Textes oder einen Grafikpinsel angibt, abhängig vom Wert des S‑Flags in den Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Setzt die BrushId. Ein 32‑Bit‑vorzeichenloser Integer, der entweder die Vordergrundfarbe des Textes oder einen Grafikpinsel angibt, abhängig vom Wert des S‑Flags in den Flags. |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Liest die driver string options flags. Ein 32‑Bit‑vorzeichenloser Integer, der den Abstand, die Ausrichtung und die Renderqualität für die Zeichenkette angibt. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Setzt die driver string options flags. Ein 32‑Bit‑vorzeichenloser Integer, der den Abstand, die Ausrichtung und die Renderqualität für die Zeichenkette angibt. |
| [getGlyphCount()](#getGlyphCount--) | Liest die GlyphCount. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Glyphen in der Zeichenkette angibt. |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Setzt die GlyphCount. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Glyphen in der Zeichenkette angibt. |
| [getGlyphPos()](#getGlyphPos--) | Liest das GlyphPos-Array. Ein Array von EmfPlusPointF‑Objekten (Abschnitt 2.2.2.36), das die Ausgabeposition jedes Zeichen-Glyphen angibt. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Setzt das GlyphPos-Array. Ein Array von EmfPlusPointF‑Objekten (Abschnitt 2.2.2.36), das die Ausgabeposition jedes Zeichen-Glyphen angibt. |
| [getGlyphs()](#getGlyphs--) | Liest das Glyphs-Array. Ein Array von 16‑Bit‑Werten, das die zu zeichnende Zeichenkette definiert. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Setzt das Glyphs-Array. Ein Array von 16‑Bit‑Werten, das die zu zeichnende Zeichenkette definiert. |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Setzt einen Wert, der angibt, ob diese Instanz farbig ist. |
| [getMatrixPresent()](#getMatrixPresent--) | Liest das MatrixPresent-Flag. Ein 32‑Bit‑vorzeichenloser Integer, der angibt, ob eine Transformationsmatrix im Feld TransformMatrix vorhanden ist (0 – keine Matrix vorhanden). |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Setzt das MatrixPresent-Flag. Ein 32‑Bit‑vorzeichenloser Integer, der angibt, ob eine Transformationsmatrix im Feld TransformMatrix vorhanden ist (0 – keine Matrix vorhanden). |
| [getTransformMatrix()](#getTransformMatrix--) | Liest die TransformMatrix. Ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die auf jeden Wert im Text‑Array anzuwendende Transformation angibt. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Setzt die TransformMatrix. Ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die auf jeden Wert im Text‑Array anzuwendende Transformation angibt. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusDrawDriverString`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Liest die Objektkennung. Der EMF+ Object Table‑Index eines ``‑Objekts (Abschnitt 2.2.1.3) zum Rendern des Textes. Der Wert MUSS zwischen 0 und 63, inklusiv, liegen.

**Returns:**
byte – Die Objektkennung.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Setzt die Objektkennung. Der EMF+ Object Table‑Index eines ``‑Objekts (Abschnitt 2.2.1.3) zum Rendern des Textes. Der Wert MUSS zwischen 0 und 63, inklusiv, liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Die Objektkennung. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Liest die Pinselkennung. Eine 32‑Bit‑vorzeichenlose Ganzzahl, die entweder die Vordergrundfarbe des Textes oder einen Grafikpinsel angibt, abhängig vom Wert des S‑Flags in den Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Setzt die BrushId. Ein 32‑Bit‑vorzeichenloser Integer, der entweder die Vordergrundfarbe des Textes oder einen Grafikpinsel angibt, abhängig vom Wert des S‑Flags in den Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Liest die driver string options flags. Ein 32‑Bit‑vorzeichenloser Integer, der den Abstand, die Ausrichtung und die Renderqualität für die Zeichenkette angibt.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Setzt die driver string options flags. Ein 32‑Bit‑vorzeichenloser Integer, der den Abstand, die Ausrichtung und die Renderqualität für die Zeichenkette angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Liest die GlyphCount. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Glyphen in der Zeichenkette angibt.

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Setzt die GlyphCount. Ein 32‑Bit‑vorzeichenloser Integer, der die Anzahl der Glyphen in der Zeichenkette angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Liest das GlyphPos-Array. Ein Array von EmfPlusPointF‑Objekten (Abschnitt 2.2.2.36), das die Ausgabeposition jedes Zeichen‑Glyphen angibt. Es MUSS GlyphCount‑Elemente geben, die eine Eins‑zu‑Eins‑Entsprechung zu den Elementen im Glyphs‑Array haben. Glyph‑Positionen werden aus der Position des ersten Glyphen berechnet, wenn das DriverStringOptionsRealizedAdvance‑Flag in den DriverStringOptions‑Flags gesetzt ist. In diesem Fall gibt GlyphPos nur die Position des ersten Glyphen an.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Setzt das GlyphPos-Array. Ein Array von EmfPlusPointF‑Objekten (Abschnitt 2.2.2.36), das die Ausgabeposition jedes Zeichen‑Glyphen angibt. Es MUSS GlyphCount‑Elemente geben, die eine Eins‑zu‑Eins‑Entsprechung zu den Elementen im Glyphs‑Array haben. Glyph‑Positionen werden aus der Position des ersten Glyphen berechnet, wenn das DriverStringOptionsRealizedAdvance‑Flag in den DriverStringOptions‑Flags gesetzt ist. In diesem Fall gibt GlyphPos nur die Position des ersten Glyphen an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Liest das Glyphs-Array. Ein Array von 16‑Bit‑Werten, das die zu zeichnende Zeichenkette definiert. Ist das DriverStringOptionsCmapLookup‑Flag im Feld DriverStringOptionsFlags gesetzt, gibt jeder Wert in diesem Array ein Unicode‑Zeichen an. Andernfalls gibt jeder Wert einen Index zu einem Zeichen‑Glyphen im EmfPlusFont‑Objekt an, das durch den ObjectId‑Wert im Flags‑Feld spezifiziert wird.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Setzt das Glyphs-Array. Ein Array von 16‑Bit‑Werten, das die zu zeichnende Zeichenkette definiert. Ist das DriverStringOptionsCmapLookup‑Flag im Feld DriverStringOptionsFlags gesetzt, gibt jeder Wert in diesem Array ein Unicode‑Zeichen an. Andernfalls gibt jeder Wert einen Index zu einem Zeichen‑Glyphen im EmfPlusFont‑Objekt an, das durch den ObjectId‑Wert im Flags‑Feld spezifiziert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist. Dieses Bit gibt den Datentyp im BrushId‑Feld an. Ist es gesetzt, gibt BrushId den Farbwert in einem EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Ist es gelöscht, enthält BrushId den EMF+ Object Table‑Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1).

**Returns:**
boolean – `true`, wenn diese Instanz farbig ist; andernfalls `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Setzt einen Wert, der angibt, ob diese Instanz farbig ist. Dieses Bit gibt den Datentyp im BrushId‑Feld an. Ist es gesetzt, gibt BrushId den Farbwert in einem EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Ist es gelöscht, enthält BrushId den EMF+ Object Table‑Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn diese Instanz farbig ist; andernfalls `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


Liest, ob das Matrix‑vorhanden‑Flag ein 32‑Bit‑Unsigned‑Integer ist, das angibt, ob eine Transformationsmatrix im Feld TransformMatrix vorhanden ist. 0 – keine Matrix vorhanden. 1 – Transformationsmatrix ist im Feld TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


Setzt, ob das Matrix‑vorhanden‑Flag ein 32‑Bit‑Unsigned‑Integer ist, das angibt, ob eine Transformationsmatrix im Feld TransformMatrix vorhanden ist. 0 – keine Matrix vorhanden. 1 – Transformationsmatrix ist im Feld TransformMatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Liest die Transformationsmatrix. Ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Transformation angibt, die auf jeden Wert im Text‑Array angewendet wird. Das Vorhandensein dieser Daten wird anhand des Feldes MatrixPresent bestimmt.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Setzt die Transformationsmatrix. Ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Transformation angibt, die auf jeden Wert im Text‑Array angewendet wird. Das Vorhandensein dieser Daten wird anhand des Feldes MatrixPresent bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

