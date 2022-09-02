---
title: LinearGradientBrush
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Encapsule unBrush../aspose.imaging/brush avec un dégradé linéaire. Cette classe ne peut pas être héritée.
type: docs
weight: 150
url: /fr/net/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Encapsule un[`Brush`](../../aspose.imaging/brush) avec un dégradé linéaire. Cette classe ne peut pas être héritée.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | Initialise une nouvelle instance du[`LinearGradientBrush`](../lineargradientbrush) classe avec les paramètres par défaut. La couleur de départ est le noir, la couleur de fin est le blanc, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec la taille (1,1). |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | Initialise une nouvelle instance du[`LinearGradientBrush`](../lineargradientbrush) classe avec les points et couleurs spécifiés. |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | Initialise une nouvelle instance du[`LinearGradientBrush`](../lineargradientbrush) classe avec les points et couleurs spécifiés. |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | Initialise une nouvelle instance du[`LinearGradientBrush`](../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation. |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | Initialise une nouvelle instance du[`LinearGradientBrush`](../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation. |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | Initialise une nouvelle instance du[`LinearGradientBrush`](../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation. |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | Initialise une nouvelle instance du[`LinearGradientBrush`](../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Obtient ou définit l'angle du dégradé. |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend) { get; set; } | Obtient ou définit un[`Blend`](../../aspose.imaging/blend) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le gradient. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor) { get; set; } | Obtient ou définit la couleur du dégradé de fin. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Obtient ou définit une valeur indiquant si[`Angle`](../lineargradientbrushbase/angle) est changé lors des transformations avec ceci[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple, définir la matrice de transformation ou appeler l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la rétrocompatibilité avec GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que le pinceau est entièrement visible, la valeur 1 signifie que le pinceau est entièrement opaque. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor) { get; set; } | Obtient ou définit la couleur de dégradé de départ. |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | Crée une atténuation du dégradé basée sur une courbe en forme de cloche. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Crée une atténuation du dégradé basée sur une courbe en forme de cloche. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Traduit la transformation géométrique locale par les dimensions spécifiées. Cette méthode ajoute la traduction au début de la transformation. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Traduit la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |

### Voir également

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* espace de noms [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
