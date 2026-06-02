---
title: "ApngImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Animated PNG（Animated Portable Network Graphics）图像文件格式的 API 是面向希望在其应用程序中集成动画内容的开发者的多功能解决方案。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Animated PNG（Animated Portable Network Graphics）图像文件格式的 API 是面向希望在其应用程序中集成动画内容的开发者的多功能解决方案。该 API 提供对帧设置的广泛控制，允许用户定义特定帧的参数，包括循环时长和 PNG 文件设置。借助此功能丰富的工具，您可以轻松管理和优化 APNG 图像的显示，导入和导出图像，提升应用程序的动态和交互性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | 通过轻松初始化新实例，开始使用 [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) 类。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 使用此便利属性，快速访问文件格式的信息。 |
| [getPageCount()](#getPageCount--) | 使用此属性，轻松检索图像文件的总页数。 |
| [getPages()](#getPages--) | 使用此便利属性，轻松访问图像的页面。 |
| [getNumPlays()](#getNumPlays--) | 使用此多功能属性，轻松控制动画循环的次数。 |
| [setNumPlays(int value)](#setNumPlays-int-) | 使用此多功能属性，轻松控制动画循环的次数。 |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | 使用此灵活属性，轻松调整创建新帧的默认帧持续时间。 |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | 使用此灵活属性，轻松调整创建新帧的默认帧持续时间。 |
| [getInterlaced()](#getInterlaced--) | 使用此便利属性，快速确定此 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 对象是否为隔行扫描。 |
| [getOriginalOptions()](#getOriginalOptions--) | 使用此直观方法，轻松根据原始文件设置检索选项。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 使用此简洁方法轻松检索默认选项。 |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | 使用此用户友好方法，快速获取资源图像上次修改的日期和时间。 |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | 使用此直观方法，轻松向图像添加新页面。 |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | 使用此直观方法，轻松通过在末尾添加新帧来扩展帧集合。 |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | 使用此直观方法，顺畅地通过追加新帧来扩展帧集合。 |
| [insertFrame(int index)](#insertFrame-int-) | 使用此直观方法，轻松在指定位置插入新帧到帧集合中。 |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | 在指定索引处向自身帧集合插入新帧。 |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | 在指定索引处向自身帧集合插入新帧。 |
| [popFrameAt(int index)](#popFrameAt-int-) | 使用此直观方法，从帧集合中移除并获取指定索引处的帧。 |
| [removeFrameAt(int index)](#removeFrameAt-int-) | 使用此方法，顺畅地从帧集合中移除指定索引处的帧。 |
| [removeAllFrames()](#removeAllFrames--) | 使用此直观方法，通过移除所有帧来清空帧集合。 |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | 使用此方法，轻松将指定的光栅图像设置为当前动画的默认图像。 |
| [resetDefaultImage()](#resetDefaultImage--) | 使用此直观方法删除先前设置的默认图像。 |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // 导出为 APNG 动画，默认无限动画循环
    image.save("Animation1.webp.png", new ApngOptions());
    // 设置动画循环
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // 设置默认帧持续时间
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


通过轻松初始化新实例开始使用 [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) 类。非常适合希望在项目中快速高效地开始使用 ApngImage 对象的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | 选项。 |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此便捷属性快速获取文件格式信息。非常适合需要轻松检索 Apng 文件格式细节的开发者。

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


使用此属性轻松获取图像文件的总页数。非常适合需要快速访问页数信息的开发者。

值：页面计数。

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


使用此便捷属性轻松访问图像的各页。非常适合希望快速轻松获取单页进行操作的开发者。

值：页面。

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


使用此多功能属性轻松控制动画循环次数。非常适合希望精确控制动画行为的开发者，若值为 0 则支持无限循环。

值：循环的次数。

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


使用此多功能属性轻松控制动画循环次数。非常适合希望精确控制动画行为的开发者，若值为 0 则支持无限循环。

值：循环的次数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


使用此灵活属性轻松调整创建新帧的默认帧时长。非常适合希望在动画中高效自定义帧时间的开发者。

值：默认帧时长（毫秒）。

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


使用此灵活属性轻松调整创建新帧的默认帧时长。非常适合希望在动画中高效自定义帧时间的开发者。

值：默认帧时长（毫秒）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


使用此便捷属性快速判断此 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 对象是否为隔行扫描。非常适合需要轻松检查 PNG 图像隔行状态的开发者。

值：若为隔行扫描则为 `true`；否则为 `false`。

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


使用此直观方法轻松检索基于原始文件设置的选项。非常适合希望访问并利用与原始文件特性保持一致的设置的开发者。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) 方法保存，输出的 PNG 图像将变为每像素 8 位。为避免这种情况并保存为每像素 1 位的 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) 方法。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


使用此简洁方法轻松检索默认选项。非常适合希望快速访问默认 Apng 图像设置的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | java.lang.Object[] | 参数。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


使用此友好方法快速获取资源图像上次修改的日期和时间。非常适合需要跟踪更改并有效管理资源的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| useDefault | boolean | 如果设置为 `true`，则使用来自 FileInfo 的信息作为默认值。 |

**Returns:**
java.util.Date - 资源图像上次修改的日期和时间。
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


使用此直观方法轻松向图像添加新页。非常适合希望动态扩展图像文件内容的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | 要添加的页面。 |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

使用此简洁方法轻松在帧集合末尾追加新帧。非常适合希望为多帧图像动画动态扩展帧集合的开发者。新帧将根据当前图像的尺寸创建。

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


使用此直观方法轻松通过在末尾添加新帧来扩展帧集合。非常适合希望动态提升多帧图像动画的开发者。新帧的内容将从指定图像填充。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 帧图像。 |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


使用此直观方法通过追加新帧无缝扩展帧集合。非常适合希望丰富多帧图像动画的开发者。新帧的内容将从指定图像填充。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 帧图像。 |
| frameTime | long | 帧时长（毫秒）。 |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


使用此直观方法轻松在指定位置插入新帧到帧集合中。非常适合希望对多帧图像动画中帧的排列进行精确控制的开发者。新帧将根据当前图像的尺寸创建。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


在指定索引处向自身帧集合插入新帧。新帧的内容将从指定图像填充。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 帧图像。 |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


在指定索引处向自身帧集合插入新帧。新帧的内容将从指定图像填充。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 帧图像。 |
| frameTime | long | 帧时长（毫秒）。 |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


使用此直观方法删除并获取帧集合中指定索引的帧。非常适合希望高效管理动画帧的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


使用此方法无缝删除帧集合中指定索引的帧。非常适合希望简化多帧图像中帧管理的开发者。被删除的帧将被释放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


通过此直观方法删除所有帧来清除您的帧集合。适用于希望重置或刷新动画的开发者。

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


使用此方法轻松将指定的光栅图像设置为当前动画的默认图像。完美适用于希望自定义动画默认图像的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 图像。 |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


通过此直观方法移除先前设置的默认图像。适用于希望在动画中重置或清除默认图像的开发者。此后，默认图像将是自身帧集合中的第一帧（无法使用此方法删除）。

