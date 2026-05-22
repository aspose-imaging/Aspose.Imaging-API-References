---
title: "Classe Size"
type: docs
weight: 7280
url: /fr/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Size()](#Size__1) | Initialise une nouvelle instance de la classe Size |
| [Size(point)](#Size_point_2) | Initialise une nouvelle instance de la structure [Size](/imaging/python-net/aspose.imaging/size/) à partir du [Point](/imaging/python-net/aspose.imaging/point/) spécifié. |
| [Size(width, height)](#Size_width_height_3) | Initialise une nouvelle instance de la structure [Size](/imaging/python-net/aspose.imaging/size/) à partir des dimensions spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtient une nouvelle instance de la structure [Size](/imaging/python-net/aspose.imaging/size/) dont les valeurs [Size.width](/imaging/python-net/aspose.imaging/size/) et [Size.height](/imaging/python-net/aspose.imaging/size/) sont définies à zéro. |
| height | int | r/w | Obtient ou définit le composant vertical de ce [Size](/imaging/python-net/aspose.imaging/size/). |
| is_empty | bool | r | Obtient une valeur indiquant si ce [Size](/imaging/python-net/aspose.imaging/size/) a une largeur et une hauteur de 0. |
| width | int | r/w | Obtient ou définit le composant horizontal de ce [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Ajoute la largeur et la hauteur d'une structure [Size](/imaging/python-net/aspose.imaging/size/) à la largeur et la hauteur d'une autre structure [Size](/imaging/python-net/aspose.imaging/size/). |
| [ceiling(size)](#ceiling_size_2) | Convertit la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifiée en une structure [Size](/imaging/python-net/aspose.imaging/size/) en arrondissant les valeurs de la structure [Size](/imaging/python-net/aspose.imaging/size/) au nombre entier supérieur le plus proche. |
| [round(size)](#round_size_3) | Convertit la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifiée en une structure [Size](/imaging/python-net/aspose.imaging/size/) en arrondissant les valeurs de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) au nombre entier le plus proche. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Soustrait la largeur et la hauteur d'une structure [Size](/imaging/python-net/aspose.imaging/size/) de la largeur et la hauteur d'une autre structure [Size](/imaging/python-net/aspose.imaging/size/). |
| [truncate(size)](#truncate_size_5) | Convertit la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifiée en une structure [Size](/imaging/python-net/aspose.imaging/size/) en tronquant les valeurs de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) au nombre entier inférieur le plus proche. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initialise une nouvelle instance de la classe Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initialise une nouvelle instance de la structure [Size](/imaging/python-net/aspose.imaging/size/) à partir du [Point](/imaging/python-net/aspose.imaging/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) à partir duquel initialiser ce [Size](/imaging/python-net/aspose.imaging/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initialise une nouvelle instance de la structure [Size](/imaging/python-net/aspose.imaging/size/) à partir des dimensions spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | Le composant largeur du nouveau [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | Le composant hauteur du nouveau [Size](/imaging/python-net/aspose.imaging/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Ajoute la largeur et la hauteur d'une structure [Size](/imaging/python-net/aspose.imaging/size/) à la largeur et la hauteur d'une autre structure [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Le premier [Size](/imaging/python-net/aspose.imaging/size/) à ajouter. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Le deuxième [Size](/imaging/python-net/aspose.imaging/size/) à ajouter. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Une structure [Size](/imaging/python-net/aspose.imaging/size/) qui est le résultat de l'opération d'addition. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Convertit la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifiée en une structure [Size](/imaging/python-net/aspose.imaging/size/) en arrondissant les valeurs de la structure [Size](/imaging/python-net/aspose.imaging/size/) au nombre entier supérieur le plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La structure [Size](/imaging/python-net/aspose.imaging/size/) vers laquelle cette méthode convertit. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Convertit la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifiée en une structure [Size](/imaging/python-net/aspose.imaging/size/) en arrondissant les valeurs de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) au nombre entier le plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La structure [Size](/imaging/python-net/aspose.imaging/size/) vers laquelle cette méthode convertit. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Soustrait la largeur et la hauteur d'une structure [Size](/imaging/python-net/aspose.imaging/size/) de la largeur et la hauteur d'une autre structure [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | La structure [Size](/imaging/python-net/aspose.imaging/size/) du côté gauche de l'opérateur de soustraction. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | La structure [Size](/imaging/python-net/aspose.imaging/size/) du côté droit de l'opérateur de soustraction. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La [Size](/imaging/python-net/aspose.imaging/size/) qui est le résultat de l'opération de soustraction. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Convertit la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifiée en une structure [Size](/imaging/python-net/aspose.imaging/size/) en tronquant les valeurs de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) au nombre entier inférieur le plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | La structure [Size](/imaging/python-net/aspose.imaging/size/) vers laquelle cette méthode convertit. |


