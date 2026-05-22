---
title: "ApngOptions.DefaultFrameTime"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ApngOptions 属性。获取或设置默认帧持续时间"
type: docs
weight: 20
url: /zh/net/aspose.imaging.imageoptions/apngoptions/defaultframetime/
---
## ApngOptions.DefaultFrameTime property

获取或设置默认帧持续时间。

```csharp
public uint DefaultFrameTime { get; set; }
```

### Property Value

默认帧时长（毫秒）。

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

* class [ApngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../apngoptions/)
* assembly [Aspose.Imaging](../../../)


