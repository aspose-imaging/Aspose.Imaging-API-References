---
title: "ApngImage.DefaultFrameTime"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ApngImage 属性。轻松使用此灵活属性调整创建新帧的默认帧时长。非常适合希望在动画中高效自定义帧时间的开发者。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.apng/apngimage/defaultframetime/
---
## ApngImage.DefaultFrameTime property

使用此灵活属性，轻松调整创建新帧的默认帧持续时间。非常适合希望在动画中高效自定义帧时间的开发者。

```csharp
public uint DefaultFrameTime { get; set; }
```

### Property Value

默认帧时长（毫秒）。

## 示例

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

* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)


