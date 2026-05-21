---
title: "CdrImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för CorelDRAW CDR vektorbildformatstöd är ett viktigt verktygspaket för utvecklare som arbetar med vektorgrafik."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

API:et för stöd för CorelDRAW CDR vektorbildformat är ett viktigt verktyg för utvecklare som arbetar med vektorgrafik. Detta API möjliggör sömlös bearbetning av CDR-filer, vilket tillåter lagring och manipulering av olika element såsom text, linjer, former, bilder, färger och effekter. Med sina omfattande funktioner kan utvecklare effektivt arbeta med vektorrepräsentationer av bildinnehåll, vilket säkerställer precision och flexibilitet vid skapande och redigering av CorelDRAW vektorgrafik programmässigt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Börja arbeta med klassen [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) utan ansträngning genom att initiera en ny instans med en ström och loadOptions‑parametrar. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Börja arbeta med klassen [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) utan ansträngning genom att initiera en ny instans med en ström och loadOptions‑parametrar. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Hämta standard‑sidan för bilden enkelt med denna användarvänliga egenskap. |
| [isCached()](#isCached--) | Bestäm utan ansträngning om objektets data för närvarande är cachad, vilket eliminerar behovet av dataläsning. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämta bildens bitdjup enkelt med den här användarvänliga egenskapen. |
| [getPageCount()](#getPageCount--) | Hämta eller uppdatera utan ansträngning det totala sidantalet för bilden med denna intuitiva egenskap. |
| [getPages()](#getPages--) | Hämta bildens sidor sömlöst med den här intuitiva egenskapen. |
| [getCdrDocument()](#getCdrDocument--) | Hämta eller uppdatera utan ansträngning CDR‑dokumentet med denna intuitiva egenskap. |
| [getFileFormat()](#getFileFormat--) | Hämta bildens filformat utan ansträngning med denna intuitiva egenskap. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [cacheData()](#cacheData--) | Cacha data utan ansträngning för att förhindra ytterligare inläsning från den underliggande källan med denna användarvänliga metod. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Anpassa bildens färgpalett med den här intuitiva metoden. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en CDR‑fil.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Detta anrop cachelagrar endast standardsidan.
    image.cacheData();

    // Cachelagra alla sidor så att ingen ytterligare dataladdning utförs från den underliggande dataströmmen.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Börja arbeta med klassen [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) utan ansträngning genom att initiera en ny instans med en ström och loadOptions‑parametrar. Idealiskt för utvecklare som söker ett bekvämt sätt att läsa in CDR‑bilder från olika datakällor samtidigt som de anpassar inläsningsprocessen efter behov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Börja arbeta med klassen [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) utan ansträngning genom att initiera en ny instans med en ström och loadOptions‑parametrar. Idealiskt för utvecklare som söker ett bekvämt sätt att läsa in CDR‑bilder från olika datakällor samtidigt som de anpassar inläsningsprocessen efter behov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream | Strömmen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Hämta standard‑sidan för bilden enkelt med denna användarvänliga egenskap. Perfekt för utvecklare som söker snabb åtkomst till bildens huvudsida, vilket säkerställer effektiv navigering och hantering.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Bestäm utan ansträngning om objektets data för närvarande är cachad, vilket eliminerar behovet av dataläsning. Idealiskt för utvecklare som vill optimera prestanda genom att utnyttja cachad data effektivt, vilket säkerställer snabbare åtkomst till objektinformation.

**Returns:**
boolean - `true` om objektets data är cachade; annars `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämta bildens bitdjup enkelt med den här användarvänliga egenskapen. Idealiskt för utvecklare som vill bestämma detaljnivån eller färgdjupet i sina bilder, vilket säkerställer korrekt bearbetning och manipulation.

**Returns:**
int - Bildens bitar per pixel-antal.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Hämta eller uppdatera utan ansträngning det totala sidantalet för bilden med denna intuitiva egenskap. Idealiskt för utvecklare som vill hantera flersidiga bilder dynamiskt, vilket säkerställer effektiv navigering och manipulation av bildinnehåll.

**Returns:**
int - sidantalet.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Hämta bildens sidor sömlöst med den här intuitiva egenskapen. Idealisk för utvecklare som vill komma åt och manipulera enskilda sidor i flersidiga bilder, vilket säkerställer effektiv navigering och bearbetning.

**Returns:**
com.aspose.imaging.Image[] - sidorna.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Hämta eller uppdatera utan ansträngning CDR‑dokumentet med denna intuitiva egenskap. Idealiskt för utvecklare som vill komma åt eller ändra CDR‑dokumentet, vilket säkerställer flexibilitet och effektivitet i deras applikationer.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta bildens filformat utan ansträngning med denna intuitiva egenskap. Idealiskt för utvecklare som vill bestämma formatet på sina bilder dynamiskt, vilket säkerställer kompatibilitet och korrekt bearbetning i deras applikationer.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

Värde: Bildens bredd.

**Returns:**
int - bildens bredd.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

Värde: Bildens höjd.

**Returns:**
int - bildens höjd.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cacha data utan ansträngning för att förhindra ytterligare inläsning från den underliggande källan med denna användarvänliga metod. Idealiskt för utvecklare som vill optimera prestanda genom att förladda data, vilket säkerställer snabbare åtkomst och smidigare drift i deras applikationer. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en CDR‑fil.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Detta anrop cachelagrar endast standardsidan.
    image.cacheData();

    // Cachelagra alla sidor så att ingen ytterligare dataladdning utförs från den underliggande dataströmmen.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Anpassa bildens färgpalett med den här intuitiva metoden. Idealisk för utvecklare som vill tillämpa specifika färgscheman eller justeringar dynamiskt, vilket säkerställer exakt kontroll över bildens visuella utseende.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

