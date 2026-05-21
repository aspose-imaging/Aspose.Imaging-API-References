---
title: "ImageResizeSettings"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Image 调整大小设置类"
type: docs
weight: 63
url: /zh/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Image 调整大小设置类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | 初始化 `ImageResizeSettings` 类的新实例，Resize type = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample))，Filter type = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular))，Color quantization method = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity))，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | 初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Filter type = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None))，Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None))，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | 初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None))，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | 初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | 初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | 获取条目计数 |
| [setEntriesCount(int value)](#setEntriesCount-int-) | 设置条目计数 |
| [getMode()](#getMode--) | 获取插值模式。 |
| [setMode(int value)](#setMode-int-) | 设置插值模式。 |
| [getFilterType()](#getFilterType--) | 获取过滤器的类型。 |
| [setFilterType(int value)](#setFilterType-int-) | 设置过滤器的类型。 |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | 获取颜色量化方法。 |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | 设置颜色量化方法。 |
| [getColorCompareMethod()](#getColorCompareMethod--) | 获取颜色比较方法。 |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | 设置颜色比较方法。 |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


初始化 `ImageResizeSettings` 类的新实例，Resize type = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample))，Filter type = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular))，Color quantization method = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity))，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Filter type = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None))，Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None))，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeType | int | 缩放类型。 |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None))，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeType | int | 缩放类型。 |
| filterType | int | 过滤器类型。 |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian))，Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeType | int | 缩放类型。 |
| filterType | int | 过滤器类型。 |
| colorQuantizationMethod | int | 颜色量化方法。 |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


初始化 [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) 类的新实例，Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeType | int | 缩放类型。 |
| filterType | int | 过滤器类型。 |
| colorQuantizationMethod | int | 颜色量化方法。 |
| colorCompareMethod | int | 颜色比较方法。 |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


获取条目计数

**Returns:**
int - 条目计数
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


设置条目计数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 条目计数 |

### getMode() {#getMode--}
```
public int getMode()
```


获取插值模式。

**Returns:**
int - 模式。
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


设置插值模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 模式。 |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


获取过滤器的类型。

**Returns:**
int - 过滤器的类型。
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


设置过滤器的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 过滤器的类型。 |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


获取颜色量化方法。

**Returns:**
int - 颜色量化方法。
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


设置颜色量化方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 颜色量化方法。 |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


获取颜色比较方法。

**Returns:**
int - 颜色比较方法。
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


设置颜色比较方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 颜色比较方法。 |

