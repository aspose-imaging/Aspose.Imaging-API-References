---
title: "EpsImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för Encapsulated PostScript EPS‑bildfilformatstöd erbjuder robusta möjligheter för att manipulera sammansättningar som består av text, grafik och bilder."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

API:et för stöd för Encapsulated PostScript (EPS) bildfilformat erbjuder robusta möjligheter att manipulera sammansättningar som består av text, grafik och bilder. Med funktioner såsom hantering av bitmap‑förhandsgranskningsbilder, vändning av orientering, hämtning av omgivningsruta för illustrationens gränser, storleksändring, rotering av bilder och tillägg av förhandsgranskningsbilder. Detta API säkerställer sömlös bearbetning och integration av EPS‑filer i olika applikationer med precision och mångsidighet.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Få åtkomst till antalet tillgängliga förhandsgranskningsbilder med lätthet. |
| [getPreviewImages()](#getPreviewImages--) | Hämta förhandsgranskningsbilderna som är associerade med din fil. |
| [getFileFormat()](#getFileFormat--) | Få åtkomst till bildfilens format med denna egenskap. |
| [getEpsType()](#getEpsType--) | Få åtkomst till och tolka undergruppsvärdet för din EPS‑bild, vilket effektiviserar ditt arbetsflöde och förbättrar kompatibiliteten över plattformar. |
| [hasRasterPreview()](#hasRasterPreview--) | Upptäck närvaron av en raster‑förhandsgranskning enkelt med denna egenskap. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Få åtkomst till bildens exakta bitdjup enkelt med denna egenskap. |
| [getWidthF()](#getWidthF--) | Hämta bildens bredd med denna praktiska egenskap. |
| [getHeightF()](#getHeightF--) | Få åtkomst till bildens höjd med hjälp av denna egenskap. |
| [isCached()](#isCached--) | Denna egenskap ger ett bekvämt sätt att kontrollera om objektets data för närvarande är cachad, vilket eliminerar behovet av ytterligare dataläsning. |
| [getPsStream()](#getPsStream--) | Hämtar strömmen som innehåller PostScript att köra. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Denna egenskap hämtar PostScript‑versionen som är associerad med [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen. |
| [getTitle()](#getTitle--) | Denna egenskap hämtar titeln som extraherats från EPS Document Structuring Conventions (DSC)-kommentarerna inbäddade i EPS‑filen. |
| [getCreator()](#getCreator--) | Denna egenskap erbjuder åtkomst till skaparinformationen som hämtas från EPS Document Structuring Conventions (DSC)-kommentarerna i EPS‑filen. |
| [getCreationDate()](#getCreationDate--) | Genom att hämta skapelsedatumet från EPS Document Structuring Conventions (DSC)-kommentarerna ger denna egenskap viktig metadata som indikerar EPS‑filens ursprung. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Genom att hämta skapelsedatumet från EPS Document Structuring Conventions (DSC)-kommentarerna ger denna egenskap viktig metadata som indikerar EPS‑filens ursprung. |
| [getBoundingBox()](#getBoundingBox--) | Genom att få åtkomst till den ursprungliga omgivningsrutan i enhetsoberoende punkter ger denna egenskap viktig geometrisk information om [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-dimensionerna. |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Denna egenskap returnerar den ursprungliga omgivningsrutan för [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen i pixlar, vilket ger viktig geometrisk data för exakt rendering och manipulation. |
| [cacheData()](#cacheData--) | Denna egenskap returnerar den ursprungliga omgivningsrutan för [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen i pixlar, vilket ger viktig geometrisk data för exakt rendering och manipulation. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Ger åtkomst till förhandsgranskningsbilderna som är kopplade till [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen, vilket möjliggör sömlös hämtning för inspektion eller användning i applikationer. |
| [getPreviewImage()](#getPreviewImage--) | Hämtar den befintliga förhandsgranskningsbilden i det angivna `format`et eller returnerar `` om ingen hittas. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Hämtar den befintliga förhandsgranskningsbilden i det angivna `format`et eller returnerar `` om ingen hittas. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Anpassa bildpaletter för att uppnå unika färgscheman och förbättra den visuella attraktionskraften. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// Läs in EPS-bild
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Ändra storlek på bilden med Mitchell kubisk interpolationsmetod
    image.resize(400, 400, ResizeType.Mitchell);

    // Exportera bild till PNG-format
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// Läs in EPS-bild
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Ställ in interpolationsläget
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Ställ in filtertypen
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Ställer in färgjämförelsesmetoden
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Ställ in färgkvantiseringmetoden
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Ändra storlek på bilden med avancerade inställningar för storleksändring
    image.resize(400, 400, resizeSettings);

    // Exportera bild till PNG-format
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Få åtkomst till antalet tillgängliga förhandsgranskningsbilder med lätthet. Denna egenskap låter dig enkelt hämta antalet förhandsgranskningsbilder som är associerade med din fil, vilket möjliggör effektiv hantering och navigering av dina bildförhandsgranskningar. Idealisk för att optimera ditt arbetsflöde och organisera dina bildresurser på ett effektivt sätt.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Hämta förhandsgranskningsbilderna som är associerade med din fil. Denna egenskap ger sömlös åtkomst till samlingen av förhandsgranskningsbilder, vilket låter dig effektivt bläddra bland dem och hantera dem efter behov. Idealisk för snabb förhandsgranskning och val av rätt bild för ditt projekt.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Få åtkomst till bildfilens format med denna egenskap. Hämta viktig information om formatet för din bildfil, vilket underlättar kompatibilitet och effektiv bearbetning. Idealisk för att identifiera formatet på dina bildfiler för sömlös integration i dina projekt.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Få åtkomst till och tolka subtypvärdet för din EPS-bild, vilket förenklar ditt arbetsflöde och förbättrar kompatibiliteten över plattformar. Perfekt för att optimera hämtning av EPS-subtyp i dina projekt med precision och effektivitet.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Upptäck närvaron av en rasterförhandsgranskning enkelt med denna egenskap. Få åtkomst till det booleska värdet som indikerar om [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen innehåller en rasterförhandsgranskning, vilket ger dina bildbehandlingsuppgifter klarhet och effektivitet. Perfekt för att förenkla arbetsflödesbeslut baserade på om rasterförhandsgranskningar finns eller saknas i EPS‑bilder.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Få enkel åtkomst till bildens exakta bitdjup med denna egenskap. Hämta antalet bitar per pixel, vilket ger viktig insikt i bildens färgdjup och hjälper till att optimera bearbetningsuppgifter. Perfekt för applikationer som kräver finmaskig kontroll över bildmanipulation och analys.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Hämta bildens bredd med denna praktiska egenskap. Skaffa bildens bredd enkelt, vilket underlättar exakta layoutberäkningar, skalningsoperationer och dimensionella uppgifter i din applikation. Perfekt för att säkerställa korrekt rendering och visning av bilder på olika plattformar och enheter.

**Returns:**
float - Bildens bredd i pixlar.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Få åtkomst till bildens höjd med denna egenskap. Skaffa bildens höjd enkelt, vilket möjliggör smidiga layoutjusteringar, beräkning av bildförhållanden och exakt rendering på olika skärmupplösningar och displaymiljöer.

**Returns:**
float - Bildens höjd i pixlar.
### isCached() {#isCached--}
```
public boolean isCached()
```


Denna egenskap ger ett bekvämt sätt att kontrollera om objektets data för närvarande är cachad, vilket eliminerar behovet av ytterligare dataläsning. Den erbjuder en snabb och effektiv metod för att avgöra om den nödvändiga informationen är tillgänglig, vilket optimerar prestanda och minskar resursbelastningen i dataintensiva operationer.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Hämtar strömmen som innehåller PostScript att köra.

**Returns:**
java.io.InputStream - strömmen som innehåller PostScript att köra.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Denna egenskap hämtar PostScript‑versionen som är associerad med [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen. Den ger insikt i den specifika PostScript‑språkversionen som används i EPS‑filen, vilket underlättar kompatibilitetsbedömning och möjliggör sömlös integration med PostScript‑kompatibla miljöer.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


Denna egenskap hämtar titeln som extraherats från EPS Document Structuring Conventions (DSC)-kommentarerna inbäddade i EPS‑filen. Den ger värdefull metadata om EPS‑filens innehåll, vilket underlättar dokumentorganisation och identifiering i kompatibla programvaruapplikationer.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Denna egenskap ger åtkomst till skaparinformationen som hämtas från EPS Document Structuring Conventions (DSC)-kommentarerna i EPS‑filen. Att förstå skapardetaljerna ger insikt i vilken programvara eller verktyg som användes för att skapa EPS‑filen, vilket underlättar kompatibilitetsbedömning över olika plattformar och applikationer.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Genom att hämta skapelsedatumet från EPS Document Structuring Conventions (DSC)-kommentarerna ger denna egenskap viktig metadata som visar EPS‑filens början. Genom att få åtkomst till denna information får användare insikt i filens ursprung och tidslinje, vilket förbättrar filhantering och organisation.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Genom att hämta skapelsedatumet från EPS Document Structuring Conventions (DSC)-kommentarerna ger denna egenskap viktig metadata som visar EPS‑filens början. Genom att få åtkomst till denna information får användare insikt i filens ursprung och tidslinje, vilket förbättrar filhantering och organisation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Genom att komma åt den ursprungliga begränsningsrutan i enhetsoberoende punkter ger denna egenskap viktig geometrisk information om [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-dimensionerna. Genom att hämta dessa data kan användare exakt bedöma bildens storlek och bildförhållande, vilket underlättar precis layout och positionering i olika applikationer.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Denna egenskap returnerar den ursprungliga begränsningsrutan för [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen i pixlar, vilket ger viktig geometrisk data för exakt rendering och manipulation. Med denna information kan användare säkerställa exakt placering och dimensionering av EPS‑bilder i sina projekt, vilket förbättrar den övergripande visuella presentationen och kvaliteten.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


Denna egenskap returnerar den ursprungliga begränsningsrutan för [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen i pixlar, vilket ger viktig geometrisk data för exakt rendering och manipulation. Med denna information kan användare säkerställa exakt placering och dimensionering av EPS‑bilder i sina projekt, vilket förbättrar den övergripande visuella presentationen och kvaliteten.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Kommer åt förhandsgranskningsbilderna som är kopplade till [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-instansen, vilket möjliggör sömlös hämtning för inspektion eller användning i applikationer. Denna metod ger bekväm åtkomst till förhandsgranskningsbilder, vilket förbättrar användarinteraktionen med bilddata.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - Förhandsgranskningsbilderna.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Hämtar den befintliga förhandsgranskningsbilden i det angivna `format`et eller returnerar `` om ingen hittas. Denna metod erbjuder flexibilitet vid åtkomst till förhandsgranskningsbilder anpassade till specifika format, vilket optimerar kompatibilitet och resursförvaltning i applikationer.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Hämtar den befintliga förhandsgranskningsbilden i det angivna `format`et eller returnerar `` om ingen hittas. Denna metod erbjuder flexibilitet vid åtkomst till förhandsgranskningsbilder anpassade till specifika format, vilket optimerar kompatibilitet och resursförvaltning i applikationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | long | EPS‑förhandsgranskningsbildformatet. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Anpassa bildpaletter för att skapa unika färgscheman och förbättra den visuella attraktionskraften. Skräddarsy färger för specifika effekter och optimera bildkvaliteten över olika plattformar och enheter med lätthet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

