---
title: ScaleX
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta la scala x.
type: docs
weight: 20
url: /it/net/aspose.imaging.imageoptions/svgrasterizationoptions/scalex/
---
## SvgRasterizationOptions.ScaleX property

Ottiene o imposta la scala x.

```csharp
public float ScaleX { get; set; }
```

### Valore della proprietà

La scala x.

### Esempi

Questo esempio mostra come caricare un'immagine SVG da un file e rasterizzarla in PNG utilizzando varie opzioni.

```csharp
[C#]

string dir = "c:\\temp\\";

// L'uso di Aspose.Imaging.Image.Load è un modo unificato per caricare l'immagine.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
    // Per rasterizzare SVG dobbiamo specificare le opzioni di rasterizzazione.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

    // Imposta il colore predefinito di uno sfondo per un'immagine. Il valore predefinito è bianco.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

    // Imposta la dimensione della pagina
    rasterizationOptions.PageSize = svgImage.Size;

    // L'antialias viene applicato a linee e curve e ai bordi delle aree riempite.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

    // Ogni carattere viene disegnato usando la sua bitmap del glifo con antialias senza alcun suggerimento.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // Ridurre la dimensione dell'immagine 10 volte, ovvero la dimensione dell'output sarà il 10% della dimensione originale.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // Salva in un file PNG
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### Guarda anche

* class [SvgRasterizationOptions](../../svgrasterizationoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../svgrasterizationoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
