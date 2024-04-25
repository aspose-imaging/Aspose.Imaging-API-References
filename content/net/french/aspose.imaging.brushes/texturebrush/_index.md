---
title: TextureBrush
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Chaque propriété duTextureBrush./texturebrush la classe est uneBrush../aspose.imaging/brush objet qui utilise une image pour remplir lintérieur dune forme. Cette classe ne peut pas être héritée.
type: docs
weight: 220
url: /fr/aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

Chaque propriété du[`TextureBrush`](../texturebrush) la classe est une[`Brush`](../../aspose.imaging/brush) objet qui utilise une image pour remplir l'intérieur d'une forme. Cette classe ne peut pas être héritée.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image spécifiée. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image et le rectangle de délimitation spécifiés. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image et le rectangle de délimitation spécifiés. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image et le mode wrap spécifiés. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image, le rectangle englobant et les attributs d'image spécifiés. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image, le rectangle englobant et les attributs d'image spécifiés. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image, le mode d'habillage et le rectangle de délimitation spécifiés. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Initialise une nouvelle instance du[`TextureBrush`](../texturebrush) classe qui utilise l'image, le mode d'habillage et le rectangle de délimitation spécifiés. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [Image](../../aspose.imaging.brushes/texturebrush/image) { get; } | Obtient le[`Image`](../../aspose.imaging/image) objet associé à ce[`TextureBrush`](../texturebrush) objet. |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes) { get; } | Obtient le[`ImageAttributes`](./imageattributes) associé à ce[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle) { get; } | Obtient le[`Rectangle`](../../aspose.imaging/rectangle) associé à ce[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple, définir la matrice de transformation ou appeler l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la rétrocompatibilité avec GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que le pinceau est entièrement visible, la valeur 1 signifie que le pinceau est entièrement opaque. |
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
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Traduit la transformation géométrique locale par les dimensions spécifiées. Cette méthode ajoute la traduction au début de la transformation. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Traduit la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |

### Voir également

* class [TransformBrush](../transformbrush)
* espace de noms [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
