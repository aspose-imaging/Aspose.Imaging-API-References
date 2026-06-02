---
title: "AutoMaskingArgs"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Argumente dar, die für automatisierte Maskierungsmethoden angegeben werden."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Stellt die Argumente dar, die für automatisierte Maskierungsmethoden angegeben werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | Liefert die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Setzt die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund). |
| [getObjectsRectangles()](#getObjectsRectangles--) | Liefert die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | Setzt die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional). |
| [getObjectsPoints()](#getObjectsPoints--) | Liefert die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | Setzt die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. |
| [getOrphanedPoints()](#getOrphanedPoints--) | Liefert die Punkte, die keinem Objekt mehr zugeordnet sind (optional). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | Setzt die Punkte, die keinem Objekt mehr zugeordnet sind (optional). |
| [getPrecision()](#getPrecision--) | Liefert die Präzision der Segmentierungsmethode (optional). |
| [setPrecision(double value)](#setPrecision-double-) | Setzt die Präzision der Segmentierungsmethode (optional). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Liefert die maximale Anzahl an Iterationen. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Setzt die maximale Anzahl an Iterationen. |

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

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Liefert die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund).

Wert: Die Anzahl der Objekte.

**Returns:**
int - die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Setzt die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund).

Wert: Die Anzahl der Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Liefert die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional). Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Objekt-Rechtecke.

**Returns:**
com.aspose.imaging.Rectangle[] - die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Setzt die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional). Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Objekt-Rechtecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Liefert die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Objektpunkte.

**Returns:**
com.aspose.imaging.Point[][] - die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Legt die Punkte fest, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Objektpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Ruft die Punkte ab, die zu keinem Objekt mehr gehören (optional). Dieser Parameter wird nur im Fall einer erneuten Segmentierung verwendet.

Wert: Die verwaisten Punkte.

**Returns:**
com.aspose.imaging.Point[] - die Punkte, die zu keinem Objekt mehr gehören (optional).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Legt die Punkte fest, die zu keinem Objekt mehr gehören (optional). Dieser Parameter wird nur im Fall einer erneuten Segmentierung verwendet.

Wert: Die verwaisten Punkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | die Punkte, die zu keinem Objekt mehr gehören (optional). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Liefert die Präzision der Segmentierungsmethode (optional).

Wert: Die Präzision der Segmentierungsmethode (optional).

**Returns:**
double - die Präzision der Segmentierungsmethode (optional).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Setzt die Präzision der Segmentierungsmethode (optional).

Wert: Die Präzision der Segmentierungsmethode (optional).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | die Präzision der Segmentierungsmethode (optional). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Liefert die maximale Anzahl an Iterationen.

Wert: Die maximale maximale Anzahl von Iterationen.

**Returns:**
int - die maximale Anzahl von Iterationen.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Setzt die maximale Anzahl an Iterationen.

Wert: Die maximale maximale Anzahl von Iterationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die maximale Anzahl von Iterationen. |

