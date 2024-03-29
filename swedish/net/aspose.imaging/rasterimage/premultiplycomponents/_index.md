---
title: PremultiplyComponents
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras.
type: docs
weight: 60
url: /sv/net/aspose.imaging/rasterimage/premultiplycomponents/
---
## RasterImage.PremultiplyComponents property

Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras.

```csharp
public virtual bool PremultiplyComponents { get; set; }
```

### Fastighetsvärde

`Sann` om bildkomponenterna måste förmultipliceras; annat,`falsk` .

### Exempel

Följande exempel skapar en ny rasterbild, sparar de angivna halvtransparenta pixlarna, laddar sedan dessa pixlar och får slutliga färger i förmultiplicerad form.

```csharp
[C#]

int imageWidth = 3;
int imageHeight = 2;

Aspose.Imaging.Color[] colors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 255, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 255),
};

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, imageWidth, imageHeight))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Spara pixlar för hela bilden.
    rasterImage.SavePixels(rasterImage.Bounds, colors);

    // Pixlarna lagras i originalbilden i icke-förmultiplicerad form.
    // Behöver ange motsvarande alternativ explicit för att erhålla förmultiplicerade färgkomponenter.
    // De förmultiplicerade färgkomponenterna beräknas med formlerna:
    // red = original_red * alfa / 255;
    // grön = original_grön * alfa / 255;
    // blå = original_blå * alfa / 255;
    rasterImage.PremultiplyComponents = true;
    Aspose.Imaging.Color[] premultipliedColors = rasterImage.LoadPixels(rasterImage.Bounds);

    for (int i = 0; i < colors.Length; i++)
    {
        System.Console.WriteLine("Original color: {0}", colors[i].ToString());
        System.Console.WriteLine("Premultiplied color: {0}", premultipliedColors[i].ToString());
    }
}
```

### Se även

* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
