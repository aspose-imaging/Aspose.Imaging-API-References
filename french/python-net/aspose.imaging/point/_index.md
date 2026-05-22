---
title: "Classe Point"
type: docs
weight: 6960
url: /fr/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Initialise une nouvelle instance de la classe Point |
| [Point(dw)](#Point_dw_2) | Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) en utilisant des coordonnées spécifiées par une valeur entière. |
| [Point(size)](#Point_size_3) | Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) à partir de la structure [Size](/imaging/python-net/aspose.imaging/size/). |
| [Point(x, y)](#Point_x_y_4) | Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) avec les coordonnées spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | Obtient une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) dont les valeurs [Point.x](/imaging/python-net/aspose.imaging/point/) et [Point.y](/imaging/python-net/aspose.imaging/point/) sont définies à zéro. |
| is_empty | bool | r | Obtient une valeur indiquant si ce [Point](/imaging/python-net/aspose.imaging/point/) est vide. |
| x | int | r/w | Obtient ou définit la coordonnée x de ce [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Obtient ou définit la coordonnée y de ce [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Ajoute le [Size](/imaging/python-net/aspose.imaging/size/) spécifié au [Point](/imaging/python-net/aspose.imaging/point/) spécifié. |
| [ceiling(point)](#ceiling_point_2) | Convertit le [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié en [Point](/imaging/python-net/aspose.imaging/point/) en arrondissant les valeurs du [PointF](/imaging/python-net/aspose.imaging/pointf/) au nombre entier supérieur le plus proche. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) en utilisant des coordonnées spécifiées par une valeur entière. |
| [create_from_size(size)](#create_from_size_size_4) | Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) à partir de la structure [Size](/imaging/python-net/aspose.imaging/size/). |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | Déconstruit un objet Point emballé dans un objet long pour séparer les valeurs entières X et Y. |
| [offset(dx, dy)](#offset_dx_dy_6) | Déplace ce [Point](/imaging/python-net/aspose.imaging/point/) du montant spécifié. |
| [offset(point)](#offset_point_7) | Déplace ce [Point](/imaging/python-net/aspose.imaging/point/) du [Point](/imaging/python-net/aspose.imaging/point/) spécifié. |
| [round(point)](#round_point_8) | Convertit le [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié en objet [Point](/imaging/python-net/aspose.imaging/point/) en arrondissant les valeurs du [Point](/imaging/python-net/aspose.imaging/point/) à l'entier le plus proche. |
| [subtract(point, size)](#subtract_point_size_9) | Renvoie le résultat de la soustraction du [Size](/imaging/python-net/aspose.imaging/size/) spécifié du [Point](/imaging/python-net/aspose.imaging/point/) spécifié. |
| [to_long()](#to_long__10) | Convertit ce Point en une seule valeur long, contenant les coordonnées X et Y dans les bits de poids fort et faible. |
| [truncate(point)](#truncate_point_11) | Convertit le [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié en [Point](/imaging/python-net/aspose.imaging/point/) en tronquant les valeurs du [Point](/imaging/python-net/aspose.imaging/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initialise une nouvelle instance de la classe Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) en utilisant des coordonnées spécifiées par une valeur entière.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dw | int | Un entier de 32 bits qui spécifie les coordonnées du nouveau point. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) à partir de la structure [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contient les coordonnées du nouveau point. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) avec les coordonnées spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La position horizontale du point. |
| y | int | La position verticale du point. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Ajoute le [Size](/imaging/python-net/aspose.imaging/size/) spécifié au [Point](/imaging/python-net/aspose.imaging/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) auquel ajouter. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Le [Size](/imaging/python-net/aspose.imaging/size/) à ajouter au _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) qui est le résultat de l'opération d'addition. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Convertit le [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié en [Point](/imaging/python-net/aspose.imaging/point/) en arrondissant les valeurs du [PointF](/imaging/python-net/aspose.imaging/pointf/) au nombre entier supérieur le plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le [PointF](/imaging/python-net/aspose.imaging/pointf/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) vers lequel cette méthode convertit. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) en utilisant des coordonnées spécifiées par une valeur entière.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dw | int | Un entier de 32 bits qui spécifie les coordonnées du nouveau point. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

Initialise une nouvelle instance de la structure [Point](/imaging/python-net/aspose.imaging/point/) à partir de la structure [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contient les coordonnées du nouveau point. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

Déconstruit un objet Point emballé dans un objet long pour séparer les valeurs entières X et Y.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| packed_point | int | L'objet Point empaqueté en une seule valeur longue. |
| x | int[] | La valeur X extraite du Point empaqueté. |
| y | int[] | La valeur Y extraite du Point empaqueté. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Déplace ce [Point](/imaging/python-net/aspose.imaging/point/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | int | Le montant pour décaler la coordonnée x. |
| dy | int | Le montant pour décaler la coordonnée y. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Déplace ce [Point](/imaging/python-net/aspose.imaging/point/) du [Point](/imaging/python-net/aspose.imaging/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) utilisé pour décaler ce [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Convertit le [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié en objet [Point](/imaging/python-net/aspose.imaging/point/) en arrondissant les valeurs du [Point](/imaging/python-net/aspose.imaging/point/) à l'entier le plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le [PointF](/imaging/python-net/aspose.imaging/pointf/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) vers lequel cette méthode convertit. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Renvoie le résultat de la soustraction du [Size](/imaging/python-net/aspose.imaging/size/) spécifié du [Point](/imaging/python-net/aspose.imaging/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) dont il faut soustraire. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Le [Size](/imaging/python-net/aspose.imaging/size/) à soustraire du _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) qui est le résultat de l'opération de soustraction. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Convertit ce Point en une seule valeur long, contenant les coordonnées X et Y dans les bits de poids fort et faible.

**Returns**

| Type | Description |
| :- | :- |
| int | L'objet Point empaqueté en une seule valeur longue. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Convertit le [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifié en [Point](/imaging/python-net/aspose.imaging/point/) en tronquant les valeurs du [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le [PointF](/imaging/python-net/aspose.imaging/pointf/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) vers lequel cette méthode convertit. |


