---
title: "TiffImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bearbeta Tagged Image File Format (TIFF) rasterbilder med vårt API som erbjuder omfattande stöd för olika upplösningar och avancerade redigeringsfunktioner som EXIF-datamanipulation och alfakanaler."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Bearbeta Tagged Image File Format (TIFF) rasterbilder med vårt API, som erbjuder omfattande stöd för olika upplösningar och avancerade redigeringsfunktioner som EXIF-datamanipulation och alfakanaler. Normalisera vinklar för skannade bilder, ändra storlek, omvandla till gråskala och applicera filter, gamma‑korrigeringar och justeringar av bildparametrar med lätthet. Hantera sömlöst flerbilds‑TIFF‑filer, skapa grafikvägar, lägga till former och enkelt spara bilder i olika format.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Initiera ett nytt objekt av klassen [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), ange ram‑parametern. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Skapa en ny instans av klassen [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), med en lista av ramar som parameter. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Hämta filformatvärdet som är associerat med bilden. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Anges om komponenter kräver förmultiplikation, vilket säkerställer effektiv hantering av visuella element. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Anges om komponenter kräver förmultiplikation, vilket säkerställer effektiv hantering av visuella element. |
| [getByteOrder()](#getByteOrder--) | Växla byteordningen för TIFF‑filer sömlöst, vilket säkerställer exakt kontroll över datainterpretation. |
| [setByteOrder(int value)](#setByteOrder-int-) | Växla byteordningen för TIFF‑filer sömlöst, vilket säkerställer exakt kontroll över datainterpretation. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Hämta den horisontella upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket underlättar exakt justering och renderingsmöjligheter. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Modifierar den horisontella upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket underlättar exakt justering och renderingsmöjligheter. |
| [getVerticalResolution()](#getVerticalResolution--) | Åtkomst till den vertikala upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket möjliggör exakt justering och renderingsoptimeringar. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Åtkomst till den vertikala upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket möjliggör exakt justering och renderingsoptimeringar. |
| [getActiveFrame()](#getActiveFrame--) | Hantera den aktiva ramen sömlöst, vilket underlättar dynamisk navigering och manipulation inom den angivna kontexten. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Hantera den aktiva ramen sömlöst, vilket underlättar dynamisk navigering och manipulation inom den angivna kontexten. |
| [getFrames()](#getFrames--) | Hämta en array av [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)-instanser, vilket möjliggör omfattande åtkomst och manipulation av enskilda ramar i TIFF‑bilden. |
| [getPageCount()](#getPageCount--) | Hämta det totala antalet sidor i det angivna dokumentet, vilket underlättar effektiv navigering och hantering av flersidigt innehåll. |
| [getPages()](#getPages--) | Åtkomst till dokumentets sidor sömlöst, vilket möjliggör dynamisk navigering och manipulation inom innehållsstrukturen. |
| [hasAlpha()](#hasAlpha--) | Bestäm om bilden har en alfakanal, vilket ger viktig information för renderings- och sammansättningsoperationer. |
| [removeMetadata()](#removeMetadata--) | Tar bort metadata för denna bildinstans genom att sätta detta `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) värde till `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämta alternativ hämtade från de ursprungliga filinställningarna, vilket underlättar sömlös bevarande av nyckelparametrar såsom bitdjup och andra väsentliga egenskaper hos den ursprungliga bilden. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Inkludera en ny sida i den befintliga bilden sömlöst, vilket utökar dess innehåll och mångsidighet. |
| [alignResolutions()](#alignResolutions--) | Implementera hjälpmethoden AlignResolutions för att synkronisera horisontella och vertikala upplösningar, vilket säkerställer enhetlighet i bilddimensioner. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Fastställer upplösningen för den angivna [RasterImage](../../com.aspose.imaging/rasterimage), vilket möjliggör exakt kontroll över bildrendering och visningsegenskaper. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Använd NormalizeAngle‑metoden som är speciellt utformad för skannade textdokument för att rätta till snedvridna skanningar och säkerställa exakt justering. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Inkludera den angivna ramen sömlöst i bilden, vilket utökar dess innehåll och mångsidighet. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Lägg till ramarna från den angivna bilden sömlöst i den aktuella ramen, konsolidera deras innehåll och förbättra den kompositionella flexibiliteten. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Integrera arrayen av ramar sömlöst i bilden, vilket berikar dess innehåll och mångsidighet. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Infoga den nya ramen på det angivna indexet i ramsekvensen för att säkerställa exakt kontroll över ramordningen. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Byt ut ramen på den angivna positionen mot en annan ram sömlöst, vilket underlättar dynamisk ramhantering i bildsekvensen. |
| [removeFrame(int index)](#removeFrame-int-) | Eliminera enkelt ramen som identifierats av sitt index från bildsekvensen och förenkla ramhanteringen i din applikation. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Ta effektivt bort den angivna ramen från bildsekvensen för att underlätta en förenklad ramhantering i din applikation. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Utför en proportionell storleksändring av bilden, bevara dess bildförhållande samtidigt som du justerar dess dimensioner. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Justera bildens bredd samtidigt som du behåller bildförhållandet, vilket säkerställer proportionell storleksändring för optimal visuell presentation. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Utför en proportionell justering av bildens höjd, bevara bildförhållandet för enhetlig visuell integritet. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Utför rotation, spegling eller en kombination av båda operationerna enbart på den aktiva ramen. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Utför dithering på den aktuella bilden för att förbättra dess visuella kvalitet och minska färgbandningsartefakter. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär bilden med ett angivet rektangulärt område, vilket möjliggör exakt urval av önskat innehåll. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Utför beskärning av bilden genom att ange förskjutningar åt vänster, höger, upp och ner. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Applicera binarisering på bilden med ett fördefinierat tröskelvärde, vilket omvandlar den till en binär bild med tydliga förgrunds- och bakgrundsområden. |
| [binarizeOtsu()](#binarizeOtsu--) | Använd Otsu-tröskling för att utföra binarisering av bilden, vilket automatiskt bestämmer det optimala tröskelvärdet baserat på bildens histogram. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Implementera binarisering på bilden med Bradleys adaptiva trösklingsalgoritm och integrerad bildtröskling. |
| [grayscale()](#grayscale--) | Konvertera bilden till dess gråskalerepresentation, vilket omvandlar den till en enkankalig bild där varje pixel representerar intensitet. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Applicera gamma‑korrektion på bilden, justera pixelintensiteter för att uppnå önskad färgbalans. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Utför gamma‑korrektion på bilden med individuella koefficienter för röd, grön och blå kanal, vilket möjliggör finjusterade justeringar av färgbalans och kontrast. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implementera `brightness`‑justering för bilden, vilket möjliggör ändring av den övergripande luminansnivån. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Förbättra kontrasten för [Image](../../com.aspose.imaging/image)-instansen, vilket förstärker skillnaderna mellan dess ljusa och mörka områden. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtrera innehållet inom den angivna rektangeln genom att applicera ett bestämt bildbehandlingsfilter för att förbättra eller ändra det valda området. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Justera bildens storlek baserat på angivna inställningar, vilket möjliggör exakt kontroll över dimensioner, bildförhållande och skalningsbeteende. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Skapa GraphicsPath med PathResources från TIFF-bild
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Rita en röd linje och spara bilden
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Skapa rektangulär Figure för GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Skapa GraphicsPath med vår Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Ställ in PathResources med GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Spara bilden
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Initiera ett nytt objekt av klassen [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) med ramparametern. Denna konstruktor underlättar skapandet av en TiffImage-instans, vilket gör det möjligt för utvecklare att ange den ram som ska laddas eller bearbetas, och effektiviserar hanteringen av Tiff-bilder i deras applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Den tiff-ram som bilden ska initieras med. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Skapa en ny instans av klassen [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) genom att ange en lista med ramar som parameter. Denna konstruktor möjliggör initiering av ett TiffImage-objekt med flera ramar, vilket underlättar effektiv hantering och bearbetning av TIFF-bildsekvenser i programvaruapplikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Ramarna. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta filformatvärdet som är associerat med bilden. Denna egenskap fungerar som en kritisk del av hämtning av bildmetadata, vilket möjliggör för programvaror att identifiera och tolka bildens format på ett effektivt sätt.

**Returns:**
long - ett värde för filformat
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Anger om komponenter kräver förmultiplikation, vilket säkerställer effektiv hantering av visuella element. Förbättra renderingsprocesser genom att växla denna egenskap, vilket strömlinjeformar grafiska arbetsflöden för optimerad prestanda.

**Returns:**
boolean - `true` om komponenter måste förmultipliceras; annars `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Anger om komponenter kräver förmultiplikation, vilket säkerställer effektiv hantering av visuella element. Förbättra renderingsprocesser genom att växla denna egenskap, vilket strömlinjeformar grafiska arbetsflöden för optimerad prestanda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om komponenter måste förmultipliceras; annars `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Spara pixlar för hela bilden.
    image.savePixels(image.getBounds(), colors);

    // Pixlarna lagras i den ursprungliga bilden i icke‑premultipliserad form.
    // Det krävs att ange motsvarande alternativ explicit för att få premultipliserade färgkomponenter.
    // De premultipliserade färgkomponenterna beräknas med formlerna:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//Utdata kommer att se ut så här:
//Original färg: Color [A=127, R=255, G=0, B=0]
//Förmultiplicerad färg: Color [A=127, R=127, G=0, B=0]
//Original färg: Color [A=127, R=0, G=255, B=0]
//Förmultiplicerad färg: Color [A=127, R=0, G=127, B=0]
//Original färg: Color [A=127, R=0, G=0, B=255]
//Förmultiplicerad färg: Color [A=127, R=0, G=0, B=127]
//Original färg: Color [A=127, R=255, G=255, B=0]
//Förmultiplicerad färg: Color [A=127, R=127, G=127, B=0]
//Original färg: Color [A=127, R=255, G=0, B=255]
//Förmultiplicerad färg: Color [A=127, R=127, G=0, B=127]
//Originalfärg: Color [A=127, R=0, G=255, B=255]
//Förmultiplicerad färg: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


Växla byteordningen för TIFF-filer sömlöst, vilket säkerställer exakt kontroll över datainterpretation. Ge dina applikationer flexibiliteten att anpassa sig till olika filspecificeringar, vilket förbättrar kompatibilitet och effektivitet i databehandling.

**Returns:**
int - TIFF-byteordningen.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


Växla byteordningen för TIFF-filer sömlöst, vilket säkerställer exakt kontroll över datainterpretation. Ge dina applikationer flexibiliteten att anpassa sig till olika filspecificeringar, vilket förbättrar kompatibilitet och effektivitet i databehandling.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | TIFF-byteordningen. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Hämta den horisontella upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket underlättar exakt justering och renderingsmöjligheter. Åtkomst till viktig bildmetadata utan ansträngning, vilket möjliggör strömlinjeformade bildbehandlingsarbetsflöden för förbättrade användarupplevelser.

**Returns:**
double - Den horisontella upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Hämta horisontell och vertikal upplösning för TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 96.0
// Den vertikala upplösningen, i pixlar per tum: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Modifierar den horisontella upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket underlättar exakt justering och renderingsmöjligheter. Åtkomst till viktig bildmetadata utan ansträngning, vilket möjliggör strömlinjeformade bildbehandlingsarbetsflöden för förbättrade användarupplevelser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den horisontella upplösningen. |

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Åtkomst till den vertikala upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket möjliggör exakt justering och renderingsoptimeringar. Använd viktig bilddata utan ansträngning för att strömlinjeforma bildbehandlingsarbetsflöden, vilket säkerställer överlägsen kvalitet och prestanda i dina applikationer.

**Returns:**
double - Den vertikala upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Hämta horisontell och vertikal upplösning för TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 96.0
// Den vertikala upplösningen, i pixlar per tum: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Åtkomst till den vertikala upplösningen för den angivna [Image](../../com.aspose.imaging/image) i pixlar per tum, vilket möjliggör exakt justering och renderingsoptimeringar. Använd viktig bilddata utan ansträngning för att strömlinjeforma bildbehandlingsarbetsflöden, vilket säkerställer överlägsen kvalitet och prestanda i dina applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den vertikala upplösningen. |

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Hantera den aktiva ramen sömlöst, vilket underlättar dynamisk navigering och manipulation inom den angivna kontexten. Ge din applikation möjlighet att interagera effektivt med multimediainnehåll, vilket förbättrar användarengagemang och produktivitet.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Detta är Font och Brush för att rita text på enskilda ramar.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Skapa 5 ramar
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Skapa en PNG‑bild och rita sidnumret på den.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Skapa en ram baserad på PNG‑bilden.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Lägg till ramen i TIFF‑bilden.
        tiffImage.addFrame(frame);
    }

    // Bilden skapades med en enda standardram. Låt oss ta bort den.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Glöm inte att frigöra ramen om du inte kommer att lägga till den i någon annan TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Hantera den aktiva ramen sömlöst, vilket underlättar dynamisk navigering och manipulation inom den angivna kontexten. Ge din applikation möjlighet att interagera effektivt med multimediainnehåll, vilket förbättrar användarengagemang och produktivitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Aktiv ram. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Detta är Font och Brush för att rita text på enskilda ramar.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Skapa 5 ramar
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Skapa en PNG‑bild och rita sidnumret på den.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Skapa en ram baserad på PNG‑bilden.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Lägg till ramen i TIFF‑bilden.
        tiffImage.addFrame(frame);
    }

    // Bilden skapades med en enda standardram. Låt oss ta bort den.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Glöm inte att frigöra ramen om du inte kommer att lägga till den i någon annan TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


Hämta en array av [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)-instanser, vilket möjliggör omfattande åtkomst och manipulation av enskilda ramar i TIFF-bilden. Utnyttja kraften i denna array för att strömlinjeforma bildbehandlingsarbetsflöden, vilket säkerställer exakt kontroll och optimering av visuellt innehåll.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] - [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)-arrayen.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Detta är Font och Brush för att rita text på enskilda ramar.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Skapa 5 ramar
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Skapa en PNG‑bild och rita sidnumret på den.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Skapa en ram baserad på PNG‑bilden.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Lägg till ramen i TIFF‑bilden.
        tiffImage.addFrame(frame);
    }

    // Bilden skapades med en enda standardram. Låt oss ta bort den.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Glöm inte att frigöra ramen om du inte kommer att lägga till den i någon annan TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämta det totala antalet sidor i det angivna dokumentet, vilket underlättar effektiv navigering och hantering av flersidigt innehåll. Inkludera denna funktion för att förbättra användarupplevelsen, vilket möjliggör sömlös åtkomst till omfattande dokumentstrukturer.

**Returns:**
int - sidantalet.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Åtkomst till dokumentets sidor sömlöst, vilket möjliggör dynamisk navigering och manipulation inom innehållsstrukturen. Ge din applikation effektiv åtkomst till enskilda sidor, vilket underlättar strömlinjeformad dokumentbehandling och förbättrad användarinteraktion.

**Returns:**
com.aspose.imaging.Image[] - sidorna.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bestäm om bilden har en alfakanal, vilket ger viktig information för renderings- och sammansättningsoperationer. Integrera denna funktion för att optimera visuella bearbetningsarbetsflöden, vilket säkerställer korrekt återgivning och manipulation av transparenta element.

**Returns:**
boolean - `true` om det finns en alfakanal.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Om den aktiva TIFF-ramen har alfakanal, anses hela TIFF-bilden ha alfakanal.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Tar bort metadata för denna bildinstans genom att sätta detta `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) värde till `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämta alternativ hämtade från de ursprungliga filinställningarna, vilket möjliggör sömlös bevarande av nyckelparametrar såsom bitdjup och andra väsentliga attribut för den ursprungliga bilden. Använd denna metod för att bibehålla trohet och konsistens i bildbehandlingsuppgifter, vilket säkerställer optimala resultat utan onödiga förändringar. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av metoden [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), kommer en PNG-bild med 8 bitar per pixel att genereras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Inkludera en ny sida i den befintliga bilden sömlöst, vilket utökar dess innehåll och mångsidighet. Använd den här metoden för att förbättra dokumentkomposition och -hantering, vilket möjliggör effektiv hantering av flersidiga bilder i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Sidan att lägga till. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Implementera hjälpmethoden AlignResolutions för att synkronisera horisontella och vertikala upplösningar, vilket säkerställer enhetlighet i bilddimensioner. Denna funktionalitet underlättar strömlinjeformade bildbehandlingsarbetsflöden genom att harmonisera upplösningsparametrar, optimera visuell kvalitet och konsistens över olika plattformar och enheter.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Fastställer upplösningen för den angivna [RasterImage](../../com.aspose.imaging/rasterimage), vilket möjliggör exakt kontroll över bildrendering och visningsegenskaper. Integrera denna funktionalitet för att optimera visuellt resultat och säkerställa kompatibilitet med olika utmatningsenheter och plattformar, vilket förbättrar den övergripande användarupplevelsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpiX | double | Den horisontella upplösningen, i punkter per tum, för [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Den vertikala upplösningen, i punkter per tum, för [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Hämta horisontell och vertikal upplösning för TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Den horisontella upplösningen, i pixlar per tum: 96.0
// Den vertikala upplösningen, i pixlar per tum: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Använd metoden NormalizeAngle som är speciellt utformad för skannade textdokument för att korrigera snedvridna skanningar, vilket säkerställer exakt justering. Integrera sömlöst denna funktionalitet i dina textbehandlingsarbetsflöden för att förbättra dokumentläsbarhet och kvalitet, vilket ökar den totala effektiviteten i textigenkänning och analysuppgifter. Denna metod använder [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\\#getSkewAngle) och [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\\#rotate-float--boolean--Color-) metoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeProportionally | boolean | om den är inställd på `true` kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, i annat fall lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Inkludera den angivna ramen sömlöst i bilden, vilket utökar dess innehåll och mångsidighet. Använd den här metoden för att förbättra bildkomposition och -hantering, vilket möjliggör effektiv hantering av flerramiga bilder i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Ramen att lägga till. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Detta är Font och Brush för att rita text på enskilda ramar.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Skapa 5 ramar
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Skapa en PNG‑bild och rita sidnumret på den.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Skapa en ram baserad på PNG‑bilden.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Lägg till ramen i TIFF‑bilden.
        tiffImage.addFrame(frame);
    }

    // Bilden skapades med en enda standardram. Låt oss ta bort den.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Glöm inte att frigöra ramen om du inte kommer att lägga till den i någon annan TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Lägg till ramarna från den angivna bilden sömlöst i den aktuella ramen, vilket konsoliderar deras innehåll och förbättrar kompositionsflexibiliteten. Integrera den här metoden för att förenkla ramhantering och manipulation i din applikation, vilket underlättar effektiv hantering av flerramiga bilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | Källbilden. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Integrera ramarrayen sömlöst i bilden, vilket berikar dess innehåll och mångsidighet. Använd den här metoden för att förbättra bildkomposition och -hantering, vilket möjliggör effektiv hantering av flerramiga bilder i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Ramarrayen att lägga till |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


Infoga den nya ramen på det angivna indexet i ramsekvensen, vilket säkerställer exakt kontroll över ramplacering. Använd den här metoden för att hantera ramsekvenser effektivt, vilket underlättar dynamisk manipulation och organisering av bildinnehåll i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet för `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Ramen för insättning. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


Byt ut ramen på den angivna positionen mot en annan ram sömlöst, vilket underlättar dynamisk ramhantering i bildsekvensen. Integrera den här metoden för att förbättra flexibilitet och precision i rammanipulation, vilket säkerställer optimal organisering och presentation av bildinnehåll i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Den nollbaserade rampositionen. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Ramen att ersätta. |

Obs: glöm inte att disponera/stänga ramen om du inte kommer att lägga till den i någon annan TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Avlägsna enkelt ramen som identifieras av sitt index från bildsekvensen, vilket förenklar ramhantering i din applikation. Integrera denna funktionalitet för att förbättra effektivitet och precision i rammanipulation, vilket möjliggör sömlös organisering och presentation av bildinnehåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Index för ramen som ska tas bort. |

--------------------

Obs: glöm inte att disponera ramen om du inte kommer att lägga till den i någon annan TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Detta är Font och Brush för att rita text på enskilda ramar.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Skapa 5 ramar
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Skapa en PNG‑bild och rita sidnumret på den.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Skapa en ram baserad på PNG‑bilden.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Lägg till ramen i TIFF‑bilden.
        tiffImage.addFrame(frame);
    }

    // Bilden skapades med en enda standardram. Låt oss ta bort den.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Glöm inte att frigöra ramen om du inte kommer att lägga till den i någon annan TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Ta effektivt bort den angivna ramen från bildsekvensen, vilket underlättar förenklad ramhantering i din applikation. Integrera denna funktionalitet för att förbättra precision och flexibilitet i rammanipulation, vilket säkerställer sömlös organisering och presentation av bildinnehåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Ramen att ta bort. |

--------------------

Obs: glöm inte att disponera ramen om du inte kommer att lägga till den i någon annan TiffImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Utför en proportionell storleksändringsoperation på bilden, bevara dess bildförhållande samtidigt som dess dimensioner justeras. Använd den här metoden för att dynamiskt skala bilder i din applikation, vilket säkerställer en konsekvent visuell återgivning av innehållsintegritet. Den proportionella storleksändringen kommer att ändra storlek på varje ram enligt förhållandet `newWidth`/width och `newHeight`/height.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Justera bildens bredd samtidigt som du behåller dess bildförhållande, vilket säkerställer proportionell storleksändring för optimal visuell presentation. Använd denna metod för att dynamiskt skala bilder i din applikation, vilket möjliggör konsekvent och estetiskt tilltalande rendering över olika visningssammanhang.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Detta exempel laddar en TIFF-bild och ändrar dess storlek proportionellt med hjälp av olika storleksändringsmetoder. Endast bredden anges, höjden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Utför en proportionell justering av bildens höjd, bevara dess bildförhållande för konsekvent visuell integritet. Använd denna metod för att dynamiskt ändra bildstorlek i din applikation, vilket säkerställer optimal visning på olika plattformar och enheter utan att kompromissa med innehållskvaliteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Detta exempel laddar en TIFF-bild och ändrar dess storlek proportionellt med hjälp av olika storleksändringsmetoder. Endast höjden anges, bredden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Utför rotation, spegling eller en kombination av båda operationerna uteslutande på den aktiva ramen. Denna metod möjliggör exakt manipulation av enskilda ramar i bildsekvensen, vilket ökar flexibiliteten i bildredigering och sammansättning i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations- och speglingstypen. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Detta är en hjälparklass.
class Utils {
    // Hämtar en strängrepresentation av roterings‑vändningstypen.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Här är huvudexemplet
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotera, vänd och spara till utdatafilen.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Utför dithering på den aktuella bilden för att förbättra dess visuella kvalitet och minska färgbandningsartefakter. Integrera denna metod i ditt bildbehandlingsflöde för att säkerställa mjukare övergångar mellan färger, vilket resulterar i förbättrat övergripande bildutseende och klarhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den anpassade paletten för dithering. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Utför tröskel-dithering med en 4-bitars färgpalett som innehåller 16 färger.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Utför Floyd-dithering med en 1-bitars färgpalett som endast innehåller 2 färger – svart och vit.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden med ett angivet rektangulärt område, vilket möjliggör exakt urval av önskat innehåll. Integrera denna metod i ditt bildbehandlingsflöde för att effektivt ta bort oönskade områden och fokusera på väsentliga detaljer, vilket förbättrar bildens övergripande klarhet och komposition.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |


**Example: The following example crops a TIFF image.**
Följande exempel beskär en TIFF-bild. Beskärningsområdet anges via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Beskär bilden. Beskärningsområdet är den rektangulära centrala delen av bilden.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Spara den beskurna bilden som PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Utför beskärning av bilden genom att ange förskjutningar åt vänster, höger, upp och ner. Denna metod möjliggör exakt urval av den önskade delen av bilden, vilket underlättar effektiv borttagning av oönskade områden och fokuserar på väsentligt innehåll. Integrera denna funktionalitet i ditt bildbehandlingsflöde för att förbättra klarhet och komposition efter behov i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | int | Den vänstra förskjutningen. |
| rightShift | int | Den högra förskjutningen. |
| topShift | int | Den övre förskjutningen. |
| bottomShift | int | Den nedre förskjutningen. |


**Example: The following example crops a TIFF image.**
Följande exempel beskär en TIFF-bild. Beskärningsområdet anges via Left, Top, Right, Bottom-marginalerna.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Beskär igen. Ställ in en marginal på 10 % av bildens storlek.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Spara den beskurna bilden som PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Applicera binarisering på bilden med en fördefinierad tröskel, vilket omvandlar den till en binär bild med tydliga förgrunds- och bakgrundsområden. Inkludera denna metod i ditt bildbehandlingsflöde för att underlätta segmentering och funktionsextraktion, vilket förbättrar noggrannheten och effektiviteten i bildanalys i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln tilldelas värdet 255, annars 0. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
Följande exempel binariserar en TIFF-bild med den fördefinierade tröskeln. Binariserade bilder innehåller endast 2 färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisera bilden med ett tröskelvärde på 127.
    // Om ett motsvarande gråvärde för en pixel är större än 127, tilldelas ett värde på 255, annars 0.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Använd Otsu-tröskling för att utföra binarisering på bilden, vilket automatiskt bestämmer det optimala tröskelvärdet baserat på bildens histogram. Integrera denna metod i ditt bildbehandlingsflöde för att uppnå effektiv segmentering och funktionsextraktion, vilket förbättrar noggrannheten och tillförlitligheten i bildanalysuppgifter i din applikation.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
Följande exempel binariserar en TIFF-bild med Otsu-tröskling. Binariserade bilder innehåller endast 2 färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisera bilden med Otsu-tröskling.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Implementera binarisering på bilden med Bradley's adaptiva trösklingsalgoritm med integral bildtröskling. Detta tillvägagångssätt beräknar dynamiskt lokala trösklar baserat på bildens omgivning, vilket ökar anpassningsförmågan till varierande ljusförhållanden och säkerställer robust segmentering för efterföljande bearbetningsuppgifter i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |
| windowSize | int | Storleken på ett s x s-fönster av pixlar centrerade kring denna pixel. |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
Följande exempel binariserar en TIFF-bild med Bradley's adaptiva trösklingsalgoritm med den angivna fönsterstorleken. Binariserade bilder innehåller endast 2 färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisera bilden med en ljusstyrkeskillnad på 5. Ljusstyrkan är skillnaden mellan en pixel och medelvärdet av ett 10 × 10‑fönster av pixlar centrerade kring den pixeln.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Konvertera bilden till dess gråskalerepresentation, vilket omvandlar den till en enkakanalbild där varje pixel representerar intensitet. Integrera denna metod i ditt bildbehandlingsflöde för att förenkla analys och förbättra kompatibiliteten med gråskalebaserade algoritmer, vilket underlättar olika datorseende- och bildanalysuppgifter i din applikation.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
Följande exempel omvandlar en färgad TIFF-bild till dess gråskalerepresentation. Gråskalebilder består uteslutande av gråtoner och innehåller endast intensitetsinformation.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Applicera gamma-korrigering på bilden, justera pixelintensiteter för att uppnå önskad färgbalans. Inkludera denna metod i ditt bildbehandlingsflöde för att förbättra den visuella kvaliteten och öka noggrannheten i efterföljande analys- eller visningsuppgifter i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalernas koefficient |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ange gamma-koefficient för röd, grön och blå kanaler.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Utför gamma-korrigering på bilden med individuella koefficienter för röda, gröna och blå kanaler, vilket möjliggör finjusterade justeringar av färgbalans och kontrast. Integrera denna metod i ditt bildbehandlingsflöde för att uppnå exakt kontroll över färgåtergivning och förbättra visuell trovärdighet i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanalkoefficient |
| gammaGreen | float | Gamma för grön kanalkoefficient |
| gammaBlue | float | Gamma för blå kanalens koefficient |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ange individuella gamma-koefficienter för röd, grön och blå kanaler.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementera `brightness`-justering för bilden, vilket möjliggör modifiering av den övergripande luminansnivån. Inkludera denna metod i ditt bildbehandlingsflöde för att förbättra synligheten och höja den visuella kvaliteten på bilder i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ställ in ljusstyrkevärdet. De accepterade värdena för ljusstyrka ligger i intervallet [-255, 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Förbättra kontrasten på [Image](../../com.aspose.imaging/image)-instansen, förstärka skillnaderna mellan dess ljusa och mörka områden. Integrera denna funktion för att förbättra den visuella klarheten och den övergripande kvaliteten på bilden i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | float | Kontrastvärde (i intervallet [-100; 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ställ in kontrastvärdet. De accepterade värdena för kontrast ligger i intervallet [-100f, 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

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


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett jämnvärde på 4,0 på hela bilden.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applicera ett rörelse‑Wiener-filter med en längd på 5, ett jämnvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applicera ett skärpningsfilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Justera bildens storlek baserat på angivna inställningar, vilket möjliggör exakt kontroll över dimensioner, bildförhållande och skalningsbeteende. Integrera denna metod i ditt bildbehandlingsflöde för att uppnå anpassade storleksändringsoperationer skräddarsydda för din applikations specifika krav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Skala ner med 2 gånger med adaptiv omsampling.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Spara som PNG
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

