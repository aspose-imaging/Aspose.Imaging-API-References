---
title: "EmfPlusTranslateWorldTransform"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusTranslateWorldTransform-Datensatz führt eine Translation der aktuellen Weltraum‑Transformation durch."
type: docs
weight: 72
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

Der EmfPlusTranslateWorldTransform-Datensatz führt eine Translation der aktuellen Weltraum‑Transformation durch.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusTranslateWorldTransform`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Liest einen Wert, der angibt, ob [post multiplied matrix]. |
| [getDx()](#getDx--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die horizontale Distanz definiert. |
| [setDx(float value)](#setDx-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die horizontale Distanz definiert. |
| [getDy()](#getDy--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die vertikale Distanz definiert. |
| [setDy(float value)](#setDy-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die vertikale Distanz definiert. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusTranslateWorldTransform`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Liest einen Wert, der angibt, ob [post multiplied matrix]. Ist das Bit gesetzt, sollte die Transformationsmatrix nachträglich multipliziert werden. Ist das Bit nicht gesetzt, sollte sie vorab multipliziert werden.

Wert: `true` wenn [post multiplied matrix]; andernfalls `false`.

**Returns:**
boolean
### getDx() {#getDx--}
```
public float getDx()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die horizontale Distanz definiert. Die Verschiebung wird durchgeführt, indem aus den Feldern dx und dy eine neue Welttransformationsmatrix erstellt wird.

Wert: Das dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die horizontale Distanz definiert. Die Verschiebung wird durchgeführt, indem aus den Feldern dx und dy eine neue Welttransformationsmatrix erstellt wird.

Wert: Das dx.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die vertikale Distanz definiert.

Wert: Das dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die vertikale Distanz definiert.

Wert: Das dy.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

