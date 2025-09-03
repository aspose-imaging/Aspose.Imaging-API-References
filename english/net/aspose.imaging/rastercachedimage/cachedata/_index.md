---
title: RasterCachedImage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Caches the data and ensures no additional data loading will be performed from the underlying DataStreamContainer
type: docs
weight: 110
url: /net/aspose.imaging/rastercachedimage/cachedata/
---
## RasterCachedImage.CacheData method

Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../datastreamsupporter/datastreamcontainer/).

```csharp
public override void CacheData()
```

## Examples

The following example shows how raster image caching affects performance. In general case, reading cached data is performed faster than reading non-cached data.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an image from a PNG file.
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Cache all pixel data so that no additional data loading will be performed from the underlying data stream
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Reading all pixels is pretty fast.
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = image.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Load an image from a PNG file
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Reading all pixels is not as fast as when caching
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = image.GetArgb32Pixel(x, y);
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

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


