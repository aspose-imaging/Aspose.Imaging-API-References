---
title: "Clase TextureBrush"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el modo de ajuste. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene el objeto [Image](/imaging/python-net/aspose.imaging/image/) asociado a este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Obtiene los [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/) asociados a este [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene el [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) asociado con este [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| is_transform_changed | bool | r | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, al establecer la matriz de transformación o<br/>            al llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+. |
| opacity | float | r/w | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece una copia de [Matrix](/imaging/python-net/aspose.imaging/matrix/) que define una transformación geométrica local para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtiene o establece una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que indica el modo de ajuste para este [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el modo de ajuste. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [deep_clone()](#deep_clone__8) | Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual. |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado. |
| reset_transform() | Restablece la propiedad [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Rota la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Escala la transformación geométrica local por las cantidades especificadas en el orden especificado. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) que contiene información adicional sobre la imagen utilizada por este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) que contiene información adicional sobre la imagen utilizada por este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el modo de ajuste.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se mosaica este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se mosaica este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se mosaica este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) que contiene información adicional sobre la imagen utilizada por este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) que contiene información adicional sobre la imagen utilizada por este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada y el modo de ajuste.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se mosaica este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se mosaica este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Inicializa una nueva instancia de la clase [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | El objeto [Image](/imaging/python-net/aspose.imaging/image/) con el que este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) rellena los interiores. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumeración [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se mosaica este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador de este objeto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuevo [Brush](/imaging/python-net/aspose.imaging/brush/) que es la clonación profunda de esta instancia de [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica en qué orden multiplicar las dos matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local en la cantidad especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe añadir al final o al principio la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


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

