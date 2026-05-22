---
title: "Classe LinearMulticolorGradientBrush"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec des paramètres par défaut.<br/>            La couleur de départ est noire, la couleur finale est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1). |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtient ou définit l'angle du dégradé. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| gamma_correction | bool | r/w | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Obtient ou définit un [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) qui définit un dégradé linéaire multicolore. |
| is_angle_scalable | bool | r/w | Obtient ou définit une valeur indiquant si [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) est modifié lors des transformations avec ce [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est totalement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit une copie de la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui définit une transformation géométrique locale pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtient ou définit une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui indique le mode d'habillage pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_points(point1, point2)](#create_with_points_point1_point2_1) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés. |
| [create_with_points_f(point1, point2)](#create_with_points_f_point1_point2_2) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés. |
| [create_with_rect(rect, angle)](#create_with_rect_rect_angle_3) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [create_with_rect_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [create_with_rect_f(rect, angle)](#create_with_rect_f_rect_angle_5) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [deep_clone()](#deep_clone__7) | Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel. |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué. |
| reset_transform() | Réinitialise la propriété [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_14) | Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_15) | Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec des paramètres par défaut.<br/>            La couleur de départ est noire, la couleur finale est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1).

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point final du dégradé linéaire. |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point final du dégradé linéaire. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié pendant les transformations avec ce [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié pendant les transformations avec ce [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

### Method: create_with_points(point1, point2)  [static] {#create_with_points_point1_point2_1}


```
 create_with_points(point1, point2) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point final du dégradé linéaire. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_points_f(point1, point2)  [static] {#create_with_points_f_point1_point2_2}


```
 create_with_points_f(point1, point2) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Une structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Une structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point final du dégradé linéaire. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect(rect, angle)  [static] {#create_with_rect_rect_angle_3}


```
 create_with_rect(rect, angle) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4}


```
 create_with_rect_angle_scalable(rect, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié pendant les transformations avec ce [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f(rect, angle)  [static] {#create_with_rect_f_rect_angle_5}


```
 create_with_rect_f(rect, angle) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6}


```
 create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié pendant les transformations avec ce [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel.

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nouveau [Brush](/imaging/python-net/aspose.imaging/brush/) qui est le clone profond de cette instance [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie dans quel ordre multiplier les deux matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


```
 scale_transform(sx, sy, order) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_14}


```
 translate_transform(dx, dy) 
```

Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_15}


```
 translate_transform(dx, dy, order) 
```

Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

