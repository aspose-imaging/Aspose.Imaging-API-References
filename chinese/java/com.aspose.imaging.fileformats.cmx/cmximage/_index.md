---
title: "CmxImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "针对 Corel Metafile Exchange CMX 矢量图像格式并支持元数据描述的 API 是面向处理 CMX 文件的开发者的综合解决方案。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

针对 Corel Metafile Exchange (CMX) 矢量图像格式并支持元数据描述的 API 是面向处理 CMX 文件的开发者的综合解决方案。该 API 允许无缝加载 CMX 图像，提取诸如每像素位数、对象尺寸等元数据。通过额外的功能，如调整大小、旋转、设置调色板以及转换为其他格式，该 API 使开发者能够高效地操作和定制 CMX 矢量图像，以满足其特定的应用需求。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | 通过初始化带有 streamContainer 和 loadOptions 参数的新实例，轻松开始使用 [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) 类。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 使用此用户友好的属性，轻松获取图像的文件格式。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 使用此用户友好的属性，轻松获取图像的位深度。 |
| [getDefaultPage()](#getDefaultPage--) | 使用此直观的属性，轻松检索图像的默认页面。 |
| [isCached()](#isCached--) | 确定对象的数据是否已缓存，从而消除读取数据的需求。 |
| [getWidthF()](#getWidthF--) | 使用此直观的属性，获取对象的宽度（英寸）。 |
| [getHeightF()](#getHeightF--) | 使用此用户友好的属性，轻松获取对象的高度（英寸）。 |
| [getDocument()](#getDocument--) | 使用此直观的属性，轻松检索 CMX 文档。 |
| [getCmxPage()](#getCmxPage--) | 使用此直观的属性，轻松检索图像的 CMX 页面。 |
| [getPageCount()](#getPageCount--) | 使用此直观的属性，获取图像的总页数。 |
| [getPages()](#getPages--) | 使用此直观的属性，流畅获取图像的页面。 |
| [cacheData()](#cacheData--) | 使用此便捷方法缓存数据，以防止从底层源 [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) 进行额外加载。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 使用此直观的方法自定义图像的颜色调色板。 |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// 从 CMX 文件加载图像。
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // 此调用仅缓存默认页面。
    image.cacheData();

    // 缓存所有页面，以便不再从底层数据流加载额外数据。
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


通过初始化带有 streamContainer 和 loadOptions 参数的新实例，轻松开始使用 [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) 类。适用于希望以便捷方式从各种数据源加载 CMX 图像并根据需要自定义加载过程的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此用户友好的属性，轻松获取图像的文件格式。适用于希望动态确定图像格式、确保兼容性并在应用程序中进行准确处理的开发者。

**Returns:**
long - 文件格式 [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


使用此用户友好的属性，轻松获取图像的位深度。适用于希望确定图像细节级别或颜色深度、确保准确处理和操作的开发者。

**Returns:**
int - 图像每像素位数。
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


使用此直观的属性，轻松检索图像的默认页面。适用于希望快速访问图像主页面、确保高效导航和管理的开发者。

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


确定对象的数据是否已缓存，从而消除读取数据的需求。适用于希望通过高效利用缓存数据来优化性能、确保更快访问信息的开发者。

**Returns:**
布尔值 - 如果对象的数据已缓存则为 `true`；否则为 `false`。
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


使用此直观的属性，获取对象的宽度（英寸）。适用于希望在应用程序中精确测量对象、确保布局和呈现准确的开发者。

**Returns:**
float - 对象宽度（英寸）。
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


使用此用户友好的属性，轻松获取对象的高度（英寸）。适用于希望在应用程序中获取精确尺寸信息以实现有效布局和呈现的开发者。

**Returns:**
float - 对象高度（英寸）。
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


使用此直观的属性，轻松检索 CMX 文档。适用于希望访问或修改 CMX 图像、确保应用程序灵活性和效率的开发者。

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


使用此直观的属性，轻松检索图像的 CMX 页面。适用于希望快速访问 CMX 图像中各个页面、确保高效导航和管理的开发者。

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


使用此直观属性检索图像的总页数。适用于希望动态管理多页图像的开发者，确保对图像内容进行高效的导航和操作。

**Returns:**
int - 页数。
### getPages() {#getPages--}
```
public Image[] getPages()
```


使用此直观属性无缝检索图像的页面。适用于希望访问和操作多页图像中各个页面的开发者，确保高效的导航和处理。

**Returns:**
com.aspose.imaging.Image[] - 页面。

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// 从 CMX 文件加载图像。
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // 此调用仅缓存默认页面。
    image.cacheData();

    // 缓存所有页面，以便不再从底层数据流加载额外数据。
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


使用此便捷方法缓存数据，以防止从底层源 [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) 进行额外加载。适用于希望通过预加载数据来优化性能的开发者，确保在其应用程序中实现更快的访问和更流畅的操作。


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// 从 CMX 文件加载图像。
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // 此调用仅缓存默认页面。
    image.cacheData();

    // 缓存所有页面，以便不再从底层数据流加载额外数据。
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


使用此直观方法自定义图像的调色板。适用于希望动态应用特定配色方案或调整的开发者，确保对图像视觉外观的精确控制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

