---
title: BufferSizeHint
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos.
type: docs
weight: 20
url: /es/net/aspose.imaging/loadoptions/buffersizehint/
---
## LoadOptions.BufferSizeHint property

Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos.

```csharp
public int BufferSizeHint { get; set; }
```

### El valor de la propiedad

La sugerencia del tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

### Ejemplos

El siguiente ejemplo muestra cómo establecer un límite de memoria al cargar una imagen CMX. El límite de memoria es el tamaño máximo permitido (en megabytes) para todos los búferes internos.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// Establecer un límite de memoria de 10 megabytes para una imagen cargada de destino.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "example.cmx", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 10 }))
{
    image.Save(dir + "output.png",
        new Aspose.Imaging.ImageOptions.PngOptions()
        {
            VectorRasterizationOptions =
                    new Aspose.Imaging.ImageOptions.CmxRasterizationOptions
                    {
                        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
                        SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias,
                        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
                    }
        });
}
```

El siguiente ejemplo muestra cómo establecer un límite de memoria al cargar una imagen JPEG. El límite de memoria es el tamaño máximo permitido (en megabytes) para todos los búferes internos.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// Establecer un límite de memoria de 50 megabytes para la imagen cargada de destino
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "inputFile.jpg", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 50 }))
{
    image.Save(dir + "outputFile_Baseline.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Baseline,
            Quality = 100
        });

    image.Save(dir + "outputFile_Progressive.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive
        });

    image.Save(dir + "outputFile_Lossless.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Lossless,
            BitsPerChannel = 4
        });

    image.Save(dir + "outputFile_JpegLs.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.JpegLs,
            JpegLsInterleaveMode = Aspose.Imaging.FileFormats.Jpeg.JpegLsInterleaveMode.None,
            JpegLsAllowedLossyError = 3,
            JpegLsPreset = null
        });
}
```

### Ver también

* class [LoadOptions](../../loadoptions)
* espacio de nombres [Aspose.Imaging](../../loadoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
