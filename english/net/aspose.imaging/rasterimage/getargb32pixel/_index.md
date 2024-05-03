---
title: RasterImage.GetArgb32Pixel
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Gets an image 32bit ARGB pixel
type: docs
weight: 290
url: /net/aspose.imaging/rasterimage/getargb32pixel/
---
## RasterImage.GetArgb32Pixel method

Gets an image 32-bit ARGB pixel.

```csharp
public int GetArgb32Pixel(int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Int32 | The pixel x location. |
| y | Int32 | The pixel y location. |

### Return Value

The 32-bit ARGB pixel for the specified location.

## Examples

The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Get an integer representation of the color of the top-left pixel of the image.
    int color = rasterImage.GetArgb32Pixel(0, 0);

    // To obtain the values of the individual color components, shift the color value by a corresponding number of bits
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

The following example shows how image caching affects performance. In general case, reading cached data is performed faster than reading non-cached data.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an image from a PNG file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Cache all pixel data so that no additional data loading will be performed from the underlying data stream
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Reading all pixels is pretty fast.
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Load an image from a PNG file
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Reading all pixels is not as fast as when caching
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// The output may look like this:
// Reading all cached pixels took 1500 ms.
// Reading all pixels without preliminary caching took 150000 ms.
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


