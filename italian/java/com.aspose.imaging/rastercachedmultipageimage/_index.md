---
title: "RasterCachedMultipageImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'immagine raster multipagina"
type: docs
weight: 90
url: /it/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

L'immagine raster multipagina
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine. |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [isCached()](#isCached--) | Restituisce un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [hasAlpha()](#hasAlpha--) | Ottiene un valore che indica se questa istanza ha alfa. |
| [hasTransparentColor()](#hasTransparentColor--) | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| [getImageOpacity()](#getImageOpacity--) | Ottiene l'opacità di questa immagine. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene un valore per il colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Imposta un valore per il colore di sfondo. |
| [getMetadata()](#getMetadata--) | Ottiene i dati XMP dal fotogramma. |
| [getPageExportingAction()](#getPageExportingAction--) | Restituisce l'azione di esportazione della pagina. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Imposta l'azione di esportazione della pagina. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la `brightness` dell'immagine. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) contrastante |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correzione gamma di un'immagine. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correzione gamma di un'immagine. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mescola questa istanza di immagine con l'immagine `overlay`. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Incorpora la firma digitale basata sulla password fornita in ogni pagina dell'immagine. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcola la percentuale di somiglianza tra i dati estratti e la password originale. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarizzazione di un'immagine con soglia predefinita |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale |
| [binarizeOtsu()](#binarizeOtsu--) | Binarizzazione di un'immagine con soglia di Otsu |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia l'immagine. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Ritaglia l'immagine con spostamenti. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Esegue il dithering sull'immagine corrente. |
| [grayscale()](#grayscale--) | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [normalizeHistogram()](#normalizeHistogram--) | Normalizza l'istogramma dell'immagine \\u2014 regola i valori dei pixel per utilizzare l'intera gamma disponibile. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` l'immagine attorno al centro. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Ruota, capovolge o ruota e capovolge tutte le pagine. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | Ruota e capovolge tutto. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona l'immagine. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ridimensiona la larghezza proporzionalmente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ridimensiona la larghezza proporzionalmente. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtra il rettangolo specificato. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normalizza l'angolo. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati in modo privato. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//È implementata la possibilità di conversione batch prima del salvataggio (esportazione) delle immagini Tiff.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // Imposta l'operazione batch per le pagine
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // Avvia la raccolta dei rifiuti per evitare l'archiviazione inutile di dati residui dalle pagine precedenti.
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


Restituisce l'altezza dell'immagine.

Valore: l'altezza dell'immagine.

**Returns:**
int - l'altezza dell'immagine.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza dell'immagine.

Valore: la larghezza dell'immagine.

**Returns:**
int - la larghezza dell'immagine.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

Valore: il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - il conteggio dei bit per pixel dell'immagine.
### isCached() {#isCached--}
```
public boolean isCached()
```


Restituisce un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache.

Valore: `true` se i dati dell'immagine sono nella cache; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se i dati dell'immagine sono attualmente nella cache.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Ottiene un valore che indica se questa istanza ha alfa.

Valore: `true` se questa istanza ha alfa; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questa istanza ha alfa.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Ottiene un valore che indica se l'immagine ha un colore trasparente.

--------------------

Questa implementazione verifica il valore `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) della `DefaultPage`(\#getDefaultPage\_internalized.getDefaultPage\_internalized).

**Returns:**
boolean - un valore che indica se l'immagine ha un colore trasparente.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Ottiene l'opacità di questa immagine.

Valore: il valore di opacità compreso tra 0.0 (completamente trasparente) e 1.0 (completamente opaco).

**Returns:**
float - opacità di questa immagine.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ottiene un valore per il colore di sfondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Imposta un valore per il colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un valore per il colore di sfondo. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Ottiene i dati XMP dal fotogramma.

Valore: wrapper dei dati del pacchetto XMP

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Restituisce l'azione di esportazione della pagina. Si noti che l'impostazione di questo metodo rilascerà automaticamente le risorse della pagina dopo la sua esecuzione. Verrà eseguito subito prima del salvataggio di ogni pagina.

Valore: l'azione di esportazione della pagina.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Imposta l'azione di esportazione della pagina. Si noti che l'impostazione di questo metodo rilascerà automaticamente le risorse della pagina dopo la sua esecuzione. Verrà eseguito subito prima del salvataggio di ogni pagina.

Valore: l'azione di esportazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | l'azione di esportazione della pagina. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Regola la `brightness` dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Mescola questa istanza di immagine con l'immagine `overlay`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine di sovrapposizione. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di sovrapposizione. |
| overlayAlpha | byte | L'alpha di sovrapposizione. |

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Incorpora la firma digitale basata sulla password fornita in ogni pagina dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password utilizzata per generare i dati della firma digitale |


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


Calcola la percentuale di somiglianza tra i dati estratti e la password originale.

--------------------

A causa delle immagini multipagina, il risultato rappresenta la `MIDDLE AVERAGED signing percentage` calcolata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password utilizzata per estrarre i dati incorporati. |

**Returns:**
int - Il valore di percentuale di somiglianza.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password per verificare la firma. |
|  | percentageThreshold | int | La soglia (in percentuale)[0-100] che determina se l'immagine è considerata firmata. Se non specificata, verrà applicata una soglia predefinita (`75`). |

--------------------

Questo metodo fornisce la rilevazione più veloce sfruttando `GetSignPercentage`. Una volta che i dati estratti raggiungono la soglia specificata, i passaggi di estrazione successivi volti a migliorare la precisione della rilevazione vengono saltati.

Il risultato è `true` solo se tutte le pagine dell'immagine multipagina sono riconosciute come firmate; altrimenti, l'immagine è considerata non firmata. |

**Returns:**
boolean - True se l'immagine è firmata, altrimenti false.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarizzazione di un'immagine con soglia predefinita

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato il valore 255, altrimenti 0. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel. |

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarizzazione di un'immagine con soglia di Otsu

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Ritaglia l'immagine con spostamenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | int | Lo spostamento sinistro. |
| rightShift | int | Lo spostamento destro. |
| topShift | int | Lo spostamento superiore. |
| bottomShift | int | Lo spostamento inferiore. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Esegue il dithering sull'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Trasformazione di un'immagine nella sua rappresentazione in scala di grigi

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normalizza l'istogramma dell'immagine \\u2014 regola i valori dei pixel per utilizzare l'intera gamma disponibile.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` l'immagine attorno al centro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | Se impostato su `true` la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Ruota, capovolge o ruota e capovolge tutte le pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


Ruota e capovolge tutto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlip | int | Il ribaltamento di rotazione. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ridimensiona l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ridimensiona la larghezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| resizeType | int | Tipo di ridimensionamento. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ridimensiona la larghezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |
| resizeType | int | Tipo di ridimensionamento. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldColorArgb | int | Valore ARGB del colore vecchio da sostituire. |
| oldColorDiff | byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| newColorArgb | int | Nuovo valore ARGB del colore da utilizzare per sostituire il colore vecchio. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Sostituisce tutti i colori non trasparenti con il nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorArgb | int | Nuovo valore ARGB del colore da utilizzare per sostituire i colori non trasparenti. |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtra il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) e [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) metodi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeProportionally | boolean | se impostato su `true` le dimensioni dell'immagine verranno modificate in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Memorizza nella cache i dati in modo privato.

