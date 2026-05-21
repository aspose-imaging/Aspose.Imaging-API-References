---
title: "EmfRasterizationOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Emf 栅格化选项。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

Emf 栅格化选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | 获取或设置渲染模式。 |
| [setRenderMode(int value)](#setRenderMode-int-) | 获取或设置渲染模式。 |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | 将此复制到 `vectorRasterizationOptions`。 |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


获取或设置渲染模式。

**Returns:**
int - 渲染模式。
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


获取或设置渲染模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 渲染模式。 |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


将此复制到 `vectorRasterizationOptions`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

