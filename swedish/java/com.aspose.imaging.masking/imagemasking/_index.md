---
title: "ImageMasking"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tillhandahåller bildmaskeringsoperationer"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.masking/imagemasking/
---
**Inheritance:**
java.lang.Object
```
public class ImageMasking
```

Tillhandahåller bildmaskeringsoperationer
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageMasking(RasterImage sourceImage)](#ImageMasking-com.aspose.imaging.RasterImage-) | Initierar en ny instans av klassen [ImageMasking](../../com.aspose.imaging.masking/imagematching). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyMask(RasterImage targetImage, RasterImage mask, MaskingOptions maskingOptions)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.RasterImage-com.aspose.imaging.masking.options.MaskingOptions-) | Applicerar masken på den angivna källbilden. |
| [decompose(MaskingOptions options)](#decompose-com.aspose.imaging.masking.options.MaskingOptions-) | Utför dekomponeringsoperationen med angivna maskeringsalternativ |
| [decomposeAsync(MaskingOptions options)](#decomposeAsync-com.aspose.imaging.masking.options.MaskingOptions-) | Skapar den asynkrona dekomponeringsuppgiften med angivna maskeringsalternativ. |
| [createSession(MaskingOptions options)](#createSession-com.aspose.imaging.masking.options.MaskingOptions-) | Skapar maskeringssessionen som kan utföra återträningsdekomponeringsoperationer. |
| [loadSession(InputStream stream)](#loadSession-java.io.InputStream-) | Läs in sessionen från den angivna strömmen. |
| [loadSession(System.IO.Stream stream)](#loadSession-com.aspose.ms.System.IO.Stream-) |  |
| [loadSession(String filePath)](#loadSession-java.lang.String-) | Läs in sessionen från den angivna filen. |

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

### ImageMasking(RasterImage sourceImage) {#ImageMasking-com.aspose.imaging.RasterImage-}
```
public ImageMasking(RasterImage sourceImage)
```


Initierar en ny instans av klassen [ImageMasking](../../com.aspose.imaging.masking/imagematching).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Källbilden. |


**Example: Using a segment mask to speed up the segmentation process**

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

### applyMask(RasterImage targetImage, RasterImage mask, MaskingOptions maskingOptions) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.RasterImage-com.aspose.imaging.masking.options.MaskingOptions-}
```
public static void applyMask(RasterImage targetImage, RasterImage mask, MaskingOptions maskingOptions)
```


Applicerar masken på den angivna källbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Målbilden. |
| mask | [RasterImage](../../com.aspose.imaging/rasterimage) | Maskbilden att tillämpa. |
| maskingOptions | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Maskeringsalternativen. |


**Example: Using a segment mask to speed up the segmentation process**

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

### decompose(MaskingOptions options) {#decompose-com.aspose.imaging.masking.options.MaskingOptions-}
```
public final MaskingResult decompose(MaskingOptions options)
```


Utför dekomponeringsoperationen med angivna maskeringsalternativ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Maskeringsalternativen. |

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

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


**Example: Using a segment mask to speed up the segmentation process**

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

### decomposeAsync(MaskingOptions options) {#decomposeAsync-com.aspose.imaging.masking.options.MaskingOptions-}
```
public final IMaskingAsyncTask decomposeAsync(MaskingOptions options)
```


Skapar den asynkrona dekomponeringsuppgiften med angivna maskeringsalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Maskeringsalternativen. |

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### createSession(MaskingOptions options) {#createSession-com.aspose.imaging.masking.options.MaskingOptions-}
```
public final IMaskingSession createSession(MaskingOptions options)
```


Skapar maskeringssessionen som kan utföra återträningsdekomponeringsoperationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Alternativen. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

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

### loadSession(InputStream stream) {#loadSession-java.io.InputStream-}
```
public final IMaskingSession loadSession(InputStream stream)
```


Läs in sessionen från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.
### loadSession(System.IO.Stream stream) {#loadSession-com.aspose.ms.System.IO.Stream-}
```
public final IMaskingSession loadSession(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession)
### loadSession(String filePath) {#loadSession-java.lang.String-}
```
public final IMaskingSession loadSession(String filePath)
```


Läs in sessionen från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.
