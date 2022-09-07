---
title: AssumedObjectData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diAssumedObjectDataaspose.imaging.masking.options/assumedobjectdata classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.masking.options/assumedobjectdata/assumedobjectdata/
---
## AssumedObjectData() {#constructor}

Inizializza una nuova istanza di[`AssumedObjectData`](../../assumedobjectdata) classe.

```csharp
public AssumedObjectData()
```

### Guarda anche

* class [AssumedObjectData](../../assumedobjectdata)
* spazio dei nomi [Aspose.Imaging.Masking.Options](../../assumedobjectdata)
* assemblea [Aspose.Imaging](../../../)

---

## AssumedObjectData(DetectedObjectType, Rectangle) {#constructor_1}

Inizializza una nuova istanza di[`AssumedObjectData`](../../assumedobjectdata) classe.

```csharp
public AssumedObjectData(DetectedObjectType type, Rectangle bounds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | DetectedObjectType | Il tipo dell'oggetto. |
| bounds | Rectangle | I limiti dell'oggetto. |

### Esempi

Salvataggio del risultato di mascheramento dell'immagine con sfumatura in base alla dimensione dell'immagine. La mascheratura dell'immagine viene eseguita utilizzando i tratti predefiniti calcolati automaticamente. Inoltre, i dati dei due oggetti presunti vengono specificati anche nella proprietà AssumedObjects di AutoMaskingGraphCutOptions.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
                                                    AssumedObjects = assumedObjects,
                                                    CalculateDefaultStrokes = true,
                                                    FeatheringRadius = (Math.Max(image.Width, image.Height) / 500) + 1,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent
    };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Salvataggio del risultato della mascheratura dell'immagine con sfumatura in base alla dimensione dell'immagine e riutilizzo delle opzioni di mascheratura per la nuova iterazione della mascheratura. La mascheratura dell'immagine viene eseguita utilizzando i tratti predefiniti calcolati automaticamente. Inoltre, i dati dei due oggetti presunti vengono specificati anche nella proprietà AssumedObjects di AutoMaskingGraphCutOptions. Dopo aver ottenuto il risultato della mascheratura iniziale, i tratti di sfondo/primo piano applicati vengono modificati e viene eseguita un'altra iterazione della mascheratura.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// A questo punto i tratti di primo piano/sfondo applicati possono essere analizzati e basati su di essi aggiuntivi 
// I tratti di primo piano/sfondo possono essere forniti manualmente.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // Riutilizzando AutoMaskingGraphCutOptions non è necessario eseguire calcoli di tratti predefiniti una seconda volta.
    options.CalculateDefaultStrokes = false;
    // Quando vengono forniti sia i tratti predefiniti che ObjectsPoints nella proprietà Args di AutoMaskingArgs, le matrici di punti vengono combinate.
    // Il primo array ObjectsPoints è considerato un array di punti di sfondo e 
    // il secondo array ObjectsPoints è considerato un array di punti in primo piano.
    // Quando vengono forniti sia DefaultObjectsRectangles che ObjectsRectangles nella proprietà Args di AutoMaskingArgs, 
    // viene utilizzato solo l'array di Args.
    options.Args = new AutoMaskingArgs()
                        {
                            ObjectsPoints = new Point[][]
                                                {
                                                    new Point[] { new Point(100, 100), new Point(150, 100) }, 
                                                    new Point[] { new Point(500, 200) }, 
                                                },
                            ObjectsRectangles = new Rectangle[]
                                                    {
                                                        new Rectangle(100, 100, 300, 300), 
                                                    }
                        };
    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Salvataggio del risultato della mascheratura dell'immagine con sfumatura in base alla dimensione dell'immagine, modifica dei tratti predefiniti ottenuti e utilizzo per la nuova iterazione della mascheratura. La mascheratura dell'immagine viene eseguita utilizzando i tratti predefiniti calcolati automaticamente. Inoltre, i dati dei due oggetti presunti vengono specificati anche nella proprietà AssumedObjects di AutoMaskingGraphCutOptions. Dopo aver ottenuto il risultato della mascheratura iniziale, i tratti di sfondo/primo piano applicati vengono modificati e viene eseguita un'altra iterazione di mascheratura utilizzando la nuova istanza di GraphCutMaskingOptions.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// A questo punto i tratti di primo piano/sfondo applicati possono essere analizzati e basati su di essi aggiuntivi 
// I tratti di primo piano/sfondo possono essere forniti manualmente.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions()
                                                    {
                                                        FeatheringRadius = 3,
                                                        Method = SegmentationMethod.GraphCut,
                                                        Decompose = false,
                                                        ExportOptions = new PngOptions()
                                                                            {
                                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                                Source = new FileCreateSource("tempFile")
                                                                            },
                                                        BackgroundReplacementColor = Color.Transparent,
                                                        Args = new AutoMaskingArgs()
                                                                {
                                                                    ObjectsPoints = new Point[][]
                                                                                        {
                                                                                            appliedBackgroundStrokes,
                                                                                            appliedForegroundStrokes
                                                                                        },
                                                                    ObjectsRectangles = appliedObjectRectangles
                                                                }
                                                    };
    results = new ImageMasking(image).Decompose(graphCutOptions);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Guarda anche

* enum [DetectedObjectType](../../detectedobjecttype)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [AssumedObjectData](../../assumedobjectdata)
* spazio dei nomi [Aspose.Imaging.Masking.Options](../../assumedobjectdata)
* assemblea [Aspose.Imaging](../../../)

---

## AssumedObjectData(string, Rectangle) {#constructor_2}

Inizializza una nuova istanza di[`AssumedObjectData`](../../assumedobjectdata) classe.

```csharp
public AssumedObjectData(string type, Rectangle bounds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Il tipo dell'oggetto. |
| bounds | Rectangle | I limiti dell'oggetto. |

### Guarda anche

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [AssumedObjectData](../../assumedobjectdata)
* spazio dei nomi [Aspose.Imaging.Masking.Options](../../assumedobjectdata)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
