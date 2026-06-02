---
title: "ApngImage.AddFrame"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ApngImage 方法。使用此简洁方法，轻松在帧集合的末尾追加新帧。适用于希望为多帧图像动画动态扩展帧集合的开发者。新帧将根据当前图像的尺寸创建。"
type: docs
weight: 80
url: /zh/net/aspose.imaging.fileformats.apng/apngimage/addframe/
---
## AddFrame() {#addframe}

使用此简洁方法，轻松在帧集合末尾追加新帧。非常适合希望为多帧图像动画动态扩展帧集合的开发者。新帧将根据当前图像的尺寸创建。

```csharp
public ApngFrame AddFrame()
```

### 返回值

新创建的 APNG 帧。

### 另请参见

* class [ApngFrame](../../apngframe/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddFrame(RasterImage) {#addframe_1}

使用此直观方法，在末尾添加新帧，轻松扩展帧集合。非常适合希望动态增强多帧图像动画的开发者。新帧的内容将从指定图像填充。

```csharp
public void AddFrame(RasterImage frameImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frameImage | RasterImage | 帧图像。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | frameImage 为 null。 |

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

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddFrame(RasterImage, uint) {#addframe_2}

使用此直观方法，通过追加新帧无缝扩展帧集合。非常适合希望丰富多帧图像动画的开发者。新帧的内容将从指定图像填充。

```csharp
public void AddFrame(RasterImage frameImage, uint frameTime)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frameImage | RasterImage | 帧图像。 |
| frameTime | UInt32 | 帧持续时间（毫秒）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | frameImage 为 null。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)


