---
title: Crop
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Recadrage de limage.
type: docs
weight: 220
url: /fr/net/aspose.imaging.fileformats.djvu/djvuimage/crop/
---
## Crop(Rectangle) {#crop}

Recadrage de l'image.

```csharp
public override void Crop(Rectangle rectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle. |

### Exemples

L'exemple suivant recadre une image DJVU. La zone de recadrage est spécifiée via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Rogner l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(djvuImage.Width / 4, djvuImage.Height / 4, djvuImage.Width / 2, djvuImage.Height / 2);
    djvuImage.Crop(area);

    // Enregistre l'image recadrée au format PNG
    djvuImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [DjvuImage](../../djvuimage)
* espace de noms [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* Assemblée [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Recadrer l'image avec des décalages.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| leftShift | Int32 | Le décalage à gauche. |
| rightShift | Int32 | Le virage à droite. |
| topShift | Int32 | Le changement supérieur. |
| bottomShift | Int32 | Le décalage du bas. |

### Voir également

* class [DjvuImage](../../djvuimage)
* espace de noms [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->