---
title: GetMask
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene la máscara de la imagen.
type: docs
weight: 30
url: /es/net/aspose.imaging.masking.result/imaskinglayer/getmask/
---
## IMaskingLayer.GetMask method

Obtiene la máscara de la imagen.

```csharp
public RasterImage GetMask()
```

### Valor_devuelto

Máscara de imagen de resultado.

### Ejemplos

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

* class [RasterImage](../../../aspose.imaging/rasterimage)
* interface [IMaskingLayer](../../imaskinglayer)
* espacio de nombres [Aspose.Imaging.Masking.Result](../../imaskinglayer)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->