---
title: "Clase ImageGrayscaleMask"
type: docs
weight: 60
url: /es/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Inicializa una nueva instancia de la clase [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con el tamaño del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) existente especificado.<br/>            El [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) especificado se almacenará como imagen de origen. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Inicializa una nueva instancia de la clase [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con el ancho y la altura especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites, en píxeles, de esta máscara. |
| height | int | r | Obtiene la altura, en píxeles, de esta máscara. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites de la parte seleccionada de la máscara, en píxeles. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Obtiene la imagen fuente utilizada para crear esta máscara, si existe. |
| width | int | r | Obtiene el ancho, en píxeles, de esta máscara. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| apply() | Aplica la máscara actual a la fuente [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), si existe. |
| [apply_to(image)](#apply_to_image_1) | Aplica la máscara actual al [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) especificado. |
| [clone()](#clone__2) | Crea un nuevo objeto que es una copia de la instancia actual. |
| [crop(rectangle)](#crop_rectangle_3) | Recorta la máscara con el rectángulo especificado. |
| [crop(size)](#crop_size_4) | Recorta la máscara con el tamaño especificado. |
| [crop(width, height)](#crop_width_height_5) | Recorta la máscara con el ancho y alto especificados. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Obtiene la disyunción exclusiva de la máscara actual con lo proporcionado. |
| [get(x, y)](#get_x_y_7) | Obtiene o establece la opacidad del píxel especificado. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Obtiene la opacidad del píxel especificado con precisión de byte. |
| [intersect(mask)](#intersect_mask_9) | Obtiene la intersección de la máscara actual con la proporcionada. |
| [invert()](#invert__10) | Obtiene la inversión de la máscara actual. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Comprueba si el píxel especificado es opaco. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Comprueba si el píxel especificado es transparente. |
| [set(x, y, value)](#set_x_y_value_13) | Establece la opacidad del píxel especificado. |
| [subtract(mask)](#subtract_mask_14) | Obtiene la sustracción de la máscara proporcionada de la actual. |
| [union(mask)](#union_mask_15) | Unión de dos máscaras. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Inicializa una nueva instancia de la clase [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con el tamaño del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) existente especificado.<br/>            El [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) especificado se almacenará como imagen de origen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen de origen. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Inicializa una nueva instancia de la clase [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con el ancho y la altura especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | Ancho de la máscara. |
| height | int | Altura de la máscara. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Aplica la máscara actual al [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen a la que aplicar la máscara. |

### Method: clone() {#clone__2}


```
 clone() 
```

Crea un nuevo objeto que es una copia de la instancia actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object | Un nuevo objeto que es una copia de esta instancia. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Recorta la máscara con el rectángulo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo especificado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Una [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) recortada. |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Recorta la máscara con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | El tamaño especificado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Una [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) recortada. |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Recorta la máscara con el ancho y alto especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho especificado. |
| height | int | La altura especificada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Una [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) recortada. |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Obtiene la disyunción exclusiva de la máscara actual con lo proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nueva [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Obtiene o establece la opacidad del píxel especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Valor de byte; 0 si es transparente; 255 si es opaco. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


```
 get_byte_opacity(x, y) 
```

Obtiene la opacidad del píxel especificado con precisión de byte.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Valor de byte, que representa la opacidad del píxel especificado. |


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Obtiene la intersección de la máscara actual con la proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nueva [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Obtiene la inversión de la máscara actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nueva [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


```
 is_opaque(x, y) 
```

Comprueba si el píxel especificado es opaco.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si el píxel especificado es opaco; de lo contrario, false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


```
 is_transparent(x, y) 
```

Comprueba si el píxel especificado es transparente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si el píxel especificado es transparente; de lo contrario, false. |


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Establece la opacidad del píxel especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |
| valor | System.Byte | Valor de byte; 0 si es transparente; 255 si es opaco. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Obtiene la sustracción de la máscara proporcionada de la actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nueva [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

Unión de dos máscaras.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nueva [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


