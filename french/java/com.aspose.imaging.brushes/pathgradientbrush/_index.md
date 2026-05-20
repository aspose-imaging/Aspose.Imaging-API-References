---
title: "PathGradientBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Encapsule un objet Aspose.Imaging.Brush avec un dégradé."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Encapsule un objet `Aspose.Imaging.Brush` avec un dégradé. Cette classe ne peut pas être héritée.

La couleur centrale est blanche par défaut. Un utilisateur peut modifier cette valeur à tout moment ultérieurement.

Le tableau des couleurs d'entourage est initialisé avec un seul élément contenant la couleur blanche par défaut. Les couleurs d'entourage peuvent être modifiées ultérieurement, cependant au moins un élément est requis lors de la configuration des couleurs d'entourage.

Voir le `Blend` pour plus de détails sur son initialisation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés et le mode d'enroulement. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés et le mode d'enroulement. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Initialise une nouvelle instance de la classe `PathGradientBrush` avec le chemin spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
| [getCenterColor()](#getCenterColor--) | Obtient la couleur au centre du dégradé de chemin. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Définit la couleur au centre du dégradé de chemin. |
| [getSurroundColors()](#getSurroundColors--) | Obtient un tableau de couleurs correspondant aux points du chemin que ce `PathGradientBrush` remplit. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | Définit un tableau de couleurs correspondant aux points du chemin que ce `PathGradientBrush` remplit. |
| [getBlend()](#getBlend--) | Obtient un `Aspose.Imaging.Blend` qui spécifie les positions et les facteurs définissant une atténuation personnalisée du dégradé. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Définit un `Aspose.Imaging.Blend` qui spécifie les positions et les facteurs définissant une atténuation personnalisée du dégradé. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crée un dégradé avec une couleur centrale et une décroissance linéaire vers une couleur d'entourage. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crée un dégradé avec une couleur centrale et une décroissance linéaire vers chaque couleur d'entourage. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures `Aspose.Imaging.PointF` qui représente les points constituant les sommets du chemin. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés et le mode d'enroulement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures `Aspose.Imaging.PointF` qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un `Aspose.Imaging.WrapMode` qui spécifie comment les remplissages dessinés avec ce `PathGradientBrush` sont répétés. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Un tableau de structures `Aspose.Imaging.Point` qui représente les points constituant les sommets du chemin. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initialise une nouvelle instance de la classe `PathGradientBrush` avec les points spécifiés et le mode d'enroulement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Un tableau de structures `Aspose.Imaging.Point` qui représente les points constituant les sommets du chemin. |
| wrapMode | int | Un `Aspose.Imaging.WrapMode` qui spécifie comment les remplissages dessinés avec ce `PathGradientBrush` sont répétés. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initialise une nouvelle instance de la classe `PathGradientBrush` avec le chemin spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `GraphicsPath` qui définit la zone remplie par ce `PathGradientBrush`. |

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

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Obtient la couleur au centre du dégradé de chemin.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Définit la couleur au centre du dégradé de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Un `com.aspose.imaging.Color` qui représente la couleur au centre du dégradé de chemin. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Obtient un tableau de couleurs correspondant aux points du chemin que ce `PathGradientBrush` remplit.

**Returns:**
com.aspose.imaging.Color[] - Un tableau de structures `com.aspose.imaging.Color` qui représente les couleurs associées à chaque point du chemin que ce `PathGradientBrush` remplit.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


Définit un tableau de couleurs correspondant aux points du chemin que ce `PathGradientBrush` remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Un tableau de structures `com.aspose.imaging.Color` qui représente les couleurs associées à chaque point du chemin que ce `PathGradientBrush` remplit. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Obtient un `Aspose.Imaging.Blend` qui spécifie les positions et les facteurs définissant une atténuation personnalisée du dégradé.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Définit un `Aspose.Imaging.Blend` qui spécifie les positions et les facteurs définissant une atténuation personnalisée du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | Un `Aspose.Imaging.Blend` qui représente une atténuation personnalisée pour le dégradé. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (par défaut) place l'intensité maximale au centre du chemin. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (par défaut) place l'intensité maximale au centre du chemin. |
| échelle | float | Une valeur comprise entre 0 et 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de la bordure. Une valeur de 1 entraîne l'intensité la plus élevée possible de la couleur centrale, et c'est la valeur par défaut. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crée un dégradé avec une couleur centrale et une décroissance linéaire vers une couleur d'entourage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (par défaut) place l'intensité maximale au centre du chemin. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crée un dégradé avec une couleur centrale et une décroissance linéaire vers chaque couleur d'entourage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui indique où, le long de n'importe quel rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (par défaut) place l'intensité maximale au centre du chemin. |
| échelle | float | Une valeur comprise entre 0 et 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de la bordure. Une valeur de 1 entraîne l'intensité la plus élevée possible de la couleur centrale, et c'est la valeur par défaut. |

