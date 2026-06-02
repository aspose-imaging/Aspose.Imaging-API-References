---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die GraphCut-Auto-Maskierungsoptionen."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.masking.options/automaskinggraphcutoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.masking.options.MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions), [com.aspose.imaging.masking.options.GraphCutMaskingOptions](../../com.aspose.imaging.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Die GraphCut-Auto-Maskierungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Initialisiert eine neue Instanz der Klasse [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Liefert die vorab berechneten Standard-Vordergrundstriche. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Liefert die Standard-Hintergrundstriche. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Liefert die Standard-Objekt-Rechtecke. |
| [getAssumedObjects()](#getAssumedObjects--) | Liefert die angenommenen Objekte. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--) | Setzt die angenommenen Objekte. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Liefert einen Wert, der angibt, ob Standard-Striche berechnet werden sollen. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Setzt einen Wert, der angibt, ob Standard-Striche berechnet werden sollen. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Liefert den Ereignishandler für den Fortschritt des Vorberechnungsprozesses der Standardpunkte. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Setzt den Ereignishandler für den Fortschritt des Vorberechnungsprozesses der Standardpunkte. |

## Example: Saving image masking result with feathering based on image size.
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Die Eigenschaft Args von AutoMaskingGraphCutOptions kann weggelassen werden, da die Standardstriche am Ende dort platziert werden. MaskingResult[] results;
``` java

MaskingResult[] results; 
            
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size.
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte ebenfalls in der Eigenschaft AssumedObjects von AutoMaskingGraphCutOptions angegeben.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße und Wiederverwenden von Maskierungsoptionen für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte ebenfalls in der Eigenschaft AssumedObjects von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden die angewendeten Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Durch Wiederverwenden von AutoMaskingGraphCutOptions ist es nicht nötig, die Berechnung der Standardstriche ein zweites Mal durchzuführen.
    options.setCalculateDefaultStrokes(false);
    // Wenn sowohl Standardstriche als auch ObjectsPoints in der Eigenschaft Args von AutoMaskingArgs bereitgestellt werden, werden die Punktarrays schließlich kombiniert.
    // Das erste ObjectsPoints-Array wird als Hintergrund-Punkt-Array betrachtet und
    // Das zweite ObjectsPoints-Array wird als Vordergrund-Punkte-Array betrachtet.
    // Wenn sowohl DefaultObjectsRectangles als auch ObjectsRectangles in der Args-Eigenschaft von AutoMaskingArgs bereitgestellt werden,
    // wird nur das Array aus den Args verwendet.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße, Anpassen der erhaltenen Standardstriche und deren Verwendung für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der AssumedObjects-Eigenschaft von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden angewandte Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration mit einer neuen GraphCutMaskingOptions-Instanz durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
```

### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Initialisiert eine neue Instanz der Klasse [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions).

### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Liefert die vorab berechneten Standard-Vordergrundstriche.

**Returns:**
com.aspose.imaging.Point[] - die vorab berechneten Standard‑Vordergrund‑Striche.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße und Wiederverwenden von Maskierungsoptionen für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte ebenfalls in der Eigenschaft AssumedObjects von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden die angewendeten Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Durch Wiederverwenden von AutoMaskingGraphCutOptions ist es nicht nötig, die Berechnung der Standardstriche ein zweites Mal durchzuführen.
    options.setCalculateDefaultStrokes(false);
    // Wenn sowohl Standardstriche als auch ObjectsPoints in der Eigenschaft Args von AutoMaskingArgs bereitgestellt werden, werden die Punktarrays schließlich kombiniert.
    // Das erste ObjectsPoints-Array wird als Hintergrund-Punkt-Array betrachtet und
    // Das zweite ObjectsPoints-Array wird als Vordergrund-Punkte-Array betrachtet.
    // Wenn sowohl DefaultObjectsRectangles als auch ObjectsRectangles in der Args-Eigenschaft von AutoMaskingArgs bereitgestellt werden,
    // wird nur das Array aus den Args verwendet.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße, Anpassen der erhaltenen Standardstriche und deren Verwendung für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der AssumedObjects-Eigenschaft von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden angewandte Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration mit einer neuen GraphCutMaskingOptions-Instanz durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
```

### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Liefert die Standard-Hintergrundstriche.

**Returns:**
com.aspose.imaging.Point[] - die Standard‑Hintergrund‑Striche.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße und Wiederverwenden von Maskierungsoptionen für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte ebenfalls in der Eigenschaft AssumedObjects von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden die angewendeten Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Durch Wiederverwenden von AutoMaskingGraphCutOptions ist es nicht nötig, die Berechnung der Standardstriche ein zweites Mal durchzuführen.
    options.setCalculateDefaultStrokes(false);
    // Wenn sowohl Standardstriche als auch ObjectsPoints in der Eigenschaft Args von AutoMaskingArgs bereitgestellt werden, werden die Punktarrays schließlich kombiniert.
    // Das erste ObjectsPoints-Array wird als Hintergrund-Punkt-Array betrachtet und
    // Das zweite ObjectsPoints-Array wird als Vordergrund-Punkte-Array betrachtet.
    // Wenn sowohl DefaultObjectsRectangles als auch ObjectsRectangles in der Args-Eigenschaft von AutoMaskingArgs bereitgestellt werden,
    // wird nur das Array aus den Args verwendet.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße, Anpassen der erhaltenen Standardstriche und deren Verwendung für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der AssumedObjects-Eigenschaft von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden angewandte Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration mit einer neuen GraphCutMaskingOptions-Instanz durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
```

### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Liefert die Standard-Objekt-Rechtecke.

**Returns:**
com.aspose.imaging.Rectangle[] - die Standard‑Objekt‑Rechtecke.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße und Wiederverwenden von Maskierungsoptionen für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte ebenfalls in der Eigenschaft AssumedObjects von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden die angewendeten Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Durch Wiederverwenden von AutoMaskingGraphCutOptions ist es nicht nötig, die Berechnung der Standardstriche ein zweites Mal durchzuführen.
    options.setCalculateDefaultStrokes(false);
    // Wenn sowohl Standardstriche als auch ObjectsPoints in der Eigenschaft Args von AutoMaskingArgs bereitgestellt werden, werden die Punktarrays schließlich kombiniert.
    // Das erste ObjectsPoints-Array wird als Hintergrund-Punkt-Array betrachtet und
    // Das zweite ObjectsPoints-Array wird als Vordergrund-Punkte-Array betrachtet.
    // Wenn sowohl DefaultObjectsRectangles als auch ObjectsRectangles in der Args-Eigenschaft von AutoMaskingArgs bereitgestellt werden,
    // wird nur das Array aus den Args verwendet.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße, Anpassen der erhaltenen Standardstriche und deren Verwendung für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der AssumedObjects-Eigenschaft von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden angewandte Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration mit einer neuen GraphCutMaskingOptions-Instanz durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
```

### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Liefert die angenommenen Objekte.

**Returns:**
java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> - die angenommenen Objekte.
### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Setzt die angenommenen Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> | die angenommenen Objekte. |

### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Liefert einen Wert, der angibt, ob Standard-Striche berechnet werden sollen.

**Returns:**
boolean - ein Wert, der angibt, ob Standard‑Striche berechnet werden sollen.
### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Setzt einen Wert, der angibt, ob Standard-Striche berechnet werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob Standard‑Striche berechnet werden sollen. |


**Example: Saving image masking result with feathering based on image size.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Die Eigenschaft Args von AutoMaskingGraphCutOptions kann weggelassen werden, da die Standardstriche am Ende dort platziert werden. MaskingResult[] results;
``` java

MaskingResult[] results; 
            
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving image masking result with feathering based on image size.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte ebenfalls in der Eigenschaft AssumedObjects von AutoMaskingGraphCutOptions angegeben.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße und Wiederverwenden von Maskierungsoptionen für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte ebenfalls in der Eigenschaft AssumedObjects von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden die angewendeten Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Durch Wiederverwenden von AutoMaskingGraphCutOptions ist es nicht nötig, die Berechnung der Standardstriche ein zweites Mal durchzuführen.
    options.setCalculateDefaultStrokes(false);
    // Wenn sowohl Standardstriche als auch ObjectsPoints in der Eigenschaft Args von AutoMaskingArgs bereitgestellt werden, werden die Punktarrays schließlich kombiniert.
    // Das erste ObjectsPoints-Array wird als Hintergrund-Punkt-Array betrachtet und
    // Das zweite ObjectsPoints-Array wird als Vordergrund-Punkte-Array betrachtet.
    // Wenn sowohl DefaultObjectsRectangles als auch ObjectsRectangles in der Args-Eigenschaft von AutoMaskingArgs bereitgestellt werden,
    // wird nur das Array aus den Args verwendet.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Speichern des Bildmaskierungsergebnisses mit Weichzeichnung basierend auf der Bildgröße, Anpassen der erhaltenen Standardstriche und deren Verwendung für die neue Maskierungsiteration. Die Bildmaskierung wird mit automatisch berechneten Standardstrichen durchgeführt. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der AssumedObjects-Eigenschaft von AutoMaskingGraphCutOptions angegeben. Nach Erhalt des anfänglichen Maskierungsergebnisses werden angewandte Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration mit einer neuen GraphCutMaskingOptions-Instanz durchgeführt.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// An diesem Punkt können die angewendeten Vordergrund-/Hintergrundstriche analysiert werden und basierend darauf zusätzliche
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// Ressourcen freigeben
for (MaskingResult res : results)
{
    res.close();
}
```

### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Liefert den Ereignishandler für den Fortschritt des Vorberechnungsprozesses der Standardpunkte.

Wert: Der Fortschritts-Ereignishandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the default points pre-calculation process progress event handler.
### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Setzt den Ereignishandler für den Fortschritt des Vorberechnungsprozesses der Standardpunkte.

Wert: Der Fortschritts-Ereignishandler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | der Ereignishandler für den Fortschritt des Vorab‑Berechnungsprozesses der Standard‑Punkte. |

