---
title: BmpImage
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avBmpImageaspose.imaging.fileformats.bmp/bmpimage class.
type: docs
weight: 10
url: /sv/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda bild från och initiera pixel- och palettdata med. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | rasterbilden är null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man laddar en BmpImage från en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en BMP-bild från en fil.
// Källpixlarna kommer att konverteras till 32-bpp-format om det behövs.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Gör lite bildbehandling.
    // Spara till en annan BMP-fil.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### Se även

* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda bild från och initiera pixel- och palettdata med. |
| bitsPerPixel | UInt16 | Bitarna per pixel. |
| compression | BitmapCompression | Kompressionen att använda. |
| horizontalResolution | Double | Den horisontella upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |
| verticalResolution | Double | Den vertikala upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Rasterbilden kan inte vara null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man laddar en BmpImage från en fil med angivet bitdjup och upplösning.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en BMP-bild från en fil.
// Källpixlarna kommer att konverteras till 24-bpp-format om det behövs.
// Upplösningen kommer att ställas in på 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Gör lite bildbehandling.
    // Spara till en annan BMP-fil.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### Se även

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att ladda bild från och initiera pixel- och palettdata med. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Rasterbilden kan inte vara null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man laddar en BmpImage från en filström.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en BMP-bild från en filström.
// Källpixlarna kommer att konverteras till 32-bpp-format om det behövs.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Gör lite bildbehandling.
        // Spara till en annan BMP-fil.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### Se även

* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att ladda bild från och initiera pixel- och palettdata med. |
| bitsPerPixel | UInt16 | Bitarna per pixel. |
| compression | BitmapCompression | Kompressionen att använda. |
| horizontalResolution | Double | Den horisontella upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |
| verticalResolution | Double | Den vertikala upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Rasterbilden kan inte vara null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man laddar en BmpImage från en filström med angivet bitdjup och upplösning.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en BMP-bild från en filström.
// Källpixlarna kommer att konverteras till 24-bpp-format om det behövs.
// Upplösningen kommer att ställas in på 96 dpi.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Gör lite bildbehandling.
        // Spara till en annan BMP-fil.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### Se även

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden att initiera pixel- och palettdata med. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Rasterbilden kan inte vara null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man laddar en BmpImage från en annan instans av RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en ny PNG-bild.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Fyll hela PNG-bilden i rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Skapa en BMP-bild baserad på PNG-bilden.
    // Källpixlarna kommer att konverteras till 32-bpp-format om det behövs.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // Spara till en BMP-fil
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden att initiera pixel- och palettdata med. |
| bitsPerPixel | UInt16 | Bitarna per pixel. |
| compression | BitmapCompression | Kompressionen att använda. |
| horizontalResolution | Double | Den horisontella upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |
| verticalResolution | Double | Den vertikala upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Rasterbilden kan inte vara null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man laddar en BmpImage från en annan instans av RasterImage med angivet bitdjup och komprimering.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en ny PNG-bild.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Fyll hela PNG-bilden i rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Skapa en BMP-bild baserad på PNG-bilden.
    // Källpixlarna kommer att konverteras till 24-bpp-format om det behövs.
    // Upplösningen kommer att ställas in på 96 dpi.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Spara till en BMP-fil
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd. |
| height | Int32 | Bildhöjden. |

### Undantag

| undantag | skick |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man skapar en BmpImage av angiven storlek.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en 32-bitars BMP-bild på 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fyll hela bilden i rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Spara till en BMP-fil
    bmpImage.Save(dir + "output.bmp");
}
```

Följande exempel visar hur man palleterar en BMP-bild för att minska dess utdatastorlek.

```csharp
[C#]

// Skapa en BMP-bild 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Den linjära gradienten från bildens övre vänstra hörn till det nedre högra hörnet.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fyll hela bilden med den linjära gradientpenseln.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Få den närmaste 8-bitars färgpalett som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palletiserad.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-bitars palett innehåller högst 256 färger.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// Utgången ser ut så här:
// Den palettiserade bildstorleken är 11078 byte.
// Den icke-palettiserade bildstorleken är 40054 byte.
```

### Se även

* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd. |
| height | Int32 | Bildhöjden. |
| bitsPerPixel | UInt16 | Bitarna per pixel. |
| palette | IColorPalette | Färgpaletten. |

### Undantag

| undantag | skick |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man skapar en BmpImage av angiven storlek med den angivna paletten.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Skapa en monokrom palett som endast innehåller röda och gröna färger.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Skapa en monokrom 1-bpp BMP-bild på 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Fyll den övre halvan av bilden med rött.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Fyll den nedre halvan av bilden med grönt.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Spara till BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### Se även

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

Initierar en ny instans av[`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd. |
| height | Int32 | Bildhöjden. |
| bitsPerPixel | UInt16 | Bitarna per pixel. |
| palette | IColorPalette | Färgpaletten. |
| compression | BitmapCompression | Kompressionen att använda. |
| horizontalResolution | Double | Den horisontella upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |
| verticalResolution | Double | Den vertikala upplösningen. Observera på grund av avrundningen kan den resulterande upplösningen skilja sig något från den godkända. |

### Undantag

| undantag | skick |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Höjden ska vara positiv. |
| ArgumentException | Palett bör anges för bilder med 8 bitar per pixel eller mindre.;palett |

### Exempel

Exemplet visar hur man skapar en BmpImage med olika alternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Skapa en monokrom palett som endast innehåller röda och gröna färger.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Skapa en monokrom 1-bpp BMP-bild på 100 x 100 px.
// Den horisontella och vertikala upplösningen kommer att ställas in på 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Fyll den övre halvan av bilden med rött.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Fyll den nedre halvan av bilden med grönt.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Spara till en BMP-fil
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### Se även

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
