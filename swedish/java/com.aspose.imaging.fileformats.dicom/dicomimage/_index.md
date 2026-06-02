---
title: "DicomImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Denna klass implementerar Digital Imaging and Communications in Medicine DICOM raster image format support och erbjuder en omfattande lösning för att bearbeta DICOM-bilder med precision och flexibilitet."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Denna klass implementerar Digital Imaging and Communications in Medicine (DICOM) raster image format support och erbjuder en omfattande lösning för att bearbeta DICOM-bilder med precision och flexibilitet. Du kan sömlöst manipulera bildsidor, inklusive operationer för att hämta, lägga till eller ta bort sidor, samt kontrollera standard- och aktiva sidor. Med möjligheter att arbeta med alfakanaler, bädda in XMP-metadata, ändra storlek, rotera, beskära, binarisera, justera, applicera filter och konvertera till andra rasterformat. Detta API ger utvecklare möjlighet att hantera DICOM-bilder effektivt samtidigt som det uppfyller olika applikationskrav i medicinska bildsammanhang.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | Initiera en ny instans av DicomImage-klassen enkelt med denna konstruktor, med hjälp av dicomOptions-parametrar. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Initiera en ny instans av DicomImage-klassen smidigt genom att använda en ström och loadOptions-parametrar i denna konstruktor. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | Skapa en ny instans av DicomImage-klassen genom att använda en strömparameter i denna konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageCount()](#getPageCount--) | Hämta bildens totala sidantal med den här intuitiva egenskapen. |
| [getPages()](#getPages--) | Åtkomst till bildens sidor med denna intuitiva egenskap. |
| [getFileInfo()](#getFileInfo--) | Hämta värdefull headerinformation från DICOM-filen utan ansträngning med denna intuitiva egenskap. |
| [getDicomPages()](#getDicomPages--) | Åtkomst till bildens sidor med denna intuitiva egenskap. |
| [getActivePage()](#getActivePage--) | Åtkomst till bildens aktiva sida med denna intuitiva egenskap. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | Hantera bildens aktiva sida med denna intuitiva egenskap. |
| [getActivePageIndex()](#getActivePageIndex--) | Hämta indexet för den aktiva sidan utan ansträngning med denna intuitiva egenskap. |
| [getFileFormat()](#getFileFormat--) | Hämta filformatets värde utan ansträngning med denna intuitiva egenskap. |
| [hasAlpha()](#hasAlpha--) | Hämta om bilden har en alfakanal utan ansträngning med denna intuitiva egenskap. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Utöka din bildsamling genom att lägga till en ny sida med denna intuitiva metod. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Bevara objektets data genom att spara det till den angivna filen (indexer + filnamn) tillsammans med specificerat filformat och alternativ. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Justera upplösningen för denna [RasterImage](../../com.aspose.imaging/rasterimage) med precision genom att använda denna enkla metod. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Ändra storleken på bilden samtidigt som du behåller bildförhållandet med denna bekväma metod. |
| [addPage()](#addPage--) | Lägg till en ny sida i slutet av bildens sidlista med denna enkla metod. |
| [insertPage(int pageIndex)](#insertPage-int-) | Infoga en ny sida i bildens sidlista på ett specificerat index med denna intuitiva metod. |
| [removePage(int pageIndex)](#removePage-int-) | Ta bort sidan på det specificerade indexet från sidlistan med denna bekväma metod. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotera bilden kring dess centrum med denna bekväma metod. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Justera bildens storlek med denna enkla metod. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Justera bildens bredd samtidigt som du behåller bildförhållandet med denna bekväma metod. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Justera bildens höjd samtidigt som du behåller bildförhållandet med denna användarvänliga metod. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Manipulera enkelt den aktiva ramen genom att rotera, vända eller utföra båda åtgärderna samtidigt med denna enkla metod. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Förbättra den aktuella bilden genom att applicera dithereffekter med denna enkla metod. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär bilden för att ta bort oönskade områden och fokusera på viktigt innehåll med denna enkla metod. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Justera beskärningsområdet för bilden genom att tillämpa förskjutningar med denna mångsidiga metod. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Konvertera enkelt bilden till ett binärt format med en fördefinierad tröskelvärde med denna enkla metod. |
| [binarizeOtsu()](#binarizeOtsu--) | Applicera Otsu-tröskling för att binarisera bilden, automatiskt bestämma det optimala tröskelvärdet baserat på bildens histogram. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisera bilder med Bradleys adaptiva trösklingsalgoritm, utnyttjande av integralbildströskling för förbättrad prestanda. |
| [grayscale()](#grayscale--) | Transformera enkelt bilder till deras gråskalerepresentation, vilket förenklar visuell analys och bearbetningsuppgifter. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Förbättra bildkvaliteten och justera den med gammakorrigering, en kraftfull teknik för finjustering av visuellt utseende. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Uppnå precisa färgjusteringar genom att tillämpa gammakorrigering oberoende på de röda, gröna och blå komponenterna i en bild. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Förbättra bildens luminans med justeringen av `brightness`, en parametriserad metod som låter utvecklare finjustera bildens ljusstyrka. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Förbättra [Image](../../com.aspose.imaging/image) kontrast med denna användarvänliga metod, som justerar skillnaden mellan ljusa och mörka områden. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Förbättra enkelt specifika områden i din bild genom att tillämpa filter på utsedda rektanglar. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Justera storleken på din bild med denna enkla omdimensioneringsmetod. |
| [cacheData()](#cacheData--) | Denna metod cachar data effektivt, optimerar prestanda och säkerställer snabb åtkomst när det behövs. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// Läs in en bild
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Rita något med vektorgrafik.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Spara pixlarna i den ritade bilden. De finns nu på den första sidan av DICOM-bilden.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Lägg till några sidor efter, vilket gör dem mörkare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Lägg till några sidor framför huvudsidan, vilket gör dem ljusare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Spara den skapade flersidiga bilden till utdatafilen.
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


Initiera en ny instans av klassen **DicomImage** enkelt med denna konstruktor, med användning av dicomOptions-parametrar. Perfekt för utvecklare som vill dyka ner i [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage)-objekt snabbt och effektivt i sina projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | Dicom-alternativen (ignoreras nu). |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


Initiera en ny instans av klassen **DicomImage** smidigt genom att använda en ström och loadOptions-parametrar i denna konstruktor. Idealiskt för utvecklare som snabbt vill börja arbeta med [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage)-objekt på ett effektivt sätt i sina projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


Skapa en ny instans av klassen **DicomImage** genom att använda en strömparameter i denna konstruktor. Perfekt för utvecklare som söker ett förenklat sätt att initiera [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage)-objekt från befintliga datastreams i sina projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämta det totala sidantalet för bilden med denna intuitiva egenskap. Idealiskt för utvecklare som snabbt vill få åtkomst till antalet sidor i en bild, vilket säkerställer effektiv navigering och hantering.

**Returns:**
int - sidantalet.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Åtkomst till bildens sidor med denna intuitiva egenskap. Idealiskt för utvecklare som vill interagera med enskilda sidor i bilden, vilket säkerställer sömlös navigering och manipulation.

**Returns:**
com.aspose.imaging.Image[] - sidorna.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


Hämta värdefull headerinformation från DICOM-filen enkelt med denna intuitiva egenskap. Idealiskt för utvecklare som snabbt vill få åtkomst till väsentliga detaljer som finns i DICOM-filen, vilket säkerställer effektiv dataextraktion och analys.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


Åtkomst till bildens sidor med denna intuitiva egenskap. Idealiskt för utvecklare som vill interagera med enskilda sidor i bilden, vilket säkerställer sömlös navigering och manipulation.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] - sidorna.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


Åtkomst till den aktiva sidan i bilden med denna intuitiva egenskap. Idealiskt för utvecklare som vill dynamiskt växla mellan sidor i flersidiga bilder, vilket säkerställer effektiv navigering och bearbetning.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


Hantera den aktiva sidan i bilden med denna intuitiva egenskap. Idealiskt för utvecklare som vill dynamiskt växla mellan sidor i flersidiga bilder, vilket säkerställer effektiv navigering och bearbetning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | den aktiva sidan. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


Hämta indexet för den aktiva sidan enkelt med denna intuitiva egenskap. Idealiskt för utvecklare som snabbt vill få åtkomst till det aktuella sidindexet i flersidiga bilder, vilket säkerställer effektiv navigering och bearbetning.

**Returns:**
int - indexet för den aktiva sidan.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta filformatvärdet enkelt med denna intuitiva egenskap. Idealiskt för utvecklare som snabbt vill få åtkomst till formatet på bildfilen, vilket säkerställer effektiv hantering och bearbetning baserat på filtypen.

**Returns:**
long - ett värde av filformatet [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämta om bilden har en alfakanal enkelt med denna intuitiva egenskap. Idealiskt för utvecklare som vill avgöra om bilden innehåller transparensinformation, vilket säkerställer exakt hantering av alfakanaldatan i bildbehandlingsuppgifter.

**Returns:**
boolean - sant om bilden har alfakanal.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Utöka din bildsamling genom att lägga till en ny sida med denna intuitiva metod. Idealiskt för utvecklare som vill dynamiskt lägga till sidor i flersidiga bilder, vilket säkerställer sömlös expansion och organisering av bildinnehållet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Sidan att lägga till. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


Bevara objektets data genom att spara det till den angivna filen (indexer + filnamn) tillsammans med specificerat filformat och alternativ. Idealiskt för utvecklare som vill lagra data säkert i olika format samtidigt som de behåller flexibilitet och kontroll över sparparametrarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Alternativen. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Justera upplösningen för denna [RasterImage](../../com.aspose.imaging/rasterimage) med precision med hjälp av denna enkla metod. Idealiskt för utvecklare som vill anpassa bildens upplösning efter specifika krav, vilket säkerställer optimal visningskvalitet och filstorlekskontroll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpiX | double | Den horisontella upplösningen, i punkter per tum, för [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Den vertikala upplösningen, i punkter per tum, för [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Ändra bildens storlek samtidigt som du behåller dess bildförhållande med denna praktiska metod. Idealiskt för utvecklare som vill justera bildens dimensioner proportionellt, vilket säkerställer konsistens och bevarar originalinnehållets proportioner. Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet `newWidth`/width och `newHeight`/height.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


Lägg till en ny sida i slutet av bildens sidlista med denna enkla metod. Idealiskt för utvecklare som vill dynamiskt expandera flersidiga bilder, vilket säkerställer sömlös integration och organisering av bildinnehållet.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


Infoga en ny sida i bildens sidlista på ett specificerat index med denna intuitiva metod. Idealiskt för utvecklare som vill ha exakt kontroll över arrangemanget av sidor i flersidiga bilder, vilket säkerställer sömlös organisering och anpassning av bildinnehållet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageIndex | int | Index för sidan. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Rita något med vektorgrafik.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Spara pixlarna i den ritade bilden. De finns nu på den första sidan av DICOM-bilden.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Lägg till några sidor efter, vilket gör dem mörkare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Lägg till några sidor framför huvudsidan, vilket gör dem ljusare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Spara den skapade flersidiga bilden till utdatafilen.
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


Ta bort sidan på det specificerade indexet från sidlistan med denna praktiska metod. Idealiskt för utvecklare som vill ha exakt kontroll över hanteringen av flersidiga bilder, vilket säkerställer sömlös organisering och anpassning av bildinnehållet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageIndex | int | Index för sidan. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotera bilden kring dess centrum med denna praktiska metod. Idealiskt för utvecklare som vill justera bildens orientering dynamiskt, vilket säkerställer optimal presentation och justering i deras applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | Om den är inställd på `true` kommer bildens storlek att ändras enligt de roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna orörda och endast `` bildinnehållet roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Läs in en DICOM-bild från en filström.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // Rotera bilden kring centrum med 60 grader medurs.
        // Använd grå som bakgrundsfärg.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Observera att om bilden är färgrik kommer den automatiskt att konverteras till gråskala enligt alternativen nedan.
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // Skapa en array av TIFF-ramar.
        // Antalet ramar är lika med antalet DJVU-sidor.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // Spara varje sida som en individuell TIFF-ram.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // Skapa en TIFF-ram baserad på DICOM-sidan.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // Sätt ihop en TIFF-bild från ramarna.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // Spara till en fil.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Justera bildens storlek med denna enkla metod. Idealiskt för utvecklare som vill dynamiskt ändra bildstorleken, vilket säkerställer att de passar sömlöst in i olika sammanhang och layouter i deras applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


Justera bildens bredd samtidigt som du behåller dess bildförhållande med denna praktiska metod. Idealiskt för utvecklare som vill ändra bildstorlek proportionellt, vilket säkerställer konsekventa och visuellt tilltalande resultat i olika visningsmiljöer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Det här exemplet laddar en DICOM-bild och ändrar dess storlek proportionellt med olika storleksändringsmetoder. Endast bredden anges, höjden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


Justera bildens höjd samtidigt som du behåller dess bildförhållande med den här användarvänliga metoden. Perfekt för utvecklare som vill dynamiskt ändra bildstorlek samtidigt som de bevarar proportionerna, vilket säkerställer optimal visning och användbarhet i deras applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Det här exemplet laddar en DICOM-bild och ändrar dess storlek proportionellt med olika storleksändringsmetoder. Endast höjden anges, bredden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


Manipulera enkelt den aktiva ramen genom att rotera, vända eller utföra båda åtgärderna samtidigt med den här enkla metoden. Idealisk för utvecklare som behöver dynamiskt justera orienteringen av specifika ramar i sina bildsekvenser, vilket säkerställer optimal presentation och justering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Den roterande vändningstypen. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
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
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Förbättra den aktuella bilden genom att applicera ditheringseffekter med den här enkla metoden. Perfekt för utvecklare som vill lägga till textur och djup i bilder, vilket förbättrar deras visuella kvalitet och övergripande attraktionskraft.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den anpassade paletten för dithering. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Utför tröskel-dithering med en 4-bitars färgpalett som innehåller 16 färger.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Utför Floyd-dithering med en 1-bitars färgpalett som endast innehåller 2 färger – svart och vit.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden för att ta bort oönskade områden och fokusera på väsentligt innehåll med den här enkla metoden. Idealisk för utvecklare som vill anpassa den visuella sammansättningen av bilder, så att de förmedlar önskat budskap effektivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |


**Example: The following example crops a DICOM image.**
Följande exempel beskär en DICOM-bild. Beskärningsområdet anges via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Beskär bilden. Beskärningsområdet är den rektangulära centrala delen av bilden.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // Spara den beskurna bilden som PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Justera beskärningsområdet för bilden genom att applicera förskjutningar med den här mångsidiga metoden. Perfekt för utvecklare som behöver exakt kontroll över beskärningsprocessen, så att viktiga detaljer behålls samtidigt som onödiga element elimineras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | int | Den vänstra förskjutningen. |
| rightShift | int | Den högra förskjutningen. |
| topShift | int | Den övre förskjutningen. |
| bottomShift | int | Den nedre förskjutningen. |


**Example: The following example crops a DICOM image.**
Följande exempel beskär en DICOM-bild. Beskärningsområdet anges via vänster, topp, höger och botten marginaler.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Beskär igen. Ställ in en marginal på 10 % av bildens storlek.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Spara den beskurna bilden som PNG.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Konvertera enkelt bilden till ett binärt format med ett fördefinierat tröskelvärde med den här enkla metoden. Idealisk för utvecklare som vill förenkla bildbehandlingsuppgifter genom att segmentera bilden i förgrunds- och bakgrundskomponenter baserat på angivna intensitetsnivåer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln tilldelas värdet 255, annars 0. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
Följande exempel binäriserar en DICOM-bild med det fördefinierade tröskelvärdet. Binäriserade bilder innehåller endast 2 färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisera bilden med ett tröskelvärde på 127.
    // Om ett motsvarande gråvärde för en pixel är större än 127, tilldelas ett värde på 255, annars 0.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Applicera Otsu-tröskelvärde för att binärisera bilden, vilket automatiskt bestämmer det optimala tröskelvärdet baserat på bildens histogram. Perfekt för utvecklare som söker en pålitlig metod för att segmentera bilder i förgrunds- och bakgrundsområden med minimal manuell inblandning.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
Följande exempel binäriserar en DICOM-bild med Otsu-tröskelvärde. Binäriserade bilder innehåller endast 2 färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisera bilden med Otsu-tröskling.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binärisera bilder med Bradleys adaptiva tröskelalgoritm, som utnyttjar integralbildströskling för förbättrad prestanda. Idealisk för utvecklare som vill automatiskt segmentera bilder baserat på lokala variationer i ljusstyrka, vilket säkerställer exakt objektdetektion och extraktion under varierande ljusförhållanden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |
| windowSize | int | Storleken på ett s x s-fönster av pixlar centrerade kring denna pixel. |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
Följande exempel binäriserar en DICOM-bild med Bradleys adaptiva tröskelalgoritm med den angivna fönsterstorleken. Binäriserade bilder innehåller endast 2 färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisera bilden med en ljusstyrkeskillnad på 5. Ljusstyrkan är skillnaden mellan en pixel och medelvärdet av ett 10 × 10‑fönster av pixlar centrerade kring den pixeln.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Omvandla enkelt bilder till deras gråskalerepresentation, vilket förenklar visuell analys och bearbetningsuppgifter. Perfekt för utvecklare som vill förbättra bildens klarhet, minska komplexiteten och underlätta effektiva gråskalebaserade algoritmer för olika tillämpningar.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
Följande exempel omvandlar en färgad DICOM-bild till dess gråskalerepresentation. Gråskalebilder består uteslutande av gråtoner och innehåller endast intensitetsinformation.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Förbättra bildkvaliteten och justera den med gamma-korrigering, en kraftfull teknik för finjustering av visuellt utseende. Perfekt för utvecklare som vill optimera bildpresentation, justera färgbalansen och säkerställa konsekvent rendering på olika enheter och miljöer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalernas koefficient |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Ange gamma-koefficient för röd, grön och blå kanaler.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Uppnå precisa färgjusteringar genom att applicera gamma-korrigering oberoende på de röda, gröna och blå komponenterna i en bild. Denna metod säkerställer korrekt färgbalans och optimal visuell output, vilket tillgodoser utvecklare som söker detaljerad kontroll över bildrendering och färgnoggrannhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanalkoefficient |
| gammaGreen | float | Gamma för grön kanalkoefficient |
| gammaBlue | float | Gamma för blå kanalens koefficient |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Ange individuella gamma-koefficienter för röd, grön och blå kanaler.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Förbättra bildens luminans med justeringen av `brightness`, en parametriserad metod som låter utvecklare finjustera bildens ljusstyrka. Denna användarvänliga funktion ger utvecklare möjlighet att sömlöst manipulera bildens ljusstyrka, vilket erbjuder flexibilitet och kontroll över den visuella estetiken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Ställ in ljusstyrkevärdet. De accepterade värdena för ljusstyrka ligger i intervallet [-255, 255].
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Förbättra [Image](../../com.aspose.imaging/image) kontrast med den här användarvänliga metoden, som justerar skillnaden mellan ljusa och mörka områden. Förbättra visuell klarhet och definition utan ansträngning, vilket ger utvecklare intuitiv kontroll över bildkontrast för optimal rendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | float | Kontrastvärde (i intervallet [-100; 100]) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Ställ in kontrastvärdet. De accepterade värdena för kontrast ligger i intervallet [-100f, 100f].
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Förbättra enkelt specifika områden i din bild genom att applicera filter på angivna rektanglar. Denna metod ger utvecklare exakt kontroll över bildmanipulation, vilket möjliggör riktade justeringar för att uppnå önskade visuella effekter med lätthet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Alternativen. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett jämnvärde på 4,0 på hela bilden.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applicera ett rörelse‑Wiener-filter med en längd på 5, ett jämnvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applicera ett skärpningsfilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Justera storleken på din bild med den här enkla storleksändringsmetoden. Oavsett om du behöver minska eller förstora bilden, säkerställer denna funktion att dina storleksändringsbehov uppfylls effektivt och exakt, vilket gör den perfekt för utvecklare som söker snabba och enkla bildstorleksjusteringar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Skala ner med 2 gånger med adaptiv omsampling.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Spara som PNG
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Denna metod cachar data effektivt, optimerar prestanda och säkerställer snabb åtkomst vid behov. Idealisk för utvecklare som vill förbättra hastigheten och effektiviteten i sina applikationer genom intelligent hantering av dataresurser.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en DICOM-fil.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Detta anrop cachar alla sidor så att ingen ytterligare dataladdning kommer att utföras från den underliggande datastreamen.
    image.cacheData();

    // Eller så kan du cacha sidorna individuellt.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

