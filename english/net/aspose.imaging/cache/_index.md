---
title: Class Cache
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Cache class. Contains cache settings
type: docs
weight: 250
url: /net/aspose.imaging/cache/
---
## Cache class

Contains cache settings.

```csharp
public static class Cache
```

## Properties

| Name | Description |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.imaging/cache/allocateddiskbytescount/) { get; } | Gets the allocated disk bytes count. |
| static [AllocatedMemoryBytesCount](../../aspose.imaging/cache/allocatedmemorybytescount/) { get; } | Gets the allocated in-memory bytes count. |
| static [CacheFolder](../../aspose.imaging/cache/cachefolder/) { get; set; } | Gets or sets the cache folder. |
| static [CacheType](../../aspose.imaging/cache/cachetype/) { get; set; } | Gets or sets the cache scheme used. |
| static [ExactReallocateOnly](../../aspose.imaging/cache/exactreallocateonly/) { get; set; } | Gets or sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher. |
| static [MaxDiskSpaceForCache](../../aspose.imaging/cache/maxdiskspaceforcache/) { get; set; } | Gets or sets the maximum available disk space for cache. The value specified is megabytes count. |
| static [MaxMemoryForCache](../../aspose.imaging/cache/maxmemoryforcache/) { get; set; } | Gets or sets the maximum available memory for cache in memory. The value specified is megabytes count. |

## Methods

| Name | Description |
| --- | --- |
| static [SetDefaults](../../aspose.imaging/cache/setdefaults/)() | Sets the `Cache` settings to defaults. |

## Examples

This example demonstrates the use of Aspose.Imaging.Cache

```csharp
[C#]

// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// Cache.CacheFolder = @"D:\\MyTemp";

// Auto mode is flexible and efficient
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

// Default value is 0, which means there is no upper limit
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
Aspose.Imaging.Cache.ExactReallocateOnly = false;

// At any time you may check how many bytes currently allocated for memory or disk 
// cache by examining the following properties
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

// Do some image processing as below
Aspose.Imaging.ImageOptions.GifOptions options = new Aspose.Imaging.ImageOptions.GifOptions();
options.Palette = new ColorPalette(new Aspose.Imaging.Color[] { Aspose.Imaging.Color.Red, Aspose.Imaging.Color.Blue, Aspose.Imaging.Color.Black, Aspose.Imaging.Color.White });
options.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(options, 100, 100))
{
    Aspose.Imaging.Color[] pixels = new Aspose.Imaging.Color[10000];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Aspose.Imaging.Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // after executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.            
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


