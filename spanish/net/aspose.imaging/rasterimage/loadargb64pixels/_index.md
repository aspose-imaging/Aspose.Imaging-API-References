---
title: LoadArgb64Pixels
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Carga píxeles ARGB de 64 bits.
type: docs
weight: 370
url: /es/net/aspose.imaging/rasterimage/loadargb64pixels/
---
## RasterImage.LoadArgb64Pixels method

Carga píxeles ARGB de 64 bits.

```csharp
public long[] LoadArgb64Pixels(Rectangle rectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | El rectángulo desde el que cargar píxeles. |

### Valor_devuelto

La matriz de píxeles ARGB de 64 bits cargada.

### Ejemplos

El siguiente ejemplo muestra cómo cargar y procesar píxeles de una imagen ráster. Los píxeles se representan como valores enteros de 64 bits. Por ejemplo, considere un problema de contar los píxeles completamente transparentes de una imagen.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\16rgba.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Carga píxeles para toda la imagen. Cualquier parte rectangular de la imagen se puede especificar como parámetro del método Aspose.Imaging.RasterImage.LoadArgb64Pixels.
    // Tenga en cuenta que la imagen en sí debe tener 16 bits por muestra, porque Aspose.Imaging.RasterImage.LoadArgb64Pixels no funciona con 8 bits por muestra.
    // Para trabajar con 8 bits por muestra, utilice el antiguo método Aspose.Imaging.RasterImage.LoadArgb32Pixels.
    long[] pixels = rasterImage.LoadArgb64Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        // Tenga en cuenta que todos los componentes de color, incluido el alfa, están representados por valores de 16 bits, por lo que sus valores permitidos están en el rango [0, 63535].
        int alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}
```

### Ver también

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* espacio de nombres [Aspose.Imaging](../../rasterimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->