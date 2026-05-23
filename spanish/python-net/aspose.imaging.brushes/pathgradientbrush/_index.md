---
title: "Clase PathGradientBrush"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Inicializa una nueva instancia de la clase PathGradientBrush |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_2) | Inicializa una nueva instancia de la clase PathGradientBrush |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_3) | Inicializa una nueva instancia de la clase PathGradientBrush |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_4) | Inicializa una nueva instancia de la clase PathGradientBrush |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_5) | Inicializa una nueva instancia de la clase PathGradientBrush |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Obtiene o establece un [Blend](/imaging/python-net/aspose.imaging/blend/) que especifica posiciones y factores que definen una caída personalizada para el gradiente. |
| center_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el color en el centro del degradado de ruta. |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece el punto central del degradado de ruta. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece el punto focal para la caída del degradado. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Obtiene la ruta gráfica sobre la que se construyó este pincel. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Obtiene o establece un [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) que define un degradado lineal multicolor. |
| is_transform_changed | bool | r | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, al establecer la matriz de transformación o<br/>            al llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+. |
| opacity | float | r/w | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene los puntos de la ruta sobre los que se construyó este pincel. |
| surround_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece una matriz de colores que corresponden a los puntos en la ruta que este [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) rellena. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece una copia de [Matrix](/imaging/python-net/aspose.imaging/matrix/) que define una transformación geométrica local para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtiene o establece una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que indica el modo de ajuste para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con la ruta especificada. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados y el modo de ajuste. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados y el modo de ajuste. |
| [deep_clone()](#deep_clone__6) | Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual. |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado. |
| reset_transform() | Restablece la propiedad [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Rota la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Escala la transformación geométrica local por las cantidades especificadas en el orden especificado. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_13) | Crea un degradado con un color central y una disminución lineal hacia un color circundante. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_14) | Crea un degradado con un color central y una disminución lineal hacia cada color circundante. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_15) | Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_16) | Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_17) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_18) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Inicializa una nueva instancia de la clase PathGradientBrush

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_2}


```
 PathGradientBrush(path_points) 
```

Inicializa una nueva instancia de la clase PathGradientBrush

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_3}


```
 PathGradientBrush(path_points) 
```

Inicializa una nueva instancia de la clase PathGradientBrush

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_4}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Inicializa una nueva instancia de la clase PathGradientBrush

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_5}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Inicializa una nueva instancia de la clase PathGradientBrush

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con la ruta especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define el área rellenada por este [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa los puntos que forman los vértices de la ruta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa los puntos que forman los vértices de la ruta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados y el modo de ajuste.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa los puntos que forman los vértices de la ruta. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se repiten los rellenos dibujados con este [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Inicializa una nueva instancia del [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) con los puntos especificados y el modo de ajuste.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que representa los puntos que forman los vértices de la ruta. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se repiten los rellenos dibujados con este [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuevo [Brush](/imaging/python-net/aspose.imaging/brush/) que es la clonación profunda de esta instancia de [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica en qué orden multiplicar las dos matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local en la cantidad especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe añadir al final o al principio la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_13}


```
 set_blend_triangular_shape(focus) 
```

Crea un degradado con un color central y una disminución lineal hacia un color circundante.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (el predeterminado) coloca la máxima intensidad en el centro de la ruta. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_14}


```
 set_blend_triangular_shape(focus, scale) 
```

Crea un degradado con un color central y una disminución lineal hacia cada color circundante.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (el predeterminado) coloca la máxima intensidad en el centro de la ruta. |
| escala | float | Un valor de 0 a 1 que especifica la intensidad máxima del color central que se mezcla con el color del límite. Un valor de 1 produce la mayor intensidad posible del color central, y es el valor predeterminado. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_15}


```
 set_sigma_bell_shape(focus) 
```

Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (el predeterminado) coloca la máxima intensidad en el centro de la ruta. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_16}


```
 set_sigma_bell_shape(focus, scale) 
```

Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (el predeterminado) coloca la máxima intensidad en el centro de la ruta. |
| escala | float | Un valor de 0 a 1 que especifica la intensidad máxima del color central que se mezcla con el color del límite. Un valor de 1 produce la mayor intensidad posible del color central, y es el valor predeterminado. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_17}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_18}


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

