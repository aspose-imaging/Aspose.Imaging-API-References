---
title: AddBlock
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Aggiunge un nuovo blocco Webp.
type: docs
weight: 80
url: /it/net/aspose.imaging.fileformats.webp/webpimage/addblock/
---
## WebPImage.AddBlock method

Aggiunge un nuovo blocco Webp.

```csharp
public void AddBlock(IFrame block)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| block | IFrame | Il blocco Webp da aggiungere. |

### Esempi

Questo esempio mostra come creare un'immagine WebP animata a più fotogrammi con le opzioni specificate.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Il frame predefinito più 36 + 36 frame aggiuntivi.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Crea un'immagine WebP di 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Il primo cerchio è rosso
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Il secondo cerchio è nero
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente l'angolo della forma dell'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Salva in un file WebP
    webPImage.Save(dir + "output.webp");
}
```

### Guarda anche

* interface [IFrame](../../iframe)
* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->