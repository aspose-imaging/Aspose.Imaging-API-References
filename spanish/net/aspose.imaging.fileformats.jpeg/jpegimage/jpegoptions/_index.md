---
title: JpegOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene las opciones de JPEG utilizadas para crear o cargar esteJpegImageaspose.imaging.fileformats.jpeg/jpegimage instancia.
type: docs
weight: 130
url: /es/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

Obtiene las opciones de JPEG utilizadas para crear o cargar este[`JpegImage`](../../jpegimage) instancia.

```csharp
public JpegOptions JpegOptions { get; }
```

### El valor de la propiedad

Las opciones JPEG.

### Ejemplos

El siguiente ejemplo muestra cómo extraer la información del encabezado de una imagen JPEG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = image.JpegOptions;

    System.Console.WriteLine("The number of bits per channel: {0}", jpegOptions.BitsPerChannel);
    System.Console.WriteLine("The max allowed size for all internal buffers: {0}", jpegOptions.BufferSizeHint);
    System.Console.WriteLine("The color type: {0}", jpegOptions.ColorType);
    System.Console.WriteLine("The compression type: {0}", jpegOptions.CompressionType);
    System.Console.WriteLine("The image quality: {0}", jpegOptions.Quality);

    if (jpegOptions.ResolutionSettings != null)
    {
        System.Console.WriteLine("The horizontal resolution: {0}", jpegOptions.ResolutionSettings.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution: {0}", jpegOptions.ResolutionSettings.VerticalResolution);
    }

    for (int i = 0; i < jpegOptions.HorizontalSampling.Length; i++)
    {
        System.Console.WriteLine("The sampling for component {0}: {1}x{2}", i, jpegOptions.HorizontalSampling[i], jpegOptions.VerticalSampling[i]);
    }
}

//La salida se ve así:
//El número de bits por canal: 8
//El tamaño máximo permitido para todos los búferes internos: 0
//El tipo de color: YCbCr
//El tipo de compresión: Línea base
//La calidad de imagen: 75
//El muestreo para el componente 0: 1x1
//El muestreo para el componente 1: 1x1
//El muestreo para el componente 2: 1x1
```

### Ver también

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
