---
title: "Classe ImageGrayscaleMask"
type: docs
weight: 60
url: /fr/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Initialise une nouvelle instance de la classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) avec la taille de l'[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) existant spécifié.<br/>            L'[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) spécifié sera stocké comme image source. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Initialise une nouvelle instance de la classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) avec la largeur et la hauteur spécifiées. |
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
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Obtient la disjonction exclusive du masque actuel avec le masque fourni. |
| [get(x, y)](#get_x_y_7) | Obtient ou définit l'opacité du pixel spécifié. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Obtient l'opacité du pixel spécifié avec une précision d'octet. |
| [intersect(mask)](#intersect_mask_9) | Obtient l'intersection du masque actuel avec celui fourni. |
| [invert()](#invert__10) | Obtient l'inversion du masque actuel. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Vérifie si le pixel spécifié est opaque. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Vérifie si le pixel spécifié est transparent. |
| [set(x, y, value)](#set_x_y_value_13) | Définit l'opacité du pixel spécifié. |
| [subtract(mask)](#subtract_mask_14) | Obtient la soustraction du masque fourni du masque actuel. |
| [union(mask)](#union_mask_15) | Union de deux masques. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Initialise une nouvelle instance de la classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) avec la taille de l'[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) existant spécifié.<br/>            L'[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) spécifié sera stocké comme image source.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image source. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Initialise une nouvelle instance de la classe [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) avec la largeur et la hauteur spécifiées.

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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Un [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) recadré. |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Un [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) recadré. |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Un [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) recadré. |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Obtient la disjonction exclusive du masque actuel avec le masque fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nouveau [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Obtient ou définit l'opacité du pixel spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Valeur d'octet ; 0 si transparent ; 255 si opaque. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


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


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Obtient l'intersection du masque actuel avec celui fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nouveau [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Obtient l'inversion du masque actuel.

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nouveau [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


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


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Définit l'opacité du pixel spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |
| value | System.Byte | Valeur d'octet ; 0 si transparent ; 255 si opaque. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Obtient la soustraction du masque fourni du masque actuel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nouveau [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

Union de deux masques.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Masque fourni |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Nouveau [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


