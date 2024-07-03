---
title: EmfSetColorAdjustment
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETCOLORADJUSTMENT record specifies color adjustment properties in the playback device context.
type: docs
weight: 122
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

The EMR\_SETCOLORADJUSTMENT record specifies color adjustment properties in the playback device context.

Color adjustment values are used to adjust the input color of the source bitmap for graphics operations performed by EMR\_STRETCHBLT and EMR\_STRETCHDIBITS records when STRETCH\_HALFTONE mode is set from the StretchMode enumeration (section 2.1.32). The ColorAdjustment object specified by this record MUST be used in graphics operations that require a ColorAdjustment object, until a different ColorAdjustment object is specified by another EMR\_SETCOLORADJUSTMENT record, or until the object is removed by a EMR\_DELETEOBJECT record.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetColorAdjustment` class. |
## Methods

| Method | Description |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Gets or sets a ColorAdjustment object (section 2.2.2) that specifies color adjustment values. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Gets or sets a ColorAdjustment object (section 2.2.2) that specifies color adjustment values. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


Initializes a new instance of the `EmfSetColorAdjustment` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Gets or sets a ColorAdjustment object (section 2.2.2) that specifies color adjustment values.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Gets or sets a ColorAdjustment object (section 2.2.2) that specifies color adjustment values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

