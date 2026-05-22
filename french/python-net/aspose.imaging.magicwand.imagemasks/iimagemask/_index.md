---
title: "IImageMask Classe"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

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
| [clone()](#clone__1) | Crée un nouvel objet qui est une copie de l'instance actuelle. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Obtient l'opacité du pixel spécifié avec une précision d'octet. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Vérifie si le pixel spécifié est opaque. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Vérifie si le pixel spécifié est transparent. |


### Method: clone() {#clone__1}


```
 clone() 
```

Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns**

| Type | Description |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


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


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


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


