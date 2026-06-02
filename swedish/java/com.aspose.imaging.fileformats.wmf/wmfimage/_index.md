---
title: "WmfImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Manipulera Microsoft Windows Metafile WMF-bilder med vårt API som sömlöst hanterar både vektor- och bitmapdata lagrade i variabel‑längd poster."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Manipulera Microsoft Windows Metafile (WMF)-bilder med vårt API, som sömlöst hanterar både vektor- och bitmapdata lagrade i variabel‑längd poster. Ändra storlek, rotera och vänd bilder med lätthet samtidigt som du ställer in anpassade bildpaletter. Konvertera WMF-filer till komprimerade WMZ-format eller spara dem i rasterbildformat för mångsidig användning på olika plattformar och i applikationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfImage()](#WmfImage--) | Skapa en ny instans av klassen [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), som initieras för vidare manipulation och bearbetning av Windows Metafile (WMF)-bilddata. |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Instansiera en ny instans av klassen [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) med anpassningsbara bredd‑ och höjdpra­meter, vilket underlättar skapandet av tomma WMF‑bilder skräddarsydda för specifika dimensioner. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isCached()](#isCached--) | Hämta ett booleskt värde som indikerar om objektets data för närvarande är cachad, vilket eliminerar behovet av ytterligare läsoperationer. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämta antalet bitar per pixel för bilden, vilket indikerar färgdjupets nivå eller granularitet. |
| [getWidthF()](#getWidthF--) | Åtkomst till bildens bredd, vilket indikerar antalet pixlar längs dess horisontella axel. |
| [getHeightF()](#getHeightF--) | Åtkomst till bildens höjd, vilket representerar antalet pixlar längs dess vertikala axel. |
| [getInch()](#getInch--) | Åtkomst till eller ändra tum‑egenskapen, som representerar en måttenhet som vanligtvis används för att ange fysiska dimensioner i utskrifts‑ eller visningssammanhang. |
| [setInch(int value)](#setInch-int-) | Åtkomst till eller ändra tum‑egenskapen, som representerar en måttenhet som vanligtvis används för att ange fysiska dimensioner i utskrifts‑ eller visningssammanhang. |
| [getFileFormat()](#getFileFormat--) | Åtkomst till filformatvärdet som är associerat med bilden, vilket ger information om det format i vilket bilden lagras. |
| [getFrameBounds()](#getFrameBounds--) | Åtkomst till ramens gränser, vilket indikerar dess position och dimensioner inom bilden. |
| [cacheData()](#cacheData--) | Cacha data effektivt, vilket eliminerar behovet av ytterligare inläsning från den underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Applicera en specificerad palett på bilden, vilket möjliggör anpassning av färgrepresentation. |
| [getUsedFonts()](#getUsedFonts--) | Hämta listan över teckensnitt som används i metafilen, vilket ger insikt i de teckensnitt som utnyttjas i bilden. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ändra storlek på bildens canvas, justera dess dimensioner samtidigt som bildinnehållet behålls. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Inkorporera det specificerade rekordobjektet i bilden, vilket berikar dess innehåll med ytterligare data eller metadata. |
| [getPostScript()](#getPostScript--) | Åtkomst till PostScript-data som är associerad med bilden, vilket ger detaljerad information om dess struktur eller innehåll. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar de ursprungliga bildalternativen. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla typer av bilder, inklusive WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text kommer att konverteras till former.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Bakgrundsfärgen på ritytan.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sidstorleken.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Om inbäddad emf finns, rendera emf; annars rendera wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
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


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Skapa en ny instans av klassen [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), initierad för vidare manipulation och bearbetning av Windows Metafile (WMF) bilddata. Denna konstruktor tillhandahåller ett grundläggande objekt för att arbeta med WMF-bilder, vilket möjliggör sömlös integration av WMF-bildhanteringsfunktioner i din applikations funktionalitet.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Instansiera en ny instans av klassen [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) med anpassningsbara bredd- och höjdparametrar, vilket underlättar skapandet av tomma WMF-bilder anpassade till specifika dimensioner. Använd denna konstruktor för att dynamiskt generera WMF-bilder med exakta dimensioner, vilket möjliggör flexibel bildskapande och manipulation i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Hämta ett booleskt värde som indikerar om objektets data för närvarande är cachad, vilket eliminerar behovet av ytterligare läsoperationer. Använd denna egenskap för att optimera prestanda genom att avgöra om objektets data är omedelbart tillgängligt utan behov av kostsamma dataåterhämtningsprocesser i din applikation.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämta antalet bitar per pixel för bilden, vilket indikerar färgdjupets nivå eller granularitet. Använd denna egenskap för att bestämma bildens färgrepresentation och precision, vilket underlättar kompatibilitetskontroller och färgrelaterad bearbetning i din applikation.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Åtkomst till bildens bredd, vilket indikerar antalet pixlar längs dess horisontella axel. Använd denna egenskap för att bestämma bildens rumsliga dimensioner och bildförhållande, vilket möjliggör exakt layout- och renderingsjustering i din applikation.

**Returns:**
float - Bildens bredd i pixlar.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Åtkomst till bildens höjd, vilket representerar antalet pixlar längs dess vertikala axel. Använd denna egenskap för att fastställa bildens rumsliga dimensioner och bildförhållande, vilket möjliggör noggrann layout- och renderingsjustering i din applikation.

**Returns:**
float - Bildens höjd i pixlar.
### getInch() {#getInch--}
```
public int getInch()
```


Åtkomst till eller ändring av tum‑egenskapen, som representerar en måttenhet som vanligtvis används för att specificera fysiska dimensioner i utskrifts- eller visningssammanhang. Använd denna egenskap för att fastställa eller hämta tumvärden som är associerade med bilden, vilket underlättar korrekt återgivning av fysiska dimensioner i din applikation.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Åtkomst till eller ändring av tum‑egenskapen, som representerar en måttenhet som vanligtvis används för att specificera fysiska dimensioner i utskrifts- eller visningssammanhang. Använd denna egenskap för att fastställa eller hämta tumvärden som är associerade med bilden, vilket underlättar korrekt återgivning av fysiska dimensioner i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Åtkomst till filformatvärdet som är associerat med bilden, vilket ger information om det format i vilket bilden lagras. Använd denna egenskap för att bestämma bildens filformat, vilket underlättar kompatibilitetskontroller och format‑specifik bearbetning i din applikation.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Åtkomst till ramens gränser, vilket indikerar dess position och dimensioner inom bilden. Använd denna egenskap för att hämta detaljerad information om ramens rumsliga placering, vilket möjliggör exakt manipulation och rendering i din applikation.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Effektivt cacha data, vilket eliminerar behovet av ytterligare inläsning från den underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Använd denna metod för att optimera prestanda och minimera resursanvändning i din applikation genom att lagra och komma åt lokalt datacache.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla typer av bilder, inklusive WMF.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Cacha data för att ladda alla poster.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // Nyckeln är en posttyp, värdet är antalet poster av den typen i WMF-bilden.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // Samla statistik
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Skriv ut statistik
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Justera utdata med mellanslag
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    wmfImage.dispose();
}

//Utdata kan se ut så här:
//Det totala antalet poster: 613
//Posttyp                              Antal
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Applicera en specificerad palett på bilden, vilket möjliggör anpassning av färgrepresentation. Använd den här metoden för att förbättra visuell rendering och uppnå specifika färgeffekter i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Hämta listan över teckensnitt som används i metafilen, vilket ger insikt i de teckensnitt som används i bilden. Använd den här metoden för att analysera teckensnittsanvändning och säkerställa teckensnittstillgänglighet för rendering eller vidare bearbetning i din applikation.

**Returns:**
java.lang.String[] - Teckensnittlistan
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Ändra storleken på bildens canvas, justera dess dimensioner samtidigt som bildinnehållet behålls. Använd den här metoden för att modifiera canvasens storlek utan att ändra innehållet, vilket underlättar layoutjusteringar och kompositionsändringar i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den nya rektangeln. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Inkludera det specificerade postobjektet i bilden, vilket berikar dess innehåll med ytterligare data eller metadata. Använd den här metoden för att sömlöst integrera postobjekt i bilden, vilket underlättar omfattande datalagring och organisering i din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | Posten. |

**Returns:**
int - Antal poster.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Åtkomst till PostScript-data som är associerad med bilden, vilket ger detaljerad information om dess struktur eller innehåll. Använd den här metoden för att hämta PostScript-data för vidare analys eller bearbetning i din applikation, vilket möjliggör avancerad funktionalitet relaterad till PostScript-rendering eller manipulation.

**Returns:**
java.lang.String - Postscriptet
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämtar de ursprungliga bildalternativen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
