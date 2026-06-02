---
title: "Classe SizeF"
type: docs
weight: 7290
url: /fr/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initialise une nouvelle instance de la classe SizeF |
| [SizeF(point)](#SizeF_point_2) | Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié. |
| [SizeF(size)](#SizeF_size_3) | Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifié. |
| [SizeF(width, height)](#SizeF_width_height_4) | Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir des dimensions spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Obtient une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) dont les valeurs [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) et [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) sont réglées à zéro. |
| height | float | r/w | Obtient ou définit le composant vertical de ce [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| is_empty | bool | r | Obtient une valeur indiquant si ce [SizeF](/imaging/python-net/aspose.imaging/sizef/) a une largeur et une hauteur nulles. |
| width | float | r/w | Obtient ou définit le composant horizontal de ce [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Ajoute la largeur et la hauteur d'une structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à la largeur et la hauteur d'une autre structure [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié. |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifié. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Soustrait la largeur et la hauteur d'une structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) de la largeur et la hauteur d'une autre structure [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [to_point_f()](#to_point_f__5) | Convertit un [SizeF](/imaging/python-net/aspose.imaging/sizef/) en un [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [to_size()](#to_size__6) | Convertit un [SizeF](/imaging/python-net/aspose.imaging/sizef/) en une structure [Size](/imaging/python-net/aspose.imaging/size/) avec des valeurs de taille tronquées. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initialise une nouvelle instance de la classe SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) à partir duquel initialiser ce [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir duquel créer le nouveau [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir des dimensions spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | float | Le composant largeur du nouveau [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| height | float | Le composant hauteur du nouveau [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Ajoute la largeur et la hauteur d'une structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à la largeur et la hauteur d'une autre structure [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Le premier [SizeF](/imaging/python-net/aspose.imaging/sizef/) à ajouter. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Le deuxième [SizeF](/imaging/python-net/aspose.imaging/sizef/) à ajouter. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Une structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) qui est le résultat de l'opération d'addition. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) à partir duquel initialiser ce [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Initialise une nouvelle instance de la structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir du [SizeF](/imaging/python-net/aspose.imaging/sizef/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) à partir duquel créer le nouveau [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Soustrait la largeur et la hauteur d'une structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) de la largeur et la hauteur d'une autre structure [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) du côté gauche de l'opérateur de soustraction. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La structure [SizeF](/imaging/python-net/aspose.imaging/sizef/) du côté droit de l'opérateur de soustraction. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Le [SizeF](/imaging/python-net/aspose.imaging/sizef/) qui est le résultat de l'opération de soustraction. |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

Convertit un [SizeF](/imaging/python-net/aspose.imaging/sizef/) en un [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Renvoie une structure [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

Convertit un [SizeF](/imaging/python-net/aspose.imaging/sizef/) en une structure [Size](/imaging/python-net/aspose.imaging/size/) avec des valeurs de taille tronquées.

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Renvoie une structure [Size](/imaging/python-net/aspose.imaging/size/). |


