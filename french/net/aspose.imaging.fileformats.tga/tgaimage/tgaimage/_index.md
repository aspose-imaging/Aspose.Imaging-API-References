---
title: TgaImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duTgaImageaspose.imaging.fileformats.tga/tgaimage classe.
type: docs
weight: 10
url: /fr/net/aspose.imaging.fileformats.tga/tgaimage/tgaimage/
---
## TgaImage(string) {#constructor_2}

Initialise une nouvelle instance du[`TgaImage`](../../tgaimage) classe.

```csharp
public TgaImage(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin pour charger une image. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Le chemin spécifié est nul. |

### Voir également

* class [TgaImage](../../tgaimage)
* espace de noms [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* Assemblée [Aspose.Imaging](../../../)

---

## TgaImage(RasterImage) {#constructor}

Initialise une nouvelle instance du[`TgaImage`](../../tgaimage) classe.

```csharp
public TgaImage(RasterImage rasterImage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image raster. |

### Exemples

Chargement de l'image PNG, conversion de celle-ci en TgaImage et enregistrement en tant qu'image TGA.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TgaImage](../../tgaimage)
* espace de noms [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* Assemblée [Aspose.Imaging](../../../)

---

## TgaImage(Stream) {#constructor_1}

Initialise une nouvelle instance du[`TgaImage`](../../tgaimage) classe.

```csharp
public TgaImage(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux pour charger une image. |

### Voir également

* class [TgaImage](../../tgaimage)
* espace de noms [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
