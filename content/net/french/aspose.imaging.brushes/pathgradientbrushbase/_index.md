---
title: PathGradientBrushBase
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente unBrush../aspose.imaging/brush avec fonctionnalité de gradient de chemin de base.
type: docs
weight: 190
url: /fr/aspose.imaging.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Représente un[`Brush`](../../aspose.imaging/brush) avec fonctionnalité de gradient de chemin de base.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Obtient ou définit le point central du dégradé du chemin. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Obtient ou définit le point focal pour l'atténuation du dégradé. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Obtient le chemin graphique sur lequel ce pinceau a été construit. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple, définir la matrice de transformation ou appeler l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la rétrocompatibilité avec GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que le pinceau est entièrement visible, la valeur 1 signifie que le pinceau est entièrement opaque. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Obtient les points de chemin sur lesquels ce pinceau a été construit. |
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

### Remarques

Notez que lors de la création du[`PathGradientBrushBase`](../pathgradientbrushbase) class il doit être initialisé avec 2 points au moins. Le chemin interne created sera toujours une figure fermée, le dernier point relie le premier point. Cette forme est remplie de ceci[`PathGradientBrushBase`](../pathgradientbrushbase) . L'implémentation de GDI+ lance uneOutOfMemoryException lors du passage dans des tableaux vides ou ensemble de points ayant les mêmes coordonnées. Le[`PathGradientBrushBase`](../pathgradientbrushbase) lève une exception lorsque le tableau de points contient moins de 2 points, leArgumentException is lancé plutôt queOutOfMemoryExceptionlorsque le tableau de points est inacceptable. Le point central est calculé comme un centre de masse pour les points transmis par défaut. Un utilisateur peut modifier ce point ultérieurement. L'échelle de mise au point est un point vide (0.0, 0.0) par défaut.

### Voir également

* class [TransformBrush](../transformbrush)
* espace de noms [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
