---
title: "SvgRasterizationOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "SVG-rasteriseringsalternativen."
type: docs
weight: 46
url: /sv/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

SVG-rasteriseringsalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | Initierar en ny instans av klassen `SvgRasterizationOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getScaleX()](#getScaleX--) | Hämtar eller anger skalan x. |
| [setScaleX(float value)](#setScaleX-float-) | Hämtar eller anger skalan x. |
| [getScaleY()](#getScaleY--) | Hämtar eller anger skalan y. |
| [setScaleY(float value)](#setScaleY-float-) | Hämtar eller anger skalan y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopierar den här instansen till `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


Initierar en ny instans av klassen `SvgRasterizationOptions`.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Hämtar eller anger skalan x.

**Returns:**
float - Skalan x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Hämtar eller anger skalan x.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Skalan x. |


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

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Hämtar eller anger skalan y.

**Returns:**
float - Skalan y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Hämtar eller anger skalan y.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Skalan y. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Kopierar den här instansen till `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Vektor rasteriseringsalternativ. |

