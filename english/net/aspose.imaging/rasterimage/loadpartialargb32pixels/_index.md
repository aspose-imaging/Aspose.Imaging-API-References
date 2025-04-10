---
title: RasterImage.LoadPartialArgb32Pixels
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Loads 32bit ARGB pixels partially by packs
type: docs
weight: 390
url: /net/aspose.imaging/rasterimage/loadpartialargb32pixels/
---
## RasterImage.LoadPartialArgb32Pixels method

Loads 32-bit ARGB pixels partially by packs.

```csharp
public void LoadPartialArgb32Pixels(Rectangle rectangle, 
    IPartialArgb32PixelLoader partialPixelLoader)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The desired rectangle. |
| partialPixelLoader | IPartialArgb32PixelLoader | The 32-bit ARGB pixel loader. |

## Examples

The following example shows how to load and process pixels of a raster image using your own partial processor. For example, consider a problem of counting of fully transparent pixels of an image. In order to count transparent pixels using partial loading mechanism, a separate class TransparentArgb32PixelCounter implementing Aspose.Imaging.IPartialArgb32PixelLoader is introduced.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Create an instance of the Aspose.Imaging.IPartialArgb32PixelLoader and pass it to the Aspose.Imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Load pixels for the whole image. Any rectangular part of the image can be specified as the first parameter of the Aspose.Imaging.RasterImage.LoadPartialArgb32Pixels method.
    rasterImage.LoadPartialArgb32Pixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// The counter may look like this:        
/// <summary>
/// Counts the number of fully transparent pixels with alpha channel value of 0.
/// </summary>
private class TransparentArgb32PixelCounter : IPartialArgb32PixelLoader
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
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, int[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (int pixel in pixels)
        {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0)
            {
                this.count++;
            }
        }
    }
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* interface [IPartialArgb32PixelLoader](../../ipartialargb32pixelloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


