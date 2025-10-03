---
title: ApngImage.AddFrame
second_title: Aspose.Imaging for .NET API Reference
description: ApngImage method. Easily append a new frame to the end of your frame collection with this straightforward method. Ideal for developers looking to expand their frame collection dynamically for animations with multiframe images. A new frame will be created according to the size of the current image
type: docs
weight: 80
url: /net/aspose.imaging.fileformats.apng/apngimage/addframe/
---
## AddFrame() {#addframe}

Easily append a new frame to the end of your frame collection with this straightforward method. Ideal for developers looking to expand their frame collection dynamically for animations with multi-frame images. A new frame will be created according to the size of the current image.

```csharp
public ApngFrame AddFrame()
```

### Return Value

The newly created APNG frame.

### See Also

* class [ApngFrame](../../apngframe/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddFrame(RasterImage) {#addframe_1}

Effortlessly expand your frame collection by adding a new frame to the end with this intuitive method. Perfect for developers seeking to enhance their animations of multi-frame images dynamically. The contents of the new frame will be filled from the specified image.

```csharp
public void AddFrame(RasterImage frameImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| frameImage | RasterImage | The frame image. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | frameImage is null. |

## Examples

The following example shows how to create APNG image from another raster single-page image.

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
        // It is possible to set image default frame time there: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Cleaning because the image contains one frame by default
        apngImage.RemoveAllFrames();

        // add first frame
        apngImage.AddFrame(sourceImage);

        // add intermediate frames
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // add last frame
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddFrame(RasterImage, uint) {#addframe_2}

Expand your frame collection seamlessly by appending a new frame to the with this intuitive method. Ideal for developers looking to enrich their animations of multi-frame images. The contents of the new frame will be filled from the specified image.

```csharp
public void AddFrame(RasterImage frameImage, uint frameTime)
```

| Parameter | Type | Description |
| --- | --- | --- |
| frameImage | RasterImage | The frame image. |
| frameTime | UInt32 | The frame duration, in milliseconds. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | frameImage is null. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)


