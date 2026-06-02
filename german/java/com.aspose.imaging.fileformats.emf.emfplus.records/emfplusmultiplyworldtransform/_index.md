---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusMultiplyWorldTransform-Datensatz multipliziert die aktuelle Weltkoordinatentransformation mit einer angegebenen Transformationsmatrix."
type: docs
weight: 41
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

Der EmfPlusMultiplyWorldTransform-Datensatz multipliziert die aktuelle Weltkoordinatentransformation mit einer angegebenen Transformationsmatrix.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusMultiplyWorldTransform`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Liest einen Wert, der angibt, ob [post multiplied matrix]. |
| [getMatrixData()](#getMatrixData--) | Liest oder setzt ein EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Multiplikationsmatrix definiert. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Liest oder setzt ein EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Multiplikationsmatrix definiert. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusMultiplyWorldTransform`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Liest einen Wert, der angibt, ob [post multiplied matrix]. Wenn gesetzt, sollte die Transformationsmatrix post‑multipliziert werden. Wenn nicht gesetzt, sollte sie pre‑multipliziert werden.

Wert: `true` wenn [post multiplied matrix]; andernfalls `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Liest oder setzt ein EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Multiplikationsmatrix definiert.

Wert: Die Matrixdaten.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Liest oder setzt ein EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Multiplikationsmatrix definiert.

Wert: Die Matrixdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

