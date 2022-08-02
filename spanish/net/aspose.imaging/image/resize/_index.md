---
title: Resize
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa.
type: docs
weight: 200
url: /es/net/aspose.imaging/image/resize/
---
## Resize(int, int) {#resize}

Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | La nueva altura. |

### Ejemplos

El siguiente ejemplo muestra cómo cambiar el tamaño de un metarchivo (WMF y EMF).

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string[] fileNames = new[] { "image3.emf", "image4.wmf" };
foreach (string fileName in fileNames)
{
    string inputFilePath = dir + fileName;
    string outputFilePath = dir + "Downscale_" + fileName;

    using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
    {
        image.Resize(image.Width / 4, image.Height / 4);
        image.Save(outputFilePath);
    }
}
```

El siguiente ejemplo muestra cómo cambiar el tamaño de una imagen SVG y guardarla en PNG.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3549";
string[] fileNames = new string[]
{
    "Logotype.svg",
    "sample_car.svg",
    "rg1024_green_grapes.svg",
    "MidMarkerFigure.svg",
    "embeddedFonts.svg"
};

Aspose.Imaging.PointF[] scales = new Aspose.Imaging.PointF[]
{
    new Aspose.Imaging.PointF(0.5f, 0.5f),
    new Aspose.Imaging.PointF(1f, 1f),
    new Aspose.Imaging.PointF(2f, 2f),
    new Aspose.Imaging.PointF(3.5f, 9.2f),
};

foreach (string inputFile in fileNames)
{
    foreach (Aspose.Imaging.PointF scale in scales)
    {
        string outputFile = string.Format("{0}_{1}_{2}.png", inputFile, scale.X.ToString(System.Globalization.CultureInfo.InvariantCulture), scale.Y.ToString(System.Globalization.CultureInfo.InvariantCulture));
        using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, inputFile)))
        {
            image.Resize((int)(image.Width * scale.X), (int)(image.Height * scale.Y));
            image.Save(System.IO.Path.Combine(dir, outputFile), new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Ver también

* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Cambia el tamaño de la imagen.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | La nueva altura. |
| resizeType | ResizeType | El tipo de cambio de tamaño. |

### Ejemplos

Cambie el tamaño de la imagen usando un tipo de cambio de tamaño específico.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Este ejemplo carga una imagen y la cambia de tamaño utilizando varios métodos de cambio de tamaño.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Escale hasta 2 veces usando el remuestreo del vecino más cercano.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Reduzca la escala 2 veces usando el remuestreo del vecino más cercano.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Escale hasta 2 veces usando el remuestreo bilineal.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Reduzca la escala 2 veces usando el remuestreo bilineal.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

Uso de una máscara de segmento para acelerar el proceso de segmentación

```csharp
[C#]

// Opciones de exportación de enmascaramiento
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Usar el agrupamiento de GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// El color de fondo será transparente.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Reduciendo el tamaño de la imagen para acelerar el proceso de segmentación
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Crea una instancia de la clase ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divide la imagen de origen en varios grupos (segmentos).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Obtener la máscara de primer plano
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Aumentar el tamaño de la máscara al tamaño de la imagen original
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Aplicando la máscara a la imagen original para obtener un segmento de primer plano
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### Ver también

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Cambia el tamaño de la imagen.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | La nueva altura. |
| settings | ImageResizeSettings | La configuración de cambio de tamaño. |

### Ejemplos

Cambie el tamaño de la imagen usando un tipo de cambio de tamaño específico.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Este ejemplo carga una imagen y la cambia de tamaño usando varias configuraciones de cambio de tamaño.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// El algoritmo adaptativo basado en función racional ponderada y combinada e interpolación lanczos3.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// El pequeño filtro rectangular
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// El número de colores en la paleta.
resizeSettings.EntriesCount = 256;

// No se utiliza la cuantización de color
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// El método euclidiano
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Reduzca la escala 2 veces usando el remuestreo adaptativo.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### Ver también

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
