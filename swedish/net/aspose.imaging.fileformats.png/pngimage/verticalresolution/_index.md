---
title: VerticalResolution
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in den vertikala upplösningen.
type: docs
weight: 140
url: /sv/net/aspose.imaging.fileformats.png/pngimage/verticalresolution/
---
## PngImage.VerticalResolution property

Hämtar eller ställer in den vertikala upplösningen.

```csharp
public override double VerticalResolution { get; set; }
```

### Exempel

Följande exempel visar hur man ställer in horisontell/vertikal upplösning för en PNG-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

    // Få horisontell och vertikal upplösning av PngImage.
    double horizontalResolution = pngImage.HorizontalResolution;
    double verticalResolution = pngImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Använd metoden SetResolution för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        pngImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", pngImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", pngImage.VerticalResolution);
    }
}
```

### Se även

* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->