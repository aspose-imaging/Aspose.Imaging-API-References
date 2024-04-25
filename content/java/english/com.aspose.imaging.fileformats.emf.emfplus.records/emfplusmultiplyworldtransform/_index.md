---
title: EmfPlusMultiplyWorldTransform
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a specified transform matrix.
type: docs
weight: 41
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a specified transform matrix.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusMultiplyWorldTransform` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Gets a value indicating whether [post multiplied matrix]. |
| [getMatrixData()](#getMatrixData--) | Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the multiplication matrix. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the multiplication matrix. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusMultiplyWorldTransform` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Gets a value indicating whether [post multiplied matrix]. If set, the transform matrix should be post-multipled. If clear, it should be premultiplied.

Value: `true` if [post multiplied matrix]; otherwise, `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the multiplication matrix.

Value: The matrix data.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the multiplication matrix.

Value: The matrix data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

