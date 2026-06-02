---
title: "RasterCachedMultipageImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den rasterbaserade flersidiga bilden."
type: docs
weight: 90
url: /sv/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

Den rasterbaserade flersidiga bilden.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| [hasAlpha()](#hasAlpha--) | Hämtar ett värde som indikerar om detta objekt har alfa. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om bilden har en transparent färg. |
| [getImageOpacity()](#getImageOpacity--) | Hämtar opaciteten för den här bilden. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar ett värde för bakgrundsfärgen. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Ställer in ett värde för bakgrundsfärgen. |
| [getMetadata()](#getMetadata--) | Hämtar XMP-data från ramen. |
| [getPageExportingAction()](#getPageExportingAction--) | Hämtar sidexportåtgärden. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Ställer in sidexportåtgärden. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Justering av en `brightness` för bilden. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) kontrasterande |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-korrigering av en bild. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-korrigering av en bild. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Blandar denna bildinstans med `overlay`-bilden. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskeln. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisering av en bild med fördefinierad tröskel |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisering av en bild med Otsu-tröskling |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär bilden. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Beskär bilden med förskjutningar. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Utför dithering på den aktuella bilden. |
| [grayscale()](#grayscale--) | Transformation av en bild till dess gråskale-representation |
| [normalizeHistogram()](#normalizeHistogram--) | Normaliserar bildens histogram \\u2014 justera pixelvärden för att använda hela tillgängliga intervallet. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` bild runt centrum. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roterar, vänder eller roterar och vänder alla sidor. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | Roterar vänd alla. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar storlek på bilden. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändrar bredden proportionellt. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändrar bredden proportionellt. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtrerar den angivna rektangeln. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normaliserar vinkeln. |
| [cacheData()](#cacheData--) | Cachar data privat. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//Möjligheten till batchkonvertering innan sparande (export) av Tiff‑bilder har implementerats.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // Ställ in batch‑operation för sidor
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // Startar skräpsamling för att undvika onödig skräpslagring från tidigare sidor.
            System.gc();

            ((com.aspose.imaging.RasterImage) page).rotate(90);
        }
    });

    tiffImage.save(outputFileNameTif);

    /* Attention! In batch mode all pages will be released in this line!
     If you want to further perform operations on the original image, you should reload it from the source to another instance. */
}
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

Värde: Bildens höjd.

**Returns:**
int - bildens höjd.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

Värde: Bildens bredd.

**Returns:**
int - bildens bredd.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

Värde: Bildens bitar per pixel-antal.

**Returns:**
int - bildens bitar per pixel-antal.
### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett värde som indikerar om bilddata för närvarande är cachad.

Värde: `true` om bilddata är cachad; annars `false`.

**Returns:**
boolean – ett värde som indikerar om bilddata för närvarande är cachad.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämtar ett värde som indikerar om detta objekt har alfa.

Värde: `true` om detta objekt har alfa; annars `false`.

**Returns:**
boolean – ett värde som indikerar om detta objekt har alfa.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om bilden har en transparent färg.

--------------------

Denna implementation kontrollerar värdet för `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) för `DefaultPage`(\#getDefaultPage\_internalized.getDefaultPage\_internalized).

**Returns:**
boolean – ett värde som indikerar om bilden har en transparent färg.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Hämtar opaciteten för den här bilden.

Värde: Opacitetsvärdet mellan 0.0 (helt transparent) och 1.0 (helt ogenomskinlig).

**Returns:**
float - opaciteten för den här bilden.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar ett värde för bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Ställer in ett värde för bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | ett värde för bakgrundsfärgen. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Hämtar XMP-data från ramen.

Värde: XMP-paketdataomslag

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Hämtar sidexportåtgärden. Observera att inställning av denna metod automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas.

Värde: Sidexportåtgärden.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Ställer in sidexportåtgärden. Observera att inställning av denna metod automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas.

Värde: Sidexportåtgärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | sidexportåtgärden. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Justering av en `brightness` för bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma-korrigering av en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanalkoefficient |
| gammaGreen | float | Gamma för grön kanalkoefficient |
| gammaBlue | float | Gamma för blå kanalens koefficient |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gamma-korrigering av en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalernas koefficient |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Blandar denna bildinstans med `overlay`-bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Bakgrundsbildens blandningsursprung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Överlagringsbilden. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Överlagringsområdet. |
| overlayAlpha | byte | Överlagringsalfa. |

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet som används för att generera digitala signaturdata |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet.

--------------------

På grund av flersidiga bilder representerar resultatet den beräknade `MIDDLE AVERAGED signing percentage`

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet som används för att extrahera den inbäddade datan. |

**Returns:**
int - Procentuell likhetsvärde.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet för att kontrollera signeringen. |
|  | percentageThreshold | int | Tröskelvärdet (i procent)[0-100] som avgör om bilden anses vara signerad. Om det inte anges, kommer ett standardtröskelvärde (`75`) att tillämpas. |

--------------------

Denna metod tillhandahåller den snabbaste detektionen genom att utnyttja `GetSignPercentage`. När den extraherade datan uppfyller det angivna tröskelvärdet, hoppar över ytterligare extraktionssteg som syftar till att förbättra detekteringsnoggrannheten.

Resultatet är `true` endast om alla sidor i den flersidiga bilden känns igen som signerade; annars betraktas bilden som osignerad. |

**Returns:**
boolean - Sant om bilden är signerad, annars falskt.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisering av en bild med fördefinierad tröskel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln tilldelas värdet 255, annars 0. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |
| windowSize | int | Storleken på ett s x s-fönster av pixlar centrerade kring denna pixel. |

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisering av en bild med Otsu-tröskling

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beskär bilden med förskjutningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | int | Den vänstra förskjutningen. |
| rightShift | int | Den högra förskjutningen. |
| topShift | int | Den övre förskjutningen. |
| bottomShift | int | Den nedre förskjutningen. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Utför dithering på den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den anpassade paletten för dithering. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation av en bild till dess gråskale-representation

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normaliserar bildens histogram \\u2014 justera pixelvärden för att använda hela tillgängliga intervallet.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` bild runt centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | Om den är inställd på `true` kommer bildens storlek att ändras enligt de roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna orörda och endast `` bildinnehållet roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder alla sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations-/vändningstypen. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


Roterar vänd alla.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlip | int | Rotationsvändning. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av storleksändring. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldColorArgb | int | Gammalt färg-ARGB-värde som ska ersättas. |
| oldColorDiff | byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| newColorArgb | int | Nytt färg-ARGB-värde att ersätta den gamla färgen med. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersätter alla icke‑transparenta färger med ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorArgb | int | Nytt färg-ARGB‑värde att ersätta icke‑transparenta färger med. |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtrerar den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Alternativen. |

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) och [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) metoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeProportionally | boolean | om den är inställd på `true` kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, i annat fall lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachar data privat.

