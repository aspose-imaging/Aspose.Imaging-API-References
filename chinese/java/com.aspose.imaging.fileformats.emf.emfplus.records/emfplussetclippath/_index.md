---
title: "EmfPlusSetClipPath"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EmfPlusSetClipPath 记录将当前裁剪区域与图形路径合并。"
type: docs
weight: 55
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

EmfPlusSetClipPath 记录将当前剪裁区域与图形路径合并。新的当前剪裁区域被设置为 CombineMode 操作的结果。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetClipPath` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCm()](#getCm--) | 获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。 |
| [setCm(byte value)](#setCm-byte-) | 获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。 |
| [getObjectId()](#getObjectId--) | 获取或设置 EmfPlusPath 对象（第 2.2.1.6 节）在 EMF+ 对象表中的索引。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置 EmfPlusPath 对象（第 2.2.1.6 节）在 EMF+ 对象表中的索引。 |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


初始化 `EmfPlusSetClipPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getCm() {#getCm--}
```
public byte getCm()
```


获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。有关各值的含义，请参阅 CombineMode 枚举（第 2.1.1.4 节）。

值：cm。

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。有关各值的含义，请参阅 CombineMode 枚举（第 2.1.1.4 节）。

值：cm。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置 EMF+ 对象表中 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置 EMF+ 对象表中 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

