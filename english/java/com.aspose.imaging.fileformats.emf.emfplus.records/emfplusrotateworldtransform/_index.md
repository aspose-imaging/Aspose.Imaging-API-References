---
title: EmfPlusRotateWorldTransform
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.
type: docs
weight: 50
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusRotateWorldTransform` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Gets a value indicating whether [post multiplied matrix]. |
| [getAngle()](#getAngle--) | Gets or sets a 32-bit floating-point value that specifies the angle of rotation in degrees. |
| [setAngle(float value)](#setAngle-float-) | Gets or sets a 32-bit floating-point value that specifies the angle of rotation in degrees. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusRotateWorldTransform` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Gets a value indicating whether [post multiplied matrix]. If set, the transform matrix should be post-multiplied. If clear, it should be premultiplied.

Value: `true` if [post multiplied matrix]; otherwise, `false`.

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


Gets or sets a 32-bit floating-point value that specifies the angle of rotation in degrees. The operation is performed by constructing a new transform matrix from the following diagram: --------------------------------- | sin(Angle) | cos(Angle) | 0 | | cos(Angle) | sin(Angle) | 0 | --------------------------------- Figure 2: Rotation Transform Matrix The current world space transform is multiplied by this matrix, and the result becomes the new current world space transform. The Flags field determines the order of multiplication.

Value: The angle.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Gets or sets a 32-bit floating-point value that specifies the angle of rotation in degrees. The operation is performed by constructing a new transform matrix from the following diagram: --------------------------------- | sin(Angle) | cos(Angle) | 0 | | cos(Angle) | sin(Angle) | 0 | --------------------------------- Figure 2: Rotation Transform Matrix The current world space transform is multiplied by this matrix, and the result becomes the new current world space transform. The Flags field determines the order of multiplication.

Value: The angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

