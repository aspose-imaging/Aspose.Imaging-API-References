---
title: RotateFlip
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ruota capovolge o ruota e capovolge limmagine.
type: docs
weight: 70
url: /it/net/aspose.imaging.fileformats.opendocument/odgimage/rotateflip/
---
## OdgImage.RotateFlip method

Ruota, capovolge o ruota e capovolge l'immagine.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Tipo di rotazione della rotazione. |

### Esempi

Questo esempio carica un'immagine ODG, la ruota di 90 gradi in senso orario e facoltativamente capovolge l'immagine orizzontalmente e/o verticalmente.

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
    // Ruota, capovolgi e salva nel file di output.
    using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### Guarda anche

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype)
* class [OdgImage](../../odgimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
