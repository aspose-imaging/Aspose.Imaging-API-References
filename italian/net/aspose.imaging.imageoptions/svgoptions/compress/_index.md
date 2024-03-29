---
title: Compress
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta un valore che indica se questoICompressedOptions è compresso.
type: docs
weight: 40
url: /it/net/aspose.imaging.imageoptions/svgoptions/compress/
---
## SvgOptions.Compress property

Ottiene o imposta un valore che indica se questoICompressedOptions è compresso.

```csharp
public bool Compress { get; set; }
```

### Valore della proprietà

`VERO` se compresso; altrimenti,`falso` .

### Esempi

L'esempio seguente mostra come convertire un'immagine svg in svgz fromat

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

### Guarda anche

* class [SvgOptions](../../svgoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../svgoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
