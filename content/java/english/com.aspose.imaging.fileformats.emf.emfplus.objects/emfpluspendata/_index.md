---
title: EmfPlusPenData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPenData object specifies properties of a graphics pen.
type: docs
weight: 64
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

The EmfPlusPenData object specifies properties of a graphics pen.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. |
| [getPenUnit()](#getPenUnit--) | Gets or sets 32-bit unsigned integer that specifies the measuring units for the pen. |
| [setPenUnit(int value)](#setPenUnit-int-) | Gets or sets 32-bit unsigned integer that specifies the measuring units for the pen. |
| [getPenWidth()](#getPenWidth--) | Gets or sets 32-bit floating-point value that specifies the width of the line drawn by the pen in the units specified by the PenUnit field. |
| [setPenWidth(float value)](#setPenWidth-float-) | Gets or sets 32-bit floating-point value that specifies the width of the line drawn by the pen in the units specified by the PenUnit field. |
| [getOptionalData()](#getOptionalData--) | Gets or sets optional EmfPlusPenOptionalData object (section 2.2.2.34) that specifies additional data for the pen object. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Gets or sets optional EmfPlusPenOptionalData object (section 2.2.2.34) that specifies additional data for the pen object. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of PenData flags (section 2.1.2.7).

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of PenData flags (section 2.1.2.7).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Gets or sets 32-bit unsigned integer that specifies the measuring units for the pen. The value MUST be from the UnitType enumeration (section 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Gets or sets 32-bit unsigned integer that specifies the measuring units for the pen. The value MUST be from the UnitType enumeration (section 2.1.1.33).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


Gets or sets 32-bit floating-point value that specifies the width of the line drawn by the pen in the units specified by the PenUnit field. If a zero width is specified, a minimum value is used, which is determined by the units

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


Gets or sets 32-bit floating-point value that specifies the width of the line drawn by the pen in the units specified by the PenUnit field. If a zero width is specified, a minimum value is used, which is determined by the units

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Gets or sets optional EmfPlusPenOptionalData object (section 2.2.2.34) that specifies additional data for the pen object. The specific contents of this field are determined by the value of the PenDataFlags field.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Gets or sets optional EmfPlusPenOptionalData object (section 2.2.2.34) that specifies additional data for the pen object. The specific contents of this field are determined by the value of the PenDataFlags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

