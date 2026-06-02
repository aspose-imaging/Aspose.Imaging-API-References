---
title: "SvgRasterizationOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "SVG 光栅化选项。"
type: docs
weight: 46
url: /zh/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

SVG 光栅化选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | 初始化 `SvgRasterizationOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getScaleX()](#getScaleX--) | 获取或设置 x 轴比例。 |
| [setScaleX(float value)](#setScaleX-float-) | 获取或设置 x 轴比例。 |
| [getScaleY()](#getScaleY--) | 获取或设置 y 轴比例。 |
| [setScaleY(float value)](#setScaleY-float-) | 获取或设置 y 轴比例。 |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | 将此实例复制到 `vectorRasterizationOptions`。 |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


初始化 `SvgRasterizationOptions` 类的新实例。

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


获取或设置 x 轴比例。

**Returns:**
float - x 轴比例。
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


获取或设置 x 轴比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | x 轴比例。 |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载图像的统一方式。
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // 为了栅格化 SVG，我们需要指定栅格化选项。
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // 设置图像背景的默认颜色。默认值为白色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // 设置页面大小
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // 对线条、曲线以及填充区域的边缘进行抗锯齿处理。
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // 每个字符使用其未使用 hinting 的抗锯齿字形位图绘制。
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // 将图像尺寸缩小 10 倍，即输出尺寸为原始尺寸的 10%。
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // 保存为 PNG 文件
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


获取或设置 y 轴比例。

**Returns:**
float - y 轴比例。
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


获取或设置 y 轴比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | y 轴比例。 |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载图像的统一方式。
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // 为了栅格化 SVG，我们需要指定栅格化选项。
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // 设置图像背景的默认颜色。默认值为白色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // 设置页面大小
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // 对线条、曲线以及填充区域的边缘进行抗锯齿处理。
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // 每个字符使用其未使用 hinting 的抗锯齿字形位图绘制。
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // 将图像尺寸缩小 10 倍，即输出尺寸为原始尺寸的 10%。
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // 保存为 PNG 文件
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


将此实例复制到 `vectorRasterizationOptions`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | 矢量光栅化选项。 |

