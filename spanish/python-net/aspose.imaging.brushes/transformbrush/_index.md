---
title: "Clase TransformBrush"
type: docs
weight: 100
url: /es/python-net/aspose.imaging.brushes/transformbrush/
---

**Summary:** A [Brush](/imaging/python-net/aspose.imaging/brush/) with transform capabilities.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TransformBrush

**Inheritance:** Brush

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| is_transform_changed | bool | r | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, al establecer la matriz de transformación o<br/>            al llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+. |
| opacity | float | r/w | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece una copia de [Matrix](/imaging/python-net/aspose.imaging/matrix/) que define una transformación geométrica local para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtiene o establece una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que indica el modo de ajuste para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado. |
| reset_transform() | Restablece la propiedad [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Rota la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Escala la transformación geométrica local por las cantidades especificadas en el orden especificado. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuevo [Brush](/imaging/python-net/aspose.imaging/brush/) que es la clonación profunda de esta instancia de [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica en qué orden multiplicar las dos matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local en la cantidad especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe añadir al final o al principio la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


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

