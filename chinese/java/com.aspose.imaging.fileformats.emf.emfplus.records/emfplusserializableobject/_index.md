---
title: "EmfPlusSerializableObject"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusSerializableObject 记录定义已序列化到数据缓冲区的图像效果参数块。"
type: docs
weight: 53
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

EmfPlusSerializableObject 记录定义已序列化到数据缓冲区的图像效果参数块。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSerializableObject` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFlags()](#getFlags--) | 获取或设置未使用的 16 位无符号整数。 |
| [setFlags(short value)](#setFlags-short-) | 获取或设置未使用的 16 位无符号整数。 |
| [getObjectGuid()](#getObjectGuid--) | 获取或设置图像效果的 GUID 包表示值（[MS-DTYP] 第 2.3.4.2 节）。 |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | 获取或设置图像效果的 GUID 包表示值（[MS-DTYP] 第 2.3.4.2 节）。 |
| [getBufferSize()](#getBufferSize--) | 获取或设置一个 32 位无符号整数，指定 32 位对齐的 Buffer 字段的字节大小。 |
| [setBufferSize(int value)](#setBufferSize-int-) | 获取或设置一个 32 位无符号整数，指定 32 位对齐的 Buffer 字段的字节大小。 |
| [getBuffer()](#getBuffer--) | 获取或设置一个 BufferSize 字节的数组，包含与 ObjectGUID 字段中的 GUID 对应的序列化图像效果参数块。 |
| [setBuffer(byte[] value)](#setBuffer-byte---) | 获取或设置一个 BufferSize 字节的数组，包含与 ObjectGUID 字段中的 GUID 对应的序列化图像效果参数块。 |
| [getImageEffect()](#getImageEffect--) | 获取或设置图像效果。 |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | 获取或设置图像效果。 |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


初始化 `EmfPlusSerializableObject` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getFlags() {#getFlags--}
```
public short getFlags()
```


获取或设置一个未使用的 16 位无符号整数。此字段应设置为零，且在接收时必须被忽略。

值：标志。

**Returns:**
短
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


获取或设置一个未使用的 16 位无符号整数。此字段应设置为零，且在接收时必须被忽略。

值：标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


获取或设置图像效果的 GUID 包表示值（[MS-DTYP] 第 2.3.4.2 节）。该值必须对应于 ImageEffects 标识符之一（第 2.1.3.1 节）。

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


获取或设置图像效果的 GUID 包表示值（[MS-DTYP] 第 2.3.4.2 节）。该值必须对应于 ImageEffects 标识符之一（第 2.1.3.1 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


获取或设置一个 32 位无符号整数，指定 32 位对齐的 Buffer 字段的字节大小。

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


获取或设置一个 32 位无符号整数，指定 32 位对齐的 Buffer 字段的字节大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


获取或设置一个 BufferSize 字节的数组，包含与 ObjectGUID 字段中的 GUID 对应的序列化图像效果参数块。该数组必须是 Image Effects 对象之一（第 2.2.3 节）。

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


获取或设置一个 BufferSize 字节的数组，包含与 ObjectGUID 字段中的 GUID 对应的序列化图像效果参数块。该数组必须是 Image Effects 对象之一（第 2.2.3 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


获取或设置图像效果。

值：图像效果。

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


获取或设置图像效果。

值：图像效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

