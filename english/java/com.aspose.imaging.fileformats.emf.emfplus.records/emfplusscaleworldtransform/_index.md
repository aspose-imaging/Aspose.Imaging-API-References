---
title: EmfPlusScaleWorldTransform
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.
type: docs
weight: 52
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusScaleWorldTransform` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Gets a value indicating whether [post multiplied matrix]. |
| [getSx()](#getSx--) | Gets or sets a 32-bit floating-point value that defines the horizontal scale factor. |
| [setSx(float value)](#setSx-float-) | Gets or sets a 32-bit floating-point value that defines the horizontal scale factor. |
| [getSy()](#getSy--) | Gets or sets a 32-bit floating-point value that defines the vertical scale factor. |
| [setSy(float value)](#setSy-float-) | Gets or sets a 32-bit floating-point value that defines the vertical scale factor. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusScaleWorldTransform` class.

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
### getSx() {#getSx--}
```
public float getSx()
```


Gets or sets a 32-bit floating-point value that defines the horizontal scale factor. The scaling is performed by constructing a new transform matrix from the Sx and Sy field values, as shown in the following table. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figure 3: Scale Transform Matrix

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Gets or sets a 32-bit floating-point value that defines the horizontal scale factor. The scaling is performed by constructing a new transform matrix from the Sx and Sy field values, as shown in the following table. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figure 3: Scale Transform Matrix

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Gets or sets a 32-bit floating-point value that defines the vertical scale factor.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Gets or sets a 32-bit floating-point value that defines the vertical scale factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

