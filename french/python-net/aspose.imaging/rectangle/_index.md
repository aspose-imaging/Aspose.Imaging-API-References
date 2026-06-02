---
title: "Classe Rectangle"
type: docs
weight: 7120
url: /fr/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initialise une nouvelle instance de la classe Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initialise une nouvelle instance de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec l'emplacement et la taille spécifiés. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initialise une nouvelle instance de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec l'emplacement et la taille spécifiés. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) et [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtient une nouvelle instance de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui a les valeurs [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) et [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) définies à zéro. |
| height | int | r/w | Obtient ou définit la hauteur de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| is_empty | bool | r | Obtient une valeur indiquant si toutes les propriétés numériques de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) ont des valeurs égales à zéro. |
| left | int | r/w | Obtient ou définit la coordonnée x du bord gauche de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | r/w | Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) et [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtient ou définit la taille de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | Obtient ou définit la coordonnée y du bord supérieur de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| width | int | r/w | Obtient ou définit la largeur de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| x | int | r/w | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | r/w | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Convertit la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée en une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en arrondissant les valeurs de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à l'entier supérieur suivant. |
| [contains(point)](#contains_point_2) | Détermine si le point spécifié est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(rect)](#contains_rect_3) | Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Détermine si le point spécifié est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_point(point)](#contains_point_point_5) | Détermine si le point spécifié est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_rect(rect)](#contains_rect_rect_6) | Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Crée une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec les emplacements de bord spécifiés. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Crée un nouveau [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) à partir de deux points spécifiés. Deux sommets du [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) créé seront égaux aux points _point1_ et _point2_. Il s'agit généralement des sommets opposés. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Crée et renvoie une copie gonflée de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifiée. La copie est gonflée du montant spécifié. La structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale reste inchangée. |
| [inflate(size)](#inflate_size_10) | Gonfle ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) du montant spécifié. |
| [inflate(width, height)](#inflate_width_height_11) | Gonfle ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) du montant spécifié. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Crée et renvoie une copie gonflée de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifiée. La copie est gonflée du montant spécifié. La structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale reste inchangée. |
| [intersect(a, b)](#intersect_a_b_13) | Renvoie une troisième structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente l'intersection de deux autres structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). S'il n'y a aucune intersection, un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vide est renvoyé. |
| [intersect(rect)](#intersect_rect_14) | Remplace ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) par l'intersection de lui-même et du [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifié. |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | Renvoie une troisième structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente l'intersection de deux autres structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). S'il n'y a aucune intersection, un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vide est renvoyé. |
| [intersects_with(rect)](#intersects_with_rect_16) | Détermine si ce rectangle intersecte _rect_. |
| normalize() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
| [offset(pos)](#offset_pos_17) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(x, y)](#offset_x_y_18) | Ajuste la position de ce rectangle du montant spécifié. |
| [round(value)](#round_value_19) | Convertit le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié en un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en arrondissant les valeurs de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à l'entier le plus proche. |
| [truncate(value)](#truncate_value_20) | Convertit le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié en un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en tronquant les valeurs de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union(a, b)](#union_a_b_21) | Obtient une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui contient l'union de deux structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initialise une nouvelle instance de la classe Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initialise une nouvelle instance de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Un [Point](/imaging/python-net/aspose.imaging/point/) qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Une [Size](/imaging/python-net/aspose.imaging/size/) qui représente la largeur et la hauteur de la région rectangulaire. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initialise une nouvelle instance de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle. |
| width | int | La largeur du rectangle. |
| height | int | La hauteur du rectangle. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Convertit la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée en une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en arrondissant les valeurs de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à l'entier supérieur suivant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Renvoie un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Détermine si le point spécifié est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point représenté par _point_ est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); sinon false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); sinon false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Détermine si le point spécifié est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point défini par _x_ et _y_ est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); sinon false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Détermine si le point spécifié est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Le [Point](/imaging/python-net/aspose.imaging/point/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point représenté par _point_ est contenu dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); sinon false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); sinon false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crée une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec les emplacements de bord spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| left | int | La coordonnée x du coin supérieur gauche de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | La coordonnée y du coin supérieur gauche de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | La coordonnée x du coin inférieur droit de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| bottom | int | La coordonnée y du coin inférieur droit de cette structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le nouveau [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que cette méthode crée. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Crée un nouveau [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) à partir de deux points spécifiés. Deux sommets du [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) créé seront égaux aux points _point1_ et _point2_. Il s'agit généralement des sommets opposés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Le premier [Point](/imaging/python-net/aspose.imaging/point/) pour le nouveau rectangle. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Le deuxième [Point](/imaging/python-net/aspose.imaging/point/) pour le nouveau rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) nouvellement créé. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Crée et renvoie une copie gonflée de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifiée. La copie est gonflée du montant spécifié. La structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale reste inchangée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec lequel commencer. Ce rectangle n'est pas modifié. |
| x | int | La quantité d'expansion horizontale de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | La quantité d'expansion verticale de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) agrandi. |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Gonfle ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La quantité d'agrandissement de ce rectangle. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Gonfle ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La quantité d'expansion horizontale de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| height | int | La quantité d'expansion verticale de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Crée et renvoie une copie gonflée de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifiée. La copie est gonflée du montant spécifié. La structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) originale reste inchangée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec lequel commencer. Ce rectangle n'est pas modifié. |
| x | int | La quantité d'expansion horizontale de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | La quantité d'expansion verticale de ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) agrandi. |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

Renvoie une troisième structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente l'intersection de deux autres structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). S'il n'y a aucune intersection, un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vide est renvoyé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un premier rectangle à intersecter. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un second rectangle à intersecter. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente l'intersection de _a_ et _b_. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Remplace ce [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) par l'intersection de lui-même et du [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) avec lequel intersecter. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

Renvoie une troisième structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente l'intersection de deux autres structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). S'il n'y a aucune intersection, un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vide est renvoyé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un premier rectangle à intersecter. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un second rectangle à intersecter. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente l'intersection de _a_ et _b_. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Détermine si ce rectangle intersecte _rect_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true s'il y a une intersection, sinon false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Valeur du décalage de la position. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | Le décalage horizontal. |
| y | int | Le décalage vertical. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Convertit le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié en un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en arrondissant les valeurs de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à l'entier le plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un nouveau [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Convertit le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié en un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en tronquant les valeurs de [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un nouveau [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

Obtient une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui contient l'union de deux structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un premier rectangle à unir. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Un deuxième rectangle à unir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui englobe l'union des deux structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


