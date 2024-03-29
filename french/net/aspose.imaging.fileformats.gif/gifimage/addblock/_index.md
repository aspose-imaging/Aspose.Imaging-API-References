---
title: AddBlock
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Ajoute un nouveau bloc GIF.
type: docs
weight: 210
url: /fr/net/aspose.imaging.fileformats.gif/gifimage/addblock/
---
## GifImage.AddBlock method

Ajoute un nouveau bloc GIF.

```csharp
public void AddBlock(IGifBlock block)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| block | IGifBlock | Le bloc GIF à ajouter. |

### Exemples

L'exemple suivant montre comment composer une image GIF animée à partir de blocs GIF individuels.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image GIF 100 x 100 px.
// Le premier bloc est entièrement noir par défaut.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Le premier cercle est rouge
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Le deuxième cercle est noir
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Augmente progressivement l'angle de la forme d'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Augmente progressivement l'angle de l'arc noir et efface l'arc rouge.
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

### Voir également

* interface [IGifBlock](../../igifblock)
* class [GifImage](../../gifimage)
* espace de noms [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
