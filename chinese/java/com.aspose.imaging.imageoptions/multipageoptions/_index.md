---
title: "MultiPageOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "支持多页的格式的基类"
type: docs
weight: 30
url: /zh/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

支持多页的格式的基类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | 初始化 `MultiPageOptions` 类的新实例。 |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | 初始化 `MultiPageOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPages()](#getPages--) | 获取或设置页面。 |
| [setPages(int[] value)](#setPages-int---) | 获取或设置页面。 |
| [getPageTitles()](#getPageTitles--) | 获取或设置页面标题。 |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | 获取或设置页面标题。 |
| [getTimeInterval()](#getTimeInterval--) | 获取时间间隔。 |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | 设置时间间隔。 |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | 获取页面光栅化选项。 |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | 设置页面光栅化选项。 |
| [getExportArea()](#getExportArea--) | 获取或设置导出区域。 |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | 获取或设置导出区域。 |
| [getMode()](#getMode--) | 获取或设置模式。 |
| [setMode(int value)](#setMode-int-) | 获取或设置模式。 |
| [getOutputLayersNames()](#getOutputLayersNames--) | 获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd）。 |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | 获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd）。 |
| [getMergeLayers()](#getMergeLayers--) | 获取指示是否[合并图层]的值。 |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | 设置指示是否[合并图层]的值。 |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | 从范围数组初始化页面。 |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


初始化 `MultiPageOptions` 类的新实例。

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pages | int[] | pages。 |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pages | int[] | pages 的数组。 |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | 导出区域。 |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | page titles。 |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | page titles。 |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | 导出区域。 |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | 该 `IntRange`。 |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | 该 `IntRange`。 |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | 导出区域。 |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | 该 `IntRange`。 |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | 该 `IntRange`。 |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | 导出区域。 |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 页面索引。 |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


初始化 `MultiPageOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 页面索引。 |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | 导出区域。 |

### getPages() {#getPages--}
```
public int[] getPages()
```


获取或设置页面。

值：pages。

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


获取或设置页面。

值：pages。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // 请注意，如果图像是彩色的，它将根据以下选项自动转换为黑白格式：
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // 默认情况下，所有页面将存储到输出 TIFF，但可以显式指定所需的页面集合。
        // 仅导出第一页和第二页。
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // 设置页面标题。
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // 保存为 TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


获取或设置页面标题。

值：page titles。

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


获取或设置页面标题。

值：page titles。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // 请注意，如果图像是彩色的，它将根据以下选项自动转换为黑白格式：
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // 默认情况下，所有页面将存储到输出 TIFF，但可以显式指定所需的页面集合。
        // 仅导出第一页和第二页。
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // 设置页面标题。
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // 保存为 TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


获取时间间隔。

值：时间间隔。

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


设置时间间隔。

值：时间间隔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | 时间间隔。 |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


获取页面光栅化选项。

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - 页面光栅化选项。
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


设置页面光栅化选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | 页面光栅化选项。 |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


获取或设置导出区域。

值：导出区域。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


获取或设置导出区域。

值：导出区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


获取或设置模式。

值：模式。

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


获取或设置模式。

值：模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd）。

值：输出图层名称。

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd）。

值：输出图层名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


获取指示是否[合并图层]的值。

值：如果[merge layers]则为 `true`；否则为 `false`。

**Returns:**
布尔值 - 表示是否[merge layers]的值。
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


设置指示是否[合并图层]的值。

值：如果[merge layers]则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 表示是否[merge layers]的值。 |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


从范围数组初始化页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | 范围。 |

