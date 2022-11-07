---
title: EmfPlusCompoundLineData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusCompoundLineData object specifies line and space data for a compound line.
type: docs
weight: 30
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCompoundLineData extends EmfPlusStructureObjectType
```

The EmfPlusCompoundLineData object specifies line and space data for a compound line.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusCompoundLineData()](#EmfPlusCompoundLineData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCompoundLineData()](#getCompoundLineData--) | Gets or sets an array of CompoundLineDataSize floating-point values that specify the compound line of a pen. |
| [setCompoundLineData(float[] value)](#setCompoundLineData-float---) | Gets or sets an array of CompoundLineDataSize floating-point values that specify the compound line of a pen. |
### EmfPlusCompoundLineData() {#EmfPlusCompoundLineData--}
```
public EmfPlusCompoundLineData()
```


### getCompoundLineData() {#getCompoundLineData--}
```
public float[] getCompoundLineData()
```


Gets or sets an array of CompoundLineDataSize floating-point values that specify the compound line of a pen. The elements MUST be in increasing order, and their values MUST be between 0.0 and 1.0, inclusive

**Returns:**
float[]
### setCompoundLineData(float[] value) {#setCompoundLineData-float---}
```
public void setCompoundLineData(float[] value)
```


Gets or sets an array of CompoundLineDataSize floating-point values that specify the compound line of a pen. The elements MUST be in increasing order, and their values MUST be between 0.0 and 1.0, inclusive

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

