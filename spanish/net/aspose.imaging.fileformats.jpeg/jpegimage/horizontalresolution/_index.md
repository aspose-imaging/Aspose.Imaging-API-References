---
title: HorizontalResolution
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece la resolución horizontal en píxeles por pulgada de esteRasterImageaspose.imaging/rasterimage .
type: docs
weight: 100
url: /es/net/aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution/
---
## JpegImage.HorizontalResolution property

Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este[`RasterImage`](../../../aspose.imaging/rasterimage) .

```csharp
public override double HorizontalResolution { get; set; }
```

### El valor de la propiedad

La resolución horizontal.

### Observaciones

Tenga en cuenta que, de forma predeterminada, este valor siempre es 96, ya que las diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

### Ejemplos

El siguiente ejemplo muestra cómo configurar la resolución horizontal/vertical de una imagen JPEG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)image;

    // Obtener resolución horizontal y vertical de BmpImage
    double horizontalResolution = jpegImage.HorizontalResolution;
    double verticalResolution = jpegImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Use el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpegImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpegImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpegImage.VerticalResolution);
    }

    // La salida puede verse así:
    // La resolución horizontal, en píxeles por pulgada: 300
    // La resolución vertical, en píxeles por pulgada: 300
    // Establecer valores de resolución a 96 dpi
    // La resolución horizontal, en píxeles por pulgada: 96
    // La resolución vertical, en píxeles por pulgada: 96
}
```

### Ver también

* class [JpegImage](../../jpegimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
