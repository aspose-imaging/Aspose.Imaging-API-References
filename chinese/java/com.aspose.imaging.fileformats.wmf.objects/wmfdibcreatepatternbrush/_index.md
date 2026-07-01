---
title: "WmfDibCreatePatternBrush"
second_title: "Aspose.Imaging for Java API 参考"
description: "META_DIBCREATEPATTERNBRUSH 记录创建一个 Brush Object 部分 2.2.1.1，使用由 DeviceIndependentBitmap DIB 对象部分 2.2.2.9 指定的图案。"
type: docs
weight: 29
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

META\_DIBCREATEPATTERNBRUSH 记录创建一个刷子对象（第 2.2.1.1 节），其图案由 DeviceIndependentBitmap (DIB) 对象（第 2.2.2.9 节）指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStyle()](#getStyle--) | 获取或设置样式。 |
| [setStyle(int value)](#setStyle-int-) | 获取或设置样式。 |
| [getColorUsage()](#getColorUsage--) | 获取或设置颜色使用情况。 |
| [setColorUsage(int value)](#setColorUsage-int-) | 获取或设置颜色使用情况。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置源位图。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置源位图。 |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


获取或设置样式。

值：此字段的合法值定义如下：如果值不是 BS\_PATTERN，则必须假设为 BS\_DIBPATTERNPT。这些值在 BrushStyle 枚举中指定（第 2.1.1.4 节）。

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


获取或设置样式。

值：此字段的合法值定义如下：如果值不是 BS\_PATTERN，则必须假设为 BS\_DIBPATTERNPT。这些值在 BrushStyle 枚举中指定（第 2.1.1.4 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


获取或设置颜色使用情况。

值：DIB 对象的 Colors 字段包含显式的 RGB 值，或调色板中的索引。

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


获取或设置颜色使用情况。

值：DIB 对象的 Colors 字段包含显式的 RGB 值，或调色板中的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


获取或设置源位图。

值：可变位 DIB 对象数据，定义在画笔中使用的图案。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置源位图。

值：可变位 DIB 对象数据，定义在画笔中使用的图案。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

