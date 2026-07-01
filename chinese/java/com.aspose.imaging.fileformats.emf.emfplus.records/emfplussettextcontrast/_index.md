---
title: "EmfPlusSetTextContrast"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EmfPlusSetTextContrast 记录根据伽马校正值指定文本对比度。"
type: docs
weight: 64
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetTextContrast extends EmfPlusPropertyRecordType
```

该 EmfPlusSetTextContrast 记录根据伽马校正值指定文本对比度。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetTextContrast(EmfPlusRecord source)](#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetTextContrast` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextContrast()](#getTextContrast--) | 获取或设置伽马校正值 X 1000，该值将应用于后续的文本渲染操作。 |
| [setTextContrast(short value)](#setTextContrast-short-) | 获取或设置伽马校正值 X 1000，该值将应用于后续的文本渲染操作。 |
### EmfPlusSetTextContrast(EmfPlusRecord source) {#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTextContrast(EmfPlusRecord source)
```


初始化 `EmfPlusSetTextContrast` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


获取或设置伽马校正值 X 1000，该值将应用于后续的文本渲染操作。允许的范围是 1000 到 2200，表示文本伽马值为 1.0 到 2.2。

**Returns:**
短
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


获取或设置伽马校正值 X 1000，该值将应用于后续的文本渲染操作。允许的范围是 1000 到 2200，表示文本伽马值为 1.0 到 2.2。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

