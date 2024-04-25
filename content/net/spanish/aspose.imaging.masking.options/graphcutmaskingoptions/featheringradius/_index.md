---
title: FeatheringRadius
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el radio de calado.
type: docs
weight: 20
url: /es/aspose.imaging.masking.options/graphcutmaskingoptions/featheringradius/
---
## GraphCutMaskingOptions.FeatheringRadius property

Obtiene o establece el radio de calado.

```csharp
public int FeatheringRadius { get; set; }
```

### Ejemplos

Guardar resultado de enmascaramiento de imagen con calado basado en el tamaño de la imagen. El enmascaramiento de imágenes se realiza utilizando trazos predeterminados calculados automáticamente. La propiedad Args de AutoMaskingGraphCutOptions se puede omitir ya que los trazos predeterminados se colocan allí al final.

```csharp
[C#]

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
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

Guardar resultado de enmascaramiento de imagen con calado basado en el tamaño de la imagen. El enmascaramiento de imágenes se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions.

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

Guardar el resultado del enmascaramiento de la imagen del corte del gráfico con el calado establecido en 3. El enmascaramiento de la imagen se realiza utilizando la matriz de puntos especificada.

```csharp
[C#]

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    GraphCutMaskingOptions options = new GraphCutMaskingOptions()
                                                {
                                                    FeatheringRadius = 3,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent,
                                                    Args = new AutoMaskingArgs()
                                                            {
                                                                ObjectsPoints = new Point[][]
                                                                                    {
                                                                                        new Point[]
                                                                                            {
                                                                                                new Point(100, 100),
                                                                                            },
                                                                                    }
                                                            }
                                                };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Guardar el resultado del enmascaramiento de imágenes con difuminado basado en el tamaño de la imagen y reutilizar las opciones de enmascaramiento para la nueva iteración de enmascaramiento. El enmascaramiento de imágenes se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado de enmascaramiento inicial, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascaramiento.

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

// En este punto, se pueden analizar los trazos aplicados de primer plano/fondo y, en función de ellos, 
// los trazos de primer plano/fondo se pueden proporcionar manualmente.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // Reutilizando AutoMaskingGraphCutOptions no es necesario realizar cálculos de trazos predeterminados por segunda vez.
    options.CalculateDefaultStrokes = false;
    // Cuando se proporcionan trazos predeterminados y ObjectsPoints en la propiedad Args de AutoMaskingArgs, las matrices de puntos terminan combinadas.
    // La primera matriz ObjectsPoints se considera una matriz de puntos de fondo y 
    // la segunda matriz ObjectsPoints se considera una matriz de puntos de primer plano.
    // Cuando se proporcionan tanto DefaultObjectsRectangles como ObjectsRectangles en la propiedad Args de AutoMaskingArgs, 
    // solo se usa la matriz de Args.
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

Guardando el resultado del enmascaramiento de la imagen con difuminado basado en el tamaño de la imagen, modificando los trazos predeterminados obtenidos y usándolos para la nueva iteración de enmascaramiento. El enmascaramiento de imágenes se realiza utilizando trazos predeterminados calculados automáticamente. Además, los datos de los dos objetos asumidos también se especifican en la propiedad AssumedObjects de AutoMaskingGraphCutOptions. Después de obtener el resultado de enmascaramiento inicial, los trazos de fondo/primer plano aplicados se modifican y se realiza otra iteración de enmascaramiento utilizando la nueva instancia de GraphCutMaskingOptions.

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

// En este punto, se pueden analizar los trazos aplicados de primer plano/fondo y, en función de ellos, 
// los trazos de primer plano/fondo se pueden proporcionar manualmente.
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

### Ver también

* class [GraphCutMaskingOptions](../../graphcutmaskingoptions)
* espacio de nombres [Aspose.Imaging.Masking.Options](../../graphcutmaskingoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
