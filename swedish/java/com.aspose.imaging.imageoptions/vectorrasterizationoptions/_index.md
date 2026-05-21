---
title: "VectorRasterizationOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Vektor rasteriseringsalternativ."
type: docs
weight: 52
url: /sv/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

Vektor rasteriseringsalternativen. Observera att [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) inte längre ärver från [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) sedan version Aspose.Imaging 24.12.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Hämtar utjämningsläget. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Ställer in utjämningsläget. |
| [getBorderX()](#getBorderX--) | Hämtar eller ställer in X-kanten. |
| [setBorderX(float value)](#setBorderX-float-) | Hämtar eller ställer in X-kanten. |
| [getBorderY()](#getBorderY--) | Hämtar eller ställer in Y-kanten. |
| [setBorderY(float value)](#setBorderY-float-) | Hämtar eller ställer in Y-kanten. |
| [getCenterDrawing()](#getCenterDrawing--) | Hämtar ett värde som indikerar om centrering av ritning. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Anger ett värde som visar om centrerad ritning. |
| [getPageHeight()](#getPageHeight--) | Hämtar sidans höjd. |
| [setPageHeight(float value)](#setPageHeight-float-) | Anger sidans höjd. |
| [getPageSize()](#getPageSize--) | Hämtar sidstorleken. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Anger sidstorleken. |
| [getPageWidth()](#getPageWidth--) | Hämtar sidans bredd. |
| [setPageWidth(float value)](#setPageWidth-float-) | Anger sidans bredd. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar en bakgrundsfärg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Anger en bakgrundsfärg. |
| [getDrawColor()](#getDrawColor--) | Hämtar en förgrundsfärg. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Anger en förgrundsfärg. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Hämtar tipset för textrendering. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Anger tipset för textrendering. |
| [getPositioning()](#getPositioning--) | Hämtar positioneringen. |
| [setPositioning(int value)](#setPositioning-int-) | Anger positioneringen. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Hämtar textersättningsmappning. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Anger textersättningsmappning. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopierar den här instansen till `vectorRasterizationOptions`. |
| [deepClone()](#deepClone--) | Skapar en ytlig klon av objektet. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Hämtar utjämningsläget.

**Returns:**
int - jämningsläget.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Ställer in utjämningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | jämningsläget. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att läsa in en bild.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // För att rasterisera SVG måste vi specificera rasteriseringsalternativ.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Ange standardfärg för en bakgrund till en bild. Standardvärdet är vitt.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Ange sidstorleken
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing tillämpas på linjer och kurvor samt kanterna på fyllda områden.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Varje tecken ritas med sin antialiasade glyf-bitmap utan hintning.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Minska bildstorleken 10 gånger, dvs. utdatastorleken blir 10 % av originalstorleken.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Spara till en PNG-fil
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Hämtar eller ställer in X-kanten.

**Returns:**
float - Kanten X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Hämtar eller ställer in X-kanten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Kanten X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Hämtar eller ställer in Y-kanten.

**Returns:**
float - Kanten Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Hämtar eller ställer in Y-kanten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Kanten Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Hämtar ett värde som indikerar om centrering av ritning.

**Returns:**
boolean - ett värde som visar om centrerad ritning.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Anger ett värde som visar om centrerad ritning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om centrering av ritning. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Hämtar sidans höjd.

**Returns:**
float - sidans höjd.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Anger sidans höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | sidans höjd. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Hämtar sidstorleken.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Anger sidstorleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | sidans storlek. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

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


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

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

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Hämtar sidans bredd.

**Returns:**
float - sidans bredd.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Anger sidans bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | sidans bredd. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar en bakgrundsfärg.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Anger en bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | en bakgrundsfärg. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

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


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

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

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Hämtar en förgrundsfärg.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Anger en förgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | en förgrundsfärg. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Hämtar tipset för textrendering.

Värde: Textåtergivningstipset.

**Returns:**
int - hint för textåtergivning.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Anger tipset för textrendering.

Värde: Textåtergivningstipset.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | hint för textåtergivning. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att läsa in en bild.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // För att rasterisera SVG måste vi specificera rasteriseringsalternativ.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Ange standardfärg för en bakgrund till en bild. Standardvärdet är vitt.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Ange sidstorleken
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing tillämpas på linjer och kurvor samt kanterna på fyllda områden.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Varje tecken ritas med sin antialiasade glyf-bitmap utan hintning.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Minska bildstorleken 10 gånger, dvs. utdatastorleken blir 10 % av originalstorleken.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Spara till en PNG-fil
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Hämtar positioneringen.

Värde: Positioneringen.

**Returns:**
int - positioneringen.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Anger positioneringen.

Värde: Positioneringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | positioneringen. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Hämtar textersättningsmappning.

Värde: Textersättningsmappning.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - textersättningsmappning.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Anger textersättningsmappning.

Värde: Textersättningsmappning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.HashMap<java.lang.String,java.lang.String> | textersättningsmappning. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Kopierar den här instansen till `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Vektor rasteriseringsalternativ. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


Skapar en ytlig klon av objektet.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
