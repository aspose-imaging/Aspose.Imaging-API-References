---
title: LoadBlockByFirstSupportedDescriptor
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Charge le bloc gif en utilisant le premier opener trouvé adapté au spécifiéstream .
type: docs
weight: 40
url: /fr/net/aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/
---
## GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor method

Charge le bloc gif en utilisant le premier opener trouvé adapté au spécifié*stream* .

```csharp
public static IGifBlock LoadBlockByFirstSupportedDescriptor(Stream stream, 
    IColorPalette containerPalette)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| containerPalette | IColorPalette | La palette du conteneur. |

### Return_Value

Le bloc gif chargé ou nul si aucun ouvreur n'est trouvé.

### Remarques

Le premier ouvreur sera en fait le dernier inscrit.

### Voir également

* interface [IGifBlock](../../igifblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifBlocksRegistry](../../gifblocksregistry)
* espace de noms [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->