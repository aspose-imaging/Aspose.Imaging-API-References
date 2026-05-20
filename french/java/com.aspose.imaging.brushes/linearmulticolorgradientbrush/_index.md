---
title: "LinearMulticolorGradientBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente un Brush avec un dégradé linéaire défini par plusieurs couleurs et des positions appropriées."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Représente un `Brush` avec un dégradé linéaire défini par plusieurs couleurs et des positions appropriées. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les paramètres par défaut. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les points spécifiés. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les points spécifiés. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les paramètres par défaut. La couleur de départ est noire, la couleur finale est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Une structure `Aspose.Imaging.Point` qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](../../com.aspose.imaging/point) | Une structure `Aspose.Imaging.Point` qui représente le point d'arrivée du dégradé linéaire. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Une structure `Aspose.Imaging.PointF` qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Une structure `Aspose.Imaging.PointF` qui représente le point d'arrivée du dégradé linéaire. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Une structure `Aspose.Imaging.RectangleF` qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure `Aspose.Imaging.RectangleF` qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Une structure `Aspose.Imaging.RectangleF` qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |
| isAngleScalable | boolean | si elle est définie sur `true`, l'angle est modifié lors des transformations avec ce `LinearMulticolorGradientBrush`. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Initialise une nouvelle instance de la classe `LinearMulticolorGradientBrush` basée sur un rectangle et un angle d'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure `Aspose.Imaging.RectangleF` qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe x, de la ligne d'orientation du dégradé. |
| isAngleScalable | boolean | si elle est définie sur `true`, l'angle est modifié lors des transformations avec ce `LinearMulticolorGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtient un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | Un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |

