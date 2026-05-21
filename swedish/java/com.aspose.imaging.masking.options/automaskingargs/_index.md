---
title: "AutoMaskingArgs"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar argumenten som specificeras för automatiserade maskeringsmetoder"
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Representerar argumenten som specificeras för automatiserade maskeringsmetoder
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | Hämtar antalet objekt att separera den ursprungliga bilden till (valfritt), standardvärdet är 2 (objekt och bakgrund). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Ställer in antalet objekt att separera den ursprungliga bilden till (valfritt), standardvärdet är 2 (objekt och bakgrund). |
| [getObjectsRectangles()](#getObjectsRectangles--) | Hämtar rektanglarna för objekten som tillhör separerade objekt (valfritt). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | Ställer in rektanglarna för objekten som tillhör separerade objekt (valfritt). |
| [getObjectsPoints()](#getObjectsPoints--) | Hämtar punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | Ställer in punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. |
| [getOrphanedPoints()](#getOrphanedPoints--) | Hämtar punkterna som inte längre tillhör något objekt (valfritt). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | Ställer in punkterna som inte längre tillhör något objekt (valfritt). |
| [getPrecision()](#getPrecision--) | Hämtar precisionen för segmenteringsmetoden (valfritt). |
| [setPrecision(double value)](#setPrecision-double-) | Ställer in precisionen för segmenteringsmetoden (valfritt). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Hämtar det maximala antalet iterationer. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Ställer in det maximala antalet iterationer. |

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

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Hämtar antalet objekt att separera den ursprungliga bilden till (valfritt), standardvärdet är 2 (objekt och bakgrund).

Värde: Antalet objekt.

**Returns:**
int - antalet objekt att separera den ursprungliga bilden till (valfritt), standardvärdet är 2 (objekt och bakgrund).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Ställer in antalet objekt att separera den ursprungliga bilden till (valfritt), standardvärdet är 2 (objekt och bakgrund).

Värde: Antalet objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | antalet objekt att separera den ursprungliga bilden till (valfritt), standardvärdet är 2 (objekt och bakgrund). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Hämtar rektanglarna för objekten som tillhör separerade objekt (valfritt). Denna parameter används för att öka precisionen för segmenteringsmetoden.

Värde: Objektens rektanglar.

**Returns:**
com.aspose.imaging.Rectangle[] - objektens rektanglar som tillhör separerade objekt (valfritt).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Ställer in rektanglarna för objekten som tillhör separerade objekt (valfritt). Denna parameter används för att öka precisionen för segmenteringsmetoden.

Värde: Objektens rektanglar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | objektens rektanglar som tillhör separerade objekt (valfritt). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Hämtar punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. Denna parameter används för att öka precisionen för segmenteringsmetoden.

Värde: Objektens punkter.

**Returns:**
com.aspose.imaging.Point[][] - punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Ställer in punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. Denna parameter används för att öka segmenteringsmetodens precision.

Värde: Objektens punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Hämtar punkterna som inte längre tillhör något objekt (valfritt). Denna parameter används endast vid omsegmentering.

Värde: De föräldralösa punkterna.

**Returns:**
com.aspose.imaging.Point[] - punkterna som inte längre tillhör något objekt (valfritt).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Ställer in punkterna som inte längre tillhör något objekt (valfritt). Denna parameter används endast vid omsegmentering.

Värde: De föräldralösa punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | punkterna som inte längre tillhör något objekt (valfritt). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Hämtar precisionen för segmenteringsmetoden (valfritt).

Värde: Precisionen för segmenteringsmetoden (valfritt).

**Returns:**
double - precisionen för segmenteringsmetoden (valfritt).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Ställer in precisionen för segmenteringsmetoden (valfritt).

Värde: Precisionen för segmenteringsmetoden (valfritt).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | precisionen för segmenteringsmetoden (valfritt). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Hämtar det maximala antalet iterationer.

Värde: Det maximala maximala antalet iterationer.

**Returns:**
int - det maximala antalet iterationer.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Ställer in det maximala antalet iterationer.

Värde: Det maximala maximala antalet iterationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | det maximala antalet iterationer. |

