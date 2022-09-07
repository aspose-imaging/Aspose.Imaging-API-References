---
title: FilterType
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in filtertypen som används under png-filsparprocessen.
type: docs
weight: 50
url: /sv/net/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

Hämtar eller ställer in filtertypen som används under png-filsparprocessen.

```csharp
public PngFilterType FilterType { get; set; }
```

### Exempel

Det här exemplet visar hur man skapar en PNG-bild med de angivna alternativen, fyller den med en linjär övertoningsfärg och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Antalet bitar per färgkanal
createOptions.BitDepth = 8;

// Varje pixel är en (röd, grön, blå) trippel följt av alfakomponenten.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Den maximala kompressionsnivån.
createOptions.CompressionLevel = 9;

// Användning av filter gör det möjligt att komprimera kontinuerliga tonala bilder mer effektivt.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Använd progressiv laddning
createOptions.Progressive = true;

// Skapa en PNG-bild med anpassade parametrar.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fyll bilden med en halvtransparent gradient.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Spara till en fil.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

Följande exempel visar hur olika filtertyper påverkar storleken på den utgående PNG-bilden.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Ställ in en filtertyp
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//Utgången kan se ut så här:
//Filtertypen är Ingen, utdatabildens storlek är 116845 byte.
//Filtertypen är upp, utdatabildens storlek är 86360 byte.
//Filtertypen är Sub, utdatabildstorleken är 94907 byte.
//Filtertypen är Paeth, utdatabildens storlek är 86403 byte.
//Filtertypen är Avg, utdatabildens storlek är 89956 byte.
//Filtertypen är Adaptiv, utdatabildens storlek är 97248 byte.
```

Följande exempel visar hur man sparar en bild i PNG-format med olika alternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
// Du kan också ladda bilder av vilket format som helst från en fil eller en stream.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fyll bilden med den blå-transparenta gradienten.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Progressiv laddning.
    saveOptions.Progressive = true;

    // Ställ in den horisontella och vertikala upplösningen till 96 pixlar per tum.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Varje pixel är en (röd, grön, blå) trippel följt av alfa.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Ställ in den maximala komprimeringsnivån.
    saveOptions.CompressionLevel = 9;

    // Detta är den bästa komprimeringen, men den långsammaste exekveringstiden.
    // Adaptiv filtrering innebär att sparprocessen kommer att välja det lämpligaste filtret för varje datarad.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // Antalet bitar per kanal.
    saveOptions.BitDepth = 8;

    // Spara till en fil.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Se även

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../pngoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
