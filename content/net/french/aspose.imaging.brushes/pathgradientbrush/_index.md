---
title: PathGradientBrush
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Encapsule unBrush../aspose.imaging/brush objet avec un dégradé. Cette classe ne peut pas être héritée.
type: docs
weight: 180
url: /fr/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

Encapsule un[`Brush`](../../aspose.imaging/brush) objet avec un dégradé. Cette classe ne peut pas être héritée.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | Initialise une nouvelle instance du[`PathGradientBrush`](../pathgradientbrush) classe avec le chemin spécifié. |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | Initialise une nouvelle instance du[`PathGradientBrush`](../pathgradientbrush) classe avec les points spécifiés. |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | Initialise une nouvelle instance du[`PathGradientBrush`](../pathgradientbrush) classe avec les points spécifiés. |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | Initialise une nouvelle instance du[`PathGradientBrush`](../pathgradientbrush) classe avec les points spécifiés et le mode wrap. |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | Initialise une nouvelle instance du[`PathGradientBrush`](../pathgradientbrush) classe avec les points spécifiés et le mode wrap. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | Obtient ou définit un[`Blend`](../../aspose.imaging/blend) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le gradient. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | Obtient ou définit la couleur au centre du dégradé du chemin. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Obtient ou définit le point central du dégradé du chemin. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Obtient ou définit le point focal pour l'atténuation du dégradé. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Obtient le chemin graphique sur lequel ce pinceau a été construit. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple, définir la matrice de transformation ou appeler l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la rétrocompatibilité avec GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que le pinceau est entièrement visible, la valeur 1 signifie que le pinceau est entièrement opaque. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Obtient les points de chemin sur lesquels ce pinceau a été construit. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | Obtient ou définit un tableau de couleurs qui correspondent aux points du chemin[`PathGradientBrush`](../pathgradientbrush) remplit. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Obtient ou définit une copie[`Matrix`](../../aspose.imaging/matrix) qui définit une transformée géométrique locale pour cette[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Obtient ou définit un[`WrapMode`](../../aspose.imaging/wrapmode) énumération qui indique le mode de bouclage pour cette[`TransformBrush`](../transformbrush) . |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Crée un nouveau clone profond du courant[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Multiplie le[`Matrix`](../../aspose.imaging/matrix) qui représente la transformée géométrique locale de ce[`LinearGradientBrush`](../lineargradientbrush) par le spécifié[`Matrix`](../../aspose.imaging/matrix) en préfixant le spécifié[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Multiplie le[`Matrix`](../../aspose.imaging/matrix) qui représente la transformée géométrique locale de ce[`LinearGradientBrush`](../lineargradientbrush) par le spécifié[`Matrix`](../../aspose.imaging/matrix) dans l'ordre spécifié. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Réinitialise le[`Transform`](../transformbrush/transform) propriété à l'identité. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Fait pivoter la transformation géométrique locale de la quantité spécifiée. Cette méthode ajoute la rotation à la transformation. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de la quantité spécifiée dans l'ordre spécifié. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Met à l'échelle la transformation géométrique locale selon les quantités spécifiées. Cette méthode ajoute la matrice de mise à l'échelle à la transformation. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Met à l'échelle la transformation géométrique locale selon les quantités spécifiées dans l'ordre spécifié. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Crée un dégradé avec une couleur centrale et une atténuation linéaire vers une couleur environnante. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Crée un dégradé avec une couleur centrale et une atténuation linéaire pour chaque couleur environnante. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | Crée un pinceau dégradé qui change de couleur à partir du centre du chemin jusqu'à la limite du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Crée un pinceau dégradé qui change de couleur à partir du centre du chemin jusqu'à la limite du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Traduit la transformation géométrique locale par les dimensions spécifiées. Cette méthode ajoute la traduction au début de la transformation. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Traduit la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |

### Remarques

La couleur centrale est blanche par défaut. Un utilisateur peut modifier cette valeur à tout moment ultérieurement.

Le tableau des couleurs surround est initialisé par un seul élément contenant la couleur blanche par défaut. Les couleurs surround peuvent être modifiées ultérieurement, mais au moins un seul élément est requis lors de la configuration des couleurs surround.

Voir le[`Blend`](./blend) pour plus de détails sur son initialisation.

### Voir également

* class [PathGradientBrushBase](../pathgradientbrushbase)
* espace de noms [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
