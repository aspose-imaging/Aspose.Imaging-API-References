---
title: AdjustBrightness
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Ajustement dunbrightness pour image.
type: docs
weight: 230
url: /fr/net/aspose.imaging.fileformats.gif/gifimage/adjustbrightness/
---
## GifImage.AdjustBrightness method

Ajustement d'un*brightness* pour image.

```csharp
public override void AdjustBrightness(int brightness)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| brightness | Int32 | Valeur de luminosité. |

### Exemples

L'exemple suivant effectue la correction de la luminosité d'une image GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Définit la valeur de luminosité. Les valeurs de luminosité acceptées sont dans la plage [-255, 255].
    gifImage.AdjustBrightness(50);
    gifImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [GifImage](../../gifimage)
* espace de noms [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->