---
title: PageSize
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el tamaño de la página.
type: docs
weight: 80
url: /es/net/aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize/
---
## VectorRasterizationOptions.PageSize property

Obtiene o establece el tamaño de la página.

```csharp
public SizeF PageSize { get; set; }
```

### Ejemplos

Este ejemplo muestra cómo cargar una imagen WMF desde un archivo y convertirla a SVG usando WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// El uso de Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // El texto se convertirá en formas.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // El tamaño de la página.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Si existe una emf incrustada, renderizar emf; de lo contrario renderizar wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

Este ejemplo muestra cómo cargar una imagen EMF desde un archivo y convertirla a SVG usando EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// El uso de Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // El texto se convertirá en formas.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // El tamaño de la página.
    rasterizationOptions.PageSize = emfImage.Size;

    // Si existe una emf incrustada, renderizar emf; de lo contrario renderizar wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Establecer el margen horizontal
    rasterizationOptions.BorderX = 50;

    // Establecer el margen vertical
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

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

* struct [SizeF](../../../aspose.imaging/sizef)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
