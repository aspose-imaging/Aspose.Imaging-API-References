---
title: "EpsInterchangeImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: 
type: docs
weight: 6580
url: /zh/net/aspose.imaging.fileformats.eps/epsinterchangeimage/
---
## EpsInterchangeImage class

封装的 PostScript 交换格式的类

```csharp
public class EpsInterchangeImage : EpsImage
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | 获取图像的每像素位数。 |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | 获取边界框左下角位置 |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | 获取 BoundingBox 字符串值 |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | 获取边界框右上角位置 |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container) { get; } | 获取 [`Image`](../../aspose.imaging/image) 容器。 |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | 获取 CreationDate 字段 |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | 获取 CreationDate 字段的字符串值 |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | 获取 Creator 字段 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [EpsType](../../aspose.imaging.fileformats.eps/epsinterchangeimage/epstype) { get; } | 获取 EPS 子类型值 |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsinterchangeimage/hasrasterpreview) { get; } | 获取一个值，指示此实例是否具有特定格式的栅格预览 |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | 获取对象的高度（英寸）。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | 获取页码 |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | 获取页面总数 |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | 获取 Photoshop 预览缩略图（如果它在初始 EPS 数据中存在） |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | 获取 PostScript 版本字段 |
| [PreviewHeight](../../aspose.imaging.fileformats.eps/epsinterchangeimage/previewheight) { get; } | 获取预览图像的高度 |
| [PreviewWidth](../../aspose.imaging.fileformats.eps/epsinterchangeimage/previewwidth) { get; } | 获取预览图像的宽度 |
| [RasterPreview](../../aspose.imaging.fileformats.eps/epsinterchangeimage/rasterpreview) { get; } | 获取黑白光栅预览（如果存在），否则返回 null |
| [Size](../../aspose.imaging/image/size) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | 获取对象的尺寸（英寸）。 |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | 获取标题字段 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | 获取对象的宽度（英寸）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | 缓存不可用。 |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| [ConvertToBinary](../../aspose.imaging.fileformats.eps/epsinterchangeimage/converttobinary)() | 将此实例转换为[`EpsBinaryImage`](../epsbinaryimage) |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 释放当前实例。 |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | 获取默认选项。 |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | 获取嵌入的图像。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save) 方法保存，它将生成每像素 8 位的输出 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将它们作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save) 方法。 |
| [Resize](../../aspose.imaging/image/resize)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | 按比例调整宽度。 |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | 旋转、翻转或同时旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | 设置图像调色板。 |
| [explicit operator](../../aspose.imaging.fileformats.eps/epsinterchangeimage/op_explicit) | 执行从[`EpsBinaryImage`](../epsbinaryimage)到[`EpsInterchangeImage`](../epsinterchangeimage)的显式转换 |

### 另请参见

* class [EpsImage](../epsimage)
* namespace [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* assembly [Aspose.Imaging](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.Imaging.dll 生成 -->
