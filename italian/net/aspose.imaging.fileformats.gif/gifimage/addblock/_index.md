---
title: AddBlock
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Aggiunge un nuovo blocco GIF.
type: docs
weight: 210
url: /it/net/aspose.imaging.fileformats.gif/gifimage/addblock/
---
## GifImage.AddBlock method

Aggiunge un nuovo blocco GIF.

```csharp
public void AddBlock(IGifBlock block)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| block | IGifBlock | Il blocco GIF da aggiungere. |

### Esempi

L'esempio seguente mostra come comporre un'immagine GIF animata da singoli blocchi GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine GIF 100 x 100 px.
// Il primo blocco è completamente nero per impostazione predefinita.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Il primo cerchio è rosso
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Il secondo cerchio è nero
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente l'angolo della forma dell'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Guarda anche

* interface [IGifBlock](../../igifblock)
* class [GifImage](../../gifimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
