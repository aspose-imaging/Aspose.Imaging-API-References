---
title: RotateFlip
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ruota capovolge o ruota e capovolge limmagine.
type: docs
weight: 140
url: /it/net/aspose.imaging/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Ruota, capovolge o ruota e capovolge l'immagine.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Il tipo di capovolgimento ruota. |

### Esempi

Questo esempio carica un'immagine raster memorizzata nella cache, la ruota di 90 gradi in senso orario e facoltativamente capovolge l'immagine orizzontalmente e/o verticalmente.

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
    using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

### Guarda anche

* enum [RotateFlipType](../../rotatefliptype)
* class [RasterCachedImage](../../rastercachedimage)
* spazio dei nomi [Aspose.Imaging](../../rastercachedimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->