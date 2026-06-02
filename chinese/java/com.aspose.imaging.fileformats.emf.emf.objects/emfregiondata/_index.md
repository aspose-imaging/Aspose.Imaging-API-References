---
title: "EmfRegionData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "RegionData 对象指定用于定义由不重叠矩形组成的区域的数据。"
type: docs
weight: 33
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

RegionData 对象指定了定义区域的数据，该区域由不重叠的矩形组成。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | 初始化 `EmfRegionData` 类的新实例。 |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | 初始化 `EmfRegionData` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | 获取描述以下数据的 256 位 RegionDataHeader 对象。 |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | 设置描述以下数据的 256 位 RegionDataHeader 对象。 |
| [getData()](#getData--) | 获取 WMF RectL 对象数组（[MS-WMF] 第 2.2.2.19 节）；这些对象将合并以创建区域。 |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | 设置 WMF RectL 对象数组（[MS-WMF] 第 2.2.2.19 节）；这些对象将合并以创建区域。 |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


初始化 `EmfRegionData` 类的新实例。

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


初始化 `EmfRegionData` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


获取描述以下数据的 256 位 RegionDataHeader 对象。

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


设置描述以下数据的 256 位 RegionDataHeader 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


获取 WMF RectL 对象数组（[MS-WMF] 第 2.2.2.19 节）；这些对象将合并以创建区域。

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


设置 WMF RectL 对象数组（[MS-WMF] 第 2.2.2.19 节）；这些对象将合并以创建区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

