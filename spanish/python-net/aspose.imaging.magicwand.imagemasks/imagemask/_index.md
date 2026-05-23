---
title: "Clase ImageMask"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.magicwand.imagemasks/imagemask/
---

**Summary:** Describes a binary image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageMask

**Inheritance:** IImageMask

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
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Obtiene la disyunción exclusiva de la máscara actual con lo proporcionado. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara. |
| [get(x, y)](#get_x_y_9) | Obtiene la opacidad del píxel especificado. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Obtiene la opacidad del píxel especificado con precisión de byte. |
| [get_feathered(settings)](#get_feathered_settings_11) | Obtiene la máscara en escala de grises con el borde difuminado según la configuración especificada. |
| [inflate(size)](#inflate_size_12) | Infla esta máscara en la cantidad especificada. |
| [intersect(image, settings)](#intersect_image_settings_13) | Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [intersect(mask)](#intersect_mask_14) | Obtiene la intersección de la máscara actual con la proporcionada. |
| [intersect(settings)](#intersect_settings_15) | Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada al origen de la máscara. |
| [invert()](#invert__16) | Obtiene la inversión de la máscara actual. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Comprueba si el píxel especificado es opaco. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Comprueba si el píxel especificado es transparente. |
| [subtract(image, settings)](#subtract_image_settings_19) | Obtiene el resultado de la selección con varita mágica aplicada a la imagen proporcionada restado de la máscara actual. |
| [subtract(mask)](#subtract_mask_20) | Obtiene la sustracción de la máscara proporcionada de la actual. |
| [subtract(settings)](#subtract_settings_21) | Obtiene el resultado de la selección con varita mágica aplicada al origen de la máscara actual restado de la máscara. |
| [union(image, settings)](#union_image_settings_22) | Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [union(mask)](#union_mask_23) | Obtiene la unión de la máscara actual con la proporcionada. |
| [union(settings)](#union_settings_24) | Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada al origen de la máscara. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Obtiene la disyunción exclusiva de la máscara actual con lo proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Obtiene la opacidad del píxel especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si el píxel especificado es opaco; de lo contrario, false. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


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


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Obtiene la máscara en escala de grises con el borde difuminado según la configuración especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Configuración de difuminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con borde difuminado. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Infla esta máscara en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tamaño | int | La cantidad para inflar esta máscara. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Obtiene la intersección de la máscara actual con la proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada al origen de la máscara.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Obtiene la inversión de la máscara actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


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


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

Obtiene el resultado de la selección con varita mágica aplicada a la imagen proporcionada restado de la máscara actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

Obtiene la sustracción de la máscara proporcionada de la actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

Obtiene el resultado de la selección con varita mágica aplicada al origen de la máscara actual restado de la máscara.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

Obtiene la unión de la máscara actual con la proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Máscara proporcionada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada al origen de la máscara.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración de la varita mágica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


