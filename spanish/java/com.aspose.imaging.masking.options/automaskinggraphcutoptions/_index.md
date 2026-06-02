---
title: "AutoMaskingGraphCutOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de enmascarado automático GraphCut."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.masking.options/automaskinggraphcutoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.masking.options.MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions), [com.aspose.imaging.masking.options.GraphCutMaskingOptions](../../com.aspose.imaging.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Las opciones de enmascarado automático GraphCut.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Inicializa una nueva instancia de la clase [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Obtiene los trazos de primer plano predeterminados precalculados. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Obtiene los trazos de fondo predeterminados. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Obtiene los rectángulos predeterminados de los objetos. |
| [getAssumedObjects()](#getAssumedObjects--) | Obtiene los objetos asumidos. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--) | Establece los objetos asumidos. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Obtiene un valor que indica si los trazos predeterminados deben calcularse. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Establece un valor que indica si los trazos predeterminados deben calcularse. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Obtiene el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Establece el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados. |

## Example: Saving image masking result with feathering based on image size.
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. La propiedad Args de AutoMaskingGraphCutOptions puede omitirse ya que los trazos predeterminados se colocan allí al final. MaskingResult[] results;
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size.
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions.
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen y reutilizando las opciones de enmascarado para la nueva iteración de enmascarado. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Reutilizando AutoMaskingGraphCutOptions no es necesario realizar los cálculos de trazos predeterminados una segunda vez.
    options.setCalculateDefaultStrokes(false);
    // Cuando se proporcionan tanto los trazos predeterminados como ObjectsPoints en la propiedad Args de AutoMaskingArgs, los arreglos de puntos terminan combinados.
    // El primer arreglo ObjectsPoints se considera un arreglo de puntos de fondo y
    // el segundo arreglo ObjectsPoints se considera un arreglo de puntos de primer plano.
    // Cuando tanto DefaultObjectsRectangles como ObjectsRectangles en la propiedad Args de AutoMaskingArgs se proporcionan,
    // solo se utiliza el arreglo de Args.
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen, modificando los trazos predeterminados obtenidos y usándolos para la nueva iteración de enmascarado. El enmascarado de imagen se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado usando una nueva instancia de GraphCutMaskingOptions.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
```

### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Inicializa una nueva instancia de la clase [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions).

### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Obtiene los trazos de primer plano predeterminados precalculados.

**Returns:**
com.aspose.imaging.Point[] - los trazos predeterminados de primer plano pre‑calculados.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen y reutilizando las opciones de enmascarado para la nueva iteración de enmascarado. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Reutilizando AutoMaskingGraphCutOptions no es necesario realizar los cálculos de trazos predeterminados una segunda vez.
    options.setCalculateDefaultStrokes(false);
    // Cuando se proporcionan tanto los trazos predeterminados como ObjectsPoints en la propiedad Args de AutoMaskingArgs, los arreglos de puntos terminan combinados.
    // El primer arreglo ObjectsPoints se considera un arreglo de puntos de fondo y
    // el segundo arreglo ObjectsPoints se considera un arreglo de puntos de primer plano.
    // Cuando tanto DefaultObjectsRectangles como ObjectsRectangles en la propiedad Args de AutoMaskingArgs se proporcionan,
    // solo se utiliza el arreglo de Args.
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen, modificando los trazos predeterminados obtenidos y usándolos para la nueva iteración de enmascarado. El enmascarado de imagen se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado usando una nueva instancia de GraphCutMaskingOptions.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
```

### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Obtiene los trazos de fondo predeterminados.

**Returns:**
com.aspose.imaging.Point[] - los trazos predeterminados de fondo.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen y reutilizando las opciones de enmascarado para la nueva iteración de enmascarado. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Reutilizando AutoMaskingGraphCutOptions no es necesario realizar los cálculos de trazos predeterminados una segunda vez.
    options.setCalculateDefaultStrokes(false);
    // Cuando se proporcionan tanto los trazos predeterminados como ObjectsPoints en la propiedad Args de AutoMaskingArgs, los arreglos de puntos terminan combinados.
    // El primer arreglo ObjectsPoints se considera un arreglo de puntos de fondo y
    // el segundo arreglo ObjectsPoints se considera un arreglo de puntos de primer plano.
    // Cuando tanto DefaultObjectsRectangles como ObjectsRectangles en la propiedad Args de AutoMaskingArgs se proporcionan,
    // solo se utiliza el arreglo de Args.
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen, modificando los trazos predeterminados obtenidos y usándolos para la nueva iteración de enmascarado. El enmascarado de imagen se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado usando una nueva instancia de GraphCutMaskingOptions.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
```

### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Obtiene los rectángulos predeterminados de los objetos.

**Returns:**
com.aspose.imaging.Rectangle[] - los rectángulos predeterminados de objetos.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen y reutilizando las opciones de enmascarado para la nueva iteración de enmascarado. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Reutilizando AutoMaskingGraphCutOptions no es necesario realizar los cálculos de trazos predeterminados una segunda vez.
    options.setCalculateDefaultStrokes(false);
    // Cuando se proporcionan tanto los trazos predeterminados como ObjectsPoints en la propiedad Args de AutoMaskingArgs, los arreglos de puntos terminan combinados.
    // El primer arreglo ObjectsPoints se considera un arreglo de puntos de fondo y
    // el segundo arreglo ObjectsPoints se considera un arreglo de puntos de primer plano.
    // Cuando tanto DefaultObjectsRectangles como ObjectsRectangles en la propiedad Args de AutoMaskingArgs se proporcionan,
    // solo se utiliza el arreglo de Args.
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen, modificando los trazos predeterminados obtenidos y usándolos para la nueva iteración de enmascarado. El enmascarado de imagen se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado usando una nueva instancia de GraphCutMaskingOptions.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
```

### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Obtiene los objetos asumidos.

**Returns:**
java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> - los objetos asumidos.
### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Establece los objetos asumidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> | los objetos asumidos. |

### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Obtiene un valor que indica si los trazos predeterminados deben calcularse.

**Returns:**
boolean - un valor que indica si los trazos predeterminados deben calcularse.
### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Establece un valor que indica si los trazos predeterminados deben calcularse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si los trazos predeterminados deben calcularse. |


**Example: Saving image masking result with feathering based on image size.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. La propiedad Args de AutoMaskingGraphCutOptions puede omitirse ya que los trazos predeterminados se colocan allí al final. MaskingResult[] results;
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving image masking result with feathering based on image size.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions.
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen y reutilizando las opciones de enmascarado para la nueva iteración de enmascarado. El enmascarado de imagen se realiza usando trazos predeterminados auto calculados. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Reutilizando AutoMaskingGraphCutOptions no es necesario realizar los cálculos de trazos predeterminados una segunda vez.
    options.setCalculateDefaultStrokes(false);
    // Cuando se proporcionan tanto los trazos predeterminados como ObjectsPoints en la propiedad Args de AutoMaskingArgs, los arreglos de puntos terminan combinados.
    // El primer arreglo ObjectsPoints se considera un arreglo de puntos de fondo y
    // el segundo arreglo ObjectsPoints se considera un arreglo de puntos de primer plano.
    // Cuando tanto DefaultObjectsRectangles como ObjectsRectangles en la propiedad Args de AutoMaskingArgs se proporcionan,
    // solo se utiliza el arreglo de Args.
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Guardando el resultado del enmascarado de imagen con difuminado basado en el tamaño de la imagen, modificando los trazos predeterminados obtenidos y usándolos para la nueva iteración de enmascarado. El enmascarado de imagen se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado inicial del enmascarado, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascarado usando una nueva instancia de GraphCutMaskingOptions.
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

// En este punto, los trazos de primer plano/fondo aplicados pueden ser analizados y, basándose en ellos, adicionales
// los trazos de primer plano/fondo pueden ser proporcionados manualmente.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// liberar recursos
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

// liberar recursos
for (MaskingResult res : results)
{
    res.close();
}
```

### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Obtiene el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados.

Valor: El controlador de evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the default points pre-calculation process progress event handler.
### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Establece el controlador de eventos de progreso del proceso de pre-cálculo de puntos predeterminados.

Valor: El controlador de evento de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | el controlador de eventos de progreso del proceso de pre‑cálculo de puntos predeterminados. |

