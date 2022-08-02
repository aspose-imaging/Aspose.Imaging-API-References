---
title: RenderMode
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el modo de renderizado WMF.
type: docs
weight: 20
url: /es/net/aspose.imaging.imageoptions/wmfrasterizationoptions/rendermode/
---
## WmfRasterizationOptions.RenderMode property

Obtiene o establece el modo de renderizado WMF.

```csharp
public WmfRenderMode RenderMode { get; set; }
```

### El valor de la propiedad

El modo de renderizado WMF.

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

### Ver también

* enum [WmfRenderMode](../../../aspose.imaging.fileformats.wmf/wmfrendermode)
* class [WmfRasterizationOptions](../../wmfrasterizationoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../wmfrasterizationoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->