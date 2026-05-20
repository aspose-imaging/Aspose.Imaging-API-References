---
title: "DetectedObjectType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione dei tipi di oggetto rilevati."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.masking.options/detectedobjecttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DetectedObjectType extends System.Enum
```

L'enumerazione dei tipi di oggetto rilevati.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Human](#Human) | Il tipo di oggetto umano. |
| [Other](#Other) | Altro tipo di oggetto. |

## Example: Saving image masking result with feathering based on image size.
Salvataggio del risultato della mascheratura dell'immagine con sfumatura basata sulla dimensione dell'immagine. La mascheratura dell'immagine viene eseguita utilizzando i tratti di default calcolati automaticamente. Inoltre i dati dei due oggetti presunti sono specificati anche nella proprietà AssumedObjects di AutoMaskingGraphCutOptions.
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

// rilascia le risorse
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Salvataggio del risultato della mascheratura dell'immagine con sfumatura basata sulla dimensione dell'immagine e riutilizzo delle opzioni di mascheratura per la nuova iterazione di mascheratura. La mascheratura dell'immagine viene eseguita utilizzando i tratti di default calcolati automaticamente. Inoltre i dati dei due oggetti presunti sono specificati anche nella proprietà AssumedObjects di AutoMaskingGraphCutOptions. Dopo aver ottenuto il risultato iniziale della mascheratura, i tratti di sfondo/primo piano applicati vengono modificati e viene eseguita un'altra iterazione di mascheratura.
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

// A questo punto i tratti di primo piano/sfondo applicati possono essere analizzati e, in base a essi, ulteriori
// i tratti di primo piano/sfondo possono essere forniti manualmente.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// rilascia le risorse
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Riutilizzando AutoMaskingGraphCutOptions non è necessario eseguire il calcolo dei tratti di default una seconda volta.
    options.setCalculateDefaultStrokes(false);
    // Quando sia i tratti di default sia ObjectsPoints nella proprietà Args di AutoMaskingArgs sono forniti, gli array di punti vengono combinati.
    // Il primo array ObjectsPoints è considerato un array di punti di sfondo e
    // il secondo array ObjectsPoints è considerato un array di punti di primo piano.
    // Quando sia DefaultObjectsRectangles sia ObjectsRectangles nella proprietà Args di AutoMaskingArgs sono forniti,
    // viene utilizzato solo l'array proveniente da Args.
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

// rilascia le risorse
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Salvataggio del risultato della mascheratura dell'immagine con feathering basato sulla dimensione dell'immagine, modificando le tracce predefinite ottenute e utilizzandole per la nuova iterazione di mascheratura. La mascheratura dell'immagine viene eseguita utilizzando tracce predefinite calcolate automaticamente. Inoltre i dati dei due oggetti presunti sono specificati anche nella proprietà AssumedObjects di AutoMaskingGraphCutOptions. Dopo aver ottenuto il risultato iniziale della mascheratura, le tracce di sfondo/primo piano applicate vengono modificate e viene eseguita un'altra iterazione di mascheratura utilizzando una nuova istanza di GraphCutMaskingOptions.
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

// A questo punto i tratti di primo piano/sfondo applicati possono essere analizzati e, in base a essi, ulteriori
// i tratti di primo piano/sfondo possono essere forniti manualmente.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// rilascia le risorse
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

// rilascia le risorse
for (MaskingResult res : results)
{
    res.close();
}
```

### Human {#Human}
```
public static final int Human
```


Il tipo di oggetto umano.

### Other {#Other}
```
public static final int Other
```


Altro tipo di oggetto.

