---
title: "RawDataSettings"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "原始数据设置"
type: docs
weight: 92
url: /zh/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

原始数据设置
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | 已初始化为空实例。 |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | 初始化 `origin` 的副本。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | 获取像素数据格式 |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | 设置像素数据格式 |
| [getColorPalette()](#getColorPalette--) | 获取颜色调色板 |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | 设置颜色调色板 |
| [getDitheringMethod()](#getDitheringMethod--) | 获取用于原始数据转换的抖动方法 |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | 设置用于原始数据转换的抖动方法 |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | 获取索引颜色转换器 |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | 设置索引颜色转换器 |
| [getCustomColorConverter()](#getCustomColorConverter--) | 获取自定义颜色转换器 |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | 设置自定义颜色转换器 |
| [getFallbackIndex()](#getFallbackIndex--) | 获取当调色板索引超出范围时使用的回退索引 |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | 设置当调色板索引超出范围时使用的回退索引 |
| [getLineSize()](#getLineSize--) | 获取用于原始数据处理的像素行大小（字节） |
| [setLineSize(int value)](#setLineSize-int-) | 设置用于原始数据处理的像素行大小（字节） |
| [<T>copy()](#-T-copy--) | 创建浅拷贝。 |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


已初始化为空实例。

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


初始化 `origin` 的副本。用于 [copy()](../../com.aspose.imaging/rawdatasettings\\#copy--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | 要复制的实例。 |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


获取像素数据格式

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


设置像素数据格式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | 像素数据格式 |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


获取颜色调色板

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


设置颜色调色板

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板 |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


获取用于原始数据转换的抖动方法

**Returns:**
int - 用于原始数据转换的抖动方法
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


设置用于原始数据转换的抖动方法

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 用于原始数据转换的抖动方法 |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


获取索引颜色转换器

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


设置索引颜色转换器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | 索引颜色转换器 |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


获取自定义颜色转换器

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


设置自定义颜色转换器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | 自定义颜色转换器 |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


获取当调色板索引超出范围时使用的回退索引

**Returns:**
int - 当调色板索引超出范围时使用的回退索引
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


设置当调色板索引超出范围时使用的回退索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 当调色板索引超出范围时使用的回退索引 |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


获取用于原始数据处理的像素行大小（字节）

**Returns:**
int - 用于原始数据处理的像素行大小（字节）
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


设置用于原始数据处理的像素行大小（字节）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 原始数据处理的像素行大小（字节） |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


创建浅拷贝。

**Returns:**
T - 浅拷贝。
