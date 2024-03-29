---
title: Compress
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta un valore che indica se questoICompressedOptions è compresso.
type: docs
weight: 20
url: /it/net/aspose.imaging.imageoptions/metafileoptions/compress/
---
## MetafileOptions.Compress property

Ottiene o imposta un valore che indica se questoICompressedOptions è compresso.

```csharp
public bool Compress { get; set; }
```

### Valore della proprietà

`VERO` se compresso; altrimenti,`falso` .

### Esempi

L'esempio seguente mostra come convertire un'immagine emf in emz fromat

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

L'esempio seguente mostra come convertire un'immagine wmf in wmz fromat

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### Guarda anche

* class [MetafileOptions](../../metafileoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../metafileoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
