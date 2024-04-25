---
title: EmfPlusSetWorldTransform
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetWorldTransform record sets the world transform according to the values in a specified transform matrix.
type: docs
weight: 68
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

The EmfPlusSetWorldTransform record sets the world transform according to the values in a specified transform matrix.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetWorldTransform` class. |
## Methods

| Method | Description |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the new current world transform. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the new current world transform. |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetWorldTransform` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the new current world transform.

Value: The matrix data.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the new current world transform.

Value: The matrix data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

