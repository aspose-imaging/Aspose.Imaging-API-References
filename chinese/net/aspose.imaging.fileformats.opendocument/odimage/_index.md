---
title: OdImage
second_title: Aspose.Imaging for .NET API 参考
description: 打开的文档
type: docs
weight: 7370
url: /zh/net/aspose.imaging.fileformats.opendocument/odimage/
---
## OdImage class

打开的文档

```csharp
public abstract class OdImage : VectorMultipageImage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [OdImage](odimage#constructor)(StreamContainer) | 初始化[`OdImage`](../odimage)类的新实例。 |
| [OdImage](odimage#constructor_1)(StreamContainer, LoadOptions) | 初始化[`OdImage`](../odimage)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel) { get; } | 获取每像素的图像位数。 |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container) { get; } | 获取[`Image`](../../aspose.imaging/image)容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | 获取或设置一个值，该值指示图像是否具有背景色。 |
| override [Height](../../aspose.imaging.fileformats.opendocument/odimage/height) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | 获取对象高度，以英寸为单位。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached) { get; } | 获取对象的数据当前是否缓存，不需要读取数据。 |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata) { get; } | 获取元数据。 |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount) { get; } | 获取页数。 |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction) { get; set; } | 获取或设置页面导出动作。 请注意，设置该方法执行后会自动释放页面资源。 它将在每个页面保存之前执行。 |
| abstract [Pages](../../aspose.imaging/vectormultipageimage/pages) { get; } | 获取页面。 |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records) { get; } | 获取记录。 |
| [Size](../../aspose.imaging/image/size) { get; } | 获取图像大小。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | 获取对象大小，以英寸为单位。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | 获取指示是否使用图像调色板的值。 |
| override [Width](../../aspose.imaging.fileformats.opendocument/odimage/width) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | 获取对象宽度，以英寸为单位。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata)() | 缓存数据并确保不会从底层 DataStreamSupporter执行额外的数据加载。数据流容器。 |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项表示的指定文件格式。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 释放当前实例。 |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | 获取默认选项。 |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | 获取嵌入的图像。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 String)方法，将生成每像素 8 位的输出 PNG 图像。 为避免它并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们传递 到ImageOptionsBase)方法作为第二个参数。 |
| [Resize](../../aspose.imaging/image/resize)(int, int) | 调整图像大小。使用默认NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | 按比例调整高度。使用默认NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | 按比例调整宽度。使用默认NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | 按比例调整宽度。 |
| override [RotateFlip](../../aspose.imaging.fileformats.opendocument/odimage/rotateflip)(RotateFlipType) | 旋转、翻转或旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流中。 |
| override [Save](../../aspose.imaging/image/save)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette)(IColorPalette, bool) | 设置图像调色板。 |

### 也可以看看

* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage)
* 命名空间 [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
