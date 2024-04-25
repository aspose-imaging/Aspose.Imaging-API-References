---
title: EmfDesignVector
second_title: Aspose.Imaging for Java API Reference
description: The DesignVector section 2.2.3 object defines the design vector which specifies values for the font axes of a multiple master font.
type: docs
weight: 13
url: /com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Gets or sets a 32-bit unsigned integer that MUST be set to the value 0x08007664. |
| [setSignature(int value)](#setSignature-int-) | Gets or sets a 32-bit unsigned integer that MUST be set to the value 0x08007664. |
| [getNumAxes()](#getNumAxes--) | Gets or sets a 32-bit unsigned integer that specifies the number of elements in the Values array. |
| [setNumAxes(int value)](#setNumAxes-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of elements in the Values array. |
| [getValues()](#getValues--) | Gets or sets an optional array of 32-bit signed integers that specify the values of the font axes of a multiple master, OpenType font. |
| [setValues(int[] value)](#setValues-int---) | Gets or sets an optional array of 32-bit signed integers that specify the values of the font axes of a multiple master, OpenType font. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets or sets a 32-bit unsigned integer that MUST be set to the value 0x08007664.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Gets or sets a 32-bit unsigned integer that MUST be set to the value 0x08007664.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


Gets or sets a 32-bit unsigned integer that specifies the number of elements in the Values array. It MUST be in the range 0 to 16, inclusive

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of elements in the Values array. It MUST be in the range 0 to 16, inclusive

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Gets or sets an optional array of 32-bit signed integers that specify the values of the font axes of a multiple master, OpenType font. The maximum number of values in the array is 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Gets or sets an optional array of 32-bit signed integers that specify the values of the font axes of a multiple master, OpenType font. The maximum number of values in the array is 16.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

