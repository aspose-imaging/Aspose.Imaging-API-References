---
title: TextRenderingHint
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece la sugerencia de representación de texto.
type: docs
weight: 120
url: /es/net/aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint/
---
## VectorRasterizationOptions.TextRenderingHint property

Obtiene o establece la sugerencia de representación de texto.

```csharp
public TextRenderingHint TextRenderingHint { get; set; }
```

### El valor de la propiedad

La sugerencia de representación de texto.

### Ejemplos

Este ejemplo muestra cómo cargar una imagen SVG desde un archivo y rasterizarla a PNG usando varias opciones.

```csharp
[C#]

string dir = "c:\\temp\\";

// El uso de Aspose.Imaging.Image.Load es una forma unificada de cargar imágenes.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
    // Para rasterizar SVG necesitamos especificar las opciones de rasterización.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

    // Establecer el color predeterminado de un fondo para una imagen. El valor predeterminado es blanco.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

    // Establecer el tamaño de la página
    rasterizationOptions.PageSize = svgImage.Size;

    // El antialiasing se aplica a las líneas y curvas y los bordes de las áreas rellenas.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

    // Cada carácter se dibuja utilizando su mapa de bits de glifo suavizado sin sugerencias.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // Reducir el tamaño de la imagen 10 veces, es decir, el tamaño de salida será el 10% del tamaño original.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // Guardar en un archivo PNG
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### Ver también

* enum [TextRenderingHint](../../../aspose.imaging/textrenderinghint)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
