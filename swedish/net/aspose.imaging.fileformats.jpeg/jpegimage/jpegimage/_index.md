---
title: JpegImage
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avJpegImageaspose.imaging.fileformats.jpeg/jpegimage class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

Initierar en ny instans av[`JpegImage`](../../jpegimage) class.

```csharp
public JpegImage(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda bild från och initiera pixel- och palettdata med. |

### Exempel

Exemplet visar hur man laddar en JpegImage från en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en JPEG-bild från en fil.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Gör lite bildbehandling.
    // Spara till en annan JPEG-fil.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Se även

* class [JpegImage](../../jpegimage)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* hopsättning [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

Initierar en ny instans av[`JpegImage`](../../jpegimage) class.

```csharp
public JpegImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen för att ladda bild från och initiera pixel- och palettdata med. |

### Exempel

Exemplet visar hur man laddar en JpegImage från en filström.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en JPEG-bild från en filström.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // Gör lite bildbehandling.
        // Spara till en annan JPEG-fil.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### Se även

* class [JpegImage](../../jpegimage)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* hopsättning [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

Initierar en ny instans av[`JpegImage`](../../jpegimage) class.

```csharp
public JpegImage(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden att initiera pixel- och palettdata med. |

### Exempel

Exemplet visar hur man laddar en JpegImage från en annan RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en JPEG-bild från en annan rasterbild.
// Skapa först en temporär PNG-bild som kommer att vara en grund för att bygga en JPEG-bild.
// Du kan också ladda PNG-bild från en fil eller använda en bild av något annat rasterformat.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Fyll hela PNG-bilden i rött.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // Skapa en JPEG-bild baserad på PNG-bilden.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // Spara till en JPEG-fil
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* hopsättning [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

Initierar en ny instans av[`JpegImage`](../../jpegimage) class.

```csharp
public JpegImage(int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd. |
| height | Int32 | Bildhöjden. |

### Exempel

Följande exempel visar hur man skapar en JPEG-bild med angiven storlek.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en JPEG-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // Gör lite bildbehandling.
    // Spara till en fil.
    jpegImage.Save(dir + "output.jpg");
}
```

Följande exempel laddar en BMP-bild och sparar den till JPEG med hjälp av olika sparalternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en BMP-bild från en fil.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Gör lite bildbehandling.

    // Använd ytterligare alternativ för att ange önskade bildparametrar.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Antalet bitar per kanal är 8.
    // När en palett används lagras färgindexet i bilddata istället för själva färgen.
    saveOptions.BitsPerChannel = 8;

    // Ställ in den progressiva typen av komprimering.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Ställ in bildkvaliteten. Det är ett värde mellan 1 och 100.
    saveOptions.Quality = 100;

    // Ställ in den horisontella/vertikala upplösningen till 96 punkter per tum.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Om källbilden är färgad kommer den att konverteras till gråskala.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Använd en palett för att minska utdatastorleken.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

### Se även

* class [JpegImage](../../jpegimage)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* hopsättning [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

Initierar en ny instans av[`JpegImage`](../../jpegimage) class.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| jpegOptions | JpegOptions | JPEG-alternativen. |
| width | Int32 | Bildbredd. |
| height | Int32 | Bildhöjd. |

### Exempel

Följande exempel laddar en BMP-bild och sparar den till JPEG med hjälp av olika sparalternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en BMP-bild från en fil.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Gör lite bildbehandling.

    // Använd ytterligare alternativ för att ange önskade bildparametrar.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Antalet bitar per kanal är 8.
    // När en palett används lagras färgindexet i bilddata istället för själva färgen.
    saveOptions.BitsPerChannel = 8;

    // Ställ in den progressiva typen av komprimering.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Ställ in bildkvaliteten. Det är ett värde mellan 1 och 100.
    saveOptions.Quality = 100;

    // Ställ in den horisontella/vertikala upplösningen till 96 punkter per tum.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Om källbilden är färgad kommer den att konverteras till gråskala.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Använd en palett för att minska utdatastorleken.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

Följande exempel visar hur man skapar en JPEG-bild av den angivna storleken med de angivna parametrarna.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en JPEG-bild på 100x100 px.
// Använd ytterligare alternativ för att ange önskade bildparametrar.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Antalet bitar per kanal är 8, 8, 8 för Y, Cr, Cb komponenter i enlighet därmed.
createOptions.BitsPerChannel = 8;

// Ställ in den progressiva typen av komprimering.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Ställ in bildkvaliteten. Det är ett värde mellan 1 och 100.
createOptions.Quality = 100;

// Ställ in den horisontella/vertikala upplösningen till 96 punkter per tum.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Detta är ett standardalternativ för JPEG-bilder.
// Två chroma-komponenter (Cb och Cr) kan bandbreddsreduceras, subsamplas, komprimeras.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Fyll bilden med en gråskalegradient
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Spara till en fil.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Se även

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
