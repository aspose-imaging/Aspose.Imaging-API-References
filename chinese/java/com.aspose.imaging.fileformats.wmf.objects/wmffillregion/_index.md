---
title: "WmfFillRegion"
second_title: "Aspose.Imaging for Java API 参考"
description: "META_FILLREGION 记录使用指定的画刷填充区域。"
type: docs
weight: 37
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

该 META\_FILLREGION 记录使用指定的画刷填充区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | 初始化 `WmfFillRegion` 类的新实例。 |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | 初始化 `WmfFillRegion` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | 获取或设置区域的索引。 |
| [setRegionIndex(int value)](#setRegionIndex-int-) | 获取或设置区域的索引。 |
| [getBrushIndex()](#getBrushIndex--) | 获取或设置画刷的索引。 |
| [setBrushIndex(int value)](#setBrushIndex-int-) | 获取或设置画刷的索引。 |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


初始化 `WmfFillRegion` 类的新实例。

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


初始化 `WmfFillRegion` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | 该区域。 |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | 画笔。 |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


获取或设置区域的索引。

值：WMF 对象表中的索引，用于获取要填充的区域。

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


获取或设置区域的索引。

值：WMF 对象表中的索引，用于获取要填充的区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


获取或设置画刷的索引。

值：WMF 对象表中的索引，用于获取用于填充区域的画刷。

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


获取或设置画刷的索引。

值：WMF 对象表中的索引，用于获取用于填充区域的画刷。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

