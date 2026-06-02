---
title: "LinearGradientBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Encapsule un Aspose.Imaging.Brush avec un dégradé linéaire."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Encapsule un `Aspose.Imaging.Brush` avec un dégradé linéaire. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) avec des paramètres par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Obtient un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Définit un `com.aspose.imaging.ColorBlend` qui définit un dégradé linéaire multicolore. |
| [getLinearColors()](#getLinearColors--) | Obtient les couleurs de départ et d'arrivée du dégradé. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Définit les couleurs de départ et d'arrivée du dégradé. |
| [getStartColor()](#getStartColor--) | Obtient la couleur de départ du dégradé. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Définit la couleur de départ du dégradé. |
| [getEndColor()](#getEndColor--) | Obtient la couleur d'arrivée du dégradé. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Définit la couleur d'arrivée du dégradé. |
| [getBlend()](#getBlend--) | Obtient un `Aspose.Imaging.Blend` qui spécifie les positions et les facteurs définissant une atténuation personnalisée du dégradé. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Définit un `Aspose.Imaging.Blend` qui spécifie les positions et les facteurs définissant une atténuation personnalisée du dégradé. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crée une atténuation du dégradé basée sur une courbe en cloche. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crée une atténuation du dégradé basée sur une courbe en cloche. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | La couleur1. |
| color2 | [Color](../../com.aspose.imaging/color) | La couleur2. |
| angle | float | L'angle. |
| isAngleScalable | boolean | si défini sur `true` [is angle scalable]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | La couleur1. |
| color2 | [Color](../../com.aspose.imaging/color) | La couleur2. |
| angle | float | L'angle. |
| isAngleScalable | boolean | si défini sur `true` [is angle scalable]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | La couleur1. |
| color2 | [Color](../../com.aspose.imaging/color) | La couleur2. |
| angle | float | L'angle. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | La couleur1. |
| color2 | [Color](../../com.aspose.imaging/color) | La couleur2. |
| angle | float | L'angle. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Le point1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Le point2. |
| color1 | [Color](../../com.aspose.imaging/color) | La couleur1. |
| color2 | [Color](../../com.aspose.imaging/color) | La couleur2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Le point1. |
| point2 | [Point](../../com.aspose.imaging/point) | Le point2. |
| color1 | [Color](../../com.aspose.imaging/color) | La couleur1. |
| color2 | [Color](../../com.aspose.imaging/color) | La couleur2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initialise une nouvelle instance de la classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) avec des paramètres par défaut. La couleur de départ est noire, la couleur d'arrivée est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1).

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

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Obtient les couleurs de départ et d'arrivée du dégradé.

**Returns:**
com.aspose.imaging.Color[] - Un tableau de deux structures `Color` qui représente les couleurs de départ et d'arrivée du dégradé.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Définit les couleurs de départ et d'arrivée du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Un tableau de deux structures `Color` qui représente les couleurs de départ et d'arrivée du dégradé. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Obtient la couleur de départ du dégradé.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Définit la couleur de départ du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | La couleur de départ du dégradé. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Obtient la couleur d'arrivée du dégradé.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Définit la couleur d'arrivée du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | La couleur d'arrivée du dégradé. |

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


Crée une atténuation du dégradé basée sur une courbe en cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où la couleur de départ et la couleur d'arrivée sont mélangées à parts égales). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crée une atténuation du dégradé basée sur une courbe en cloche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |
| échelle | float | Une valeur comprise entre 0 et 1 qui indique la rapidité avec laquelle les couleurs diminuent à partir du `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur d'arrivée). |
| échelle | float | Une valeur comprise entre 0 et 1 qui indique la rapidité avec laquelle les couleurs diminuent de la couleur de départ vers le `focus` (couleur d'arrivée). |

