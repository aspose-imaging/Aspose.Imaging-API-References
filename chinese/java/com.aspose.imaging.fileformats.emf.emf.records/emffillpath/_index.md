---
title: "EmfFillPath"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_FILLPATH 记录关闭当前路径中的所有未闭合图形，并使用当前画刷和多边形填充模式填充路径内部。"
type: docs
weight: 58
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emffillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillPath extends EmfDrawingRecordType
```

EMR_FILLPATH 记录关闭当前路径中的所有未闭合图形，并使用当前画刷和多边形填充模式填充路径内部。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfFillPath(EmfRecord source)](#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfFillPath` 类的新实例。 |
| [EmfFillPath()](#EmfFillPath--) | 初始化 `EmfFillPath` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），用于指定以设备单位表示的边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），用于指定以设备单位表示的边界矩形。 |
### EmfFillPath(EmfRecord source) {#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillPath(EmfRecord source)
```


初始化 `EmfFillPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfFillPath() {#EmfFillPath--}
```
public EmfFillPath()
```


初始化 `EmfFillPath` 类的新实例。

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），用于指定以设备单位表示的边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），用于指定以设备单位表示的边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

