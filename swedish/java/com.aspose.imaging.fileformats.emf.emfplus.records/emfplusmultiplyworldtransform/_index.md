---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusMultiplyWorldTransform-posten multiplicerar den aktuella världsrumstransformen med en specificerad transformationsmatris."
type: docs
weight: 41
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusMultiplyWorldTransform-posten multiplicerar den aktuella världsrumstransformen med en specificerad transformationsmatris.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusMultiplyWorldTransform`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Hämtar ett värde som indikerar om [post multiplied matrix]. |
| [getMatrixData()](#getMatrixData--) | Hämtar eller anger ett EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som definierar multiplikationsmatrisen. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Hämtar eller anger ett EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som definierar multiplikationsmatrisen. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusMultiplyWorldTransform`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Hämtar ett värde som indikerar om [post multiplicerad matris]. Om satt ska transformmatrisen post‑multipliceras. Om avmarkerad ska den premultipliceras.

Värde: `true` om [post multiplied matrix]; annars `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Hämtar eller anger ett EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som definierar multiplikationsmatrisen.

Värde: Matrisdata.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Hämtar eller anger ett EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som definierar multiplikationsmatrisen.

Värde: Matrisdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

