---
title: "Classe EmptyImageMask"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.magicwand.imagemasks/emptyimagemask/
---

**Summary:** Describes an empty non-abstract mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.EmptyImageMask

**Inheritance:** IImageMask, ImageMask

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmptyImageMask(width, height)](#EmptyImageMask_width_height_1) | Inizializza una nuova istanza della classe [EmptyImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/emptyimagemask/) con la larghezza e l'altezza specificate. |
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
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione magic wand applicata all'immagine fornita. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera. |
| [get(x, y)](#get_x_y_9) | Ottiene l'opacità del pixel specificato. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Ottiene l'opacità del pixel specificato con precisione byte. |
| [get_feathered(settings)](#get_feathered_settings_11) | Ottiene la maschera in scala di grigi con il bordo sfumato secondo le impostazioni specificate. |
| [inflate(size)](#inflate_size_12) | Espande questa maschera dell'importo specificato. |
| [intersect(image, settings)](#intersect_image_settings_13) | Restituisce l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita. |
| [intersect(mask)](#intersect_mask_14) | Restituisce l'intersezione della maschera corrente con quella fornita. |
| [intersect(settings)](#intersect_settings_15) | Restituisce l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera. |
| [invert()](#invert__16) | Restituisce l'inversione della maschera corrente. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Verifica se il pixel specificato è opaco. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Verifica se il pixel specificato è trasparente. |
| [subtract(image, settings)](#subtract_image_settings_19) | Restituisce il risultato della selezione bacchetta magica applicata all'immagine fornita sottratto dalla maschera corrente. |
| [subtract(mask)](#subtract_mask_20) | Restituisce la sottrazione della maschera fornita dalla corrente. |
| [subtract(settings)](#subtract_settings_21) | Restituisce il risultato della selezione bacchetta magica applicata alla sorgente della maschera corrente sottratto dalla maschera. |
| [union(image, settings)](#union_image_settings_22) | Restituisce l'unione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita. |
| [union(mask)](#union_mask_23) | Restituisce l'unione della maschera corrente con quella fornita. |
| [union(settings)](#union_settings_24) | Restituisce l'unione della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera. |


### Constructor: EmptyImageMask(width, height) {#EmptyImageMask_width_height_1}


```
 EmptyImageMask(width, height) 
```

Inizializza una nuova istanza della classe [EmptyImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/emptyimagemask/) con la larghezza e l'altezza specificate.

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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una EmptyImageMask ritagliata come ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione magic wand applicata all'immagine fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Ottiene l'opacità del pixel specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se il pixel specificato è opaco; altrimenti, false. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


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


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Ottiene la maschera in scala di grigi con il bordo sfumato secondo le impostazioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Impostazioni di sfumatura. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) con bordo sfumato. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Espande questa maschera dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | La quantità di gonfiatura di questa maschera. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Una EmptyImageMask gonfiata come ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Restituisce l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Restituisce l'intersezione della maschera corrente con quella fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Restituisce l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Restituisce l'inversione della maschera corrente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


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


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

Restituisce il risultato della selezione bacchetta magica applicata all'immagine fornita sottratto dalla maschera corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

Restituisce la sottrazione della maschera fornita dalla corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

Restituisce il risultato della selezione bacchetta magica applicata alla sorgente della maschera corrente sottratto dalla maschera.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

Restituisce l'unione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

Restituisce l'unione della maschera corrente con quella fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Maschera fornita |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

Restituisce l'unione della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni della bacchetta magica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


