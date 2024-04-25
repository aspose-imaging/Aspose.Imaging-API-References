---
title: ResizeHeightProportionally
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa.
type: docs
weight: 210
url: /es/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa.

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newHeight | Int32 | La nueva altura. |

### Ver también

* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

Cambia el tamaño de la altura proporcionalmente.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newHeight | Int32 | La nueva altura. |
| resizeType | ResizeType | Tipo de cambio de tamaño. |

### Ejemplos

Este ejemplo carga una imagen y la cambia de tamaño proporcionalmente utilizando varios métodos de cambio de tamaño. Solo se especifica la altura, el ancho se calcula automáticamente.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Escale hasta 2 veces usando el remuestreo del vecino más cercano.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Reduzca la escala 2 veces usando el remuestreo del vecino más cercano.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Escale hasta 2 veces usando el remuestreo bilineal.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Reduzca la escala 2 veces usando el remuestreo bilineal.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
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

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

Cambia el tamaño de la altura proporcionalmente.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newHeight | Int32 | La nueva altura. |
| settings | ImageResizeSettings | La configuración de cambio de tamaño de la imagen. |

### Ver también

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
