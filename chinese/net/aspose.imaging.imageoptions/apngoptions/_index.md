---
title: "类 ApngOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.ApngOptions 类。用于创建动画 PNG（Animated Portable Network Graphics）图像文件格式的 API 是一个为希望生成引人入胜的动画图像的开发者提供的动态工具。通过可自定义的选项，如帧持续时间和循环次数，该 API 允许根据特定需求微调动画内容。无论是创建引人注目的网页图形还是交互式视觉效果，都可以利用此 API 无缝地将 APNG 图像集成，并对动画参数进行精确控制。"
type: docs
weight: 10230
url: /zh/net/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Animated PNG（Animated Portable Network Graphics）图像文件格式创建的 API 是为希望生成引人入胜的动画图像的开发者提供的动态工具。通过可自定义的选项，如帧持续时间和循环次数，此 API 允许根据特定需求微调动画内容。无论是创建吸引人的网页图形还是交互式视觉效果，您都可以利用此 API 无缝地嵌入 APNG 图像，并对动画参数进行精确控制。

```csharp
public class ApngOptions : PngOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ApngOptions](apngoptions/)() | 初始化 `ApngOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth/) { get; set; } | 获取或设置位深度值，范围为 1、2、4、8、16。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype/) { get; set; } | 获取或设置颜色的类型。 |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime/) { get; set; } | 获取或设置默认帧持续时间。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype/) { get; set; } | 获取或设置在 png 文件保存过程中使用的过滤器类型。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays/) { get; set; } | 获取或设置动画循环的次数。0 表示无限循环。 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [PngCompressionLevel](../../aspose.imaging.imageoptions/pngoptions/pngcompressionlevel/) { get; set; } | 获取或设置 [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) 的压缩级别。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive/) { get; set; } | 获取或设置一个值，指示 [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) 是否为渐进式。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | 创建此实例的成员逐一克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | 尝试设置一个 *metadata* 实例，如果此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 实例。 |

## 示例

以下示例展示了如何将其他非动画多页格式导出为 APNG 文件格式。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // 设置默认帧持续时间
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

以下示例展示了如何导出为 APNG 文件格式。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // 导出为 APNG 动画，默认无限循环播放
    image.Save("Animation1.webp.png", new ApngOptions());
    // 设置动画循环次数
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

以下示例展示了如何从另一个光栅单页图像创建 APNG 图像。

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // 可以在此处设置图像的默认帧时间：apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // 正在清理，因为图像默认包含一个帧
        apngImage.RemoveAllFrames();

        // 添加第一帧
        apngImage.AddFrame(sourceImage);

        // 添加中间帧
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // 添加最后一帧
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### 另请参见

* class [PngOptions](../pngoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


