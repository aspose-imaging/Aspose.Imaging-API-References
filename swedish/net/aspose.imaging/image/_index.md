---
title: Image
second_title: Aspose.Imaging för .NET API-referens
description: Bilden är basklassen för alla typer av bilder.
type: docs
weight: 9660
url: /sv/net/aspose.imaging/image/
---
## Image class

Bilden är basklassen för alla typer av bilder.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Får värdet filformat |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Hämtar bildhöjden. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Hämtar bildens bredd. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | Skapar en ny bild med de angivna bilderna som pages |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | Skapar en ny bild de angivna bilderna som sidor. |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | Skapar en ny bild med de angivna skapaalternativen. |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | Laddar en ny bild från den angivna strömmen. |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | Laddar en ny bild från den angivna filen. |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | Laddar en ny bild från den angivna strömmen. |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | Laddar en ny bild från den angivna filen. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](./save) metod som den andra parametern. |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
| [Save](../../aspose.imaging/image/save#save)() | Sparar bilddata till den underliggande strömmen. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Sparar objektets data till den angivna strömmen. |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | Sparar bilden till den angivna filplatsen. |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Ställer in bildpaletten. |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | Bestämmer om bilden kan laddas från den angivna strömmen. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | Bestämmer om bilden kan laddas från den angivna sökvägen. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | Bestämmer om bilden kan laddas från den angivna strömmen och eventuellt använda den angivna*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | Bestämmer om bilden kan laddas från den angivna sökvägen och eventuellt med de angivna öppna alternativen. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | Hämtar filformatet. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | Hämtar filformatet. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Får rektangel som passar den aktuella bilden. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Får rektangel som passar den aktuella bilden. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | Får en proportionell höjd. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | Får en proportionell bredd. |

### Exempel

Bestäm om paletten används av bilden.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

Ändra storlek på bild med hjälp av specifik storleksändringstyp.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Det här exemplet skapar en ny bildfil på någon diskplats som specificeras av Source-egenskapen för BmpOptions-instansen. Flera egenskaper för BmpOptions-instansen ställs in innan den faktiska bilden skapas. Speciellt egenskapen Source, som refererar till den faktiska diskplatsen i det här fallet.

```csharp
[C#]

//Skapa en instans av BmpOptions och ställ in dess olika egenskaper
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Skapa en instans av bild och initiera den med instans av BmpOptions genom att anropa metoden Skapa
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //gör lite bildbehandling

    // spara alla ändringar
    image.Save();
}
```

### Se även

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
