---
title: EmfModifyWorldTransform
second_title: Aspose.Imaging for Java API Reference
description: The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space transform in the playback device context.
type: docs
weight: 72
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

The EMR\_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space transform in the playback device context.

For more information concerning transforms and coordinate spaces, see [MSDN-WRLDPGSPC]. See section 2.3.12 for the specification of other transform record types.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfModifyWorldTransform` class. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Initializes a new instance of the `EmfModifyWorldTransform` class. |
## Methods

| Method | Description |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Gets or sets a 32-bit unsigned integer that specifies how the transform specified in Xform is used. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Gets or sets a 32-bit unsigned integer that specifies how the transform specified in Xform is used. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Initializes a new instance of the `EmfModifyWorldTransform` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Initializes a new instance of the `EmfModifyWorldTransform` class.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Gets or sets a 32-bit unsigned integer that specifies how the transform specified in Xform is used. This value MUST be in the ModifyWorldTransformMode enumeration (section 2.1.24).

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how the transform specified in Xform is used. This value MUST be in the ModifyWorldTransformMode enumeration (section 2.1.24).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

