---
title: "EmfPlusSetClipRect"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EmfPlusSetClipRect 记录将当前裁剪区域与矩形合并。"
type: docs
weight: 56
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

该 EmfPlusSetClipRect 记录将当前裁剪区域与矩形合并。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetClipRect` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCm()](#getCm--) | 获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。 |
| [setCm(byte value)](#setCm-byte-) | 获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。 |
| [getClipRect()](#getClipRect--) | 获取或设置一个 EmfPlusRectF 对象（章节 2.2.2.39），该对象定义在 CombineMode 操作中使用的矩形。 |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | 获取或设置一个 EmfPlusRectF 对象（章节 2.2.2.39），该对象定义在 CombineMode 操作中使用的矩形。 |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


初始化 `EmfPlusSetClipRect` 类的新实例。

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

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


获取或设置一个 EmfPlusRectF 对象（章节 2.2.2.39），该对象定义在 CombineMode 操作中使用的矩形。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


获取或设置一个 EmfPlusRectF 对象（章节 2.2.2.39），该对象定义在 CombineMode 操作中使用的矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

