---
title: "AssumedObjectData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I dati degli oggetti presunti."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.masking.options/assumedobjectdata/
---
**Inheritance:**
java.lang.Object
```
public class AssumedObjectData
```

I dati dell'oggetto presunto. Include il tipo e l'area dell'oggetto.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AssumedObjectData()](#AssumedObjectData--) | Inizializza una nuova istanza della classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(int type, Rectangle bounds)](#AssumedObjectData-int-com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(String type, Rectangle bounds)](#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Ottiene il tipo dell'oggetto. |
| [setType(int value)](#setType-int-) | Imposta il tipo dell'oggetto. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Imposta i limiti dell'oggetto. |

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

### AssumedObjectData() {#AssumedObjectData--}
```
public AssumedObjectData()
```


Inizializza una nuova istanza della classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

### AssumedObjectData(int type, Rectangle bounds) {#AssumedObjectData-int-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(int type, Rectangle bounds)
```


Inizializza una nuova istanza della classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Il tipo dell'oggetto. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | I limiti dell'oggetto. |

### AssumedObjectData(String type, Rectangle bounds) {#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(String type, Rectangle bounds)
```


Inizializza una nuova istanza della classe [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | java.lang.String | Il tipo dell'oggetto. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | I limiti dell'oggetto. |

### getType() {#getType--}
```
public final int getType()
```


Ottiene il tipo dell'oggetto.

**Returns:**
int - il tipo dell'oggetto.
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Imposta il tipo dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il tipo dell'oggetto. |

### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Ottiene i limiti dell'oggetto.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the object's bounds.
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Imposta i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | i limiti dell'oggetto. |

