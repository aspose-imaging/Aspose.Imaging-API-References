---
title: "MaskingOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta le comuni opzioni di mascheramento delle immagini."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.masking.options/maskingoptions/
---
**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Rappresenta le comuni opzioni di mascheramento delle immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Il numero dell'oggetto di sfondo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMethod()](#getMethod--) | Ottiene il metodo di segmentazione. |
| [setMethod(int value)](#setMethod-int-) | Imposta il metodo di segmentazione. |
| [getArgs()](#getArgs--) | Ottiene gli argomenti per l'algoritmo di segmentazione. |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-) | Imposta gli argomenti per l'algoritmo di segmentazione. |
| [getExportOptions()](#getExportOptions--) | Ottiene le opzioni di esportazione dell'immagine. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.imaging.ImageOptionsBase-) | Imposta le opzioni di esportazione dell'immagine. |
| [getMaskingArea()](#getMaskingArea--) | Ottiene l'area di mascheramento. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.imaging.Rectangle-) | Imposta l'area di mascheramento. |
| [getDecompose()](#getDecompose--) | Ottiene un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Imposta un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Ottiene il colore di sostituzione dello sfondo. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.imaging.Color-) | Imposta il colore di sostituzione dello sfondo. |

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


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
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

### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Il numero dell'oggetto di sfondo

### getMethod() {#getMethod--}
```
public final int getMethod()
```


Ottiene il metodo di segmentazione.

Valore: Il metodo di segmentazione.

**Returns:**
int - il metodo di segmentazione.
### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Imposta il metodo di segmentazione.

Valore: Il metodo di segmentazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il metodo di segmentazione. |


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

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Ottiene gli argomenti per l'algoritmo di segmentazione.

Valore: Gli argomenti per l'algoritmo di segmentazione.

**Returns:**
[IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### setArgs(IMaskingArgs value) {#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Imposta gli argomenti per l'algoritmo di segmentazione.

Valore: Gli argomenti per l'algoritmo di segmentazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | gli argomenti per l'algoritmo di segmentazione. |

### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Ottiene le opzioni di esportazione dell'immagine.

Valore: Le opzioni di esportazione dell'immagine che saranno utilizzate per creare le immagini risultanti.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - the image export options.
### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.imaging.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Imposta le opzioni di esportazione dell'immagine.

Valore: Le opzioni di esportazione dell'immagine che saranno utilizzate per creare le immagini risultanti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | le opzioni di esportazione dell'immagine. |


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

### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Ottiene l'area di mascheramento.

Valore: L'area di mascheramento che è un'area parziale dell'immagine sorgente. Il valore Rectangle.Empty indica l'intera area dell'immagine sorgente.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the masking area.
### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.imaging.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Imposta l'area di mascheramento.

Valore: L'area di mascheramento che è un'area parziale dell'immagine sorgente. Il valore Rectangle.Empty indica l'intera area dell'immagine sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | l'area di mascheramento. |

### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Ottiene un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.

Valore: `true` se decomporre; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se è superfluo separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.
### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Imposta un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.

Valore: `true` se decomporre; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se è superfluo separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |

### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Ottiene il colore di sostituzione dello sfondo.

Valore: Il colore di sostituzione dello sfondo. Questo colore sarà usato come colore di sfondo nelle immagini risultanti.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background replacement color.
### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.imaging.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Imposta il colore di sostituzione dello sfondo.

Valore: Il colore di sostituzione dello sfondo. Questo colore sarà usato come colore di sfondo nelle immagini risultanti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | il colore di sostituzione dello sfondo. |


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

