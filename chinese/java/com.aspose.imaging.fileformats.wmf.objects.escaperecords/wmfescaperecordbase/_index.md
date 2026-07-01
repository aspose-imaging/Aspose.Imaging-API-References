---
title: "WmfEscapeRecordBase"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 escape 记录基类。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfEscapeRecordBase extends WmfObject
```

该 escape 记录基类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfEscapeRecordBase()](#WmfEscapeRecordBase--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getByteCount()](#getByteCount--) | 获取或设置字节计数。 |
| [setByteCount(int value)](#setByteCount-int-) | 获取或设置字节计数。 |
| [getData()](#getData--) | 获取或设置数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置数据。 |
| [getChecked()](#getChecked--) | 获取一个值，指示此 `WmfEscapeRecordBase` 是否已选中。 |
| [setChecked(boolean value)](#setChecked-boolean-) | 获取一个值，指示此 `WmfEscapeRecordBase` 是否已选中。 |
### WmfEscapeRecordBase() {#WmfEscapeRecordBase--}
```
public WmfEscapeRecordBase()
```


### getByteCount() {#getByteCount--}
```
public int getByteCount()
```


获取或设置字节计数。

值：一个 16 位无符号整数，指定随后记录数据的大小（单位为字节）。此值必须等于 34 加上 EnhancedMetafileDataSize 字段的值。

**Returns:**
int
### setByteCount(int value) {#setByteCount-int-}
```
public void setByteCount(int value)
```


获取或设置字节计数。

值：一个 16 位无符号整数，指定随后记录数据的大小（单位为字节）。此值必须等于 34 加上 EnhancedMetafileDataSize 字段的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置数据。

值：数据。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置数据。

值：数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### getChecked() {#getChecked--}
```
public boolean getChecked()
```


获取一个值，指示此 `WmfEscapeRecordBase` 是否已选中。

值：如果已选中则为 `true`；否则为 `false`。

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public void setChecked(boolean value)
```


获取一个值，指示此 `WmfEscapeRecordBase` 是否已选中。

值：如果已选中则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

