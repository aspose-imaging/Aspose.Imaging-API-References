---
title: "EmfSetColorAdjustment"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETCOLORADJUSTMENT 记录指定回放设备上下文中的颜色调整属性。"
type: docs
weight: 122
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

EMR\_SETCOLORADJUSTMENT 记录在回放设备上下文中指定颜色调整属性。

当 STRETCH\_HALFTONE 模式从 StretchMode 枚举（第 2.1.32 节）设置时，颜色调整值用于调整源位图的输入颜色，以供 EMR\_STRETCHBLT 和 EMR\_STRETCHDIBITS 记录执行的图形操作。此记录指定的 ColorAdjustment 对象必须在需要 ColorAdjustment 对象的图形操作中使用，直至通过另一个 EMR\_SETCOLORADJUSTMENT 记录指定不同的 ColorAdjustment 对象，或通过 EMR\_DELETEOBJECT 记录将其删除。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetColorAdjustment` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | 获取或设置一个 ColorAdjustment 对象（第 2.2.2 节），该对象指定颜色调整值。 |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | 获取或设置一个 ColorAdjustment 对象（第 2.2.2 节），该对象指定颜色调整值。 |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


初始化 `EmfSetColorAdjustment` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


获取或设置一个 ColorAdjustment 对象（第 2.2.2 节），该对象指定颜色调整值。

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


获取或设置一个 ColorAdjustment 对象（第 2.2.2 节），该对象指定颜色调整值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

