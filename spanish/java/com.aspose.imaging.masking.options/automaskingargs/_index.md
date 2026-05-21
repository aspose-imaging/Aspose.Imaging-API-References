---
title: "AutoMaskingArgs"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa los argumentos que se especifican para los métodos de enmascarado automatizado"
type: docs
weight: 11
url: /es/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Representa los argumentos que se especifican para los métodos de enmascarado automatizado
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | Obtiene el número de objetos para separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Establece el número de objetos para separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo). |
| [getObjectsRectangles()](#getObjectsRectangles--) | Obtiene los rectángulos de los objetos que pertenecen a los objetos separados (opcional). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | Establece los rectángulos de los objetos que pertenecen a los objetos separados (opcional). |
| [getObjectsPoints()](#getObjectsPoints--) | Obtiene los puntos que pertenecen a los objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | Establece los puntos que pertenecen a los objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial. |
| [getOrphanedPoints()](#getOrphanedPoints--) | Obtiene los puntos que ya no pertenecen a ningún objeto (opcional). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | Establece los puntos que ya no pertenecen a ningún objeto (opcional). |
| [getPrecision()](#getPrecision--) | Obtiene la precisión del método de segmentación (opcional). |
| [setPrecision(double value)](#setPrecision-double-) | Establece la precisión del método de segmentación (opcional). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Obtiene el número máximo de iteraciones. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Establece el número máximo de iteraciones. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
Este ejemplo muestra cómo descomponer una imagen raster en múltiples imágenes usando enmascarado de imagen y el algoritmo de segmentación K-means. El enmascarado de imagen es una técnica de procesamiento de imágenes que se utiliza para separar el fondo de los objetos de la imagen en primer plano.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Establezca el número de clústeres (objetos separados). El valor predeterminado es 2, el objeto en primer plano y el fondo.
    args.setNumberOfObjects(3);

    // Establezca el número máximo de iteraciones.
    args.setMaxIterationNumber(50);

    // Establezca la precisión del método de segmentación (opcional)
    args.setPrecision(1);

    // Cada clúster (segmento) se almacenará en un archivo PNG separado.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Utilice el agrupamiento K-means.
    // El agrupamiento K-means permite dividir la imagen en varios clústeres (segmentos) independientes.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // El color de fondo será naranja.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Crea una instancia de la clase ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide la imagen fuente en varios clústeres (segmentos).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Obtenga imágenes del resultado del enmascarado y guárdelas en PNG.
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
Este ejemplo muestra cómo especificar sugerencias para el algoritmo de enmascarado de imagen para mejorar la precisión del método de segmentación (agrupamiento). El enmascarado de imagen es una técnica de procesamiento de imágenes que se utiliza para separar el fondo de los objetos de la imagen en primer plano.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Sugerencia #1.
    // Analice la imagen visualmente y establezca el área de interés. El resultado de la segmentación incluirá solo los objetos que estén completamente ubicados dentro de esta área.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Sugerencia #2.
    // Analiza la imagen visualmente y establece los puntos que pertenecen a objetos separados.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Cada clúster (segmento) se almacenará en un archivo PNG separado.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Utilice el agrupamiento GraphCut.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // El color de fondo será naranja.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Crea una instancia de la clase ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide la imagen fuente en varios clústeres (segmentos).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtenga imágenes del resultado del enmascarado y guárdelas en PNG.
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
// Opciones de exportación de enmascarado
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Utilice el agrupamiento GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// El color de fondo será transparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Reduciendo el tamaño de la imagen para acelerar el proceso de segmentación
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Crea una instancia de la clase ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide la imagen fuente en varios clústeres (segmentos).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Obteniendo la máscara de primer plano
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Aumenta el tamaño de la máscara al tamaño de la imagen original
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Aplicando la máscara a la imagen original para obtener un segmento de primer plano
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

// Opciones de exportación de enmascarado
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Utilice el agrupamiento GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// El color de fondo será naranja.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Iniciando una sesión por primera vez y guardando en un archivo
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Crea una instancia de la clase ImageMasking.
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

// Reanudando una sesión de enmascarado desde un archivo
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Crea una instancia de la clase ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analiza la imagen visualmente y establece los puntos que pertenecen a objetos separados.
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
            // Transferencia explícita de opciones de exportación, ya que no es serializable
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


Obtiene el número de objetos para separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo).

Valor: El número de objetos.

**Returns:**
int - el número de objetos para separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Establece el número de objetos para separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo).

Valor: El número de objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el número de objetos para separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Obtiene los rectángulos de los objetos que pertenecen a los objetos separados (opcional). Este parámetro se utiliza para aumentar la precisión del método de segmentación.

Valor: Los rectángulos de los objetos.

**Returns:**
com.aspose.imaging.Rectangle[] - los rectángulos de los objetos que pertenecen a los objetos separados (opcional).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Establece los rectángulos de los objetos que pertenecen a los objetos separados (opcional). Este parámetro se utiliza para aumentar la precisión del método de segmentación.

Valor: Los rectángulos de los objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | los rectángulos de los objetos que pertenecen a los objetos separados (opcional). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Obtiene los puntos que pertenecen a los objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial. Este parámetro se utiliza para aumentar la precisión del método de segmentación.

Valor: Los puntos de los objetos.

**Returns:**
com.aspose.imaging.Point[][] - los puntos que pertenecen a los objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Establece los puntos que pertenecen a objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a NumberOfObjects objetos de la imagen inicial. Este parámetro se usa para aumentar la precisión del método de segmentación.

Valor: Los puntos de los objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | los puntos que pertenecen a objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a NumberOfObjects objetos de la imagen inicial. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Obtiene los puntos que ya no pertenecen a ningún objeto (opcional). Este parámetro se usa solo en caso de resegmentación.

Valor: Los puntos huérfanos.

**Returns:**
com.aspose.imaging.Point[] - los puntos que ya no pertenecen a ningún objeto (opcional).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Establece los puntos que ya no pertenecen a ningún objeto (opcional). Este parámetro se usa solo en caso de resegmentación.

Valor: Los puntos huérfanos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | los puntos que ya no pertenecen a ningún objeto (opcional). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Obtiene la precisión del método de segmentación (opcional).

Valor: La precisión del método de segmentación (opcional).

**Returns:**
double - la precisión del método de segmentación (opcional).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Establece la precisión del método de segmentación (opcional).

Valor: La precisión del método de segmentación (opcional).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | la precisión del método de segmentación (opcional). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Obtiene el número máximo de iteraciones.

Valor: El número máximo máximo de iteraciones.

**Returns:**
int - el número máximo de iteraciones.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Establece el número máximo de iteraciones.

Valor: El número máximo máximo de iteraciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el número máximo de iteraciones. |

