---
title: RasterImage.LoadPartialPixels
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Loads pixels partially by packs
type: docs
weight: 420
url: /net/aspose.imaging/rasterimage/loadpartialpixels/
---
## RasterImage.LoadPartialPixels method

Loads pixels partially by packs.

```csharp
public void LoadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```

| Parameter | Type | Description |
| --- | --- | --- |
| desiredRectangle | Rectangle | The desired rectangle. |
| pixelLoader | IPartialPixelLoader | The pixel loader. |

## Examples

The following example shows how to load and process pixels of a raster image using your own partial processor. For example, consider a problem of counting of fully transparent pixels of an image. In order to count transparent using partial loading mechanism, a separate class TransparentPixelCounter implementing Aspose.Imaging.IPartialPixelLoader is introduced.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Create an instance of the Aspose.Imaging.IPartialPixelLoader and pass it to the Aspose.Imaging.RasterImage.LoadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Load pixels for the whole image. Any rectangular part of the image can be specified as the first parameter of the Aspose.Imaging.RasterImage.LoadPartialPixels method.
    rasterImage.LoadPartialPixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// The counter may look like this:
/// <summary>
/// Counts the number of fully transparent pixels with alpha channel value of 0.
/// </summary>
private class TransparentPixelCounter : IPartialPixelLoader
{
    /// <summary>
    /// The number of fully transparent pixels.
    /// </summary>
    private int count;

    /// <summary>
    /// Gets the number of fully transparent pixels.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.
    /// </summary>
    /// <param name="pixelsRectangle">The pixels rectangle.</param>
    /// <param name="pixels">The 32-bit ARGB pixels.</param>
    /// <param name="start">The start pixels point.</param>
    /// <param name="end">The end pixels point.</param>
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, Aspose.Imaging.Color[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (Color pixel in pixels)
        {
            if (pixel.A == 0)
            {
                this.count++;
            }
        }
    }
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* interface [IPartialPixelLoader](../../ipartialpixelloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


