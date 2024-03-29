---
title: Compress
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece un valor que indica si esteICompressedOptions está comprimido.
type: docs
weight: 40
url: /es/net/aspose.imaging.imageoptions/svgoptions/compress/
---
## SvgOptions.Compress property

Obtiene o establece un valor que indica si esteICompressedOptions está comprimido.

```csharp
public bool Compress { get; set; }
```

### El valor de la propiedad

`verdadero` si está comprimido; de lo contrario,`falso` .

### Ejemplos

El siguiente ejemplo muestra cómo convertir imágenes svg a svgz fromat

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### Ver también

* class [SvgOptions](../../svgoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../svgoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
