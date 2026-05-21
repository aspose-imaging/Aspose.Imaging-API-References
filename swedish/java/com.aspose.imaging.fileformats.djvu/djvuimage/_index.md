---
title: "DjvuImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "DjVu-dokumentklassen stöder grafikfilformat och underlättar sömlös hantering av skannade dokument och böcker genom att integrera text, teckningar, bilder och foton i ett enda format."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

DjVu-dokumentklassen stöder grafikfilformat och underlättar sömlös hantering av skannade dokument och böcker genom att integrera text, teckningar, bilder och foton i ett enda format. Genom att stödja flersidiga operationer kan du effektivt komma åt unika dokumentidentifierare, räkna sidor, ange aktiva sidor och hämta specifika dokumentsidor. Med funktioner för storleksändring, rotation, dithering, beskärning, gråskaletransformation, gamma‑korrektioner, justeringar och filterapplikation ger denna klass möjlighet till exakt manipulation och förbättring av DjVu‑bilder för att möta olika applikationsbehov med lätthet och precision.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Börja arbeta med DjVu‑bilder genom att initiera en ny instans av klassen [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) med en Stream‑parameter. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Börja arbeta med DjVu‑bilder sömlöst med denna konstruktor, som initierar en ny [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)‑klassinstans med en Stream‑ och LoadOptions‑parameter. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Börja arbeta med DjVu‑bilder sömlöst med denna konstruktor, som initierar en ny [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)‑klassinstans med en Stream‑ och LoadOptions‑parameter. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Uppstår när ett egenskapsvärde ändras. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Läs in ditt DjVu‑dokument med denna metod. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Läser in dokumentet. |
| [getIdentifier()](#getIdentifier--) | Hämtar det unika identifieraren för dokumentet |
| [getPageCount()](#getPageCount--) | Hämta det totala antalet sidor i din DjVu-bildsamling med denna egenskap. |
| [getPages()](#getPages--) | Åtkomst till de enskilda sidorna i din DjVu-bildsamling med denna egenskap. |
| [getDjvuPages()](#getDjvuPages--) | Hämta snabbt alla sidor som finns i ditt DjVu-dokument med hjälp av denna egenskap. |
| [getActivePage()](#getActivePage--) | Navigera genom ditt DjVu-dokument genom att komma åt eller ställa in den för närvarande aktiva sidan med denna egenskap. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Navigera genom ditt DjVu-dokument genom att komma åt eller ställa in den för närvarande aktiva sidan med denna egenskap. |
| [getFirstPage()](#getFirstPage--) | Åtkomst till den första sidan i ditt DjVu-dokument med denna egenskap. |
| [getLastPage()](#getLastPage--) | Hämta den sista sidan i ditt DjVu-dokument med denna egenskap. |
| [getNextPage()](#getNextPage--) | Navigera genom ditt DjVu-dokument genom att komma åt nästa sida med denna praktiska egenskap. |
| [getPreviousPage()](#getPreviousPage--) | Flytta snabbt bakåt i ditt DjVu-dokument vid visning eller bearbetning genom att komma åt föregående sida med denna praktiska egenskap. |
| [getFileFormat()](#getFileFormat--) | Få filformatinformationen som är associerad med din DjVu-bildfil. |
| [hasAlpha()](#hasAlpha--) | Bestäm snabbt om din DjVu-bildfil innehåller en alfakanal. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotera bilden runt dess centrum med Rotate‑metoden i klassen RasterCachedMultipageImage. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändra storleken på bilden med hjälp av `Resize`‑metoden, vilket ger ett enkelt och effektivt sätt att justera dimensionerna på dina bilder enligt dina krav. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Metoden `ResizeWidthProportionally` erbjuder en bekväm lösning för att justera bildens bredd samtidigt som bildförhållandet bevaras. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Metoden `ResizeHeightProportionally` låter dig justera bildens höjd samtidigt som bildförhållandet bevaras. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | `RotateFlip`‑metoden erbjuder mångsidiga manipuleringsalternativ för din bild, så att du kan rotera, vända eller utföra båda operationerna på den aktiva ramen oberoende av varandra. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | \"Dither\"‑funktionen applicerar en dithereffekt på din bild, vilket förbättrar dess visuella kvalitet genom att minska bandning och förbättra färgövergångar. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | \"Crop\" beskär din bild för att fokusera på specifika detaljer eller ta bort oönskade element, vilket förbättrar dess komposition och visuella intryck. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop med förskjutningar låter dig exakt justera positionen och dimensionerna på det beskärda området i en bild. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisering med ett fördefinierat tröskelvärde förenklar komplexa bilder till binära representationer, där pixlar kategoriseras som antingen svarta eller vita baserat på deras intensitet i förhållande till ett angivet tröskelvärde. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisering med Otsu-tröskelvärde är en teknik som automatiskt beräknar ett optimalt tröskelvärde baserat på bildens histogram. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisering med Bradleys adaptiva tröskelalgoritm med integrerad bildtröskel är en metod som beräknar ett lokalt tröskelvärde för varje pixel baserat på ett lokalt grannskap. |
| [grayscale()](#grayscale--) | Gråskaletransformation omvandlar en bild till en svart‑vit representation, där varje pixels intensitet representeras av ett enda värde som sträcker sig från svart till vitt. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gammakorrigering, specifikt för de röda, gröna och blå kanalerna, innebär att justera ljusstyrkan för varje färgkomponent separat. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gammakorrigering appliceras på en bild med anpassningsbara parametrar för de röda, gröna och blå kanalerna, vilket möjliggör exakt justering av färgbalans och ljusstyrka. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Justera bildens `brightness` med en angiven parameter, vilket ger kontroll över luminansnivåer för optimal visuell klarhet. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Förbättra [Image](../../com.aspose.imaging/image) kontrast för att förbättra visuell klarhet och framhäva detaljer med denna metod, som justerar skillnaden i brightness mellan ljusa och mörka områden. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Applicera filter på ett angivet rektangulärt område i bilden för att förbättra eller ändra dess utseende. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändra bildens storlek till den angivna bredden och höjden samtidigt som du tillämpar ytterligare inställningar vid behov. |
| [cacheData()](#cacheData--) | Cacha data privat för att optimera prestanda och minska behovet av upprepad datainhämtning från externa källor. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Spara varje sida som en enskild PNG-bild.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Generera ett filnamn baserat på sidnumret.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Börja arbeta med DjVu-bilder genom att initiera en ny instans av klassen [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) med en Stream-parameter. Perfekt för utvecklare som vill ha sömlös integration av DjVu-bildbehandling i sina projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Börja arbeta med DjVu-bilder sömlöst med denna konstruktor, som initierar en ny [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)-klassinstans med en Stream- och LoadOptions-parameter. Perfekt för utvecklare som vill ha exakt kontroll över DjVu-bildladdningsalternativ samtidigt som de behåller enkelhet och effektivitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa från. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Börja arbeta med DjVu-bilder sömlöst med denna konstruktor, som initierar en ny [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)-klassinstans med en Stream- och LoadOptions-parameter. Perfekt för utvecklare som vill ha exakt kontroll över DjVu-bildladdningsalternativ samtidigt som de behåller enkelhet och effektivitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream | Strömmen att läsa från. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Uppstår när ett egenskapsvärde ändras.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Läs in ditt DjVu-dokument med denna metod. Effektivisera processen genom att snabbt komma åt och importera dina DjVu-filer till din applikation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Läser in dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Hämtar det unika identifieraren för dokumentet

**Returns:**
int - Identifieraren.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämta det totala antalet sidor i din DjVu-bildsamling med denna egenskap. Idealisk för att snabbt bedöma omfattningen av ditt dokument eller bok lagrad i DjVu-format. Förbättra din arbetsflödeseffektivitet med exakt sidantalinformation.

**Returns:**
int - Sidantalet.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Åtkomst till de enskilda sidorna i din DjVu-bildsamling med denna egenskap. Förenkla navigering och manipulation av ditt dokument eller bok lagrad i DjVu-format genom att direkt komma åt varje sida. Förbättra din arbetsflödeseffektivitet med enkel sidhämtning.

**Returns:**
com.aspose.imaging.Image[] - Sidorna.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Spara varje sida som en enskild PNG-bild.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Generera ett filnamn baserat på sidnumret.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Hämta snabbt alla sidor som finns i ditt DjVu-dokument med denna egenskap. Förenkla ditt dokumentbehandlingsarbetsflöde genom att enkelt komma åt och hantera enskilda sidor i dina DjVu-filer. Förbättra effektiviteten och strömlinjeforma dina uppgifter med bekväm sidhämtning.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - Sidorna.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Navigera genom ditt DjVu-dokument genom att komma åt eller ställa in den för närvarande aktiva sidan med denna egenskap. Byt sömlöst mellan sidor för att fokusera på specifikt innehåll och förbättra din dokumentvisningsupplevelse.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Utdata kan se ut så här:
//Det totala antalet sidor: 2
//Det aktiva sidnumret:    1
//Det första sidnumret:     1
//Det sista sidnumret:      2
//--------------------------------------------------
//Sidnummer:     1
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
//--------------------------------------------------
//Sidnummer:     2
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Navigera genom ditt DjVu-dokument genom att komma åt eller ställa in den för närvarande aktiva sidan med denna egenskap. Byt sömlöst mellan sidor för att fokusera på specifikt innehåll och förbättra din dokumentvisningsupplevelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | Den aktiva sidan. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Kom åt den första sidan i ditt DjVu-dokument med denna egenskap. Hämta snabbt den inledande sidan för att börja visa eller bearbeta ditt dokument effektivt.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Utdata kan se ut så här:
//Det totala antalet sidor: 2
//Det aktiva sidnumret:    1
//Det första sidnumret:     1
//Det sista sidnumret:      2
//--------------------------------------------------
//Sidnummer:     1
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
//--------------------------------------------------
//Sidnummer:     2
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Hämta den sista sidan i ditt DjVu-dokument med denna egenskap. Kom snabbt åt den sista sidan för visning eller bearbetning med lätthet.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Utdata kan se ut så här:
//Det totala antalet sidor: 2
//Det aktiva sidnumret:    1
//Det första sidnumret:     1
//Det sista sidnumret:      2
//--------------------------------------------------
//Sidnummer:     1
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
//--------------------------------------------------
//Sidnummer:     2
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Navigera genom ditt DjVu-dokument genom att komma åt nästa sida med denna praktiska egenskap. Flytta snabbt framåt i dina dokumentvisnings- eller bearbetningsuppgifter.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Flytta snabbt bakåt i dina DjVu-dokumentvisnings- eller bearbetningsuppgifter genom att komma åt föregående sida med denna praktiska egenskap. Navigera effektivt genom ditt dokument med lätthet.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta filformatinformationen som är kopplad till din DjVu-bildfil. Bestäm snabbt formatet på din fil för sömlös integration i ditt arbetsflöde.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bestäm snabbt om din DjVu-bildfil innehåller en alfakanal. Förenkla ditt arbetsflöde genom att kontrollera förekomsten av transparensinformation i dina bilder.

**Returns:**
boolean - Har alfakanal.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotera bilden runt dess centrum med Rotate‑metoden i klassen RasterCachedMultipageImage. Denna praktiska funktion gör att du enkelt kan justera bildens orientering samtidigt som du behåller dess mittposition, vilket förbättrar dina bildmanipuleringsmöjligheter.

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


Ändra storlek på bilden med \`Resize\`‑metoden, vilket ger ett enkelt och effektivt sätt att justera dimensionerna på dina bilder enligt dina krav. Denna mångsidiga funktionalitet gör att du enkelt kan skala bilder till önskad storlek, vilket förbättrar deras användbarhet på olika plattformar och i applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Metoden \`ResizeWidthProportionally\` erbjuder en bekväm lösning för att justera bildens bredd samtidigt som bildförhållandet bevaras. Genom att proportionellt ändra bredden kan du säkerställa att dina bilder förblir visuellt tilltalande och konsekventa på olika enheter och skärmstorlekar, vilket ökar deras mångsidighet och användbarhet i olika sammanhang.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Detta exempel laddar en DJVU‑bild och ändrar dess storlek proportionellt med olika storleksändringsmetoder. Endast bredden anges, höjden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Metoden \`ResizeHeightProportionally\` låter dig justera bildens höjd samtidigt som bildförhållandet bevaras. Detta säkerställer att bilden behåller sina proportioner, förhindrar förvrängning och bevarar dess visuella integritet. Oavsett om du optimerar bilder för webbsidor, mobilappar eller tryckt media, garanterar denna metod att dina bilder ser bäst ut på olika plattformar och enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Detta exempel laddar en DJVU‑bild och ändrar dess storlek proportionellt med olika storleksändringsmetoder. Endast höjden anges, bredden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativen.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Metoden \`RotateFlip\` erbjuder mångsidiga manipuleringsalternativ för din bild, så att du kan rotera, vända eller utföra båda operationerna på den aktiva ramen oberoende av varandra. Oavsett om du redigerar foton, skapar grafik eller förbättrar digital konst, ger denna metod exakt kontroll över bildens orientering och sammansättning, vilket säkerställer att de uppfyller din kreativa vision med lätthet och effektivitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations- och vändningstypen. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

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
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Funktionen \"Dither\" applicerar en dithereffekt på din bild, vilket förbättrar dess visuella kvalitet genom att minska bandning och förbättra färgövergångar. Oavsett om du arbetar med digital konst, fotografi eller grafisk design, ger denna funktion en professionell touch till dina bilder, så att de framstår som mjukare och mer raffinerade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den anpassade paletten för dithering. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Utför tröskel-dithering med en 4-bitars färgpalett som innehåller 16 färger.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Utför Floyd-dithering med en 1-bitars färgpalett som endast innehåller 2 färger – svart och vit.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


\"Crop\" beskär din bild för att fokusera på specifika detaljer eller ta bort oönskade element, vilket förbättrar dess komposition och visuella intryck. Oavsett om du anpassar foton för sociala medier, skapar webbplatsbanners eller designar tryckt material, hjälper detta verktyg dig att förfina dina bilder med precision och klarhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |


**Example: The following example crops a DJVU image.**
Följande exempel beskär en DJVU‑bild. Beskärningsområdet specificeras via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Beskär bilden. Beskärningsområdet är den rektangulära centrala delen av bilden.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Spara den beskurna bilden som PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beskärning med förskjutningar låter dig exakt justera position och dimensioner för det beskurna området i en bild. Denna funktion är ovärderlig för att förfina kompositioner, justera element och framhäva fokuspunkter i dina visuella verk. Genom att inkludera förskjutningar i beskärningsprocessen kan du uppnå pixelperfekt precision och finjustera bildens inramning med lätthet.

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


Binarisering med ett fördefinierat tröskelvärde förenklar komplexa bilder till binära representationer, där pixlar kategoriseras som antingen svarta eller vita baserat på deras intensitet i förhållande till ett specificerat tröskelvärde. Denna teknik används ofta inom bildbehandling för att förbättra klarhet, förenkla analys och förbereda bilder för vidare bearbetning, såsom optisk teckenigenkänning (OCR). Genom att tillämpa ett fast tröskelvärde kan du snabbt omvandla gråskalebilder till binär form, vilket gör dem lättare att tolka och extrahera meningsfull information från.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln tilldelas värdet 255, annars 0. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
Följande exempel binariserar en DJVU‑bild med det fördefinierade tröskelvärdet. Binariserade bilder innehåller endast två färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

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


Binarisering med Otsu-tröskelvärde är en teknik som automatiskt beräknar ett optimalt tröskelvärde baserat på bildens histogram. Den separerar bilden i förgrund och bakgrund genom att minimera intra-klassvariansen. Otsus metod används ofta för att segmentera bilder till binär form, särskilt när fördelningen av pixelintensiteter är bimodal eller multimodal. Detta tillvägagångssätt är fördelaktigt för uppgifter som objektidentifiering, bildsegmentering och funktionsextraktion, där exakt avgränsning mellan förgrund och bakgrund är avgörande.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
Följande exempel binariserar en DJVU‑bild med Otsu-tröskelvärde. Binariserade bilder innehåller endast två färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisera bilden med Otsu-tröskling.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisering med Bradleys adaptiva tröskelalgoritm och integralbildströskel är en metod som beräknar ett lokalt tröskelvärde för varje pixel baserat på ett lokalt grannskap. Den anpassar sig till variationer i belysning över bilden, vilket gör den lämplig för bilder med ojämna ljusförhållanden. Genom att beräkna tröskeln med integralbilder hanterar den effektivt stora grannskap, vilket gör den tillämplig för realtidsapplikationer. Denna teknik används ofta i dokumentbehandling, OCR (Optisk teckenigenkänning) och bildsegmenteringsuppgifter där exakt binarisering är avgörande för efterföljande analys.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |
| windowSize | int | Storleken på ett s x s-fönster av pixlar centrerade kring denna pixel. |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
Följande exempel binariserar en DJVU‑bild med Bradleys adaptiva tröskelalgoritm med angiven fönsterstorlek. Binariserade bilder innehåller endast två färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisera bilden med en ljusstyrkeskillnad på 5. Ljusstyrkan är skillnaden mellan en pixel och medelvärdet av ett 10 × 10‑fönster av pixlar centrerade kring den pixeln.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Gråskaletransformation konverterar en bild till en svart‑vit representation, där varje pixels intensitet representeras av ett enda värde som sträcker sig från svart till vitt. Denna process tar bort färginformation och resulterar i en monokrom bild. Gråskalebilder används ofta i applikationer där färg är onödig eller där enkelhet föredras, såsom dokumentavläsning, utskrift och vissa typer av bildanalys.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
Följande exempel omvandlar en färgad DJVU‑bild till dess gråskalerepresentation. Gråskalebilder består uteslutande av gråtoner och innehåller endast intensitetsinformation.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gammakorrigering, specifikt för de röda, gröna och blå kanalerna, innebär att justera ljusstyrkan för varje färgkomponent separat. Genom att applicera olika gammakoefficienter på RGB‑kanalerna kan du finjustera bildens totala ljusstyrka och kontrast. Denna teknik säkerställer korrekt färgrepresentation och förbättrar bildens visuella kvalitet på olika displayenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalernas koefficient |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Ange gamma-koefficient för röd, grön och blå kanaler.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gammakorrigering appliceras på en bild med anpassningsbara parametrar för de röda, gröna och blå kanalerna, vilket möjliggör exakt justering av färgbalans och ljusstyrka. Denna metod förbättrar bildkvaliteten genom att finjustera färgrepresentationen, vilket säkerställer optimal återgivning på olika displayenheter. Justering av gammavärden för enskilda kanaler förbättrar färgbalansen och den visuella attraktionskraften.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanalkoefficient |
| gammaGreen | float | Gamma för grön kanalkoefficient |
| gammaBlue | float | Gamma för blå kanalens koefficient |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Ange individuella gamma-koefficienter för röd, grön och blå kanaler.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Justera bildens `brightness` med en specificerad parameter, vilket ger kontroll över luminansnivåerna för optimal visuell klarhet. Denna metod ökar eller minskar bildens totala ljusstyrka, vilket möjliggör finjusteringar för att uppnå önskade ljuseffekter. Genom att modulera ljusstyrkan kan användare optimera bildens synlighet och förbättra detaljåtergivning för en förbättrad visningsupplevelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Ställ in ljusstyrkevärdet. De accepterade värdena för ljusstyrka ligger i intervallet [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Förbättra [Image](../../com.aspose.imaging/image)‑kontrasten för att öka visuell klarhet och framhäva detaljer med denna metod, som justerar skillnaden i ljusstyrka mellan ljusa och mörka områden. Genom att finjustera kontrastnivåerna kan användare skapa mer levande och slagkraftiga bilder, förbättra den övergripande bildkvaliteten och maximera detaljernas synlighet. Denna justering hjälper till att framhäva subtila nyanser i färg och textur, vilket resulterar i mer dynamiska och visuellt tilltalande bilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | float | Kontrastvärde (i intervallet [-100; 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Ställ in kontrastvärdet. De accepterade värdena för kontrast ligger i intervallet [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Applicera filter på ett specificerat rektangulärt område i bilden för att förbättra eller ändra dess utseende. Genom att rikta in sig på specifika regioner möjliggör denna metod precisa justeringar, såsom suddning, skärpning eller applicering av konstnärliga effekter, för att uppnå önskat visuellt resultat. Finjustering av filter på utvalda områden ger användare möjlighet att anpassa bildens estetik, förbättra klarhet och skapa konstnärliga effekter som matchar deras preferenser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Alternativen. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett jämnvärde på 4,0 på hela bilden.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applicera ett rörelse‑Wiener-filter med en längd på 5, ett jämnvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applicera ett skärpningsfilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändra storleken på bilden till den angivna bredden och höjden samtidigt som ytterligare inställningar tillämpas vid behov. Denna metod gör det möjligt för användare att justera bildens dimensioner samtidigt som önskade egenskaper såsom bildförhållande, bildkvalitet och komprimeringsinställningar bibehålls. Genom att erbjuda flexibilitet i storleksändringsalternativ kan användare anpassa bilden för att uppfylla specifika krav och optimera dess utseende för olika applikationer och plattformar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Skala ner med 2 gånger med adaptiv omsampling.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Spara som PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cacha data privat för att optimera prestanda och minska behovet av upprepad datainhämtning från externa källor. Detta tillvägagångssätt hjälper också till att spara resurser, särskilt i scenarier där dataåtkomst är frekvent eller resurser är begränsade.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en DJVU-fil.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Detta anrop cachar alla sidor så att ingen ytterligare dataladdning kommer att utföras från den underliggande datastreamen.
    image.cacheData();

    // Eller så kan du cacha sidorna individuellt.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

