---
title: TransparentColor
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene il colore trasparente.
type: docs
weight: 130
url: /it/net/aspose.imaging.fileformats.png/pngimage/transparentcolor/
---
## PngImage.TransparentColor property

Ottiene il colore trasparente.

```csharp
public override Color TransparentColor { get; set; }
```

### Esempi

L'esempio seguente mostra come impostare colori completamente trasparenti per una parte di un'immagine PNG TrueColor che non supporta il canale alfa.

```csharp
[C#]

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\transparent.png", false);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.Truecolor;

// Crea un'immagine PNG TrueColor di 100x100 px.
using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);

    // Tutti i pixel rossi saranno considerati completamente trasparenti.
    pngImage.TransparentColor = Aspose.Imaging.Color.Red;
    pngImage.HasTransparentColor = true;

    // Tutti i pixel trasparenti avranno un colore di sfondo.
    pngImage.BackgroundColor = Aspose.Imaging.Color.Green;
    pngImage.HasBackgroundColor = true;

    // Riempi l'intera immagine con il colore bianco.
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White), pngImage.Bounds);

    // Riempi il quarto in alto a sinistra dell'immagine con il colore trasparente.
    // Questo rende il quarto in alto a sinistra colorato nel colore di sfondo.
    Rectangle rect = new Rectangle(0, 0, pngImage.Width / 2, pngImage.Height / 2);
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red), rect);

    pngImage.Save();
}
```

### Guarda anche

* struct [Color](../../../aspose.imaging/color)
* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->