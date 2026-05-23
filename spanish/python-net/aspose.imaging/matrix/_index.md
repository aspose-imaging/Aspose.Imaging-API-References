---
title: "Clase Matrix"
type: docs
weight: 6070
url: /es/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Matrix()](#Matrix__1) | Inicializa una nueva instancia de la clase Matrix como la matriz identidad. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Crea una copia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Este bit de bandera indica que la transformación definida por este objeto<br/>            realiza una inversión de imagen espejo alrededor de algún eje que cambia el<br/>            sistema de coordenadas normalmente derecho a uno izquierdo<br/>            además de las conversiones indicadas por otros bits de bandera.<br/>            Un sistema de coordenadas derecho es aquel donde el eje X positivo<br/>            gira en sentido antihorario para superponerse al eje Y positivo<br/>            similar a la dirección en que los dedos de su mano derecha<br/>            se curvan cuando mira de frente su pulgar.<br/>            Un sistema de coordenadas izquierdo es aquel donde el eje X positivo<br/>            gira en sentido horario para superponerse al eje Y positivo similar<br/>            a la dirección en que los dedos de su mano izquierda se curvan.<br/>            No hay forma matemática de determinar el ángulo de la<br/>            inversión o espejo original ya que todos los ángulos<br/>            de volteo son idénticos dado una rotación de ajuste apropiada.<br/>            NOTA: TypeFlip se añadió después de que GENERAL_TRANSFORM estuviera en circulación pública<br/>            y los bits de bandera ya no pudieron renumerarse convenientemente<br/>            sin introducir incompatibilidad binaria en código externo. |
| TYPE_GENERAL_ROTATION [static] | int | r | Este bit de bandera indica que la transformación definida por este objeto<br/>            realiza una rotación por un ángulo arbitrario además de las<br/>            conversiones indicadas por otros bits de bandera.<br/>            Una rotación cambia los ángulos de los vectores en la misma cantidad<br/>            sin importar la dirección original del vector y sin<br/>            cambiar la longitud del vector.<br/>            Este bit de bandera es mutuamente excluyente con el |
| TYPE_GENERAL_SCALE [static] | int | r | Una escala general multiplica la longitud de los vectores por diferentes<br/>            cantidades en las direcciones x e y sin cambiar el ángulo<br/>            entre vectores perpendiculares.<br/>            Este bit de bandera es mutuamente excluyente con la bandera TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Esta constante indica que la transformación definida por este objeto<br/>            realiza una conversión arbitraria de las coordenadas de entrada.<br/>            Si esta transformación puede clasificarse mediante cualquiera de las constantes anteriores,<br/>            el tipo será la constante TypeIdentity o una<br/>            combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas<br/>            que realiza esta transformación. |
| TYPE_IDENTITY [static] | int | r | Una transformación de identidad es aquella en la que las coordenadas de salida son<br/>            siempre las mismas que las coordenadas de entrada.<br/>            Si esta transformación es algo distinto de la transformación de identidad,<br/>            el tipo será la constante GENERAL_TRANSFORM o una<br/>            combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas<br/>            que realiza esta transformación. |
| TYPE_MASK_ROTATION [static] | int | r | Esta constante es una máscara de bits para cualquiera de los bits de bandera de rotación. |
| TYPE_MASK_SCALE [static] | int | r | Esta constante es una máscara de bits para cualquiera de los bits de bandera de escala. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Este bit de bandera indica que la transformación definida por este objeto<br/>            realiza una rotación de cuadrante por algún múltiplo de 90 grados además de las<br/>            conversiones indicadas por otros bits de bandera.<br/>            Una rotación cambia los ángulos de los vectores en la misma cantidad<br/>            sin importar la dirección original del vector y sin<br/>            cambiar la longitud del vector.<br/>            Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | Una traducción mueve las coordenadas una cantidad constante en x<br/>            e y sin cambiar la longitud o el ángulo de los vectores. |
| TYPE_UNIFORM_SCALE [static] | int | r | Una escala uniforme multiplica la longitud de los vectores por la misma cantidad<br/>            en ambas direcciones x e y sin cambiar el ángulo entre<br/>            vectores.<br/>            Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralScale. |
| elements | float[] | r | Obtiene una matriz de valores de punto flotante que representa los elementos de este [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| m11 | float | r | Obtiene el elemento de la matriz en la primera fila, primera columna. Representa la escala a lo largo del eje X. |
| m12 | float | r | Obtiene el elemento de la matriz en la primera fila, segunda columna. Representa el sesgo a lo largo del eje Y. |
| m21 | float | r | Obtiene el elemento de la matriz en la segunda fila, primera columna. Representa una cizalla a lo largo del eje X. |
| m22 | float | r | Obtiene el elemento de la matriz en la segunda fila, segunda columna. Representa una escala a lo largo del eje Y. |
| m31 | float | r | Obtiene el elemento de la matriz en la tercera fila, primera columna. Representa una traslación a lo largo del eje X. |
| m32 | float | r | Obtiene el elemento de la matriz en la tercera fila, primera columna. Representa una traslación a lo largo del eje Y. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
| [get_elements()](#get_elements__3) | Obtiene una copia de los elementos de la matriz. |
| [multiply(t_tx)](#multiply_t_tx_4) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend. |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order. |
| reset() | Restablece esta Matrix para que tenga los elementos de la matriz identidad. |
| [rotate(angle)](#rotate_angle_6) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden predeterminado (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_7) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden especificado. |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden predeterminado (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | Aplica el vector de escala especificado (scaleX y scaleY) a este [Matrix](/imaging/python-net/aspose.imaging/matrix/) usando el orden especificado. |
| [scale(sx, sy)](#scale_sx_sy_11) | Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden (predeterminado) Prepend. |
| [transform_points(points)](#transform_points_points_12) | Aplica la transformación geométrica representada por este [Matrix](/imaging/python-net/aspose.imaging/matrix/) a una matriz de puntos especificada. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | Aplica el vector de traslación especificado a esta Matrix en el orden especificado. |
| [translate(tx, ty)](#translate_tx_ty_14) | Aplica el vector de traslación especificado a este [Matrix](/imaging/python-net/aspose.imaging/matrix/) usando el orden (predeterminado) Prepend. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Inicializa una nueva instancia de la clase Matrix como la matriz identidad.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| m11 | float | m00     M11     Escala X |
| m12 | float | m10     M12     Cizalla Y |
| m21 | float | m01     M21     Cizalla X |
| m22 | float | m11     M22     Escala Y |
| m31 | float | m02     M31     Traslación X |
| m32 | float | m12     M32     Trasladar Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Crea una copia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Una matriz base para copiar |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo a transformar. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de tres estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo a transformar. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Una matriz de tres estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo a transformar. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Una matriz de tres estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

Inicializa una nueva instancia de la clase [Matrix](/imaging/python-net/aspose.imaging/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo a transformar. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Una matriz de tres estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

Obtiene una copia de los elementos de la matriz.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] | Una copia de los elementos de la matriz. |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

Multiplica esta Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz con la que multiplicar. |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

Multiplica esta Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | El tx. El tx. El tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden. El orden. El orden. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden predeterminado (Prepend).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden de la matriz. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden predeterminado (Prepend).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El punto. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El punto. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

Aplica el vector de escala especificado (scaleX y scaleY) a este [Matrix](/imaging/python-net/aspose.imaging/matrix/) usando el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scale_x | float | La escala X. |
| scale_y | float | La escala Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden. |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden (predeterminado) Prepend.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | El sx. El sx. El sx. |
| sy | float | El sy. El sy. El sy. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

Aplica la transformación geométrica representada por este [Matrix](/imaging/python-net/aspose.imaging/matrix/) a una matriz de puntos especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Los puntos. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

Aplica el vector de traslación especificado a esta Matrix en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| offset_x | float | El desplazamiento X. |
| offset_y | float | El desplazamiento Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden. |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

Aplica el vector de traslación especificado a este [Matrix](/imaging/python-net/aspose.imaging/matrix/) usando el orden (predeterminado) Prepend.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tx | float | El tx. El tx. El tx. |
| ty | float | El ty. El ty. El ty. |

