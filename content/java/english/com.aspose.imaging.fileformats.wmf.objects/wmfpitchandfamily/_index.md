---
title: WmfPitchAndFamily
second_title: Aspose.Imaging for Java API Reference
description: The PitchAndFamily object specifies the pitch and family properties of a     Font object section 2.2.1.2.
type: docs
weight: 54
url: /com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

The PitchAndFamily object specifies the pitch and family properties of a Font object (section 2.2.1.2). Pitch refers to the width of the characters, and family refers to the general appearance of a font.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | Initializes a new instance of the `WmfPitchAndFamily` struct. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | Initializes a new instance of the `WmfPitchAndFamily` struct. |
## Methods

| Method | Description |
| --- | --- |
| [getFamily()](#getFamily--) | Gets A property of a font that describes its general appearance. |
| [getPitch()](#getPitch--) | Gets A property of a font that describes the pitch, of the characters. |
| [getByteData()](#getByteData--) | Sets the `` data. |
| [setByteData(byte value)](#setByteData-byte-) | Sets the `` data. |
| [toByte()](#toByte--) | To the byte. |
| [CloneTo(WmfPitchAndFamily that)](#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)](#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
### WmfPitchAndFamily() {#WmfPitchAndFamily--}
```
public WmfPitchAndFamily()
```


### WmfPitchAndFamily(byte byteData) {#WmfPitchAndFamily-byte-}
```
public WmfPitchAndFamily(byte byteData)
```


Initializes a new instance of the `WmfPitchAndFamily` struct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteData | byte | The `` data. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


Initializes a new instance of the `WmfPitchAndFamily` struct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pitch | byte | The pitch. |
| family | byte | The family. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Gets A property of a font that describes its general appearance. This MUST be a value in the FamilyFont enumeration

Value: The family.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Gets A property of a font that describes the pitch, of the characters. This MUST be a value in the PitchFont enumeration.

Value: The pitch.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


Sets the `` data.

Value: The `` data.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


Sets the `` data.

Value: The `` data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


To the byte.

**Returns:**
byte - The byte value.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### Clone() {#Clone--}
```
public WmfPitchAndFamily Clone()
```




**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
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
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
