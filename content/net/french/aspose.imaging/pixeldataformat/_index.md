---
title: PixelDataFormat
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Le format de données en pixels. Ceci est un objet immuable.
type: docs
weight: 10720
url: /fr/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

Le format de données en pixels. Ceci est un objet immuable.

```csharp
public class PixelDataFormat
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 32 bits par pixel avec 8 bits pour chacun des cyan, magenta, jaune et noir. |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka) { get; } | Obtient l'acmyk. |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat)défini pour 8 bits par pixel avec 8 bits représentant l'intensité des niveaux de gris dans l'intervalle 0-255. |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 16 bits par pixel avec 8 bits représentant l'intensité des niveaux de gris dans l'intervalle 0-255 et un composant alpha supplémentaire de 8 bits. |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 16 bits par pixel avec 5 bits pour chacun des rouges, verts et bleus, alpha n'est pas défini. |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 16 bits par pixel avec 5 bits pour le rouge, 6 bits pour le vert et 5 bits pour le bleu, alpha n'est pas défini. |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 24 bits par pixel avec 8 bits pour chacun des alpha, rouge, vert et bleu, alpha n'est pas défini. |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 24 bits par pixel avec 8 bits pour chacun des alpha, rouge, vert et bleu, alpha n'est pas défini. |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 32 bits par pixel avec 8 bits pour chacun des alpha, rouge, vert et bleu. |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 32 bits par pixel avec 8 bits pour chacun des alpha, rouge, vert et bleu. |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour indexé 1 bit par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération de données partout où la palette de couleurs est utilisée. À utiliser avec prudence, car peut nécessiter une conversion d'une palette à une autre ou de RVBA à un modèle de couleurs indexées . |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat)défini pour 2 bits indexés par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération de données partout où la palette de couleurs est utilisée. À utiliser avec prudence, car peut nécessiter une conversion d'une palette à une autre ou de RVBA à un modèle de couleurs indexées . |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 4 bits indexés par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération de données partout où la palette de couleurs est utilisée. À utiliser avec prudence, car peut nécessiter une conversion d'une palette à une autre ou de RVBA à un modèle de couleurs indexées . |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat)défini pour 8 bits indexés par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération de données partout où la palette de couleurs est utilisée. À utiliser avec prudence, car peut nécessiter une conversion d'une palette à une autre ou de RVBA à un modèle de couleurs indexées . |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 24 bits par pixel avec 8 bits pour chacune des composantes de chrominance luma, différence bleue et différence rouge. |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck) { get; } | Obtient le[`PixelDataFormat`](../pixeldataformat) défini pour 32 bits par pixel avec 8 bits pour chacune des composantes luma, différence bleue, différence rouge et chrominance noire. |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel) { get; } | Obtient les bits par pixel. |
| [Caption](../../aspose.imaging/pixeldataformat/caption) { get; } | Obtient la légende du format de données pixel. |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits) { get; } | Obtient le nombre de bits pour chaque canal. |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount) { get; } | Obtient le nombre de canaux. |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat) { get; } | Obtient le format de pixel. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr)(int) | Obtient la couleur BGR avec un nombre spécifié de bits par échantillon. |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra)(int) | Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon. |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab)(int, int, int) | Obtient la couleur CIE Lab avec un nombre spécifié de bits par échantillon. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk)(int) | Obtient la couleur CMJN avec un nombre spécifié de bits par échantillon. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk_1)(int, int, int, int) | Obtient la couleur CMJN avec un nombre spécifié de bits par échantillon. |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka)(int, int, int, int, int) | Obtient la couleur CMJNA avec un nombre spécifié de bits par échantillon. |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale)(int) | Obtient une couleur en niveaux de gris avec un nombre spécifié de bits par échantillon. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha)(int) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha_1)(int, int) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb)(int) | Obtient la couleur RVB avec un nombre spécifié de bits par échantillon. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb_1)(int, int, int) | Obtient la couleur RVB avec un nombre spécifié de bits par échantillon. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba)(int) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba_1)(int, int, int, int) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed)(int) | Obtient la couleur indexée BGRA avec un nombre spécifié de bits par échantillon. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr)(int) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr_1)(int, int, int) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck)(int) | Obtient la couleur YCCK avec un nombre spécifié de bits par échantillon. |
| override [Equals](../../aspose.imaging/pixeldataformat/equals)(object) | Détermine si la valeur spécifiéeObject est égal à cette instance. |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode)() | Renvoie un code de hachage pour cette instance. |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring)() | Renvoie unString qui représente cette instance. |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality) | Renvoie le résultat de l'égalité pour deux[`PixelDataFormat`](../pixeldataformat) cours. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality) | Renvoie le résultat de la non-égalité pour deux[`PixelDataFormat`](../pixeldataformat) cours. |

### Voir également

* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
