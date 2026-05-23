---
title: "Classe ImageGrayscaleMask"
type: docs
weight: 60
url: /it/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Inizializza una nuova istanza della classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con le dimensioni della [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) esistente specificata.<br/>            La [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) specificata verrà memorizzata come immagine sorgente. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Inizializza una nuova istanza della classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con la larghezza e l'altezza specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Restituisce i limiti, in pixel, di questa maschera. |
| height | int | r | Restituisce l'altezza, in pixel, di questa maschera. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Restituisce i limiti della parte selezionata della maschera, in pixel. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Restituisce l'immagine sorgente utilizzata per creare questa maschera, se esiste. |
| width | int | r | Restituisce la larghezza, in pixel, di questa maschera. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| apply() | Applica la maschera corrente alla sorgente [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), se esiste. |
| [apply_to(image)](#apply_to_image_1) | Applica la maschera corrente al [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) specificato. |
| [clone()](#clone__2) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
| [crop(rectangle)](#crop_rectangle_3) | Ritaglia la maschera con il rettangolo specificato. |
| [crop(size)](#crop_size_4) | Ritaglia la maschera con la dimensione specificata. |
| [crop(width, height)](#crop_width_height_5) | Ritaglia la maschera con la larghezza e l'altezza specificate. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita. |
| [get(x, y)](#get_x_y_7) | Ottiene o imposta l'opacità del pixel specificato. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Ottiene l'opacità del pixel specificato con precisione byte. |
| [intersect(mask)](#intersect_mask_9) | Restituisce l'intersezione della maschera corrente con quella fornita. |
| [invert()](#invert__10) | Restituisce l'inversione della maschera corrente. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Verifica se il pixel specificato è opaco. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Verifica se il pixel specificato è trasparente. |
| [set(x, y, value)](#set_x_y_value_13) | Imposta l'opacità del pixel specificato. |
| [subtract(mask)](#subtract_mask_14) | Restituisce la sottrazione della maschera fornita dalla corrente. |
| [union(mask)](#union_mask_15) | Unione di due maschere. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Inizializza una nuova istanza della classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con le dimensioni della [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) esistente specificata.<br/>            La [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) specificata verrà memorizzata come immagine sorgente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Immagine sorgente. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Inizializza una nuova istanza della classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con la larghezza e l'altezza specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | Larghezza della maschera. |
| height | int | Altezza della maschera. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Applica la maschera corrente al [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Immagine a cui applicare la maschera. |

### Method: clone() {#clone__2}


```
 clone() 
```

Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Object | Un nuovo oggetto che è una copia di questa istanza. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Ritaglia la maschera con il rettangolo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo specificato. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Una [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) ritagliata. |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Ritaglia la maschera con la dimensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La dimensione specificata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Una [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) ritagliata. |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Ritaglia la maschera con la larghezza e l'altezza specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza specificata. |
| height | int | L'altezza specificata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Una [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) ritagliata. |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nuova [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Ottiene o imposta l'opacità del pixel specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | Valore byte; 0 se trasparente; 255 se opaco. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


```
 get_byte_opacity(x, y) 
```

Ottiene l'opacità del pixel specificato con precisione byte.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | Valore byte, che rappresenta l'opacità del pixel specificato. |


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Restituisce l'intersezione della maschera corrente con quella fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nuova [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Restituisce l'inversione della maschera corrente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nuova [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


```
 is_opaque(x, y) 
```

Verifica se il pixel specificato è opaco.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se il pixel specificato è opaco; altrimenti, false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


```
 is_transparent(x, y) 
```

Verifica se il pixel specificato è trasparente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se il pixel specificato è trasparente; altrimenti, false. |


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Imposta l'opacità del pixel specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |
| valore | System.Byte | Valore byte; 0 se trasparente; 255 se opaco. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Restituisce la sottrazione della maschera fornita dalla corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nuova [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

Unione di due maschere.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nuova [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


