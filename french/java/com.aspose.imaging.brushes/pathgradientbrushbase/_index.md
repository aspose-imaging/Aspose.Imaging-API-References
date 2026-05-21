---
title: "PathGradientBrushBase"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente un Brush avec une fonctionnalité de dégradé de chemin de base."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Représente un `Brush` avec une fonctionnalité de dégradé de chemin de base.

Notez que lors de la création de la classe `PathGradientBrushBase`, elle doit être initialisée avec au moins 2 points. Le chemin interne créé sera toujours une figure fermée, le dernier point relie le premier point. Cette forme est remplie avec ce `PathGradientBrushBase`. L'implémentation GDI+ lance une `OutOfMemoryError` lorsqu'on passe des tableaux vides ou des ensembles de points ayant les mêmes coordonnées. Le `PathGradientBrushBase` lance une exception lorsque le tableau de points contient moins de 2 points ; l'`ArgumentException` est lancée plutôt que `OutOfMemoryError` lorsque le tableau de points est inacceptable. Le point central est calculé comme le centre de masse des points fournis par défaut. Un utilisateur peut modifier ce point ultérieurement. Le point de mise au point est un point vide (0,0) par défaut.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Obtient les points du chemin sur lesquels ce brush a été construit. |
| [getGraphicsPath()](#getGraphicsPath--) | Obtient le chemin graphique sur lequel ce brush a été construit. |
| [getCenterPoint()](#getCenterPoint--) | Obtient ou définit le point central du dégradé de chemin. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Obtient ou définit le point central du dégradé de chemin. |
| [getFocusScales()](#getFocusScales--) | Obtient le point de focalisation pour la décroissance du dégradé. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Obtient ou définit le point de focalisation pour la décroissance du dégradé. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Obtient les points du chemin sur lesquels ce brush a été construit.

**Returns:**
com.aspose.imaging.PointF[] - Les points du chemin.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Obtient le chemin graphique sur lequel ce brush a été construit.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Obtient ou définit le point central du dégradé de chemin.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Obtient ou définit le point central du dégradé de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Un `Aspose.Imaging.PointF` qui représente le point central du dégradé de chemin. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Obtient le point de focalisation pour la décroissance du dégradé.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Obtient ou définit le point de focalisation pour la décroissance du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Un `Aspose.Imaging.PointF` qui représente le point de focalisation pour la diminution du dégradé. |

