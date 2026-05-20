---
title: "PathMulticolorGradientBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Encapsule un objet Aspose.Imaging.Brush avec un dégradé."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.brushes/pathmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Encapsule un objet `Aspose.Imaging.Brush` avec un dégradé. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés. |
| [PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés et le mode d'habillage. |
| [PathMulticolorGradientBrush(Point[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés. |
| [PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés et le mode d'habillage. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-) | Initialise une nouvelle instance de la classe `PathMulticolorGradientBrush` avec le chemin spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient ou définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Obtient ou définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
### PathMulticolorGradientBrush(PointF[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---}
```
public PathMulticolorGradientBrush(PointF[] pathPoints)
```


Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures [PointF](../../com.aspose.imaging/pointf) qui représente les points constituant les sommets du chemin. |

### PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)
```


Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés et le mode d'habillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures [PointF](../../com.aspose.imaging/pointf) qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un [WrapMode](../../com.aspose.imaging/wrapmode) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) sont juxtaposés. |

### PathMulticolorGradientBrush(Point[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---}
```
public PathMulticolorGradientBrush(Point[] pathPoints)
```


Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | Un tableau de structures [Point](../../com.aspose.imaging/point) qui représente les points constituant les sommets du chemin. |

### PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-}
```
public PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)
```


Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) avec les points spécifiés et le mode d'habillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | Un tableau de structures [Point](../../com.aspose.imaging/point) qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un [WrapMode](../../com.aspose.imaging/wrapmode) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) sont juxtaposés. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Initialise une nouvelle instance de la classe `PathMulticolorGradientBrush` avec le chemin spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `GraphicsPath` qui définit la zone remplie par ce `PathMulticolorGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtient ou définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore.

Valeur : un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Obtient ou définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore.

Valeur : un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) |  |

