---
title: "Classe LinearGradientBrush"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) avec des paramètres par défaut.<br/>            La couleur de départ est noire, la couleur de fin est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtient ou définit l'angle du dégradé. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Obtient ou définit un [Blend](/imaging/python-net/aspose.imaging/blend/) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit la couleur de fin du dégradé. |
| gamma_correction | bool | r/w | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Obtient ou définit un [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) qui définit un dégradé linéaire multicolore. |
| is_angle_scalable | bool | r/w | Obtient ou définit une valeur indiquant si [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) est modifié lors des transformations avec ce [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit les couleurs de départ et de fin du dégradé. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est totalement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit la couleur de départ du dégradé. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit une copie de la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui définit une transformation géométrique locale pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtient ou définit une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui indique le mode d'habillage pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) avec les points et les couleurs spécifiés. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) avec les points et les couleurs spécifiés. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation. |
| [deep_clone()](#deep_clone__7) | Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel. |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué. |
| reset_transform() | Réinitialise la propriété [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | Crée une atténuation de dégradé basée sur une courbe en forme de cloche. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | Crée une atténuation de dégradé basée sur une courbe en forme de cloche. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) avec des paramètres par défaut.<br/>            La couleur de départ est noire, la couleur de fin est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le point1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le point2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Le point1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Le point2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur2. |
| angle | float | L'angle. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur2. |
| angle | float | L'angle. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur2. |
| angle | float | L'angle. |
| is_angle_scalable | bool | si défini sur <c>true</c> [l'angle est évolutif]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur2. |
| angle | float | L'angle. |
| is_angle_scalable | bool | si défini sur <c>true</c> [l'angle est évolutif]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) avec les points et les couleurs spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Une structure [Point](/imaging/python-net/aspose.imaging/point/) qui représente le point final du dégradé linéaire. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de fin du dégradé linéaire. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) avec les points et les couleurs spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Une structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Une structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le point final du dégradé linéaire. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de fin du dégradé linéaire. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de fin du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de fin du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié pendant les transformations avec ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de fin du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basée sur un rectangle, les couleurs de départ et de fin, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Une structure [Color](/imaging/python-net/aspose.imaging/color/) qui représente la couleur de fin du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié pendant les transformations avec ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur de 0 à 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur de fin). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une couleur unique aux deux extrémités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur de 0 à 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur de fin). |
| échelle | float | Une valeur de 0 à 1 qui spécifie la rapidité avec laquelle les couleurs diminuent de la couleur de départ vers le _focus_ (couleur de fin) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

Crée une atténuation de dégradé basée sur une courbe en forme de cloche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur de 0 à 1 qui spécifie le centre du dégradé (le point où la couleur de départ et la couleur de fin sont mélangées à parts égales). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

Crée une atténuation de dégradé basée sur une courbe en forme de cloche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur de 0 à 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur de fin). |
| échelle | float | Une valeur de 0 à 1 qui spécifie la rapidité avec laquelle les couleurs diminuent depuis le _focus_. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


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

