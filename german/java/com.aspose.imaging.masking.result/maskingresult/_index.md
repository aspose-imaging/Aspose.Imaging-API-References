---
title: "MaskingResult"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Abstrakte Basisklasse, die ein Ergebnisbild aus dem Bildmaskierungssystem bereitstellen kann."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.masking.result/maskingresult/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class MaskingResult extends DisposableObject implements Iterable<IMaskingLayer>
```

Abstrakte Basisklasse, die ein Ergebnisbild aus dem Bildmaskierungssystem bereitstellen kann.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MaskingOptions](#MaskingOptions) | Die Maskierungsoptionen |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLayers()](#getLayers--) | Gibt die Ebenen zurück. |
| [getLength()](#getLength--) | Gibt die Länge zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das [IMaskingLayer](../../com.aspose.imaging.masking.result/imatchinglayer) am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt den Enumerator zurück. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
Dieses Beispiel zeigt, wie ein Rasterbild mithilfe von Bildmaskierung und dem K-means-Segmentierungsalgorithmus in mehrere Bilder zerlegt wird. Bildmaskierung ist eine Bildverarbeitungstechnik, die verwendet wird, um den Hintergrund von den Vordergrund‑Bildobjekten zu trennen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Legen Sie die Anzahl der Cluster (getrennte Objekte) fest. Der Standardwert ist 2, das Vordergrundobjekt und der Hintergrund.
    args.setNumberOfObjects(3);

    // Legen Sie die maximale Anzahl an Iterationen fest.
    args.setMaxIterationNumber(50);

    // Legen Sie die Präzision der Segmentierungsmethode fest (optional)
    args.setPrecision(1);

    // Jeder Cluster (Segment) wird in einer separaten PNG‑Datei gespeichert.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Verwenden Sie K-means-Clustering.
    // K-means-Clustering ermöglicht es, das Bild in mehrere unabhängige Cluster (Segmente) zu teilen.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // Die Hintergrundfarbe wird orange sein.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente) auf.
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Erhalten Sie Bilder aus dem Maskierungsergebnis und speichern Sie sie als PNG.
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
Dieses Beispiel zeigt, wie Vorschläge für den Bildmaskierungsalgorithmus angegeben werden, um die Präzision der Segmentierungs‑ (Clustering‑)Methode zu verbessern. Bildmaskierung ist eine Bildverarbeitungstechnik, die verwendet wird, um den Hintergrund von den Vordergrund‑Bildobjekten zu trennen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Vorschlag #1.
    // Analysieren Sie das Bild visuell und legen Sie den Interessensbereich fest. Das Ergebnis der Segmentierung wird nur Objekte enthalten, die vollständig innerhalb dieses Bereichs liegen.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Vorschlag #2.
    // Analysiere das Bild visuell und setze die Punkte, die zu getrennten Objekten gehören.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Jeder Cluster (Segment) wird in einer separaten PNG‑Datei gespeichert.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Verwenden Sie GraphCut‑Clustering.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Die Hintergrundfarbe wird orange sein.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente) auf.
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Erhalten Sie Bilder aus dem Maskierungsergebnis und speichern Sie sie als PNG.
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
// Maskierungs‑Exportoptionen
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Verwenden Sie GraphCut‑Clustering.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Die Hintergrundfarbe wird transparent sein.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Reduzierung der Bildgröße zur Beschleunigung des Segmentierungsprozesses.
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente) auf.
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ermitteln der Vordergrundmaske.
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Vergrößern Sie die Größe der Maske auf die Größe des Originalbildes.
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Anwenden der Maske auf das Originalbild, um einen Vordergrundabschnitt zu erhalten.
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

// Maskierungs‑Exportoptionen
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Verwenden Sie GraphCut‑Clustering.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Die Hintergrundfarbe wird orange sein.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Starten einer Sitzung zum ersten Mal und Speichern in eine Datei
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Erstellen Sie eine Instanz der Klasse ImageMasking.
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

// Fortsetzen einer Maskierungssitzung aus einer Datei
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analysiere das Bild visuell und setze die Punkte, die zu getrennten Objekten gehören.
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
            // Explizite Übertragung der Exportoptionen, da sie nicht serialisierbar ist
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

### MaskingOptions {#MaskingOptions}
```
public final MaskingOptions MaskingOptions
```


Die Maskierungsoptionen

### getLayers() {#getLayers--}
```
public abstract IMaskingLayer[] getLayers()
```


Gibt die Ebenen zurück.

Wert: Die Ebenen.

**Returns:**
com.aspose.imaging.masking.result.IMatchingLayer[] - die Ebenen.
### getLength() {#getLength--}
```
public final int getLength()
```


Gibt die Länge zurück.

Wert: Die Länge.

**Returns:**
int - die Länge.

**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
Dieses Beispiel zeigt, wie Vorschläge für den Bildmaskierungsalgorithmus angegeben werden, um die Präzision der Segmentierungs‑ (Clustering‑)Methode zu verbessern. Bildmaskierung ist eine Bildverarbeitungstechnik, die verwendet wird, um den Hintergrund von den Vordergrund‑Bildobjekten zu trennen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Vorschlag #1.
    // Analysieren Sie das Bild visuell und legen Sie den Interessensbereich fest. Das Ergebnis der Segmentierung wird nur Objekte enthalten, die vollständig innerhalb dieses Bereichs liegen.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Vorschlag #2.
    // Analysiere das Bild visuell und setze die Punkte, die zu getrennten Objekten gehören.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Jeder Cluster (Segment) wird in einer separaten PNG‑Datei gespeichert.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Verwenden Sie GraphCut‑Clustering.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Die Hintergrundfarbe wird orange sein.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente) auf.
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Erhalten Sie Bilder aus dem Maskierungsergebnis und speichern Sie sie als PNG.
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

### get_Item(int index) {#get-Item-int-}
```
public final IMaskingLayer get_Item(int index)
```


Gibt das [IMaskingLayer](../../com.aspose.imaging.masking.result/imatchinglayer) am angegebenen Index zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index. Wert: Das [IMatchingLayer](../../com.aspose.imaging.masking.result/imatchinglayer). |

**Returns:**
[IMaskingLayer](../../com.aspose.imaging.masking.result/imaskinglayer) - The masking layer.
### iterator() {#iterator--}
```
public final Iterator<IMaskingLayer> iterator()
```


Gibt den Enumerator zurück.

**Returns:**
java.util.Iterator<com.aspose.imaging.masking.result.IMatchingLayer> - der Enumerator.
