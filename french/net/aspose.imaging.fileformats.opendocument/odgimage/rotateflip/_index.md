---
title: RotateFlip
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Fait pivoter retourne ou fait pivoter et retourne limage.
type: docs
weight: 70
url: /fr/net/aspose.imaging.fileformats.opendocument/odgimage/rotateflip/
---
## OdgImage.RotateFlip method

Fait pivoter, retourne ou fait pivoter et retourne l'image.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Type de retournement de rotation. |

### Exemples

Cet exemple charge une image ODG, la fait pivoter de 90 degrés dans le sens des aiguilles d'une montre et retourne éventuellement l'image horizontalement et (ou) verticalement.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // Rotation, retournement et sauvegarde dans le fichier de sortie.
    using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### Voir également

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype)
* class [OdgImage](../../odgimage)
* espace de noms [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
