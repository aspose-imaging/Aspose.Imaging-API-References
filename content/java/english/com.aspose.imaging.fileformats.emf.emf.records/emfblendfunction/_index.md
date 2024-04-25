---
title: EmfBlendFunction
second_title: Aspose.Imaging for Java API Reference
description: A structure that specifies the blending operations for source and destination bitmaps.
type: docs
weight: 18
url: /com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

A structure that specifies the blending operations for source and destination bitmaps.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | Initializes a new instance of the `EmfBlendFunction` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Gets the blend operation code. |
| [getBlendFlags()](#getBlendFlags--) | Gets the blend flags. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Gets an 8-bit unsigned integer that specifies alpha transparency, which determines the blend of the source and destination bitmaps. |
| [getAlphaFormat()](#getAlphaFormat--) | Gets a structure that specifies how source and destination pixels are interpreted with respect to alpha transparency. |
| [toInt()](#toInt--) | Converts the string representation of a number to an integer. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


Initializes a new instance of the `EmfBlendFunction` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dwordData | int | The dword data. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Gets the blend operation code. The only source and destination blend operation that has been defined is 0x00, which specifies that the source bitmap MUST be combined with the destination bitmap based on the alpha transparency values of the source pixels. See the following equations for details.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Gets the blend flags. This value MUST be 0x00 and MUST be ignored.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Gets an 8-bit unsigned integer that specifies alpha transparency, which determines the blend of the source and destination bitmaps. This value MUST be used on the entire source bitmap. The minimum alpha transparency value, zero, corresponds to completely transparent the maximum value, 0xFF, corresponds to completely opaque. In effect, a value of 0xFF specifies that the per-pixel alpha values determine the blend of the source and destination bitmaps. See the equations later in this section for details.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Gets a structure that specifies how source and destination pixels are interpreted with respect to alpha transparency.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Converts the string representation of a number to an integer.

**Returns:**
int - The DWORD value of structure.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
