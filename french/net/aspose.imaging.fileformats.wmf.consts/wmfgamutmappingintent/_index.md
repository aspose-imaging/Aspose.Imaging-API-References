---
title: WmfGamutMappingIntent
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération GamutMappingIntent spécifie la relation entre les couleurs logiques et physiques.
type: docs
weight: 8190
url: /fr/net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
## WmfGamutMappingIntent enumeration

L'énumération GamutMappingIntent spécifie la relation entre les couleurs logiques et physiques.

```csharp
[Flags]
public enum WmfGamutMappingIntent
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| LCS_GM_ABS_COLORIMETRIC | `8` | Spécifie que le point blanc DEVRAIT être conservé. Généralement utilisé lorsque les couleurs logiques DOIVENT correspondre à leur couleur physique la plus proche dans la gamme de couleurs de destination. Intention : Match Nom ICC : Absolute Colorimetric |
| LCS_GM_BUSINESS | `1` | Spécifie que la saturation DOIT être maintenue. Généralement utilisé pour les graphiques d'entreprise et d'autres situations dans lesquelles le tramage n'est pas nécessaire. Intention : Graphic Nom ICC : Saturation |
| LCS_GM_GRAPHICS | `2` | Spécifie qu'une correspondance colorimétrique DOIT être maintenue. Généralement utilisé pour les conceptions graphiques et les couleurs nommées. Intention : Proof Nom ICC : Relative Colorimetric |
| LCS_GM_IMAGES | `4` | Spécifie que le contraste DEVRAIT être maintenu. Généralement utilisé pour photographies et images naturelles. Intention : Picture Nom ICC : Perceptual |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
