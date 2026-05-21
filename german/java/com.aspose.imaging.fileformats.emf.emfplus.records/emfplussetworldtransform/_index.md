---
title: "EmfPlusSetWorldTransform"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetWorldTransform-Datensatz setzt die Welttransformation gemäß den Werten in einer angegebenen Transformationsmatrix."
type: docs
weight: 68
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

Der EmfPlusSetWorldTransform-Datensatz setzt die Welttransformation gemäß den Werten in einer angegebenen Transformationsmatrix.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusSetWorldTransform`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | Ruft ein EmfPlusTransformMatrix‑Objekt ab oder legt es fest (Abschnitt 2.2.2.47), das die neue aktuelle Welttransformation definiert. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Ruft ein EmfPlusTransformMatrix‑Objekt ab oder legt es fest (Abschnitt 2.2.2.47), das die neue aktuelle Welttransformation definiert. |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusSetWorldTransform`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Ruft ein EmfPlusTransformMatrix‑Objekt ab oder legt es fest (Abschnitt 2.2.2.47), das die neue aktuelle Welttransformation definiert.

Wert: Die Matrixdaten.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Ruft ein EmfPlusTransformMatrix‑Objekt ab oder legt es fest (Abschnitt 2.2.2.47), das die neue aktuelle Welttransformation definiert.

Wert: Die Matrixdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

