---
title: BackgroundColor
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta un colore di sfondo.
type: docs
weight: 20
url: /it/net/aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor/
---
## VectorRasterizationOptions.BackgroundColor property

Ottiene o imposta un colore di sfondo.

```csharp
public Color BackgroundColor { get; set; }
```

### Esempi

Questo esempio mostra come caricare un'immagine WMF da un file e convertirla in SVG utilizzando WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// L'uso di Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Il testo verrà convertito in forme.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // La dimensione della pagina.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Se esiste emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

Questo esempio mostra come caricare un'immagine EMF da un file e convertirla in SVG utilizzando EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// L'uso di Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // Il testo verrà convertito in forme.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // La dimensione della pagina.
    rasterizationOptions.PageSize = emfImage.Size;

    // Se esiste emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Imposta il margine orizzontale
    rasterizationOptions.BorderX = 50;

    // Imposta il margine verticale
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

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

* struct [Color](../../../aspose.imaging/color)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
