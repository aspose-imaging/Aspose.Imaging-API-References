---
title: GifImage.AddPage
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Incorporate a new page seamlessly into the existing image enhancing its content and expanding its scope. This method augment image collections with additional content fostering creativity and flexibility in image management and composition
type: docs
weight: 200
url: /net/aspose.imaging.fileformats.gif/gifimage/addpage/
---
## GifImage.AddPage method

Incorporate a new page seamlessly into the existing image, enhancing its content and expanding its scope. This method augment image collections with additional content, fostering creativity and flexibility in image management and composition.

```csharp
public void AddPage(RasterImage page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | RasterImage | The page to add. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *page* is null. |

## Examples

Create multipage GIF image using single page raster images.

```csharp
[C#]

static void Main(string[] args)
{
    // Load frames
    var frames = LoadFrames("Animation frames").ToArray();

    // Create GIF image using the first frame
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Add frames to the GIF image using the AddPage method
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Save GIF image
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


