---
title: EmfPlusSerializableObject
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSerializableObject record defines an image effects parameter block that has been serialized into a data buffer.
type: docs
weight: 53
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

The EmfPlusSerializableObject record defines an image effects parameter block that has been serialized into a data buffer.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSerializableObject` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Gets or sets a 16-bit unsigned integer that is not used. |
| [setFlags(short value)](#setFlags-short-) | Gets or sets a 16-bit unsigned integer that is not used. |
| [getObjectGuid()](#getObjectGuid--) | Gets or sets the GUID packet representation value ([MS-DTYP] section 2.3.4.2) for the image effect. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Gets or sets the GUID packet representation value ([MS-DTYP] section 2.3.4.2) for the image effect. |
| [getBufferSize()](#getBufferSize--) | Gets or sets a 32-bit unsigned integer that specifies the size in bytes of the 32-bitaligned Buffer field. |
| [setBufferSize(int value)](#setBufferSize-int-) | Gets or sets a 32-bit unsigned integer that specifies the size in bytes of the 32-bitaligned Buffer field. |
| [getBuffer()](#getBuffer--) | Gets or sets an array of BufferSize bytes that contain the serialized image effects parameter block that corresponds to the GUID in the ObjectGUID field. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | Gets or sets an array of BufferSize bytes that contain the serialized image effects parameter block that corresponds to the GUID in the ObjectGUID field. |
| [getImageEffect()](#getImageEffect--) | Gets or sets the image effect. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Gets or sets the image effect. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSerializableObject` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero and MUST be ignored upon receipt.

Value: The flags.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero and MUST be ignored upon receipt.

Value: The flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Gets or sets the GUID packet representation value ([MS-DTYP] section 2.3.4.2) for the image effect. This MUST correspond to one of the ImageEffects identifiers (section 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Gets or sets the GUID packet representation value ([MS-DTYP] section 2.3.4.2) for the image effect. This MUST correspond to one of the ImageEffects identifiers (section 2.1.3.1).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


Gets or sets a 32-bit unsigned integer that specifies the size in bytes of the 32-bitaligned Buffer field.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size in bytes of the 32-bitaligned Buffer field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


Gets or sets an array of BufferSize bytes that contain the serialized image effects parameter block that corresponds to the GUID in the ObjectGUID field. This MUST be one of the Image Effects objects (section 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


Gets or sets an array of BufferSize bytes that contain the serialized image effects parameter block that corresponds to the GUID in the ObjectGUID field. This MUST be one of the Image Effects objects (section 2.2.3).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Gets or sets the image effect.

Value: The image effect.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Gets or sets the image effect.

Value: The image effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

