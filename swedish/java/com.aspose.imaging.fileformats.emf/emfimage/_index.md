---
title: "EmfImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för stöd av vektorbildformatet Enhanced Metafile Format EMF är ett omfattande verktyg för att bearbeta grafiska bilder på ett enhetsoberoende sätt samtidigt som deras ursprungliga egenskaper bevaras."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

API:et för stöd av vektorbildformatet Enhanced Metafile Format (EMF) är ett omfattande verktyg för att bearbeta grafiska bilder på ett enhetsoberoende sätt samtidigt som deras ursprungliga egenskaper bevaras. Det är utvecklat för att behålla proportioner, dimensioner, färger och andra grafiska attribut, och inkluderar stöd för EMF Plus-formatet samt funktioner för att beskära regioner, ändra storlek på duk och bilder, rotera, vända, ställa in bildpaletter, exportera och importera till APS-enhetssammanhang, komprimera och konvertera EMF till andra format, vilket säkerställer mångsidig manipulation och sömlös integration av EMF-bilder i olika applikationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfImage()](#EmfImage--) | Börja arbeta med EMF-bilder genom att initiera en ny instans av klassen [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Skapa en ny instans av klassen [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) genom att ange bredd- och höjdparametrarna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeader()](#getHeader--) | Hämta EMF-metafilens huvudpost med denna egenskap. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Modifiera EMF-metafilens huvudpost med denna egenskap. |
| [isCached()](#isCached--) | Få åtkomst till ett värde som indikerar om objektets data för närvarande är cachade, vilket eliminerar behovet av ytterligare dataläsning. |
| [getRecords()](#getRecords--) | Hämta eller modifiera posterna som är associerade med objektet. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Modifiera posterna som är associerade med objektet. |
| [getFileFormat()](#getFileFormat--) | Få åtkomst till filformatvärdet som är associerat med objektet. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämta bit-per-pixel-antalet som är specifikt för rasterbilder, eftersom denna parameter inte gäller för vektorbilder. |
| [getWidthF()](#getWidthF--) | Få åtkomst till bildens bredd, vilket ger viktig information för exakt rendering och bearbetning. |
| [getHeightF()](#getHeightF--) | Hämta bildens höjd, vilket underlättar exakt rendering och layoutjusteringar. |
| [cacheData()](#cacheData--) | Cacha data effektivt och förhindra redundant laddning från underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) med denna metod. |
| [getUsedFonts()](#getUsedFonts--) | Hämta listan över teckensnitt som används i metafilen med denna metod. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ändra storlek på duken enkelt med denna funktion. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar de ursprungliga bildalternativen. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Ställer in bildpaletten. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla bildtyper inklusive EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text kommer att konverteras till former.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Bakgrundsfärgen på ritytan.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sidstorleken.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Om inbäddad emf finns, rendera emf; annars rendera wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Ställ in den horisontella marginalen
    rasterizationOptions.setBorderX(50);

    // Ställ in den vertikala marginalen
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


Börja arbeta med EMF-bilder genom att initiera en ny instans av klassen [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). Idealiskt för att snabbt integrera EMF-bilder i dina projekt med enkelhet och effektivitet.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Skapa en ny instans av klassen [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) genom att ange bredd- och höjdparametrarna. Denna konstruktor förenklar processen att initiera EMF-bilder med specifika dimensioner, vilket förbättrar effektiviteten i ditt utvecklingsarbetsflöde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Hämta EMF-metafilens huvudpost med denna egenskap. Idealiskt för att hantera metafildata effektivt i din applikation. Förbättra ditt arbetsflöde med förenklad åtkomst till huvudinformation för metafilen.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Modifiera EMF-metafilens huvudpost med denna egenskap. Idealiskt för att hantera metafildata effektivt i din applikation. Förbättra ditt arbetsflöde med förenklad åtkomst till huvudinformation för metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Få åtkomst till ett värde som indikerar om objektets data för närvarande är cachade, vilket eliminerar behovet av ytterligare dataläsning. Öka effektiviteten genom att snabbt avgöra om cachade data är tillgängliga för omedelbar åtkomst. Optimera ditt arbetsflöde med förenklade processer för datahämtning.

**Returns:**
boolean - `true` om objektets data är cachade; annars `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Hämta eller ändra posterna som är associerade med objektet. Åtkomst och hantera samlingen av poster effektivt för förbättrad datamanipulation och bearbetning. Optimera ditt arbetsflöde genom att sömlöst interagera med objektets poster.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Ändra posterna som är associerade med objektet. Åtkomst och hantera samlingen av poster effektivt för förbättrad datamanipulation och bearbetning. Optimera ditt arbetsflöde genom att sömlöst interagera med objektets poster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Posterna. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Åtkomst till filformatvärdet som är associerat med objektet. Bestäm enkelt formatet på filen som är kopplad till objektet för förenklad bearbetning och kompatibilitetskontroller. Förenkla ditt arbetsflöde genom att enkelt hämta information om filformatet.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämta bit-per-pixel‑antalet som är specifikt för rasterbilder, eftersom denna parameter inte gäller för vektorbilder. Fastställ snabbt pixeldjupet för rasterbilder för exakt analys och manipulation, vilket säkerställer korrekt hantering av bilddata.

**Returns:**
int - Bildens bitar per pixel-antal.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Åtkomst till bildens bredd, vilket ger viktig information för exakt rendering och bearbetning. Hämta snabbt bildens bredd för att säkerställa kompatibilitet och korrekt layout i olika applikationer och plattformar.

**Returns:**
float - Bildens bredd i pixlar.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Hämta bildens höjd, vilket underlättar exakt rendering och layoutjusteringar. Åtkomst till höjd‑egenskapen säkerställer kompatibilitet och sömlös integration över olika plattformar och applikationer.

**Returns:**
float - Bildens höjd i pixlar.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cacha data effektivt och förhindra redundant inläsning från den underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) med den här metoden. Förbättra prestanda och förenkla dataåtkomst i din applikation, optimera resursanvändning för förbättrad svarstid.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla typer av bilder, inklusive WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Cacha data för att ladda alla poster.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Nyckeln är en posttyp, värdet är antalet poster av den typen i WMF-bilden.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Samla statistik
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
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
    emfImage.dispose();
}

//Utdata kan se ut så här:
//Det totala antalet poster: 1188
//Posttyp                              Antal
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Hämta listan över teckensnitt som används i metafilen med den här metoden. Få insikt i teckensnittsanvändning, vilket underlättar effektiv hantering och optimering av teckensnittresurser för förbättrad rendering och bildkvalitet.

**Returns:**
java.lang.String[] - Teckensnittlistan
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Ändra storlek på duken enkelt med den här funktionen. Perfekt för att justera bildens totala dimensioner utan att ändra dess innehåll. Förbättra presentationen och förbered bilder för olika skärmstorlekar utan ansträngning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den nya rektangeln. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämtar de ursprungliga bildalternativen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Ställer in bildpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

