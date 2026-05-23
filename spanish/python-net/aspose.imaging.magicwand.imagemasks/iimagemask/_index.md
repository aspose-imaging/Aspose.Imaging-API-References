---
title: "Clase IImageMask"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

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
| [clone()](#clone__1) | Crea un nuevo objeto que es una copia de la instancia actual. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Obtiene la opacidad del píxel especificado con precisión de byte. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Comprueba si el píxel especificado es opaco. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Comprueba si el píxel especificado es transparente. |


### Method: clone() {#clone__1}


```
 clone() 
```

Crea un nuevo objeto que es una copia de la instancia actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


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


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


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


