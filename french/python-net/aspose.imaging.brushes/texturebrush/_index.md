---
title: "Classe TextureBrush"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le mode d'enroulement. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtient l'objet [Image](/imaging/python-net/aspose.imaging/image/) associé à cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Obtient les [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/) associés à ce [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) associé à ce [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est totalement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit une copie de la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui définit une transformation géométrique locale pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtient ou définit une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui indique le mode d'habillage pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le mode d'enroulement. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation. |
| [deep_clone()](#deep_clone__8) | Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel. |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué. |
| reset_transform() | Réinitialise la propriété [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) qui contient des informations supplémentaires sur l'image utilisée par cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) qui contient des informations supplémentaires sur l'image utilisée par cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) est répété. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) est répété. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) est répété. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) qui contient des informations supplémentaires sur l'image utilisée par cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) qui contient des informations supplémentaires sur l'image utilisée par cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) est répété. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) est répété. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'enroulement et le rectangle de délimitation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'objet [Image](/imaging/python-net/aspose.imaging/image/) avec lequel cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) est répété. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant de cet objet [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel.

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nouveau [Brush](/imaging/python-net/aspose.imaging/brush/) qui est le clone profond de cette instance [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie dans quel ordre multiplier les deux matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


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

