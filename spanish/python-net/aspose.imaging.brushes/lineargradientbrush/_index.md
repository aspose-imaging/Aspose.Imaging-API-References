---
title: "Clase LinearGradientBrush"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con parámetros predeterminados.<br/>            El color inicial es negro, el color final es blanco, el ángulo es 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtiene o establece el ángulo del degradado. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Obtiene o establece un [Blend](/imaging/python-net/aspose.imaging/blend/) que especifica posiciones y factores que definen una caída personalizada para el gradiente. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el color final del gradiente. |
| gamma_correction | bool | r/w | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Obtiene o establece un [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) que define un degradado lineal multicolor. |
| is_angle_scalable | bool | r/w | Obtiene o establece un valor que indica si [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) se modifica durante las transformaciones con este [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, al establecer la matriz de transformación o<br/>            al llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece los colores inicial y final del gradiente. |
| opacity | float | r/w | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece una región rectangular que define los puntos inicial y final del degradado. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el color inicial del gradiente. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece una copia de [Matrix](/imaging/python-net/aspose.imaging/matrix/) que define una transformación geométrica local para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtiene o establece una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que indica el modo de ajuste para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con los puntos y colores especificados. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con los puntos y colores especificados. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [deep_clone()](#deep_clone__7) | Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual. |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado. |
| reset_transform() | Restablece la propiedad [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Rota la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Escala la transformación geométrica local por las cantidades especificadas en el orden especificado. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | Crea un gradiente lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | Crea un gradiente lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | Crea una caída de gradiente basada en una curva en forma de campana. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | Crea una caída de gradiente basada en una curva en forma de campana. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con parámetros predeterminados.<br/>            El color inicial es negro, el color final es blanco, el ángulo es 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El punto1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El punto2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | El color1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | El color2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | El punto1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | El punto2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | El color1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | El color2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | El color1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | El color2. |
| angle | float | El ángulo. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | El color1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | El color2. |
| angle | float | El ángulo. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | El color1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | El color2. |
| angle | float | El ángulo. |
| is_angle_scalable | bool | si se establece en <c>true</c> [es escalable el ángulo]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | El color1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | El color2. |
| angle | float | El ángulo. |
| is_angle_scalable | bool | si se establece en <c>true</c> [es escalable el ángulo]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con los puntos y colores especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Una estructura [Point](/imaging/python-net/aspose.imaging/point/) que representa el punto inicial del degradado lineal. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Una estructura [Point](/imaging/python-net/aspose.imaging/point/) que representa el punto final del degradado lineal. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color inicial del degradado lineal. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color final del degradado lineal. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) con los puntos y colores especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Una estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto inicial del degradado lineal. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Una estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa el punto final del degradado lineal. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color inicial del degradado lineal. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color final del degradado lineal. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color inicial del degradado. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color final del degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color inicial del degradado. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color final del degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| is_angle_scalable | bool | si se establece en <c>true</c> el ángulo se cambia durante las transformaciones con este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color inicial del degradado. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color final del degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color inicial del degradado. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Color](/imaging/python-net/aspose.imaging/color/) que representa el color final del degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| is_angle_scalable | bool | si se establece en <c>true</c> el ángulo se cambia durante las transformaciones con este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuevo [Brush](/imaging/python-net/aspose.imaging/brush/) que es la clonación profunda de esta instancia de [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica en qué orden multiplicar las dos matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local en la cantidad especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe añadir al final o al principio la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


```
 scale_transform(sx, sy, order) 
```

Escala la transformación geométrica local por las cantidades especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe agregar o anteponer la matriz de escala. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

Crea un gradiente lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

Crea un gradiente lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |
| escala | float | Un valor de 0 a 1 que especifica la rapidez con la que los colores disminuyen desde el color inicial hasta el _enfoque_ (color final) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

Crea una caída de gradiente basada en una curva en forma de campana.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el color inicial y el color final se mezclan por igual). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

Crea una caída de gradiente basada en una curva en forma de campana.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |
| escala | float | Un valor de 0 a 1 que especifica la rapidez con la que los colores disminuyen desde el _enfoque_. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


```
 translate_transform(dx, dy, order) 
```

Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden (anteponer o agregar) en el que se aplica la traslación. |

