---
title: "VectorRasterizationOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "矢量光栅化选项。"
type: docs
weight: 52
url: /zh/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

向量光栅化选项。请注意，自 Aspose.Imaging 24.12 版本起，[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) 将不再继承自 [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | 获取平滑模式。 |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | 设置平滑模式。 |
| [getBorderX()](#getBorderX--) | 获取或设置边框 X。 |
| [setBorderX(float value)](#setBorderX-float-) | 获取或设置边框 X。 |
| [getBorderY()](#getBorderY--) | 获取或设置边框 Y。 |
| [setBorderY(float value)](#setBorderY-float-) | 获取或设置边框 Y。 |
| [getCenterDrawing()](#getCenterDrawing--) | 获取一个值，指示是否居中绘制。 |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | 设置一个指示是否居中绘制的值。 |
| [getPageHeight()](#getPageHeight--) | 获取页面高度。 |
| [setPageHeight(float value)](#setPageHeight-float-) | 设置页面高度。 |
| [getPageSize()](#getPageSize--) | 获取页面大小。 |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | 设置页面大小。 |
| [getPageWidth()](#getPageWidth--) | 获取页面宽度。 |
| [setPageWidth(float value)](#setPageWidth-float-) | 设置页面宽度。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 设置背景颜色。 |
| [getDrawColor()](#getDrawColor--) | 获取前景颜色。 |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | 设置前景颜色。 |
| [getTextRenderingHint()](#getTextRenderingHint--) | 获取文本渲染提示。 |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | 设置文本渲染提示。 |
| [getPositioning()](#getPositioning--) | 获取定位。 |
| [setPositioning(int value)](#setPositioning-int-) | 设置定位。 |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | 获取文本替换映射。 |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | 设置文本替换映射。 |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | 将此实例复制到 `vectorRasterizationOptions`。 |
| [deepClone()](#deepClone--) | 对对象进行浅克隆。 |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


获取平滑模式。

**Returns:**
int - 平滑模式。
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


设置平滑模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 平滑模式。 |


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

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


获取或设置边框 X。

**Returns:**
float - 边框 X。
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


获取或设置边框 X。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 边框 X。 |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


获取或设置边框 Y。

**Returns:**
float - 边框 Y。
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


获取或设置边框 Y。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 边框 Y。 |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


获取一个值，指示是否居中绘制。

**Returns:**
boolean - 指示是否居中绘制的值。
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


设置一个指示是否居中绘制的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示是否居中绘制的值。 |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


获取页面高度。

**Returns:**
float - 页面高度。
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


设置页面高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 页面高度。 |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


获取页面大小。

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


设置页面大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | 页面大小。 |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // 文本将被转换为形状。
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // 页面尺寸。
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 EMF 在内的所有类型图像的统一方式。
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // 文本将被转换为形状。
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // 页面尺寸。
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // 设置水平边距
    rasterizationOptions.setBorderX(50);

    // 设置垂直边距
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


获取页面宽度。

**Returns:**
float - 页面宽度。
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


设置页面宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 页面宽度。 |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


设置背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 背景颜色。 |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // 文本将被转换为形状。
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // 页面尺寸。
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 EMF 在内的所有类型图像的统一方式。
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // 文本将被转换为形状。
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // 页面尺寸。
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // 设置水平边距
    rasterizationOptions.setBorderX(50);

    // 设置垂直边距
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


获取前景颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


设置前景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 前景颜色。 |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


获取文本渲染提示。

值：文本渲染提示。

**Returns:**
int - 文本渲染提示。
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


设置文本渲染提示。

值：文本渲染提示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 文本渲染提示。 |


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

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


获取定位。

值：定位。

**Returns:**
int - 定位。
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


设置定位。

值：定位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 定位。 |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


获取文本替换映射。

值：文本替换映射。

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - 文本替换映射。
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


设置文本替换映射。

值：文本替换映射。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.HashMap<java.lang.String,java.lang.String> | 文本替换映射。 |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


将此实例复制到 `vectorRasterizationOptions`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | 矢量光栅化选项。 |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


对对象进行浅克隆。

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
