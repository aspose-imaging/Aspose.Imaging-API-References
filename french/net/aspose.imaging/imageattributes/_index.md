---
title: ImageAttributes
second_title: Référence de l'API Aspose.Imaging pour .NET
description: UnImageAttributes./imageattributes Lobjet contient des informations sur la manière dont les couleurs des bitmaps et des métafichiers sont manipulées lors du rendu. UnImageAttributes./imageattributesLobjet conserve plusieurs paramètres dajustement des couleurs notamment les matrices dajustement des couleurs les matrices dajustement des niveaux de gris les valeurs de correction gamma les tables de cartes de couleurs et les valeurs de seuil de couleur. Pendant le rendu les couleurs peuvent être corrigées assombries éclaircies et supprimées. Pour appliquer de telles manipulations initialisez unImageAttributes./imageattributes objet et passez le chemin de celui-ciImageAttributes./imageattributes objet ainsi que le chemin dunImage./image  à la méthode DrawImage.
type: docs
weight: 9680
url: /fr/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

Un[`ImageAttributes`](../imageattributes) L'objet contient des informations sur la manière dont les couleurs des bitmaps et des métafichiers sont manipulées lors du rendu. Un[`ImageAttributes`](../imageattributes)L'objet conserve plusieurs paramètres d'ajustement des couleurs, notamment les matrices d'ajustement des couleurs, les matrices d'ajustement des niveaux de gris, les valeurs de correction gamma, les tables de cartes de couleurs et les valeurs de seuil de couleur. Pendant le rendu, les couleurs peuvent être corrigées, assombries, éclaircies et supprimées. Pour appliquer de telles manipulations, initialisez un[`ImageAttributes`](../imageattributes) objet et passez le chemin de celui-ci[`ImageAttributes`](../imageattributes) objet (ainsi que le chemin d'un[`Image`](../image) ) à la méthode DrawImage.

```csharp
public sealed class ImageAttributes
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageAttributes](imageattributes)() | Default_Constructor |

## Méthodes

| Nom | La description |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Efface la table de remappage des couleurs du pinceau de ce[`ImageAttributes`](../imageattributes) objet. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | Efface la clé de couleur (plage de transparence) pour la catégorie par défaut. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | Efface la matrice de réglage des couleurs pour la catégorie par défaut. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Efface la matrice de réglage des couleurs pour une catégorie spécifiée. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | Désactive la correction gamma pour la catégorie par défaut. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Désactive la correction gamma pour une catégorie spécifiée. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | Efface le paramètre NoOp pour la catégorie par défaut. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Efface le paramètre NoOp pour une catégorie spécifiée. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | Efface le paramètre du canal de sortie CMJN (cyan-magenta-jaune-noir) pour la catégorie par défaut. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Efface le paramètre de canal de sortie (cyan-magenta-jaune-noir) pour une catégorie spécifiée. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Efface le paramètre de profil de couleur du canal de sortie pour la catégorie par défaut. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Efface le paramètre de profil de couleur du canal de sortie pour une catégorie spécifiée. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | Efface la table de remappage des couleurs pour la catégorie par défaut. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Efface la table de remappage des couleurs pour une catégorie spécifiée. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | Efface la valeur de seuil pour la catégorie par défaut. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Efface la valeur de seuil pour une catégorie spécifiée. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Définit la table de remappage des couleurs pour la catégorie de pinceaux. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Définit la clé de couleur pour la catégorie par défaut. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Définit la matrice de réglage des couleurs et la matrice de réglage des niveaux de gris pour la catégorie par défaut. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Définit la matrice de réglage des couleurs et la matrice de réglage des niveaux de gris pour la catégorie par défaut. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Définit la matrice de réglage des couleurs et la matrice de réglage des niveaux de gris pour une catégorie spécifiée. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Définit la matrice de réglage des couleurs pour la catégorie par défaut. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Définit la matrice de réglage des couleurs pour la catégorie par défaut. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Définit la matrice de réglage des couleurs pour une catégorie spécifiée. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | Définit la valeur gamma pour la catégorie par défaut. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Définit la valeur gamma pour une catégorie spécifiée. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | Désactive le réglage des couleurs pour la catégorie par défaut. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Désactive le réglage des couleurs pour une catégorie spécifiée. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Définit le canal de sortie CMJN (cyan-magenta-jaune-noir) pour la catégorie par défaut. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Définit le canal de sortie CMJN (cyan-magenta-jaune-noir) pour une catégorie spécifiée. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Définit le fichier de profil de couleur du canal de sortie pour la catégorie par défaut. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Définit le fichier de profil de couleur du canal de sortie pour une catégorie spécifiée. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Définit la table de remappage des couleurs pour la catégorie par défaut. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Définit la table de remappage des couleurs pour une catégorie spécifiée. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | Définit le seuil (plage de transparence) pour la catégorie par défaut. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Définit le seuil (plage de transparence) pour une catégorie spécifiée. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Définit le mode d'habillage qui est utilisé pour décider comment juxtaposer une texture sur une forme ou aux limites de la forme. Une texture est disposée en mosaïque sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Définit le mode d'habillage et la couleur utilisés pour décider comment juxtaposer une texture sur une forme ou aux limites de la forme. Une texture est disposée en mosaïque sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Définit le mode d'habillage et la couleur utilisés pour décider comment juxtaposer une texture sur une forme ou aux limites de la forme. Une texture est disposée en mosaïque sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |

### Voir également

* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
