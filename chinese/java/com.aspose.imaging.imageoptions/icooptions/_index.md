---
title: "IcoOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用我们的 API 轻松创建用于应用程序图标的自定义 ICO 图像文件，帮助您无缝展示软件。"
type: docs
weight: 24
url: /zh/java/com.aspose.imaging.imageoptions/icooptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class IcoOptions extends ImageOptionsBase
```

使用我们的 API 轻松创建用于应用程序图标的自定义 ICO 图像文件，帮助您无缝展示软件。我们的 API 支持 PNG 和 BMP 图像帧以及各种每像素位数，确保在图标创建需求中具备多样性和兼容性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [IcoOptions()](#IcoOptions--) | 初始化 [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) 类的新实例，ICO 帧格式设为 Png，bitsPerPixel 为 32。 |
| [IcoOptions(IcoOptions options)](#IcoOptions-com.aspose.imaging.imageoptions.IcoOptions-) |  |
| [IcoOptions(long format)](#IcoOptions-long-) | 初始化 [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) 类的新实例，ICO 帧格式设为 [`format`]，bitsPerPixel 为 32。 |
| [IcoOptions(long format, int bitsPerPixel)](#IcoOptions-long-int-) | 初始化 [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) | 获取 ICO 帧格式。 |
| [setFormat(long value)](#setFormat-long-) | 设置 ICO 帧格式。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取 bits-per-pixel 值。 |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | 设置 bits-per-pixel 值。 |
### IcoOptions() {#IcoOptions--}
```
public IcoOptions()
```


初始化 [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) 类的新实例，ICO 帧格式设为 Png，bitsPerPixel 为 32。

### IcoOptions(IcoOptions options) {#IcoOptions-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoOptions(IcoOptions options)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) |  |

### IcoOptions(long format) {#IcoOptions-long-}
```
public IcoOptions(long format)
```


初始化 [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) 类的新实例，ICO 帧格式设为 [`format`]，bitsPerPixel 为 32。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | long | ICO 帧格式。请注意，ICO 图像仅支持 [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png) 和 [FileFormat.Bmp](../../com.aspose.imaging/fileformat\#Bmp) 作为条目。 |

### IcoOptions(long format, int bitsPerPixel) {#IcoOptions-long-int-}
```
public IcoOptions(long format, int bitsPerPixel)
```


初始化 [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | long | ICO 帧格式。请注意，ICO 图像仅支持 [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png) 和 [FileFormat.Bmp](../../com.aspose.imaging/fileformat\#Bmp) 作为条目。 |
| bitsPerPixel | int | bits-per-pixel 值。 |

### getFormat() {#getFormat--}
```
public final long getFormat()
```


获取 ICO 帧格式。

**Returns:**
long - ICO 帧格式。
### setFormat(long value) {#setFormat-long-}
```
public final void setFormat(long value)
```


设置 ICO 帧格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | ICO 帧格式。 |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


获取 bits-per-pixel 值。

**Returns:**
int - 每像素位数值。
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


设置 bits-per-pixel 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 每像素位数值。 |

