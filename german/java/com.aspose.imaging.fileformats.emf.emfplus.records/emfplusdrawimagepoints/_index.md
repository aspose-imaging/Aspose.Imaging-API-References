---
title: "EmfPlusDrawImagePoints"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusDrawImagePoints-Datensatz gibt das Zeichnen eines skalierten Bildes innerhalb eines Parallelogramms an."
type: docs
weight: 23
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

Der EmfPlusDrawImagePoints-Datensatz gibt das Zeichnen eines skalierten Bildes innerhalb eines Parallelogramms an.

Ein EmfPlusImage kann entweder ein Bitmap oder eine Metadatei angeben. Farben in einem Bild können während des Renderns manipuliert werden. Sie können korrigiert, abgedunkelt, aufgehellt und entfernt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusDrawImagePoints`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompressed()](#getCompressed--) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Liest oder setzt einen Wert, der angibt, ob [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Liest oder setzt einen Wert, der angibt, ob [applying an effect]. |
| [getRelative()](#getRelative--) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawImagePoints` relativ ist. |
| [setRelative(boolean value)](#setRelative-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses `EmfPlusDrawImagePoints` relativ ist. |
| [getImageAttributesId()](#getImageAttributesId--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des optionalen EmfPlusImageAttributes‑Objekts (Abschnitt 2.2.1.5) in der EMF+‑Objekttabelle enthält. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des optionalen EmfPlusImageAttributes‑Objekts (Abschnitt 2.2.1.5) in der EMF+‑Objekttabelle enthält. |
| [getSrcUnit()](#getSrcUnit--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Einheiten des SrcRect‑Feldes definiert. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Einheiten des SrcRect‑Feldes definiert. |
| [getSrcRect()](#getSrcRect--) | Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das einen Teil des zu rendernden Bildes definiert. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das einen Teil des zu rendernden Bildes definiert. |
| [getPointData()](#getPointData--) | Liest oder setzt ein Array von Count‑Punkten, die drei Punkte eines Parallelogramms angeben. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Liest oder setzt ein Array von Count‑Punkten, die drei Punkte eines Parallelogramms angeben. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusDrawImagePoints`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. Dieses Bit gibt an, ob das PointData‑Feld komprimierte Daten enthält. Ist das Bit gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Ist das Bit gelöscht, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. Hinweis: Wenn das P‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. Dieses Bit gibt an, ob das PointData‑Feld komprimierte Daten enthält. Ist das Bit gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Ist das Bit gelöscht, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. Hinweis: Wenn das P‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden.

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

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Liest oder schreibt einen Wert, der angibt, ob [applying an effect]. Dieses Bit zeigt an, dass die Bilddarstellung das Anwenden eines Effekts beinhaltet. Ist es gesetzt, muss ein Objekt der Klasse Effect in einem früheren EmfPlusSerializableObject‑Datensatz (Abschnitt 2.3.5.2) angegeben worden sein.

Wert: `true`, wenn [applying an effect]; andernfalls `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob [applying an effect]. Dieses Bit zeigt an, dass die Bilddarstellung das Anwenden eines Effekts beinhaltet. Ist es gesetzt, muss ein Objekt der Klasse Effect in einem früheren EmfPlusSerializableObject‑Datensatz (Abschnitt 2.3.5.2) angegeben worden sein.

Wert: `true`, wenn [applying an effect]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusDrawImagePoints` relativ ist. Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt. Ist es gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Für das erste Element in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Ist das Bit gelöscht, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusDrawImagePoints` relativ ist. Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt. Ist es gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Für das erste Element in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Ist das Bit gelöscht, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des optionalen EmfPlusImageAttributes‑Objekts (Abschnitt 2.2.1.5) in der EMF+‑Objekttabelle enthält.

Wert: Der Bildattribute‑Bezeichner.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des optionalen EmfPlusImageAttributes‑Objekts (Abschnitt 2.2.1.5) in der EMF+‑Objekttabelle enthält.

Wert: Der Bildattribute‑Bezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Liest oder schreibt ein 32‑Bit‑Vorzeichen‑Integer, das die Einheiten des SrcRect‑Feldes definiert. Es MUSS der UnitPixel‑Wert der Aufzählung UnitType sein (Abschnitt 2.1.1.33).

Wert: Die Quell‑Einheit.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Liest oder schreibt ein 32‑Bit‑Vorzeichen‑Integer, das die Einheiten des SrcRect‑Feldes definiert. Es MUSS der UnitPixel‑Wert der Aufzählung UnitType sein (Abschnitt 2.1.1.33).

Wert: Die Quell‑Einheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das einen Teil des zu rendernden Bildes definiert.

Wert: Das Quell‑Rechteck.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das einen Teil des zu rendernden Bildes definiert.

Wert: Das Quell‑Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Liest oder schreibt ein Array von Count‑Punkten, die drei Punkte eines Parallelogramms angeben. Die drei Punkte stellen die obere linke, obere rechte und untere linke Ecke des Parallelogramms dar. Der vierte Punkt des Parallelogramms wird aus den ersten drei extrapoliert. Der durch das SrcRect‑Feld angegebene Bildausschnitt SOLLTE bei Bedarf Skalierungs‑ und Schertransformationen erhalten, um in das Parallelogramm zu passen.

Wert: Die Punktdaten.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Liest oder schreibt ein Array von Count‑Punkten, die drei Punkte eines Parallelogramms angeben. Die drei Punkte stellen die obere linke, obere rechte und untere linke Ecke des Parallelogramms dar. Der vierte Punkt des Parallelogramms wird aus den ersten drei extrapoliert. Der durch das SrcRect‑Feld angegebene Bildausschnitt SOLLTE bei Bedarf Skalierungs‑ und Schertransformationen erhalten, um in das Parallelogramm zu passen.

Wert: Die Punktdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

