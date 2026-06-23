---
title: "WmfRasterizationOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "Wmf 光栅化选项。"
type: docs
weight: 55
url: /zh/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Wmf 光栅化选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | 初始化 `WmfRasterizationOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | 获取或设置 WMF 渲染模式。 |
| [setRenderMode(int value)](#setRenderMode-int-) | 获取或设置 WMF 渲染模式。 |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | 将此复制到 `vectorRasterizationOptions`。 |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


初始化 `WmfRasterizationOptions` 类的新实例。

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


获取或设置 WMF 渲染模式。

值：WMF 渲染模式。

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


获取或设置 WMF 渲染模式。

值：WMF 渲染模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


将此复制到 `vectorRasterizationOptions`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

