---
title: "WmfFrameRegion"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 wmf frame region 对象。"
type: docs
weight: 39
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfframeregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfFrameRegion extends WmfObject
```

该 wmf frame region 对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfFrameRegion()](#WmfFrameRegion--) | 初始化 `WmfFillRegion` 类的新实例。 |
| [WmfFrameRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFrameRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | 初始化 `WmfFillRegion` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | 获取或设置区域的索引。 |
| [setRegionIndex(int value)](#setRegionIndex-int-) | 获取或设置区域的索引。 |
| [getBrushIndex()](#getBrushIndex--) | 获取或设置画笔的索引。 |
| [setBrushIndex(int value)](#setBrushIndex-int-) | 获取或设置画笔的索引。 |
| [getHeight()](#getHeight--) | 获取或设置高度。 |
| [setHeight(short value)](#setHeight-short-) | 获取或设置高度。 |
| [getWidth()](#getWidth--) | 获取或设置宽度。 |
| [setWidth(short value)](#setWidth-short-) | 获取或设置宽度。 |
### WmfFrameRegion() {#WmfFrameRegion--}
```
public WmfFrameRegion()
```


初始化 `WmfFillRegion` 类的新实例。

### WmfFrameRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFrameRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFrameRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


初始化 `WmfFillRegion` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | 该区域。 |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | 画刷。 |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


获取或设置区域的索引。

值：在 WMF 对象表中的索引，用于获取要填充的区域。

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


获取或设置区域的索引。

值：在 WMF 对象表中的索引，用于获取要填充的区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


获取或设置画笔的索引。

值：在 WMF 对象表中的索引，用于获取用于填充区域的画笔。

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


获取或设置画笔的索引。

值：在 WMF 对象表中的索引，用于获取用于填充区域的画笔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


获取或设置高度。

值：区域框架的高度（逻辑单位）。

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


获取或设置高度。

值：区域框架的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


获取或设置宽度。

值：区域框架的宽度（逻辑单位）。

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


获取或设置宽度。

值：区域框架的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

