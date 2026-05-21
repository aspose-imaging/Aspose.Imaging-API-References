---
title: "GifImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för Graphical Interchange Format GIF-bildfil ger utvecklare mångsidiga verktyg för att bearbeta komprimerade rasterbilder och animerade GIF-filer."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

API:et för Graphical Interchange Format (GIF)-bildfil ger utvecklare mångsidiga verktyg för att bearbeta komprimerade rasterbilder och animerade GIF-filer. Det erbjuder funktioner som XMP-metadatahantering, färgpalettinställningar, bakgrunds- och transparent färgkontroll, opacitetsinställningar, storleksändring, beskärning, filtertillämpning, gamma-korrigeringar, kontrastjustering, gråskaleomvandling och konvertering till andra format. Detta API möjliggör sömlös manipulation och förbättring av GIF-bilder för ett brett spektrum av tillämpningar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | Initiera ett nytt [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-objekt med angivna parametrar för den första ramen och den globala paletten. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Att skapa GIF-bilder blir enkelt med [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-konstruktorn. |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | Kom igång utan ansträngning med [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-konstruktorn. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Hämta filformatet utan ansträngning med denna egenskap. |
| [hasTrailer()](#hasTrailer--) | Hantera närvaron av en trailer i dina GIF-filer med den här egenskapen. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Hantera närvaron av en trailer i dina GIF-filer med den här egenskapen. |
| [isPaletteSorted()](#isPaletteSorted--) | Styr sorteringen av paletten i dina GIF-bilder med den här egenskapen. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Styr sorteringen av paletten i dina GIF-bilder med den här egenskapen. |
| [getLoopsCount()](#getLoopsCount--) | Hämta loopantalet enkelt med den här egenskapen. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Hämta loopantalet enkelt med den här egenskapen. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Hantera palettens färgupplösning i dina GIF-bilder med den här egenskapen. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Hantera palettens färgupplösning i dina GIF-bilder med den här egenskapen. |
| [getPageCount()](#getPageCount--) | Hämta det totala antalet sidor som finns i bilden med denna enkla egenskap. |
| [getPages()](#getPages--) | Få åtkomst till sidorna i bilden via denna praktiska egenskap, vilket möjliggör sömlös navigering och manipulation av enskilda sidor vid behov. |
| [getBlocks()](#getBlocks--) | Få sömlös åtkomst till GIF-blocken med den här egenskapen, vilket underlättar enkel hämtning och manipulation av bildens underliggande datastrukturer. |
| [isInterlaced()](#isInterlaced--) | Bestämmer om bilden är interlaced, vilket påverkar dess visning under inläsning. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämta de ursprungliga filinställningsbaserade alternativen, avgörande för att upprätthålla noggrannhet och konsistens i bildbehandling och manipulation. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Inkludera en ny sida sömlöst i den befintliga bilden, vilket förbättrar dess innehåll och utökar dess omfattning. |
| [getActiveFrame()](#getActiveFrame--) | Hantera och manipulera ramar med den här egenskapen, vilket möjliggör smidig navigering och modifiering av den aktiva ramen i GIF-bilden. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Hantera och manipulera ramar med den här egenskapen, vilket möjliggör smidig navigering och modifiering av den aktiva ramen i GIF-bilden. |
| [getBackgroundColor()](#getBackgroundColor--) | Hantera bakgrundsfärgen i GIF-bilden med den här egenskapen. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Hantera bakgrundsfärgen i GIF-bilden med den här egenskapen. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Styr bakgrundsfärgsindexet i GIF-bilden med den här egenskapen. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Styr bakgrundsfärgsindexet i GIF-bilden med den här egenskapen. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Hantera pixelns bildförhållande i GIF-bilden med den här egenskapen. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Hantera pixelns bildförhållande i GIF-bilden med den här egenskapen. |
| [hasTransparentColor()](#hasTransparentColor--) | Bestäm om den aktiva ramen i GIF-bilden innehåller en transparent färg. |
| [getTransparentColor()](#getTransparentColor--) | Hämta den transparenta färgen för den aktiva ramen i GIF-bilden. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Bestäm om den aktiva ramen i GIF-bilden innehåller en transparent färg. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Den här egenskapen bestämmer om GIF-bilden innehåller en bakgrundsfärg. |
| [getImageOpacity()](#getImageOpacity--) | Hämta opaciteten för den aktiva ramen i bilden, vilket ger insikt i dess transparensnivå. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på detta [Image](../../com.aspose.imaging/image)-instans. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar storlek på detta [Image](../../com.aspose.imaging/image)-instans. |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | Storleksändring av bilden med hänsyn till hela ramarna för varje sida i en GIF, vilket förhindrar att potentiella artefakter uppstår. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Utför rotation, spegling eller båda på den aktiva ramen exklusivt. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Applicera dithering på den aktuella bilden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär bilden med ett angivet rektangelområde. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Förbättra bildkvaliteten genom att applicera gamma-korrigering. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Applicera ett specifikt filter på det utsedda området i bilden, vilket förbättrar dess visuella kvalitet eller ändrar dess utseende enligt önskemål. |
| [setFrameTime(int time)](#setFrameTime-int-) | Justerar varaktigheten för varje bildruta i millisekunder och säkerställer konsekvent timing genom hela bildsekvensen. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Justera bildens ljusstyrka enligt den angivna `brightness`-parametern. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Justera bildens kontrast, vilket förbättrar eller minskar skillnaden i ljusstyrka mellan pixlar. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma‑korrektion av en bild tillämpar en icke‑linjär justering av pixelvärdena, vilket förbättrar eller minskar ljusstyrkan baserat på de angivna koefficienterna för de röda, gröna och blå kanalerna. |
| [grayscale()](#grayscale--) | Omvandlingen av en bild till dess gråskalerepresentation konverterar färgbilden till en gråskala genom att ta bort färginformation samtidigt som luminansen bevaras. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisering av en bild med ett fördefinierat tröskelvärde konverterar en gråskala‑ eller färgbild till en binär bild, där varje pixel klassificeras som antingen svart eller vit beroende på om dess intensitetsvärde överstiger ett specificerat tröskelvärde. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisering av en bild med Otsu‑tröskelvärde är en metod som automatiskt bestämmer det optimala tröskelvärdet för att konvertera en gråskalebild till en binär bild. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskel är en metod för att konvertera en gråskalebild till en binär bild. |
| [orderBlocks()](#orderBlocks--) | Sortering av GIF‑blocken enligt GIF‑specifikationen säkerställer korrekt GIF‑layout och efterlevnad av standarden. |
| [clearBlocks()](#clearBlocks--) | Rensning av alla GIF‑block tar bort all befintlig data som lagrats i bilden. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | Infogning av ett nytt GIF‑block låter dig lägga till anpassad data på en specifik position i bilden. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Lägg till ett nytt GIF‑block låter dig inkludera ytterligare data i bilden. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Borttagning av ett GIF‑block tar bort specifik data från bilden och ger möjlighet att rensa eller ändra bildstrukturen. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Proportionell storleksändring behåller bildens bildförhållande medan dess storlek justeras, vilket säkerställer att bilden inte blir utdragen eller förvrängd. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Denna metod roterar bilden kring dess mittpunkt. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// Skapa ett GIF‑ramblock på 100 x 100 px.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Fyll hela blocket med rött.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Läs in ramar
    RasterImage[] frames = loadFrames("Animation frames");

    // Skapa GIF‑bild med den första ramen
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Lägg till ramar i GIF‑bilden med metoden AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Spara GIF‑bild
        image.save("Multipage.gif");
    }

    // frisläpp resurser
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


Initiera ett nytt [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-objekt med angivna parametrar för den första ramen och den globala paletten. Börja hantera GIF‑bilder snabbt, säkerställ exakt återgivning med anpassningsbara inställningar för optimala resultat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Den första ramen för att initiera GIF‑bilden med. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den globala paletten att använda. Observera att om både `firstFrame` och `globalPalette` är null så används standard‑globalpaletten. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


Att skapa GIF-bilder blir enkelt med [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-konstruktorn. Med bara firstFrame‑parametern går du in i en värld av dynamisk visuell kommunikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Den första ramen för att initiera GIF‑bilden med. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Kom igång enkelt med [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-konstruktorn. Med denna enkla metod kan du börja skapa animerade GIF-filer med lätthet. Ange bara firstFrame, globalPalette, paletteColorResolution, aspectRatio och andra parametrar, så är du redo att ge dina visuella element liv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Den första ramen för att initiera GIF‑bilden med. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den globala paletten att använda. Observera att om både `firstFrame` och `globalPalette` är null så används standard‑globalpaletten. |
| isPaletteSorted | boolean | Om den är satt till `true` sorteras paletten. Observera att parametern används när `globalPalette` inte är null. |
| paletteColorResolution | byte | Palettens färgupplösning. Observera att parametern används när `globalPalette` inte är null. |
| paletteBackgroundColorIndex | byte | Palettens bakgrundsfärgindex. |
| aspectRatio | byte | Bildförhållandet. |
| hasTrailer | boolean | Om den är satt till `true` har GIF-bilden en trailer, annars skrivs ingen trailer i slutet av strömmen. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta filformatet enkelt med den här egenskapen. Det är din primära källa för att identifiera formatet på dina filer. Sömlöst integrerad i ditt arbetsflöde ger den viktig information utan krångel.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Hantera förekomsten av en trailer i dina GIF-filer med den här egenskapen. Oavsett om du behöver kontrollera om en trailer finns eller ange dess närvaro förenklar egenskapen processen. Håll dina GIF-filer strukturerade och i enlighet med detta intuitiva verktyg.

**Returns:**
boolean - `true` om GIF har trailer; annars `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Hantera förekomsten av en trailer i dina GIF-filer med den här egenskapen. Oavsett om du behöver kontrollera om en trailer finns eller ange dess närvaro förenklar egenskapen processen. Håll dina GIF-filer strukturerade och i enlighet med detta intuitiva verktyg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om GIF har trailer; annars `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Styr sorteringen av paletten i dina GIF-bilder med den här egenskapen. Oavsett om du behöver kontrollera om paletten är sorterad eller ange sorteringsbeteendet ger egenskapen ett enkelt sätt att hantera palettorganisationen i dina GIF-filer.

**Returns:**
boolean - `true` om paletten är sorterad; annars `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Styr sorteringen av paletten i dina GIF-bilder med den här egenskapen. Oavsett om du behöver kontrollera om paletten är sorterad eller ange sorteringsbeteendet ger egenskapen ett enkelt sätt att hantera palettorganisationen i dina GIF-filer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om paletten är sorterad; annars `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Hämta loopantalet enkelt med den här egenskapen. Om din GIF-bild innehåller loopinformation ger egenskapen dig snabb åtkomst till loopantalet, vilket gör det möjligt att sömlöst hantera loopbeteendet i dina GIF-filer.

**Returns:**
int - Loopantalet eller 1 (standardvärde)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Hämta loopantalet enkelt med den här egenskapen. Om din GIF-bild innehåller loopinformation ger egenskapen dig snabb åtkomst till loopantalet, vilket gör det möjligt att sömlöst hantera loopbeteendet i dina GIF-filer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Loopantalet eller 1 (standardvärde) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Hantera palettens färgupplösning för dina GIF-bilder med den här egenskapen. Justera antalet bitar som används för att representera färger i paletten, vilket ger fin kontroll över färgdjup och bildkvalitet.

**Returns:**
byte - Palettens färgupplösningsbitar.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Hantera palettens färgupplösning för dina GIF-bilder med den här egenskapen. Justera antalet bitar som används för att representera färger i paletten, vilket ger fin kontroll över färgdjup och bildkvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | Palettens färgupplösningsbitar. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämta det totala antalet sidor som finns i bilden med denna enkla egenskap. Perfekt för att snabbt bedöma bildens omfattning.

**Returns:**
int - sidantalet.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Få åtkomst till sidorna i bilden via denna praktiska egenskap, vilket möjliggör sömlös navigering och manipulation av enskilda sidor vid behov.

**Returns:**
com.aspose.imaging.Image[] - sidorna.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Få sömlös åtkomst till GIF-blocken med den här egenskapen, vilket underlättar enkel hämtning och manipulation av bildens underliggande datastrukturer.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - GIF-blocken.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Bestämmer om bilden är interlaced, vilket påverkar dess visning under inläsning. Denna egenskap ger insikt i bildens renderingsbeteende, vilket är avgörande för att optimera laddningsstrategier och förbättra den övergripande visningsupplevelsen.

**Returns:**
boolean - `true` om denna bildinstans är interlaced; annars `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämta de ursprungliga filinställningsbaserade alternativen, avgörande för att upprätthålla noggrannhet och konsistens i bildbehandling och manipulation. Denna metod möjliggör sömlös integration av filspecifika parametrar i efterföljande operationer, vilket säkerställer korrekt återgivning och efterlevnad av bildens inneboende egenskaper. Detta kan vara hjälpsamt för att behålla bitdjup och andra parametrar från den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) metoden, kommer en PNG-bild med 8‑bit per pixel att produceras. För att undvika detta och spara PNG-bilden med 1‑bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) metoden som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Inkludera en ny sida sömlöst i den befintliga bilden, förbättra dess innehåll och utöka dess räckvidd. Denna metod utökar bildsamlingar med ytterligare innehåll, vilket främjar kreativitet och flexibilitet i bildhantering och sammansättning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Sidan att lägga till. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Läs in ramar
    RasterImage[] frames = loadFrames("Animation frames");

    // Skapa GIF‑bild med den första ramen
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Lägg till ramar i GIF‑bilden med metoden AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Spara GIF‑bild
        image.save("Multipage.gif");
    }

    // frisläpp resurser
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Hantera och manipulera ramar med den här egenskapen, vilket möjliggör smidig navigering och modifiering av den aktiva ramen i GIF-bilden.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Utdata ser ut så här:
// Aktiv bildramstorlek: { Width = 100, Height = 100}
// Rensa alla block
// Aktiv bildram är inte angiven
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Hantera och manipulera ramar med den här egenskapen, vilket möjliggör smidig navigering och modifiering av den aktiva ramen i GIF-bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | den aktiva bildramen. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hantera bakgrundsfärgen för GIF-bilden med denna egenskap. Du kan ange eller hämta bakgrundsfärgen för att säkerställa konsistens och förbättra den visuella attraktionskraften.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Hantera bakgrundsfärgen för GIF-bilden med denna egenskap. Du kan ange eller hämta bakgrundsfärgen för att säkerställa konsistens och förbättra den visuella attraktionskraften.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | bakgrundsfärgen. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Styr bakgrundsfärgindexet för GIF-bilden med denna egenskap. Ange eller hämta indexet för att upprätthålla konsistens eller uppnå önskade visuella effekter.

**Returns:**
byte - bakgrundsfärgindexet.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Styr bakgrundsfärgindexet för GIF-bilden med denna egenskap. Ange eller hämta indexet för att upprätthålla konsistens eller uppnå önskade visuella effekter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | bakgrundsfärgindexet. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Hantera pixelaspektförhållandet för GIF-bilden med denna egenskap. Ange eller hämta förhållandet för att säkerställa korrekt rendering och bibehålla visuell noggrannhet.

**Returns:**
byte - pixelaspektförhållandet.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Hantera pixelaspektförhållandet för GIF-bilden med denna egenskap. Ange eller hämta förhållandet för att säkerställa korrekt rendering och bibehålla visuell noggrannhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | pixelaspektförhållandet. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Bestäm om den aktiva bildramen i GIF-bilden innehåller en transparent färg. Denna egenskap ger ett bekvämt sätt att kontrollera transparens i bilden.

**Returns:**
boolean - ett värde som indikerar om den aktiva bildramen har transparent färg.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämta den transparenta färgen för den aktiva bildramen i GIF-bilden. Denna egenskap låter dig komma åt den specifika färg som har markerats som transparent i den aktuella aktiva bildramen.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Bestäm om den aktiva bildramen i GIF-bilden innehåller en transparent färg. Denna egenskap ger ett bekvämt sätt att kontrollera transparens i bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om den aktiva bildramen har transparent färg. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Denna egenskap avgör om GIF-bilden innehåller en bakgrundsfärg. Om true indikerar det att bilden inkluderar en bakgrundsfärg.

**Returns:**
boolean - ett värde som indikerar om bilden har bakgrundsfärg.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Hämta opaciteten för den aktiva bildramen i bilden, vilket ger insikt i dess transparensnivå. Denna egenskap är särskilt användbar för att förstå graden av transparens eller ogenomskinlighet i den aktiva bildramen i bilden.

Opacitetsvärdet mellan 0.0 (fullt transparent) och 1.0 (fullt ogenomskinlig).

**Returns:**
float - opaciteten för denna bild (aktiv bildram).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändrar storlek på detta [Image](../../com.aspose.imaging/image)-instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar storlek på detta [Image](../../com.aspose.imaging/image)-instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Den adaptiva algoritmen baserad på viktad och blandad rationell funktion och lanczos3-interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Det lilla rektangulära filtret
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Antalet färger i paletten.
resizeSettings.setEntriesCount(256);

// Färgkvantiseringen används inte
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Den euklidiska metoden
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Skala ner med 2 gånger med adaptiv omsampling.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Spara som PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


Ändring av bildens storlek samtidigt som hela bildramarna för varje sida i en GIF tas i beaktande, vilket förhindrar att potentiella artefakter uppstår. Denna metod är avgörande för att bevara bildens integritet och kvalitet, särskilt vid hantering av animerade GIF:ar eller sekvenser av bildramar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Utför rotation, spegling eller båda på den aktiva ramen exklusivt. Denna operation tillämpar transformationer enbart på den för närvarande aktiva ramen i bilden, och bevarar integriteten hos de andra ramarna i sekvensen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations-/vändningstypen. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// Hjälparklassen som används i huvudexemplet nedan.
class Utils {
    // Hjälpmetoden för att få en strängrepresentation av filformatet.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// Här är huvudexemplet
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotera, vänd och spara till utdatafilen.
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Applicera dithering på den aktuella bilden. Denna process förbättrar bildkvaliteten genom att minska färgbandning och förbättra färgövergångar, vilket resulterar i ett jämnare utseende.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den anpassade paletten för dithering. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Utför tröskel-dithering med en 4-bitars färgpalett som innehåller 16 färger.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Utför Floyd-dithering med en 1-bitars färgpalett som endast innehåller 2 färger – svart och vit.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden med ett angivet rektangelområde. Denna operation tar bort bildens yttre del och lämnar endast det valda området som definieras av rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |


**Example: The following example crops a GIF image.**
Följande exempel beskär en GIF-bild. Beskärningsområdet specificeras via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Beskär bilden. Beskärningsområdet är den rektangulära centrala delen av bilden.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Spara den beskurna bilden som PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Förbättra bildkvaliteten genom att tillämpa gamma‑korrigering. Denna metod justerar bildens färggamma för att uppnå optimal visuell klarhet. Den ändrar varje pixels gammavärde, vilket ger förbättrad färgåtergivning och övergripande bildutseende.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalernas koefficient |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Ange gamma-koefficient för röd, grön och blå kanaler.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Applicera ett specifikt filter på det angivna området i bilden, vilket förbättrar dess visuella kvalitet eller ändrar dess utseende enligt önskemål. Denna metod bearbetar selektivt pixlar inom den definierade rektangeln, vilket möjliggör riktade justeringar samtidigt som integriteten hos den omgivande bilddata bevaras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Alternativen. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett jämnvärde på 4,0 på hela bilden.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applicera ett rörelse‑Wiener-filter med en längd på 5, ett jämnvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applicera ett skärpningsfilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Justera varaktigheten för varje ram i millisekunder, vilket säkerställer konsekvent timing genom hela bildsekvensen. Denna metod sätter enhetligt visningstiden för varje ram, vilket möjliggör exakt kontroll över animationshastigheten. Att ändra detta värde återställer fördröjningen för alla ramar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tid | int | Tiden för ramens varaktighet i millisekunder. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Justera bildens ljusstyrka enligt den angivna `brightness`‑parametern. Denna metod ändrar ljusstyrkan för hela bilden enhetligt, vilket förstärker eller minskar den totala luminansen för att uppnå önskad effekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Ställ in ljusstyrkevärdet. De accepterade värdena för ljusstyrka ligger i intervallet [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Justera bildens kontrast, vilket förstärker eller minskar skillnaden i ljusstyrka mellan pixlar. Denna metod ändrar bildens övergripande tonomfång, så att mörkare områden blir mörkare och ljusare områden blir ljusare för att förbättra visuell klarhet och detalj.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | float | Kontrastvärde (i intervallet [-100; 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Ställ in kontrastvärdet. De accepterade värdena för kontrast ligger i intervallet [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma‑korrigering av en bild tillämpar en icke‑linjär justering av pixelvärdena, vilket förstärker eller minskar ljusstyrkan baserat på de angivna koefficienterna för de röda, gröna och blå kanalerna. Denna metod hjälper till att finjustera färgbalansen och luminansen i bilden, vilket förbättrar dess övergripande utseende och visuella kvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanalkoefficient |
| gammaGreen | float | Gamma för grön kanalkoefficient |
| gammaBlue | float | Gamma för blå kanalens koefficient |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Ange individuella gamma-koefficienter för röd, grön och blå kanaler.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Omvandlingen av en bild till dess gråskale‑representation konverterar färgbilden till en gråskalaversion genom att ta bort färginformation samtidigt som luminansen bevaras. Denna process förenklar bilden till nyanser av grått, vilket gör den lämplig för olika tillämpningar såsom utskrift, dokumentbehandling och gråskaleanalys.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
Följande exempel omvandlar en färgad GIF-bild till dess gråskale‑representation. Gråskalebilder består uteslutande av nyanser av grått och innehåller endast intensitetsinformation.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisering av en bild med ett fördefinierat tröskelvärde konverterar en gråskala‑ eller färgbild till en binär bild, där varje pixel klassificeras som antingen svart eller vit beroende på om dess intensitetsvärde överstiger ett specificerat tröskelvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln tilldelas värdet 255, annars 0. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
Följande exempel binäriserar en GIF-bild med den fördefinierade tröskeln. Binäriserade bilder innehåller endast 2 färger – svart och vitt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarisera bilden med ett tröskelvärde på 127.
    // Om ett motsvarande gråvärde för en pixel är större än 127, tilldelas ett värde på 255, annars 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binärisering av en bild med Otsu‑tröskling är en metod som används för att automatiskt bestämma det optimala tröskelvärdet för att konvertera en gråskalebild till en binär bild. Otsu‑trösklingsalgoritmen beräknar den tröskel som minimerar intra‑klassvariansen av pixelintensiteterna i de två resulterande klasserna (förgrund och bakgrund). Denna teknik är särskilt användbar när det optimala tröskelvärdet är okänt och behöver bestämmas adaptivt baserat på bildens histogram.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
Följande exempel binäriserar en GIF-bild med Otsu‑tröskling. Binäriserade bilder innehåller endast 2 färger – svart och vitt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarisera bilden med Otsu-tröskling.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binärisering av en bild med Bradleys adaptiva trösklingsalgoritm med integralbildströskling är en metod för att konvertera en gråskalebild till en binär bild. Denna algoritm beräknar en lokal tröskel för varje pixel baserat på den genomsnittliga intensiteten hos de omgivande pixlarna inom ett angivet fönster. Genom att adaptivt justera tröskeln baserat på lokala pixelintensiteter är Bradleys metod effektiv för att hantera variationer i belysning och kontrast över bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


Att ordna GIF‑blocken enligt GIF‑specifikationen säkerställer korrekt GIF‑layout och efterlevnad av standarden. Denna process innebär att blocken placeras i rätt sekvens enligt specifikationen. Dessutom kan det innebära att vissa [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock)-instanser som inte är nödvändiga för den slutgiltiga layouten tas bort. Genom att följa GIF‑specifikationen blir den resulterande bilden korrekt strukturerad och kompatibel med GIF‑visningsprogram.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Att rensa alla GIF‑block tar bort all befintlig data som lagrats i bilden. Denna operation återställer effektivt bilden till ett tomt tillstånd och tar bort eventuella tidigare tillagda block. Använd denna metod när du behöver börja om med en ren släta för att skapa eller modifiera en GIF‑bild.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Utdata ser ut så här:
// Aktiv bildramstorlek: { Width = 100, Height = 100}
// Rensa alla block
// Aktiv bildram är inte angiven
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


Att infoga ett nytt GIF‑block gör att du kan lägga till anpassad data på en specifik position i bilden. Denna metod gör att du kan placera anpassade block på en önskad plats i GIF‑bilden, vilket ger flexibilitet i organisering och strukturering av bilddata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade elementet där blocket kommer att infogas. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | GIF‑blocket som ska läggas till. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


Att lägga till ett nytt GIF‑block gör att du kan inkludera ytterligare data i bilden. Denna metod möjliggör att du kan bifoga anpassade block till GIF‑bilden, vilka kan innehålla olika typer av information.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | GIF‑blocket som ska läggas till. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Skapa en GIF‑bild 100 x 100 px.
// Det första blocket är helt svart som standard.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // Den första cirkeln är röd
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Den andra cirkeln är svart
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Öka gradvis vinkeln på den röda bågformen.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Öka gradvis vinkeln på den svarta bågen och radera den röda bågen.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


Att ta bort ett GIF‑block tar bort specifik data från bilden och ger möjlighet att rensa eller ändra bildens struktur. Denna metod gör det möjligt att ta bort oönskade eller onödiga block, vilket optimerar GIF‑bilden för effektiv lagring. Använd denna funktion för att eliminera föråldrad information från bilden samtidigt som dess integritet och kvalitet bevaras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Blocket att ta bort. |

--------------------

Obs: glöm inte att Dispose blocket om du inte kommer att lägga till det i någon annan GifImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Proportionell storleksändring behåller bildens bildförhållande samtidigt som dess storlek justeras, vilket säkerställer att bilden inte blir utdragen eller förvrängd. Denna metod ändrar bildens storlek proportionellt genom att skala både bredd och höjd med samma faktor. Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet `newWidth`/width och `newHeight`/height.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Denna metod roterar bilden kring dess mittpunkt. Genom att ange rotationsvinkeln kan du rotera bilden medurs eller moturs för att uppnå önskad orientering. Denna rotation hjälper till att justera bildens presentation eller justering utan att förvränga dess innehåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | Om den är inställd på `true` kommer bildens storlek att ändras enligt de roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna orörda och endast `` bildinnehållet roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

