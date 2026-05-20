---
title: "EmfCommentBeginGroup"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_COMMENT_BEGINGROUP 记录指定一组绘图记录的开始。"
type: docs
weight: 26
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

EMR\_COMMENT\_BEGINGROUP 记录指定一组绘图记录的开始。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCommentBeginGroup` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRectangle()](#getRectangle--) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定逻辑坐标中的输出矩形。 |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定逻辑坐标中的输出矩形。 |
| [getNDescription()](#getNDescription--) | 获取或设置后续可选描述字符串中的 Unicode 字符数量。 |
| [setNDescription(int value)](#setNDescription-int-) | 获取或设置后续可选描述字符串中的 Unicode 字符数量。 |
| [getDescription()](#getDescription--) | 获取或设置一个可选的、以空字符结尾的 Unicode 字符串，用于描述此记录组。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 获取或设置一个可选的、以空字符结尾的 Unicode 字符串，用于描述此记录组。 |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


初始化 `EmfCommentBeginGroup` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定逻辑坐标中的输出矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定逻辑坐标中的输出矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


获取或设置后续可选描述字符串中的 Unicode 字符数量。

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


获取或设置后续可选描述字符串中的 Unicode 字符数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


获取或设置一个可选的、以空字符结尾的 Unicode 字符串，用于描述此记录组。

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


获取或设置一个可选的、以空字符结尾的 Unicode 字符串，用于描述此记录组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

