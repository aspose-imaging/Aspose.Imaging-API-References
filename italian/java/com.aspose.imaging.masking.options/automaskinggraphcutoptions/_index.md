---
title: "AutoMaskingGraphCutOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di mascheramento automatico GraphCut."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.masking.options/automaskinggraphcutoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.masking.options.MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions), [com.aspose.imaging.masking.options.GraphCutMaskingOptions](../../com.aspose.imaging.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Le opzioni di mascheramento automatico GraphCut.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Inizializza una nuova istanza della classe [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Ottiene i tratti di primo piano pre-calcolati di default. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Ottiene i tratti di sfondo di default. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Ottiene i rettangoli degli oggetti di default. |
| [getAssumedObjects()](#getAssumedObjects--) | Ottiene gli oggetti presunti. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--) | Imposta gli oggetti presunti. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Ottiene un valore che indica se i tratti di default devono essere calcolati. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Imposta un valore che indica se i tratti di default devono essere calcolati. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti di default. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti di default. |

## Example: Saving image masking result with feathering based on image size.
Salvataggio del risultato della mascheratura dell'immagine con sfumatura basata sulla dimensione dell'immagine. La mascheratura dell'immagine viene eseguita utilizzando i tratti di default calcolati automaticamente. La proprietà Args di AutoMaskingGraphCutOptions può essere omessa poiché i tratti di default vi vengono inseriti alla fine. MaskingResult[] results;
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

// rilascia le risorse
for (MaskingResult res : results)
{
    res.close();
}
            
```


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

### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Inizializza una nuova istanza della classe [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions).

### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Ottiene i tratti di primo piano pre-calcolati di default.

**Returns:**
com.aspose.imaging.Point[] - le tracce pre-calcolate di primo piano predefinite.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
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


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
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

### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Ottiene i tratti di sfondo di default.

**Returns:**
com.aspose.imaging.Point[] - le tracce di sfondo predefinite.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
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


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
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

### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Ottiene i rettangoli degli oggetti di default.

**Returns:**
com.aspose.imaging.Rectangle[] - i rettangoli degli oggetti predefiniti.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
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


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
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

### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Ottiene gli oggetti presunti.

**Returns:**
java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> - gli oggetti presunti.
### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Imposta gli oggetti presunti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> | gli oggetti presunti. |

### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Ottiene un valore che indica se i tratti di default devono essere calcolati.

**Returns:**
boolean - un valore che indica se le tracce predefinite devono essere calcolate.
### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Imposta un valore che indica se i tratti di default devono essere calcolati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se le tracce predefinite devono essere calcolate. |


**Example: Saving image masking result with feathering based on image size.**
Salvataggio del risultato della mascheratura dell'immagine con sfumatura basata sulla dimensione dell'immagine. La mascheratura dell'immagine viene eseguita utilizzando i tratti di default calcolati automaticamente. La proprietà Args di AutoMaskingGraphCutOptions può essere omessa poiché i tratti di default vi vengono inseriti alla fine. MaskingResult[] results;
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

// rilascia le risorse
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving image masking result with feathering based on image size.**
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


**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
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


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
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

### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti di default.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the default points pre-calculation process progress event handler.
### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Imposta il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti di default.

Valore: Il gestore dell'evento di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti predefiniti. |

