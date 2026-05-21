---
title: "ApngOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Animated PNG Animated Portable Network Graphics 图像文件格式创建的 API 是一个为希望生成引人入胜的动画图像的开发者提供的动态工具。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

Animated PNG (Animated Portable Network Graphics) 图像文件格式创建的 API 是一个为希望生成引人入胜的动画图像的开发者提供的动态工具。通过可自定义的选项，如帧持续时间和循环次数，此 API 允许根据特定需求微调动画内容。无论是创建引人注目的网页图形还是交互式视觉效果，您都可以利用此 API 无缝地将 APNG 图像集成，并对动画参数进行精确控制。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | 初始化 [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) 类的新实例。 |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | 初始化 `ApngOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | 获取动画循环的次数。 |
| [setNumPlays(int value)](#setNumPlays-int-) | 设置动画循环的次数。 |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | 获取默认帧持续时间。 |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | 设置默认帧持续时间。 |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // 导出为 APNG 动画，默认无限动画循环
    image.save("Animation1.webp.png", new ApngOptions());
    // 设置动画循环
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // 设置默认帧持续时间
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


初始化 [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) 类的新实例。

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


初始化 `ApngOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | PNG 选项。 |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


获取动画循环的次数。0 表示无限循环。

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // 导出为 APNG 动画，默认无限动画循环
    image.save("Animation1.webp.png", new ApngOptions());
    // 设置动画循环
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


设置动画循环的次数。0 表示无限循环。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // 导出为 APNG 动画，默认无限动画循环
    image.save("Animation1.webp.png", new ApngOptions());
    // 设置动画循环
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


获取默认帧持续时间。

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


设置默认帧持续时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

