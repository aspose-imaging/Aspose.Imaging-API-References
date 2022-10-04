---
title: AddBlock
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Ajoute un nouveau bloc Webp.
type: docs
weight: 80
url: /fr/net/aspose.imaging.fileformats.webp/webpimage/addblock/
---
## WebPImage.AddBlock method

Ajoute un nouveau bloc Webp.

```csharp
public void AddBlock(IFrame block)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| block | IFrame | Le bloc Webp à ajouter. |

### Exemples

Cet exemple montre comment créer une image WebP animée à plusieurs images avec les options spécifiées.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Le cadre par défaut plus 36 + 36 cadres supplémentaires.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Crée une image WebP de 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Le premier cercle est rouge
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Le deuxième cercle est noir
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Augmente progressivement l'angle de la forme d'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Augmente progressivement l'angle de l'arc noir et efface l'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Enregistrer dans un fichier WebP
    webPImage.Save(dir + "output.webp");
}
```

### Voir également

* interface [IFrame](../../iframe)
* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->