---
title: "EmfSelectClipPath"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SELECTCLIPPATH 记录将当前路径指定为回放设备上下文的剪裁区域，并使用指定的模式将新区域与任何现有剪裁区域合并。"
type: docs
weight: 115
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

EMR\_SELECTCLIPPATH 记录将当前路径指定为回放设备上下文的裁剪区域，使用指定的模式将新区域与任何现有裁剪区域合并。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSelectClipPath` 类的新实例。 |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | 初始化 `EmfSelectClipPath` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | 获取或设置一个 32 位无符号整数，用于指定路径的使用方式。 |
| [setRegionMode(int value)](#setRegionMode-int-) | 获取或设置一个 32 位无符号整数，用于指定路径的使用方式。 |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


初始化 `EmfSelectClipPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


初始化 `EmfSelectClipPath` 类的新实例。

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


获取或设置一个 32 位无符号整数，用于指定路径的使用方式。该值 必须属于 RegionMode 枚举（第 2.1.29 节）。

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


获取或设置一个 32 位无符号整数，用于指定路径的使用方式。该值 必须属于 RegionMode 枚举（第 2.1.29 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

