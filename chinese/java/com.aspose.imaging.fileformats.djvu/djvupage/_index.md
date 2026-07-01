---
title: "DjvuPage"
second_title: "Aspose.Imaging for Java API 参考"
description: "Djvu 页面类"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Djvu 页面类
## 字段

| 字段 | 描述 |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | 当 [page exported action] 发生。 |
| [PropertyChanged](#PropertyChanged) | 当属性值更改时发生。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [getParentImage()](#getParentImage--) | 获取页面所属的父图像 |
| [getWidth()](#getWidth--) | 获取页面的宽度 |
| [getHeight()](#getHeight--) | 获取页面的高度 |
| [getImage()](#getImage--) | 获取图像。 |
| [getThumbnailImage()](#getThumbnailImage--) | 获取或设置页面的缩略图像 |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | 获取或设置页面的缩略图像 |
| [getPageNumber()](#getPageNumber--) | 获取页码。 |
| [isColor()](#isColor--) | 获取一个值，指示此实例是否为彩色。 |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | 获取矩形位置的文本 |
| [getForegroundImage()](#getForegroundImage--) | 获取页面的前景图像 |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | 获取页面的前景图像 |
| [getTextImage()](#getTextImage--) | 获取文本图像。 |
| [getTextImage(int subsample)](#getTextImage-int-) | 获取文本图像。 |
| [getBackgroundImage()](#getBackgroundImage--) | 获取背景图像。 |
| [extractThumbnailImage()](#extractThumbnailImage--) | 从 Djvu 页面提取缩略图像。 |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


当 [page exported action] 发生。

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


当属性值更改时发生。

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

值：图像每像素位数。

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


获取页面所属的父图像

值：文档。

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取页面的宽度

值：宽度。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取页面的高度

值：高度。

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


获取图像。

值：图像。

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


获取或设置页面的缩略图像

值：缩略图像。

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


获取或设置页面的缩略图像

值：缩略图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


获取页码。

值：页码。

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//输出可能如下所示：
//总页数：2
//当前页码：    1
//第一页页码：     1
//最后一页页码：      2
//--------------------------------------------------
//页码：     1
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
//--------------------------------------------------
//页码：     2
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


获取一个值，指示此实例是否为彩色。

值：如果此实例为颜色则为 `true`；否则为 `false`。

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


获取矩形位置的文本

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 位置矩形。 |

**Returns:**
java.lang.String - 在位置找到的文本
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


获取页面的前景图像

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


获取页面的前景图像

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 子采样 | int | 子采样。 |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


获取文本图像。

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


获取文本图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 子采样 | int | 子采样。 |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


获取背景图像。

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


从 Djvu 页面提取缩略图像。

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
