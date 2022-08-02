---
title: PageTitles
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece los títulos de página.
type: docs
weight: 80
url: /es/net/aspose.imaging.imageoptions/multipageoptions/pagetitles/
---
## MultiPageOptions.PageTitles property

Obtiene o establece los títulos de página.

```csharp
public string[] PageTitles { get; set; }
```

### El valor de la propiedad

Los títulos de página.

### Ejemplos

Este ejemplo muestra cómo convertir una imagen DJVU de varias páginas en una imagen TIFF de varios cuadros.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivos.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // Tenga en cuenta que si la imagen es colorida, se convertirá automáticamente a formato B/N de acuerdo con la siguiente opción:
        saveOptions.BitsPerSample = new ushort[] { 1 };

        saveOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.DjvuMultiPageOptions();

        // De forma predeterminada, todas las páginas se almacenarán en el TIFF de salida, pero el conjunto de páginas deseado se puede especificar explícitamente.
        // Solo se exportarán la primera y la segunda página.
        saveOptions.MultiPageOptions.Pages = new int[] { 0, 1 };

        // Establecer títulos de página.
        saveOptions.MultiPageOptions.PageTitles = new string[] { "The First Page", "The Second Page" };

        // Guardar en TIFF
        djvuImage.Save(dir + "sample.tif", saveOptions);
    }
}
```

### Ver también

* class [MultiPageOptions](../../multipageoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../multipageoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->