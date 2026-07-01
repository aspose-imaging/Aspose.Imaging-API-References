---
title: "Html5CanvasOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "轻松使用我们的 API 创建 HTML5 Canvas 文件，能够无缝组合表单、文本、图像、动画和链接等元素。"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

轻松使用我们的 API 创建 HTML5 Canvas 文件，能够无缝组合表单、文本、图像、动画和链接等元素。受益于包括标签标识符和编码设置支持在内的强大功能，确保您的 Web 项目获得最佳性能和定制化。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | 初始化一个新的 [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) 类的实例。 |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | 初始化一个新的 `ImageOptionsBase` 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | 获取 canvas 标签标识符。 |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | 设置 canvas 标签标识符。 |
| [getFullHtmlPage()](#getFullHtmlPage--) | 获取一个指示是否应生成完整 HTML 页面 的值。 |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | 设置一个指示是否应生成完整 HTML 页面 的值。 |
| [getEncoding()](#getEncoding--) | 获取编码。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置编码。 |

## Example: Any vector image (SVG, WMF, CMX, etc.
任何矢量图像（SVG、WMF、CMX 等）都可以用作 Canvas 图像的来源。以下代码创建了一个简单的 Canvas 图像。
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save("Canvas.html", options);
}
```


## Example: You can embed more than one Canvas image within HTML page or update already existing page.
您可以在 HTML 页面中嵌入多个 Canvas 图像或更新已有页面。为此，您只需导出 Canvas 标签。
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### Html5CanvasOptions() {#Html5CanvasOptions--}
```
public Html5CanvasOptions()
```


初始化一个新的 [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) 类的实例。

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


初始化一个新的 `ImageOptionsBase` 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | 图像选项。 |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


获取 canvas 标签标识符。

**Returns:**
java.lang.String - canvas 标签标识符。
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


设置 canvas 标签标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | canvas 标签标识符。 |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


获取一个指示是否应生成完整 HTML 页面 的值。

**Returns:**
boolean - 指示是否应生成完整 HTML 页面 的值。
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


设置一个指示是否应生成完整 HTML 页面 的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示是否应生成完整 HTML 页面 的值。 |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
您可以在 HTML 页面中嵌入多个 Canvas 图像或更新已有页面。为此，您只需导出 Canvas 标签。
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


获取编码。

**Returns:**
java.nio.charset.Charset - 编码。
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


设置编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset | 编码。 |

