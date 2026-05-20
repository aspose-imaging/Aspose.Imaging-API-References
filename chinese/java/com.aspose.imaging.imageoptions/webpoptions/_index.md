---
title: "WebPOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们的 API 创建现代 WebP 栅格网页图像，提供对无损和有损压缩、以及 alpha 通道和动画循环的强大支持。"
type: docs
weight: 53
url: /zh/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

使用我们的 API 创建现代 WebP 栅格网页图像，提供对无损和有损压缩、以及 alpha 通道和动画循环的强大支持。通过动态视觉效果提升您的网页内容，同时优化文件大小以改善加载速度和用户体验。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLossless()](#getLossless--) | 获取或设置一个值，指示此 `WebPOptions` 是否为无损。 |
| [setLossless(boolean value)](#setLossless-boolean-) | 获取或设置一个值，指示此 `WebPOptions` 是否为无损。 |
| [getQuality()](#getQuality--) | 获取或设置质量。 |
| [setQuality(float value)](#setQuality-float-) | 获取或设置质量。 |
| [getAnimLoopCount()](#getAnimLoopCount--) | 获取或设置动画循环计数。 |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | 获取或设置动画循环计数。 |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | 获取或设置动画背景的颜色。 |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | 获取或设置动画背景的颜色。 |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。这些页面将在输出的 WEBP 中以动画帧的形式呈现。
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


获取或设置一个值，指示此 `WebPOptions` 是否为无损。

**Returns:**
boolean - 如果是无损则为 `true`；否则为 `false`。
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


获取或设置一个值，指示此 `WebPOptions` 是否为无损。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | `true` 如果是无损；否则为 `false`。 |

### getQuality() {#getQuality--}
```
public float getQuality()
```


获取或设置质量。

**Returns:**
float - 质量。
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


获取或设置质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 质量。 |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


获取或设置动画循环计数。

**Returns:**
int - 动画循环计数，0 表示无限。
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


获取或设置动画循环计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 动画循环计数，0 表示无限。 |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


获取或设置动画背景的颜色。

**Returns:**
long - 动画背景的颜色。
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


获取或设置动画背景的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 动画背景的颜色。 |

