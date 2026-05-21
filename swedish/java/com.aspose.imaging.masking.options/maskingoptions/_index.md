---
title: "MaskingOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar de vanliga bildmaskeringsalternativen."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.masking.options/maskingoptions/
---
**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Representerar de vanliga bildmaskeringsalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Bakgrundsobjektets nummer |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMethod()](#getMethod--) | Hämtar segmenteringsmetoden. |
| [setMethod(int value)](#setMethod-int-) | Ställer in segmenteringsmetoden. |
| [getArgs()](#getArgs--) | Hämtar argumenten för segmenteringsalgoritmen. |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-) | Ställer in argumenten för segmenteringsalgoritmen. |
| [getExportOptions()](#getExportOptions--) | Hämtar bildexportalternativen. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.imaging.ImageOptionsBase-) | Ställer in bildexportalternativen. |
| [getMaskingArea()](#getMaskingArea--) | Hämtar maskeringsområdet. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.imaging.Rectangle-) | Ställer in maskeringsområdet. |
| [getDecompose()](#getDecompose--) | Hämtar ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Ställer in ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Hämtar bakgrundens ersättningsfärg. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.imaging.Color-) | Ställer in bakgrundens ersättningsfärg. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
Det här exemplet visar hur man dekomponerar en rasterbild till flera bilder med hjälp av bildmaskering och K-means-segmenteringsalgoritmen. Bildmaskering är en bildbehandlingsteknik som används för att separera bakgrunden från förgrundens bildobjekt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Ange antalet kluster (separerade objekt). Standardvärdet är 2, förgrundsobjektet och bakgrunden.
    args.setNumberOfObjects(3);

    // Ange det maximala antalet iterationer.
    args.setMaxIterationNumber(50);

    // Ange precisionen för segmenteringsmetoden (valfritt)
    args.setPrecision(1);

    // Varje kluster (segment) kommer att sparas i en separat PNG-fil.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Använd K-means-klustring.
    // K-means-klustring möjliggör att dela upp bilden i flera oberoende kluster (segment).
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // Bakgrundsfärgen blir orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Hämta bilder från maskeringsresultatet och spara dem som PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            final IMaskingLayer resultsItem = maskingResults.get_Item(i);
            String outputFileName = String.format("Blue hills.Segment%s.png", resultsItem.getObjectNumber());
            Image resultImage = resultsItem.getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
Det här exemplet visar hur man specificerar förslag för bildmaskeringsalgoritmen för att förbättra precisionen i segmenterings- (klustrings)metoden. Bildmaskering är en bildbehandlingsteknik som används för att separera bakgrunden från förgrundens bildobjekt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Förslag #1.
    // Analysera bilden visuellt och ange intresseområdet. Resultatet av segmenteringen kommer endast att inkludera objekt som är helt placerade inom detta område.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Förslag #2.
    // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Varje kluster (segment) kommer att sparas i en separat PNG-fil.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Använd GraphCut‑klustring.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Bakgrundsfärgen kommer att vara orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Hämta bilder från maskeringsresultatet och spara dem som PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: Using a segment mask to speed up the segmentation process

``` java
// Maskerings‑exportalternativ
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Använd GraphCut‑klustring.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Bakgrundsfärgen kommer att vara transparent.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Minska bildstorleken för att påskynda segmenteringsprocessen
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Hämtar förgrundsmasken
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Öka maskens storlek till den ursprungliga bildens storlek
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applicera masken på den ursprungliga bilden för att få ett förgrundssegment
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Maskerings‑exportalternativ
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Använd GraphCut‑klustring.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Bakgrundsfärgen kommer att vara orange.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Startar en session för första gången och sparar till en fil
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Återupptar en maskeringssession från en fil
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Explicit överföring av exportalternativ, eftersom den inte är serialiserbar
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Bakgrundsobjektets nummer

### getMethod() {#getMethod--}
```
public final int getMethod()
```


Hämtar segmenteringsmetoden.

Värde: Segmenteringsmetoden.

**Returns:**
int - segmenteringsmetoden.
### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Ställer in segmenteringsmetoden.

Värde: Segmenteringsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | segmenteringsmetoden. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
Det här exemplet visar hur man specificerar förslag för bildmaskeringsalgoritmen för att förbättra precisionen i segmenterings- (klustrings)metoden. Bildmaskering är en bildbehandlingsteknik som används för att separera bakgrunden från förgrundens bildobjekt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Förslag #1.
    // Analysera bilden visuellt och ange intresseområdet. Resultatet av segmenteringen kommer endast att inkludera objekt som är helt placerade inom detta område.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Förslag #2.
    // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Varje kluster (segment) kommer att sparas i en separat PNG-fil.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Använd GraphCut‑klustring.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Bakgrundsfärgen kommer att vara orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Hämta bilder från maskeringsresultatet och spara dem som PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Hämtar argumenten för segmenteringsalgoritmen.

Värde: Argumenten för segmenteringsalgoritmen.

**Returns:**
[IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### setArgs(IMaskingArgs value) {#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Ställer in argumenten för segmenteringsalgoritmen.

Värde: Argumenten för segmenteringsalgoritmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | argumenten för segmenteringsalgoritmen. |

### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Hämtar bildexportalternativen.

Värde: Bildexportalternativen som kommer att användas för att skapa de resulterande bilderna.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - the image export options.
### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.imaging.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Ställer in bildexportalternativen.

Värde: Bildexportalternativen som kommer att användas för att skapa de resulterande bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | bildexportalternativen. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
Det här exemplet visar hur man specificerar förslag för bildmaskeringsalgoritmen för att förbättra precisionen i segmenterings- (klustrings)metoden. Bildmaskering är en bildbehandlingsteknik som används för att separera bakgrunden från förgrundens bildobjekt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Förslag #1.
    // Analysera bilden visuellt och ange intresseområdet. Resultatet av segmenteringen kommer endast att inkludera objekt som är helt placerade inom detta område.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Förslag #2.
    // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Varje kluster (segment) kommer att sparas i en separat PNG-fil.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Använd GraphCut‑klustring.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Bakgrundsfärgen kommer att vara orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Hämta bilder från maskeringsresultatet och spara dem som PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```

### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Hämtar maskeringsområdet.

Värde: Maskeringsområdet som är ett delområde av källbilden. Rectangle.Empty-värdet betyder hela källbildens område.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the masking area.
### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.imaging.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Ställer in maskeringsområdet.

Värde: Maskeringsområdet som är ett delområde av källbilden. Rectangle.Empty-värdet betyder hela källbildens område.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | maskeringsområdet. |

### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Hämtar ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.

Värde: `true` om dekomponeras; annars `false`.

**Returns:**
boolean - ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.
### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Ställer in ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.

Värde: `true` om dekomponeras; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |

### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Hämtar bakgrundens ersättningsfärg.

Värde: Bakgrundsersättningsfärgen. Denna färg kommer att användas som bakgrundsfärg i de resulterande bilderna.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background replacement color.
### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.imaging.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Ställer in bakgrundens ersättningsfärg.

Värde: Bakgrundsersättningsfärgen. Denna färg kommer att användas som bakgrundsfärg i de resulterande bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | bakgrundsersättningsfärgen. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
Det här exemplet visar hur man specificerar förslag för bildmaskeringsalgoritmen för att förbättra precisionen i segmenterings- (klustrings)metoden. Bildmaskering är en bildbehandlingsteknik som används för att separera bakgrunden från förgrundens bildobjekt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Förslag #1.
    // Analysera bilden visuellt och ange intresseområdet. Resultatet av segmenteringen kommer endast att inkludera objekt som är helt placerade inom detta område.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Förslag #2.
    // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Varje kluster (segment) kommer att sparas i en separat PNG-fil.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Använd GraphCut‑klustring.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Bakgrundsfärgen kommer att vara orange.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Hämta bilder från maskeringsresultatet och spara dem som PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```

