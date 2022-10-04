---
title: MaxDiskSpaceForCache
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in maximalt tillgängligt diskutrymme för cache. Det angivna värdet är megabyte count.
type: docs
weight: 60
url: /sv/net/aspose.imaging/cache/maxdiskspaceforcache/
---
## Cache.MaxDiskSpaceForCache property

Hämtar eller ställer in maximalt tillgängligt diskutrymme för cache. Det angivna värdet är megabyte count.

```csharp
public static int MaxDiskSpaceForCache { get; set; }
```

### Fastighetsvärde

Maximalt tillgängligt diskutrymme för cache.

### Anmärkningar

Värdet 0 kommer att förbruka allt tillgängligt minne och fungerar som ingen övre gräns.

### Exempel

Detta exempel visar användningen av Aspose.Imaging.Cache

```csharp
[C#]

// Som standard är cachemappen inställd på användarens lokala temporära katalog.
// Du kan också ange en annan cachemapp än standard som följande:
// Cache.CacheFolder = @"D:\\MyTemp";

// Autoläget är flexibelt och effektivt
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom det i hög grad kan påverka prestandan
Aspose.Imaging.Cache.ExactReallocateOnly = false;

// Du kan när som helst kontrollera hur många byte som för närvarande är allokerade för minne eller disk 
// cache genom att undersöka följande egenskaper
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

// Gör lite bildbearbetning enligt nedan
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

    // efter exekvering av koden ovan kommer det att tilldelas 40000 byte i minnet.
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt var korrekt bortskaffade.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.            
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### Se även

* class [Cache](../../cache)
* namnutrymme [Aspose.Imaging](../../cache)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->