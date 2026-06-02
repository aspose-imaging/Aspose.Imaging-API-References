---
title: "SvgImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera Scalar Vector Graphics SVG-bildfiler med vårt API som utnyttjar kraften i XML-baserat textformat för sömlös anpassning och skalbarhet."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

Manipulera Scalar Vector Graphics (SVG)-bildfiler med vårt API, som utnyttjar kraften i XML-baserat textformat för sömlös anpassning och skalbarhet. Ladda enkelt SVG-bilder, rasterisera vektorelement och konvertera till andra format, samtidigt som du styr komprimeringsnivåer för att optimera filstorlek och kvalitet för dina projekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Instansierar ett nytt objekt av klassen [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), med den angivna sökvägen för att hitta och ladda bilden. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Skapar en ny instans av klassen [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), som laddar bilden från den angivna strömmen. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Instansierar ett nytt [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-objekt med angiven bredd och höjd. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Skapar en ny instans av klassen [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) med specificerade SVG-alternativ, bildbredd och höjdparametrar. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isCached()](#isCached--) | Hämtar ett booleskt värde som indikerar om objektets data för närvarande är cachad, vilket eliminerar behovet av ytterligare läsoperationer. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bitar per pixel för bilden. |
| [getFileFormat()](#getFileFormat--) | Hämtar filformatet för bilden, vilket ger viktig metadata för bearbetning och kompatibilitetskontroller. |
| [cacheData()](#cacheData--) | Cacha data och garantera att ingen ytterligare data laddas från den underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändra bildens storlek så att den passar de angivna dimensionerna samtidigt som bildförhållandet bevaras. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär den angivna rektangeln. |
| [rotate(float angle)](#rotate-float-) | Rotera bilden kring centrum. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Tillämpar en specificerad palett på bilden, vilket möjliggör anpassning av färgscheman för estetiska eller funktionella ändamål. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Läs in en SVG-bild från en filström.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // För att rasterisera SVG måste vi specificera rasteriseringsalternativ.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
Följande exempel visar hur man konverterar komprimerade bilder (*.emz,*.wmz, *.svgz) till rasterformat
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Instansierar ett nytt objekt av klassen [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), med den angivna sökvägen för att hitta och ladda bilden. Denna konstruktor underlättar skapandet av SVG-bildinstanser från externa filer, vilket möjliggör sömlös integration i mjukvarusystem och arbetsflöden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att läsa in bilden från och initiera pixel- och palettdata med. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Skapar en ny instans av klassen [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), som laddar bilden från den angivna strömmen. Denna konstruktor möjliggör direkt inläsning av SVG-bilder från strömmar, vilket förbättrar flexibilitet och effektivitet vid hantering av bildresurser i mjukvaruapplikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa in bilden från och initiera pixel- och palettdata med. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Instansierar ett nytt [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-objekt med angiven bredd och höjd. Denna konstruktor låter utvecklare skapa SVG-bilder med fördefinierade dimensioner, vilket underlättar exakt kontroll över bildens storlek under initieringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Skapar en ny instans av klassen [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) med specificerade SVG-alternativ, bildbredd och höjdparametrar. Denna konstruktor gör det möjligt för utvecklare att initiera SVG-bilder med anpassade alternativ och dimensioner, vilket ger flexibilitet i hanteringen av SVG-innehåll och layout.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | SVG-alternativen. |
| bredd | int | Bildbredd. |
| höjd | int | Bildhöjd. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett booleskt värde som indikerar om objektets data för närvarande är cachad, vilket eliminerar behovet av ytterligare data läsoperationer. Denna egenskap ger insikt i den aktuella cachestatusen, optimerar datahämtning och bearbetningsarbetsflöden för förbättrad prestanda och effektivitet.

**Returns:**
boolean - `true` om objektets data är cachade; annars `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bitar per pixel i bilden. Det är viktigt att notera att denna parameter inte är tillämplig på vektorbilder, eftersom de inte mäts i pixlar. Denna egenskap ger avgörande information om bildens färgdjup, vilket underlättar bearbetnings- och manipuleringsuppgifter.

**Returns:**
int - Bildens bitar per pixel-antal.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar bildens filformat och tillhandahåller viktig metadata för bearbetning och kompatibilitetskontroller. Denna egenskap är avgörande för att bestämma lämpliga avkodnings- och kodningsstrategier för att effektivt hantera bilddata över olika system och applikationer.

**Returns:**
long - filformat
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cacha data och garantera att det inte kommer att laddas mer data från den underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Denna optimering förbättrar prestanda genom att eliminera redundanta datahämtningar, särskilt fördelaktig i scenarier som kräver frekvent åtkomst till bilddata.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändra storlek på bilden så att den passar de angivna dimensionerna samtidigt som bildförhållandet bevaras. Denna metod ger ett bekvämt sätt att justera bildens storlek utan att förvränga proportionerna, vilket säkerställer optimal visning eller lagring enligt de önskade dimensionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotera bilden kring centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Tillämpar en angiven palett på bilden, vilket möjliggör anpassning av färgscheman för estetiska eller funktionella ändamål. Denna metod ger flexibilitet i hanteringen av färgpaletter för att passa olika design- eller applikationskrav.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

