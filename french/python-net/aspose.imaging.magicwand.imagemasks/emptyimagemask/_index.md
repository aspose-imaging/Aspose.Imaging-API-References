---
title: "Classe EmptyImageMask"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.magicwand.imagemasks/emptyimagemask/
---

**Summary:** Describes an empty non-abstract mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.EmptyImageMask

**Inheritance:** IImageMask, ImageMask

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmptyImageMask(width, height)](#EmptyImageMask_width_height_1) | Initialise une nouvelle instance de la classe [EmptyImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/emptyimagemask/) avec la largeur et la hauteur spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtient les limites, en pixels, de ce masque. |
| height | int | r | Obtient la hauteur, en pixels, de ce masque. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtient les limites de la partie sélectionnée du masque, en pixels. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Obtient l'image source utilisée pour créer ce masque, si elle existe. |
| width | int | r | Obtient la largeur, en pixels, de ce masque. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| apply() | Applique le masque actuel à la source [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) , si elle existe. |
| [apply_to(image)](#apply_to_image_1) | Applique le masque actuel au [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) spécifié. |
| [clone()](#clone__2) | Crée un nouvel objet qui est une copie de l'instance actuelle. |
| [crop(rectangle)](#crop_rectangle_3) | Recadre le masque avec le rectangle spécifié. |
| [crop(size)](#crop_size_4) | Recadre le masque avec la taille spécifiée. |
| [crop(width, height)](#crop_width_height_5) | Recadre le masque avec la largeur et la hauteur spécifiées. |
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Obtient la disjonction exclusive du masque actuel avec le résultat de la sélection baguette magique appliquée à l'image fournie. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Obtient la disjonction exclusive du masque actuel avec le masque fourni. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Obtient la disjonction exclusive du masque actuel avec le résultat de la sélection baguette magique appliquée à la source du masque. |
| [get(x, y)](#get_x_y_9) | Obtient l'opacité du pixel spécifié. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Obtient l'opacité du pixel spécifié avec une précision d'octet. |
| [get_feathered(settings)](#get_feathered_settings_11) | Obtient le masque en niveaux de gris avec la bordure adoucie selon les paramètres spécifiés. |
| [inflate(size)](#inflate_size_12) | Gonfle ce masque du montant spécifié. |
| [intersect(image, settings)](#intersect_image_settings_13) | Obtient l'intersection du masque actuel avec le résultat de la sélection baguette magique appliquée à l'image fournie. |
| [intersect(mask)](#intersect_mask_14) | Obtient l'intersection du masque actuel avec celui fourni. |
| [intersect(settings)](#intersect_settings_15) | Obtient l'intersection du masque actuel avec le résultat de la sélection baguette magique appliquée à la source du masque. |
| [invert()](#invert__16) | Obtient l'inversion du masque actuel. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Vérifie si le pixel spécifié est opaque. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Vérifie si le pixel spécifié est transparent. |
| [subtract(image, settings)](#subtract_image_settings_19) | Obtient le résultat de la sélection baguette magique appliquée à l'image fournie soustrait du masque actuel. |
| [subtract(mask)](#subtract_mask_20) | Obtient la soustraction du masque fourni du masque actuel. |
| [subtract(settings)](#subtract_settings_21) | Obtient le résultat de la sélection baguette magique appliquée à la source du masque actuel soustrait du masque. |
| [union(image, settings)](#union_image_settings_22) | Obtient l'union du masque actuel avec le résultat de la sélection baguette magique appliquée à l'image fournie. |
| [union(mask)](#union_mask_23) | Obtient l'union du masque actuel avec celui fourni. |
| [union(settings)](#union_settings_24) | Obtient l'union du masque actuel avec le résultat de la sélection baguette magique appliquée à la source du masque. |


### Constructor: EmptyImageMask(width, height) {#EmptyImageMask_width_height_1}


```
 EmptyImageMask(width, height) 
```

Initialise une nouvelle instance de la classe [EmptyImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/emptyimagemask/) avec la largeur et la hauteur spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | Largeur du masque. |
| height | int | Hauteur du masque. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Applique le masque actuel au [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image à laquelle appliquer le masque. |

### Method: clone() {#clone__2}


```
 clone() 
```

Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | Un nouvel objet qui est une copie de cette instance. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Recadre le masque avec le rectangle spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle spécifié. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Un EmptyImageMask recadré en tant qu'ImageMask. |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Recadre le masque avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La taille spécifiée. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Un ImageMask. |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Recadre le masque avec la largeur et la hauteur spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La largeur spécifiée. |
| height | int | La hauteur spécifiée. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Un ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Obtient la disjonction exclusive du masque actuel avec le résultat de la sélection baguette magique appliquée à l'image fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image pour la baguette magique. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Obtient la disjonction exclusive du masque actuel avec le masque fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Obtient la disjonction exclusive du masque actuel avec le résultat de la sélection baguette magique appliquée à la source du masque.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Obtient l'opacité du pixel spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si le pixel spécifié est opaque ; sinon, false. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


```
 get_byte_opacity(x, y) 
```

Obtient l'opacité du pixel spécifié avec une précision d'octet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Valeur d'octet, représentant l'opacité du pixel spécifié. |


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Obtient le masque en niveaux de gris avec la bordure adoucie selon les paramètres spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Paramètres de l'adoucissement. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) avec bordure adoucie. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Gonfle ce masque du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | int | La quantité pour gonfler ce masque. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Un EmptyImageMask gonflé en tant qu'ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Obtient l'intersection du masque actuel avec le résultat de la sélection baguette magique appliquée à l'image fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image pour la baguette magique. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Obtient l'intersection du masque actuel avec celui fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Obtient l'intersection du masque actuel avec le résultat de la sélection baguette magique appliquée à la source du masque.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Obtient l'inversion du masque actuel.

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


```
 is_opaque(x, y) 
```

Vérifie si le pixel spécifié est opaque.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si le pixel spécifié est opaque ; sinon, false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


```
 is_transparent(x, y) 
```

Vérifie si le pixel spécifié est transparent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si le pixel spécifié est transparent ; sinon, false. |


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

Obtient le résultat de la sélection baguette magique appliquée à l'image fournie soustrait du masque actuel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image pour la baguette magique. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

Obtient la soustraction du masque fourni du masque actuel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

Obtient le résultat de la sélection baguette magique appliquée à la source du masque actuel soustrait du masque.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

Obtient l'union du masque actuel avec le résultat de la sélection baguette magique appliquée à l'image fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image pour la baguette magique. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

Obtient l'union du masque actuel avec celui fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

Obtient l'union du masque actuel avec le résultat de la sélection baguette magique appliquée à la source du masque.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de la baguette magique. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


