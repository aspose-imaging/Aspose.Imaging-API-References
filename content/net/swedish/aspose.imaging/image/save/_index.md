---
title: Save
second_title: Aspose.Imaging för .NET API-referens
description: Sparar bilddata till den underliggande strömmen.
type: docs
weight: 240
url: /sv/aspose.imaging/image/save/
---
## Save() {#save}

Sparar bilddata till den underliggande strömmen.

```csharp
public void Save()
```

### Exempel

Följande exempel visar hur man sparar en hel BMP-bild eller en del av den till en fil eller stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertera till en svartvit bild
    bmpImage.BinarizeOtsu();

    // Spara på samma plats med standardalternativ.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // En palett innehåller bara två färger: Svart och vit i det här fallet.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // För alla monokroma bilder (inklusive svart-vita) räcker det att allokera 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Spara till en annan plats med de angivna alternativen.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Spara endast den centrala delen av bilden.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Spara hela bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Spara den centrala delen av bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Utgången kan se ut så här:
//Storleken på hela bilden i byte: 24062
//Storleken på den centrala delen av bilden i byte: 6046
```

### Se även

* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Sparar bilden till den angivna filplatsen.

```csharp
public override void Save(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att spara bilden till. |

### Se även

* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| options | ImageOptionsBase | Alternativen. |

### Exempel

Följande exempel laddar en BMP-bild från en fil och sparar sedan bilden till en PNG-fil.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Spara hela bilden till en PNG-fil.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

Det här exemplet visar de enkla stegen för att spara en bild. För att demonstrera denna operation laddar vi en befintlig fil från någon diskplats, utför rotera operationen på bilden och sparar bilden i PSD-format med hjälp av filsökväg

```csharp
[C#]

string dir = "c:\\temp\\";

//Skapa en instans av bildklass och initiera den med en befintlig fil via filsökväg
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Rotera bilden 180 grader runt X-axeln
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //Spara bilden som PSD till filsökväg med standardinställningar för PsdOptions
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

Följande exempel visar hur man sparar en hel BMP-bild eller en del av den till en fil eller stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertera till en svartvit bild
    bmpImage.BinarizeOtsu();

    // Spara på samma plats med standardalternativ.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // En palett innehåller bara två färger: Svart och vit i det här fallet.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // För alla monokroma bilder (inklusive svart-vita) räcker det att allokera 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Spara till en annan plats med de angivna alternativen.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Spara endast den centrala delen av bilden.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Spara hela bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Spara den centrala delen av bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Utgången kan se ut så här:
//Storleken på hela bilden i byte: 24062
//Storleken på den centrala delen av bilden i byte: 6046
```

### Se även

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| options | ImageOptionsBase | Alternativen. |
| boundsRectangle | Rectangle | Målbilden avgränsar rektangeln. Ställ in den tomma rektangeln för att använda sura gränser. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | alternativ |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Det gick inte att spara bild. |

### Exempel

Följande exempel laddar en BMP-bild från en fil och sparar sedan en rektangulär del av bilden till en PNG-fil.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Spara den övre halvan av bilden till en PNG-fil.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

Följande exempel visar hur man sparar en hel BMP-bild eller en del av den till en fil eller stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertera till en svartvit bild
    bmpImage.BinarizeOtsu();

    // Spara på samma plats med standardalternativ.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // En palett innehåller bara två färger: Svart och vit i det här fallet.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // För alla monokroma bilder (inklusive svart-vita) räcker det att allokera 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Spara till en annan plats med de angivna alternativen.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Spara endast den centrala delen av bilden.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Spara hela bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Spara den centrala delen av bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Utgången kan se ut så här:
//Storleken på hela bilden i byte: 24062
//Storleken på den centrala delen av bilden i byte: 6046
```

### Se även

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen att spara bildens data till. |
| optionsBase | ImageOptionsBase | Spara alternativen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | alternativBas |
| ArgumentException | Det går inte att spara i det angivna formatet eftersom det inte stöds för tillfället.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Bildexport misslyckades. |

### Exempel

Följande exempel laddar en bild från en fil och sparar sedan bilden i en PNG-filström.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Spara hela bilden i en filström.
        image.Save(outputStream, saveOptions);
    }
}
```

Det här exemplet visar processen att spara en bild i MemoryStream. För att demonstrera den här operationen, laddar exemplet en befintlig fil från någon diskplats, utför rotera operationen på bilden och sparar bilden i PSD-format

```csharp
[C#]

//Skapa en instans av MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Skapa en instans av bildklass och initiera den med en befintlig fil via filsökväg
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //Rotera bilden 180 grader runt X-axeln
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //Spara bilden som PSD till MemoryStream med standardinställningar för PsdOptions
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

Följande exempel visar hur man sparar en hel BMP-bild eller en del av den till en fil eller stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertera till en svartvit bild
    bmpImage.BinarizeOtsu();

    // Spara på samma plats med standardalternativ.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // En palett innehåller bara två färger: Svart och vit i det här fallet.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // För alla monokroma bilder (inklusive svart-vita) räcker det att allokera 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Spara till en annan plats med de angivna alternativen.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Spara endast den centrala delen av bilden.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Spara hela bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Spara den centrala delen av bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Utgången kan se ut så här:
//Storleken på hela bilden i byte: 24062
//Storleken på den centrala delen av bilden i byte: 6046
```

### Se även

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen att spara bildens data till. |
| optionsBase | ImageOptionsBase | Spara alternativen. |
| boundsRectangle | Rectangle | Målbilden avgränsar rektangeln. Ställ in den tomma rektangeln för användningskällans gränser. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | alternativBas |
| ArgumentException | Det går inte att spara i det angivna formatet eftersom det inte stöds för tillfället.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Bildexport misslyckades. |

### Exempel

Följande exempel laddar en bild från en fil och sparar sedan en rektangulär del av bilden till en PNG-filström.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Spara den övre halvan av bilden till en filström.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

Följande exempel visar hur man sparar en hel BMP-bild eller en del av den till en fil eller stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertera till en svartvit bild
    bmpImage.BinarizeOtsu();

    // Spara på samma plats med standardalternativ.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // En palett innehåller bara två färger: Svart och vit i det här fallet.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // För alla monokroma bilder (inklusive svart-vita) räcker det att allokera 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Spara till en annan plats med de angivna alternativen.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Spara endast den centrala delen av bilden.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Spara hela bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Spara den centrala delen av bilden i en minnesström
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Utgången kan se ut så här:
//Storleken på hela bilden i byte: 24062
//Storleken på den centrala delen av bilden i byte: 6046
```

### Se även

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
