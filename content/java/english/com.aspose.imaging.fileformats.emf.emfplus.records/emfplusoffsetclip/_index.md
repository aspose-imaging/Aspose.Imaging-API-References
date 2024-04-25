---
title: EmfPlusOffsetClip
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space.
type: docs
weight: 44
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusOffsetClip extends EmfPlusClippingRecordType
```

The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space. The new current clipping region is set to the result of the translation transform.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusOffsetClip(EmfPlusRecord source)](#EmfPlusOffsetClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusOffsetClip` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDx()](#getDx--) | Gets or sets a 32-bit floating-point value that specifies the horizontal offset for the translation. |
| [setDx(float value)](#setDx-float-) | Gets or sets a 32-bit floating-point value that specifies the horizontal offset for the translation. |
| [getDy()](#getDy--) | Gets or sets a 32-bit floating-point value that specifies the vertical offset for the translation. |
| [setDy(float value)](#setDy-float-) | Gets or sets a 32-bit floating-point value that specifies the vertical offset for the translation. |
### EmfPlusOffsetClip(EmfPlusRecord source) {#EmfPlusOffsetClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusOffsetClip(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusOffsetClip` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getDx() {#getDx--}
```
public float getDx()
```


Gets or sets a 32-bit floating-point value that specifies the horizontal offset for the translation.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Gets or sets a 32-bit floating-point value that specifies the horizontal offset for the translation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Gets or sets a 32-bit floating-point value that specifies the vertical offset for the translation.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Gets or sets a 32-bit floating-point value that specifies the vertical offset for the translation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

