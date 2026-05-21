---
title: "AutoMaskingArgs"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta gli argomenti specificati per i metodi di mascheramento automatico"
type: docs
weight: 11
url: /it/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Rappresenta gli argomenti specificati per i metodi di mascheramento automatico
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | Restituisce il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Imposta il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo). |
| [getObjectsRectangles()](#getObjectsRectangles--) | Restituisce i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | Imposta i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale). |
| [getObjectsPoints()](#getObjectsPoints--) | Restituisce i punti che appartengono agli oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | Imposta i punti che appartengono agli oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. |
| [getOrphanedPoints()](#getOrphanedPoints--) | Restituisce i punti che non appartengono più a nessun oggetto (opzionale). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | Imposta i punti che non appartengono più a nessun oggetto (opzionale). |
| [getPrecision()](#getPrecision--) | Restituisce la precisione del metodo di segmentazione (opzionale). |
| [setPrecision(double value)](#setPrecision-double-) | Imposta la precisione del metodo di segmentazione (opzionale). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Restituisce il numero massimo di iterazioni. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Imposta il numero massimo di iterazioni. |

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

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Restituisce il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo).

Valore: Il numero di oggetti.

**Returns:**
int - il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Imposta il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo).

Valore: Il numero di oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Restituisce i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale). Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I rettangoli degli oggetti.

**Returns:**
com.aspose.imaging.Rectangle[] - i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Imposta i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale). Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I rettangoli degli oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Restituisce i punti che appartengono agli oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I punti degli oggetti.

**Returns:**
com.aspose.imaging.Point[][] - i punti che appartengono agli oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Imposta i punti che appartengono a oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I punti degli oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | i punti che appartengono a oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Ottiene i punti che non appartengono più a nessun oggetto (opzionale). Questo parametro è usato solo in caso di ri-segmentazione.

Valore: I punti orfani.

**Returns:**
com.aspose.imaging.Point[] - i punti che non appartengono più a nessun oggetto (opzionale).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Imposta i punti che non appartengono più a nessun oggetto (opzionale). Questo parametro è usato solo in caso di ri-segmentazione.

Valore: I punti orfani.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | i punti che non appartengono più a nessun oggetto (opzionale). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Restituisce la precisione del metodo di segmentazione (opzionale).

Valore: La precisione del metodo di segmentazione (opzionale).

**Returns:**
double - la precisione del metodo di segmentazione (opzionale).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Imposta la precisione del metodo di segmentazione (opzionale).

Valore: La precisione del metodo di segmentazione (opzionale).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | la precisione del metodo di segmentazione (opzionale). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Restituisce il numero massimo di iterazioni.

Valore: Il numero massimo di iterazioni.

**Returns:**
int - il numero massimo di iterazioni.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Imposta il numero massimo di iterazioni.

Valore: Il numero massimo di iterazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il numero massimo di iterazioni. |

