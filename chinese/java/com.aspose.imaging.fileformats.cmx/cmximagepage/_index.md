---
title: "CmxImagePage"
second_title: "Aspose.Imaging for Java API 参考"
description: "CMX 页面图像"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

CMX 页面图像
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | 初始化一个新的 [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) 类实例。 |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | 初始化一个新的 [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | 获取 CMX 页面。 |
| [getFileFormat()](#getFileFormat--) | 获取文件格式的值 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [isCached()](#isCached--) | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [getWidthF()](#getWidthF--) | 获取对象的宽度（英寸）。 |
| [getHeightF()](#getHeightF--) | 获取对象的高度，单位为英寸。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 获取默认选项。 |
| [cacheData()](#cacheData--) | 缓存不能使用。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 设置图像调色板。 |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


初始化一个新的 [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | CMX 页面。 |
| container | [Image](../../com.aspose.imaging/image) | 容器。 |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


初始化一个新的 [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | CMX 页面。 |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


获取 CMX 页面。

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


获取文件格式的值

**Returns:**
long - 文件格式的值
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

**Returns:**
int - 图像每像素位数。
### isCached() {#isCached--}
```
public boolean isCached()
```


获取一个值，指示对象的数据当前是否已缓存且无需读取数据。

值：如果对象的数据已缓存则为 `true`；否则为 `false`。

**Returns:**
boolean - 一个值，指示对象的数据当前是否已缓存且无需读取数据。
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


获取对象的宽度（英寸）。

**Returns:**
float - 对象的宽度，单位为英寸。
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


获取对象的高度，单位为英寸。

**Returns:**
float - 对象的高度，单位为英寸。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

值：图像宽度。

**Returns:**
int - 图像宽度。
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

值：图像高度。

**Returns:**
int - 图像高度。
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


获取默认选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | java.lang.Object[] | 参数。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


缓存不能使用。


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// 从 CMX 文件加载图像。
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // 此调用仅缓存默认页面。
    image.cacheData();

    // 缓存所有页面，以防止从底层数据流进行额外的数据加载。
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


设置图像调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

