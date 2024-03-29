---
title: Lossless
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in ett värde som indikerar om dettaWebPOptionsaspose.imaging.imageoptions/webpoptions är förlustfri.
type: docs
weight: 40
url: /sv/net/aspose.imaging.imageoptions/webpoptions/lossless/
---
## WebPOptions.Lossless property

Hämtar eller ställer in ett värde som indikerar om detta[`WebPOptions`](../../webpoptions) är förlustfri.

```csharp
public bool Lossless { get; set; }
```

### Fastighetsvärde

`Sann` om förlustfri; annat,`falsk` .

### Exempel

Det här exemplet visar hur man skapar en WebP-bild från en annan rasterbild med annan komprimeringskvalitet.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en GIF-animation
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // för förlustfri komprimering, ökad kvalitetsinställning ökar komprimeringskvaliteten och minskar filstorleken
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // filstorlek: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // filstorlek: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // filstorlek: 40 KB


    // för komprimering med förlust, ökar kvalitetsvärdet bildkvaliteten och filstorleken
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // filstorlek: 24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // filstorlek: 36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // filstorlek: 51 KB
}
```

### Se även

* class [WebPOptions](../../webpoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../webpoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
