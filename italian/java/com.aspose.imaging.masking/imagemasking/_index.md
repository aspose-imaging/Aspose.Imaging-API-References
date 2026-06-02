---
title: "ImageMasking"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Fornisce operazioni di mascheramento dell'immagine"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.masking/imagemasking/
---
**Inheritance:**
java.lang.Object
```
public class ImageMasking
```

Fornisce operazioni di mascheramento dell'immagine
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageMasking(RasterImage sourceImage)](#ImageMasking-com.aspose.imaging.RasterImage-) | Inizializza una nuova istanza della classe [ImageMasking](../../com.aspose.imaging.masking/imagemasking). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyMask(RasterImage targetImage, RasterImage mask, MaskingOptions maskingOptions)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.RasterImage-com.aspose.imaging.masking.options.MaskingOptions-) | Applica la maschera all'immagine sorgente specificata. |
| [decompose(MaskingOptions options)](#decompose-com.aspose.imaging.masking.options.MaskingOptions-) | Esegue l'operazione di scomposizione usando le opzioni di mascheramento specificate |
| [decomposeAsync(MaskingOptions options)](#decomposeAsync-com.aspose.imaging.masking.options.MaskingOptions-) | Crea l'attività asincrona di scomposizione usando le opzioni di mascheramento specificate. |
| [createSession(MaskingOptions options)](#createSession-com.aspose.imaging.masking.options.MaskingOptions-) | Crea la sessione di mascheramento che può eseguire operazioni di scomposizione di riaddestramento. |
| [loadSession(InputStream stream)](#loadSession-java.io.InputStream-) | Carica la sessione dallo stream specificato. |
| [loadSession(System.IO.Stream stream)](#loadSession-com.aspose.ms.System.IO.Stream-) |  |
| [loadSession(String filePath)](#loadSession-java.lang.String-) | Carica la sessione dal file specificato. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
Questo esempio mostra come scomporre un'immagine raster in più immagini utilizzando il mascheramento dell'immagine e l'algoritmo di segmentazione K-means. Il mascheramento dell'immagine è una tecnica di elaborazione delle immagini che viene usata per separare lo sfondo dagli oggetti dell'immagine in primo piano.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Imposta il numero di cluster (oggetti separati). Il valore predefinito è 2, l'oggetto in primo piano e lo sfondo.
    args.setNumberOfObjects(3);

    // Imposta il numero massimo di iterazioni.
    args.setMaxIterationNumber(50);

    // Imposta la precisione del metodo di segmentazione (opzionale)
    args.setPrecision(1);

    // Ogni cluster (segmento) verrà salvato in un file PNG separato.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Usa il clustering K-means.
    // Il clustering K-means consente di suddividere l'immagine in diversi cluster (segmenti) indipendenti.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // Il colore di sfondo sarà arancione.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Ottieni le immagini dal risultato del mascheramento e salvale in PNG.
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
// Opzioni di esportazione mascheramento
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Usa il clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Il colore di sfondo sarà trasparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Riduzione delle dimensioni dell'immagine per velocizzare il processo di segmentazione
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ottenere la maschera di primo piano
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Aumenta le dimensioni della maschera alla dimensione dell'immagine originale
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applicare la maschera all'immagine originale per ottenere un segmento di primo piano
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

// Opzioni di esportazione mascheramento
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Usa il clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Il colore di sfondo sarà arancione.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Avvio di una sessione per la prima volta e salvataggio su un file
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Crea un'istanza della classe ImageMasking.
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

// Ripresa di una sessione di mascheramento da un file
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analizza l'immagine visivamente e imposta i punti che appartengono a oggetti separati.
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
            // Trasferimento esplicito delle opzioni di esportazione, poiché non è serializzabile
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


Inizializza una nuova istanza della classe [ImageMasking](../../com.aspose.imaging.masking/imagemasking).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine di origine. |


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Opzioni di esportazione mascheramento
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Usa il clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Il colore di sfondo sarà trasparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Riduzione delle dimensioni dell'immagine per velocizzare il processo di segmentazione
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ottenere la maschera di primo piano
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Aumenta le dimensioni della maschera alla dimensione dell'immagine originale
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applicare la maschera all'immagine originale per ottenere un segmento di primo piano
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


Applica la maschera all'immagine sorgente specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine di destinazione. |
| mask | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine maschera da applicare. |
| maskingOptions | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Le opzioni di mascheramento. |


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Opzioni di esportazione mascheramento
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Usa il clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Il colore di sfondo sarà trasparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Riduzione delle dimensioni dell'immagine per velocizzare il processo di segmentazione
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ottenere la maschera di primo piano
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Aumenta le dimensioni della maschera alla dimensione dell'immagine originale
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applicare la maschera all'immagine originale per ottenere un segmento di primo piano
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


Esegue l'operazione di scomposizione usando le opzioni di mascheramento specificate

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Le opzioni di mascheramento. |

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
Questo esempio mostra come specificare suggerimenti per l'algoritmo di mascheramento dell'immagine al fine di migliorare la precisione del metodo di segmentazione (clustering). Il mascheramento dell'immagine è una tecnica di elaborazione delle immagini che viene usata per separare lo sfondo dagli oggetti dell'immagine in primo piano.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Suggerimento n. 1.
    // Analizza l'immagine visivamente e imposta l'area di interesse. Il risultato della segmentazione includerà solo gli oggetti che saranno completamente situati all'interno di quest'area.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Suggerimento n. 2.
    // Analizza l'immagine visivamente e imposta i punti che appartengono a oggetti separati.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Ogni cluster (segmento) verrà salvato in un file PNG separato.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Usa il clustering GraphCut.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Il colore di sfondo sarà arancione.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Ottieni le immagini dal risultato del mascheramento e salvale in PNG.
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
// Opzioni di esportazione mascheramento
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Usa il clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Il colore di sfondo sarà trasparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Riduzione delle dimensioni dell'immagine per velocizzare il processo di segmentazione
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ottenere la maschera di primo piano
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Aumenta le dimensioni della maschera alla dimensione dell'immagine originale
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applicare la maschera all'immagine originale per ottenere un segmento di primo piano
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


Crea l'attività asincrona di scomposizione usando le opzioni di mascheramento specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Le opzioni di mascheramento. |

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### createSession(MaskingOptions options) {#createSession-com.aspose.imaging.masking.options.MaskingOptions-}
```
public final IMaskingSession createSession(MaskingOptions options)
```


Crea la sessione di mascheramento che può eseguire operazioni di scomposizione di riaddestramento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Le opzioni. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Opzioni di esportazione mascheramento
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Usa il clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Il colore di sfondo sarà arancione.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Avvio di una sessione per la prima volta e salvataggio su un file
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Crea un'istanza della classe ImageMasking.
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

// Ripresa di una sessione di mascheramento da un file
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Crea un'istanza della classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analizza l'immagine visivamente e imposta i punti che appartengono a oggetti separati.
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
            // Trasferimento esplicito delle opzioni di esportazione, poiché non è serializzabile
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


Carica la sessione dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.
### loadSession(System.IO.Stream stream) {#loadSession-com.aspose.ms.System.IO.Stream-}
```
public final IMaskingSession loadSession(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession)
### loadSession(String filePath) {#loadSession-java.lang.String-}
```
public final IMaskingSession loadSession(String filePath)
```


Carica la sessione dal file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.
