---
title: "CmxImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för Corel Metafile Exchange CMX vektorbildformat med stöd för metadata beskrivningar är en omfattande lösning för utvecklare som arbetar med CMX-filer."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

API:et för Corel Metafile Exchange (CMX) vektorbildformat med stöd för metadata beskrivningar är en omfattande lösning för utvecklare som arbetar med CMX-filer. Detta API möjliggör sömlös inläsning av CMX-bilder, extrahering av metadata såsom bitar per pixel, objektdimensioner och mer. Med ytterligare funktioner som storleksändring, rotation, inställning av paletter och konvertering till andra format, ger detta API utvecklare möjlighet att effektivt manipulera och anpassa CMX-vektorbilder för att möta deras specifika applikationskrav.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Börja arbeta med klassen [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) sömlöst genom att initiera en ny instans med parametrarna streamContainer och loadOptions. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Hämta bildens filformat enkelt med den här användarvänliga egenskapen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämta bildens bitdjup enkelt med den här användarvänliga egenskapen. |
| [getDefaultPage()](#getDefaultPage--) | Hämta bildens standardsida enkelt med den här intuitiva egenskapen. |
| [isCached()](#isCached--) | Bestäm om objektets data för närvarande är cachad, vilket eliminerar behovet av att läsa data. |
| [getWidthF()](#getWidthF--) | Hämta objektets bredd i tum med den här intuitiva egenskapen. |
| [getHeightF()](#getHeightF--) | Hämta objektets höjd, mätt i tum, enkelt med den här användarvänliga egenskapen. |
| [getDocument()](#getDocument--) | Hämta CMX-dokumentet enkelt med den här intuitiva egenskapen. |
| [getCmxPage()](#getCmxPage--) | Hämta CMX-sidan för bilden enkelt med den här intuitiva egenskapen. |
| [getPageCount()](#getPageCount--) | Hämta bildens totala sidantal med den här intuitiva egenskapen. |
| [getPages()](#getPages--) | Hämta bildens sidor sömlöst med den här intuitiva egenskapen. |
| [cacheData()](#cacheData--) | Cacha data för att förhindra ytterligare inläsning från den underliggande källan [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) med den här praktiska metoden. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Anpassa bildens färgpalett med den här intuitiva metoden. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en CMX-fil.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Detta anrop cachelagrar endast standardsidan.
    image.cacheData();

    // Cachelagra alla sidor så att ingen ytterligare dataladdning utförs från den underliggande dataströmmen.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Börja arbeta med klassen [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) sömlöst genom att initiera en ny instans med parametrarna streamContainer och loadOptions. Idealiskt för utvecklare som söker ett bekvämt sätt att ladda CMX-bilder från olika datakällor samtidigt som de anpassar inläsningsprocessen efter behov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta bildens filformat enkelt med den här användarvänliga egenskapen. Idealiskt för utvecklare som vill bestämma formatet på sina bilder dynamiskt, vilket säkerställer kompatibilitet och korrekt bearbetning i deras applikationer.

**Returns:**
long - Filformatet [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämta bildens bitdjup enkelt med den här användarvänliga egenskapen. Idealiskt för utvecklare som vill bestämma detaljnivån eller färgdjupet i sina bilder, vilket säkerställer korrekt bearbetning och manipulation.

**Returns:**
int - Bildens bitar per pixel-antal.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Hämta bildens standardsida enkelt med den här intuitiva egenskapen. Idealiskt för utvecklare som vill ha snabb åtkomst till bildens huvudsida, vilket säkerställer effektiv navigering och hantering.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Bestäm om objektets data för närvarande är cachad, vilket eliminerar behovet av att läsa data. Idealiskt för utvecklare som vill optimera prestanda genom att utnyttja cachad data effektivt, vilket säkerställer snabbare åtkomst till objektinformation.

**Returns:**
boolean - `true` om objektets data är cachade; annars `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Hämta objektets bredd i tum med den här intuitiva egenskapen. Idealiskt för utvecklare som söker precisa mått på objekt i sina applikationer, vilket säkerställer korrekt layout och presentation.

**Returns:**
float - Objektets bredd, i tum.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Hämta objektets höjd, mätt i tum, enkelt med den här användarvänliga egenskapen. Idealiskt för utvecklare som söker exakt dimensionell information för effektiv layout och presentation i sina applikationer.

**Returns:**
float - Objektets höjd, i tum.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Hämta CMX-dokumentet enkelt med den här intuitiva egenskapen. Idealiskt för utvecklare som vill komma åt eller modifiera CMX-bilder, vilket säkerställer flexibilitet och effektivitet i deras applikationer.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Hämta CMX-sidan för bilden enkelt med den här intuitiva egenskapen. Idealiskt för utvecklare som vill ha snabb åtkomst till enskilda sidor i CMX-bilder, vilket säkerställer effektiv navigering och hantering.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämta det totala sidantalet för bilden med den här intuitiva egenskapen. Idealisk för utvecklare som vill hantera flersidiga bilder dynamiskt, vilket säkerställer effektiv navigering och manipulation av bildinnehåll.

**Returns:**
int - sidantalet.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Hämta bildens sidor sömlöst med den här intuitiva egenskapen. Idealisk för utvecklare som vill komma åt och manipulera enskilda sidor i flersidiga bilder, vilket säkerställer effektiv navigering och bearbetning.

**Returns:**
com.aspose.imaging.Image[] - sidorna.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en CMX-fil.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Detta anrop cachelagrar endast standardsidan.
    image.cacheData();

    // Cachelagra alla sidor så att ingen ytterligare dataladdning utförs från den underliggande dataströmmen.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cacha data för att förhindra ytterligare inläsning från den underliggande källan [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) med den här praktiska metoden. Idealisk för utvecklare som vill optimera prestanda genom att förladda data, vilket säkerställer snabbare åtkomst och smidigare drift i deras applikationer.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en CMX-fil.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Detta anrop cachelagrar endast standardsidan.
    image.cacheData();

    // Cachelagra alla sidor så att ingen ytterligare dataladdning utförs från den underliggande dataströmmen.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
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

