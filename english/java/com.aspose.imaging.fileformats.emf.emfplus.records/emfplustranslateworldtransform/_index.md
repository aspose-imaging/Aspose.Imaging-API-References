---
title: EmfPlusTranslateWorldTransform
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.
type: docs
weight: 72
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusTranslateWorldTransform` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Gets a value indicating whether [post multiplied matrix]. |
| [getDx()](#getDx--) | Gets or sets a 32-bit floating-point value that defines the horizontal distance. |
| [setDx(float value)](#setDx-float-) | Gets or sets a 32-bit floating-point value that defines the horizontal distance. |
| [getDy()](#getDy--) | Gets or sets a 32-bit floating-point value that defines the vertical distance value. |
| [setDy(float value)](#setDy-float-) | Gets or sets a 32-bit floating-point value that defines the vertical distance value. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusTranslateWorldTransform` class.

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
### getDx() {#getDx--}
```
public float getDx()
```


Gets or sets a 32-bit floating-point value that defines the horizontal distance. The translation is performed by constructing a new world transform matrix from the dx and dy fields

Value: The dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Gets or sets a 32-bit floating-point value that defines the horizontal distance. The translation is performed by constructing a new world transform matrix from the dx and dy fields

Value: The dx.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Gets or sets a 32-bit floating-point value that defines the vertical distance value.

Value: The dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Gets or sets a 32-bit floating-point value that defines the vertical distance value.

Value: The dy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

