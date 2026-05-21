---
title: "WebPImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera WebP rasterbilder med vårt API med hjälp av dess moderna funktioner för både förlustfri och förlustkomprimering och säkerställa optimal bildkvalitet med minskade filstorlekar."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Manipulera WebP rasterbilder med vårt API, med hjälp av dess moderna funktioner för både förlustfri och förlustkomprimering, och säkerställa optimal bildkvalitet med minskade filstorlekar. Hantera sömlöst utökade filformat, animationer och alfakanaler, samtidigt som du enkelt uppdaterar dimensioner, ändrar storlek proportionellt, beskär, roterar, tillämpar filter, justerar bildparametrar och konverterar till andra bildformat för mångsidig webb bildoptimering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initierad från en angiven strömkälla. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en ström och angivna inläsningsalternativ, vilket möjliggör mångsidig hantering av WebP bilddata. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Skapa en ny fräsch instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initierad från en angiven filkälla. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en fil och angivna inläsningsalternativ, vilket möjliggör flexibel hantering av WebP bilddata. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initierad från ett angivet rasterImage‑objekt. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med ett rasterImage‑objekt och angivna inläsningsalternativ, vilket möjliggör flexibel hantering av bilddata. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en tom bild med angivna bredd‑ och höjdmått. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en tom bild och angivna inläsningsalternativ. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOptions()](#getOptions--) | Hämta eller ändra de alternativ som är associerade med den angivna egenskapen, vilket möjliggör finjusterad anpassning av beteende och inställningar. |
| [getPages()](#getPages--) | Åtkomst till WebP‑blocken i bilden, vilket möjliggör detaljerad granskning eller manipulation av den underliggande blockstrukturen. |
| [getPageCount()](#getPageCount--) | Hämta det totala antalet sidor i det angivna dokumentet, vilket underlättar effektiv navigering och hantering av flersidigt innehåll. |
| [getFileFormat()](#getFileFormat--) | Åtkomst till filformatvärdet som är associerat med bilden, vilket ger information om det format i vilket bilden lagras. |
| [hasAlpha()](#hasAlpha--) | Hämta om bilden innehåller en alfakanal, vilket indikerar närvaron av transparensinformation. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Lägg till en ny sida i bilden, vilket utökar dess innehåll och möjliggör ytterligare visuella element. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Inkludera ett nytt WebP‑block i bilden, vilket berikar dess innehåll och underlättar avancerad bildmanipulation. |
| [clearBlocks()](#clearBlocks--) | Rensa alla befintliga WebP‑block från bilden, vilket ger en ren start för efterföljande ändringar eller tillägg. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Infoga ett nytt WebP‑block på det angivna indexet i bilden, vilket möjliggör exakt kontroll över blocksekvensen. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Ta bort det angivna WebP‑blocket från bilden, vilket underlättar effektiv hantering av bilddatastrukturen. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar alternativen baserat på de ursprungliga filinställningarna. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotera bilden kring dess centrum med en angiven vinkel, samtidigt som den skalas proportionellt och angivna bakgrundsfärgsparametrar tillämpas. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändra storlek på bilden, justera dess dimensioner samtidigt som bildförhållandet bevaras. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Justera bildens bredd proportionellt samtidigt som bildförhållandet bibehålls. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Justera bildens höjd proportionellt, samtidigt som bildförhållandet bevaras för enhetlig storleksändring. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Tillämpa rotation, spegling eller båda operationerna uteslutande på den aktiva ramen i bilden. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Utför dithering på den aktuella bilden för att minska färgbandning och förbättra den visuella kvaliteten. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär bilden med ett angivet rektangelområde, ta bort oönskade delar samtidigt som önskat innehåll behålls. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Beskär bilden genom att tillämpa vänster-, höger-, topp- och bottenförskjutningar, vilket effektivt väljer ett intresseområde inom bilden. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Utför binarisering av bilden med ett fördefinierat tröskelvärde, vilket konverterar den till en binär bild där pixlar klassificeras som förgrund eller bakgrund baserat på deras intensitet i förhållande till tröskeln. |
| [binarizeOtsu()](#binarizeOtsu--) | Utför binarisering av bilden med Otsus tröskelmetod, som automatiskt bestämmer det optimala tröskelvärdet baserat på bildens histogram. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Tillämpa binarisering på bilden med Bradleys adaptiva tröskelalgoritm med integral bildtröskling. |
| [grayscale()](#grayscale--) | Tillämpa binarisering på bilden med Bradleys adaptiva tröskelalgoritm med integral bildtröskling. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Tillämpa gamma‑korrektion på bilden, justera pixelintensiteter för att uppnå önskad ljusstyrka och färgbalans. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Utför gamma‑korrektion på bilden med individuella koefficienter för de röda, gröna och blå kanalerna, vilket möjliggör finjusterade justeringar av färgbalans och kontrast. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implementera `brightness`‑justering för bilden, vilket möjliggör ändring av den övergripande luminansnivån. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Förbättra kontrasten i [Image](../../com.aspose.imaging/image), förstärka skillnaderna mellan ljusa och mörka områden. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtrera innehållet inom den angivna rektangeln genom att applicera ett bestämt bildbehandlingsfilter för att förbättra eller ändra det valda området. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändra storlek på bilden enligt angivna inställningar, vilket möjliggör exakt kontroll över dimensioner, bildförhållande och skalningsbeteende. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Läs in en WebP‑bild från en fil.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // Spara som PNG
    // Observera att endast den aktiva ramen kommer att sparas till PNG, eftersom PNG inte är ett flersidigt format.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


Instansiera en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initierad från en angiven strömkälla. Använd denna konstruktor för att sömlöst skapa WebP‑bildobjekt direkt från strömmar, vilket möjliggör effektiv hantering och manipulation av WebP‑bilddata i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen WebP‑bild. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en ström och angivna inläsningsalternativ, vilket underlättar mångsidig hantering av WebP‑bilddata. Inkludera denna konstruktor för att sömlöst initiera WebP‑bildobjekt från strömmar samtidigt som du anpassar inläsningsparametrar efter behov i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen WebP‑bild. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Instansiera en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initierad från en angiven filkälla. Använd denna konstruktor för att sömlöst skapa WebP‑bildobjekt direkt från filer, vilket förenklar processen för inläsning och manipulation av WebP‑bilddata i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen till filen WebP‑bild |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en fil och angivna inläsningsalternativ, vilket möjliggör flexibel hantering av WebP‑bilddata. Använd denna konstruktor för att sömlöst initiera WebP‑bildobjekt från filer samtidigt som du anpassar inläsningsparametrar enligt din applikations krav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen till filen WebP‑bild |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Instansiera en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initierad från ett angivet rasterImage‑objekt. Denna konstruktor möjliggör sömlös konvertering av rasterbilder till WebP‑format, vilket möjliggör effektiv hantering och manipulation av bilddata i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med ett rasterImage‑objekt och angivna inläsningsalternativ, vilket möjliggör flexibel hantering av bilddata. Använd denna konstruktor för att sömlöst initiera WebP‑bildobjekt från rasterbilder samtidigt som du anpassar inläsningsparametrar enligt din applikations krav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Instansiera en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en tom bild med angivna bredd- och höjdmått. Denna konstruktor möjliggör skapandet av tomma WebP‑bilder, vilket ger en grund för efterföljande bildmanipulation och innehållsgenerering i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd |
| höjd | int | Bildens höjd. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Alternativen. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


Skapa en ny instans av klassen [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) med en tom bild och angivna inläsningsalternativ. Denna konstruktor möjliggör initiering av WebP‑bilder med anpassningsbara inläsningsparametrar, vilket ger flexibilitet vid bildskapande och manipulation i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd |
| höjd | int | Bildens höjd. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Alternativen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Hämta eller ändra alternativen som är kopplade till den angivna egenskapen, vilket möjliggör finjusterad anpassning av beteende och inställningar. Använd denna egenskap för att sömlöst komma åt och manipulera konfigurerbara parametrar, vilket underlättar mångsidig kontroll och optimering i din applikations funktionalitet.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Kom åt WebP‑blocken i bilden, vilket möjliggör detaljerad granskning eller manipulation av den underliggande blockstrukturen. Använd denna egenskap för att analysera eller ändra enskilda block i WebP‑bilddata, vilket underlättar avancerade bildbehandlingstekniker i din applikation.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämta det totala antalet sidor i det angivna dokumentet, vilket underlättar effektiv navigering och hantering av flersidigt innehåll. Inkludera denna funktion för att förbättra användarupplevelsen, vilket möjliggör sömlös åtkomst till omfattande dokumentstrukturer.

**Returns:**
int - sidantalet.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Åtkomst till filformatvärdet som är associerat med bilden, vilket ger information om det format i vilket bilden lagras. Använd denna egenskap för att bestämma bildens filformat, vilket underlättar kompatibilitetskontroller och format‑specifik bearbetning i din applikation.

**Returns:**
long - ett värde för filformat
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämta om bilden innehåller en alfakanal, vilket indikerar närvaro av transparensinformation. Använd denna egenskap för att avgöra om bilden har transparens, vilket möjliggör lämplig hantering och bearbetning av alfarelaterade operationer i din applikation.

**Returns:**
boolean - `true` om det finns en alfakanal.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Om den aktiva TIFF-ramen har alfakanal, anses hela TIFF-bilden ha alfakanal.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Lägg till en ny sida i bilden, utöka dess innehåll och rymma ytterligare visuella element. Integrera denna metod för att underlätta dynamisk sidhantering i din applikation, vilket möjliggör sömlös skapande och utökning av flersidiga dokument eller bilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Sidan att lägga till. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Inkludera ett nytt WebP‑block i bilden, berika dess innehåll och underlätta avancerad bildmanipulation. Integrera denna metod för att dynamiskt förbättra strukturen och komplexiteten i WebP‑bilddata i din applikation, vilket möjliggör exakt kontroll och optimering av bildrendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Webp‑blocket att lägga till. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// Standardramen plus 36 + 36 ytterligare ramar.
createOptions.setAnimLoopCount(36 + 36 + 1);

// Skapa en WebP‑bild på 100 × 100 px.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // Den första cirkeln är röd
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Den andra cirkeln är svart
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Öka gradvis vinkeln på den röda bågformen.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Öka gradvis vinkeln på den svarta bågen och radera den röda bågen.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // Spara till en WebP‑fil
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Rensa alla befintliga WebP‑block från bilden, vilket ger en ren start för efterföljande ändringar eller tillägg. Använd denna metod för att effektivt återställa blockstrukturen i WebP‑bilddata, vilket säkerställer optimal hantering och organisering av bildinnehåll i din applikation.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Infoga ett nytt WebP‑block på det angivna indexet i bilden, vilket möjliggör exakt kontroll över blocksekvensen. Integrera denna metod för att sömlöst lägga till ytterligare WebP‑block i bilddatastrukturen, vilket underlättar avancerad bildbehandling och optimering i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade elementet där `block` kommer att infogas. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Webp‑blocket att lägga till. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Ta bort det angivna WebP‑blocket från bilden, vilket underlättar effektiv hantering av bilddatastrukturen. Använd denna metod för att förenkla bildbehandlingsarbetsflöden genom att eliminera onödiga block eller komponenter i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Blocket att ta bort. |

--------------------

Obs: glöm inte att avyttra `block` om du inte kommer att lägga till det i någon annan WebPImage. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Får alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av metoden [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), kommer en PNG-bild med 8 bitar per pixel att produceras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotera bilden kring dess centrum med en angiven vinkel, samtidigt som den proportionellt skalas om och appliceras med angivna bakgrundsfärgsparametrar. Inkludera denna metod i ditt bildbehandlingsarbetsflöde för att uppnå precisa transformationer med anpassningsbara bakgrundsfärger, vilket säkerställer optimal visuell presentation i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | Om den är inställd på `true` kommer bildens storlek att ändras enligt de roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna orörda och endast `` bildinnehållet roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Skala om bilden, justera dess dimensioner samtidigt som bildförhållandet bevaras. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att dynamiskt skala bilder så att de passar olika visnings- eller lagringskrav i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Justera bildens bredd proportionellt samtidigt som bildförhållandet bibehålls. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att dynamiskt ändra storlek på bilder med konsekventa proportioner, vilket säkerställer optimal visning eller lagring i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av storleksändring. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Justera bildens höjd proportionellt, samtidigt som bildförhållandet bevaras för enhetlig storleksändring. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att dynamiskt ändra storlek på bilder med jämna proportioner, vilket säkerställer optimal visning eller lagring i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Applicera rotation, spegling eller båda operationerna uteslutande på den aktiva ramen i bilden. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att uppnå exakt manipulation av enskilda ramar, vilket ökar flexibiliteten och kontrollen över ramtransformationer i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations-/vändningstypen. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Utför dithering på den aktuella bilden för att minska färgbandning och förbättra den visuella kvaliteten. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att uppnå mjukare färgövergångar och förbättra bildens övergripande utseende i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den anpassade paletten för dithering. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden med ett angivet rektangelområde, ta bort oönskade delar samtidigt som önskat innehåll behålls. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att exakt extrahera och fokusera på specifika intresseområden i bilden, vilket förbättrar klarhet och komposition för olika tillämpningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beskär bilden genom att tillämpa vänster-, höger-, topp- och bottenförskjutningar, vilket effektivt väljer ett intresseområde i bilden. Använd denna metod för att dynamiskt extrahera önskade delar av bilden samtidigt som dess sammansättning och fokus justeras enligt din applikations krav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | int | Den vänstra förskjutningen. |
| rightShift | int | Den högra förskjutningen. |
| topShift | int | Den övre förskjutningen. |
| bottomShift | int | Den nedre förskjutningen. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Utför binarisering av bilden med ett fördefinierat tröskelvärde, vilket konverterar den till en binär bild där pixlar klassificeras som förgrund eller bakgrund baserat på deras intensitet i förhållande till tröskeln. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att underlätta segmentering och funktionsextraktion, vilket förbättrar noggrannheten och effektiviteten i efterföljande analys i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln tilldelas den värdet (byte)255, annars 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Utför binarisering av bilden med Otsu's tröskelmetod, som automatiskt bestämmer det optimala tröskelvärdet baserat på bildens histogram. Integrera denna metod i ditt bildbehandlingsflöde för att uppnå effektiv segmentering och funktionsextraktion, vilket förbättrar noggrannheten och tillförlitligheten i bildanalysuppgifter inom din applikation.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Applicera binarisering på bilden med Bradleys adaptiva tröskelalgoritm med integrerad bildtröskling. Denna metod beräknar dynamiskt lokala tröskelvärden baserat på bildens omgivning, vilket förbättrar anpassningsförmågan till varierande ljusförhållanden och säkerställer robust segmentering för efterföljande bearbetningsuppgifter inom din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |
| windowSize | int | Storleken på ett s x s-fönster av pixlar centrerade kring denna pixel. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Applicera binarisering på bilden med Bradleys adaptiva tröskelalgoritm med integrerad bildtröskling. Denna metod beräknar dynamiskt lokala tröskelvärden baserat på bildens omgivning, vilket förbättrar anpassningsförmågan till varierande ljusförhållanden och säkerställer robust segmentering för efterföljande bearbetningsuppgifter inom din applikation.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Applicera gamma‑korrektion på bilden och justera pixelintensiteter för att uppnå önskad ljusstyrka och färgbalans. Inkludera denna metod i ditt bildbehandlingsflöde för att förbättra den visuella kvaliteten och öka noggrannheten i efterföljande analys‑ eller visningsuppgifter inom din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalernas koefficient |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Utför gamma‑korrektion på bilden med individuella koefficienter för de röda, gröna och blå kanalerna, vilket möjliggör finjusterade justeringar av färgbalans och kontrast. Integrera denna metod i din bildbehandlingspipeline för att uppnå exakt kontroll över färgåtergivning och förbättra den visuella äktheten i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanalkoefficient |
| gammaGreen | float | Gamma för grön kanalkoefficient |
| gammaBlue | float | Gamma för blå kanalens koefficient |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementera `brightness`-justering för bilden, vilket möjliggör modifiering av den övergripande luminansnivån. Inkludera denna metod i ditt bildbehandlingsflöde för att förbättra synligheten och höja den visuella kvaliteten på bilder i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Förbättra kontrasten på [Image](../../com.aspose.imaging/image) genom att förstärka skillnaderna mellan ljusa och mörka områden. Integrera denna metod i ditt bildbehandlingsflöde för att förbättra den visuella klarheten och den övergripande bildkvaliteten i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtrera innehållet inom den angivna rektangeln genom att applicera ett bestämt bildbehandlingsfilter för att förbättra eller ändra det valda området. Integrera denna metod i ditt bildmanipuleringsflöde för att uppnå riktade förbättringar eller transformationer i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Alternativen. |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett jämnvärde på 4,0 på hela bilden.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applicera ett rörelse‑Wiener-filter med en längd på 5, ett jämnvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applicera ett skärpningsfilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändra storlek på bilden enligt angivna inställningar, vilket möjliggör exakt kontroll över dimensioner, bildförhållande och skalningsbeteende. Integrera denna metod i ditt bildbehandlingsflöde för att uppnå anpassade storleksändringsoperationer som är skräddarsydda för din applikations specifika krav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |

