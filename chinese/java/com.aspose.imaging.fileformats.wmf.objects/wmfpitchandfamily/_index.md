---
title: "WmfPitchAndFamily"
second_title: "Aspose.Imaging for Java API 参考"
description: "PitchAndFamily 对象指定 Font 对象的间距和族属性（第 2.2.1.2 节）。"
type: docs
weight: 54
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

PitchAndFamily 对象指定 Font 对象的间距和族属性（第 2.2.1.2 节）。间距指字符的宽度，族指字体的一般外观。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | 初始化 `WmfPitchAndFamily` 结构的新实例。 |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | 初始化 `WmfPitchAndFamily` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFamily()](#getFamily--) | 获取字体的一个属性，该属性描述其整体外观。 |
| [getPitch()](#getPitch--) | 获取字体的一个属性，该属性描述字符的音高。 |
| [getByteData()](#getByteData--) | 设置 `` 数据。 |
| [setByteData(byte value)](#setByteData-byte-) | 设置 `` 数据。 |
| [toByte()](#toByte--) | 到字节。 |
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


初始化 `WmfPitchAndFamily` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| byteData | byte | 该 `` 数据。 |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


初始化 `WmfPitchAndFamily` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pitch | byte | 该音高。 |
| family | byte | 该字体族。 |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


获取字体的一个属性，该属性描述其整体外观。此值必须是 FamilyFont 枚举中的一个值。

值：该字体族。

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


获取字体的一个属性，该属性描述字符的音高。此值必须是 PitchFont 枚举中的一个值。

值：该音高。

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


设置 `` 数据。

值：该 `` 数据。

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


设置 `` 数据。

值：该 `` 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


到字节。

**Returns:**
byte - 字节值。
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
