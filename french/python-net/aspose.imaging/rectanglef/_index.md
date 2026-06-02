---
title: "Classe RectangleF"
type: docs
weight: 7130
url: /fr/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initialise une nouvelle instance de la classe RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initialise une nouvelle instance de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) avec l'emplacement et la taille spécifiés. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initialise une nouvelle instance de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) avec l'emplacement et la taille spécifiés. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | Obtient ou définit la coordonnée y qui est la somme de [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) et de [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient une nouvelle instance de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui a les valeurs [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) et [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) définies à zéro. |
| height | float | r/w | Obtient ou définit la hauteur de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| is_empty | bool | r | Obtient une valeur indiquant si la propriété [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) ou [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) de ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a une valeur de zéro. |
| left | float | r/w | Obtient ou définit la coordonnée x du bord gauche de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| right | float | r/w | Obtient ou définit la coordonnée x qui est la somme de [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) et de [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Obtient ou définit la taille de ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | Obtient ou définit la coordonnée y du bord supérieur de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| width | float | r/w | Obtient ou définit la largeur de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| x | float | r/w | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| y | float | r/w | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | Détermine si le point spécifié est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Détermine si le point spécifié est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_point_f(point)](#contains_point_f_point_4) | Détermine si le point spécifié est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Crée une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Crée un nouveau [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) à partir de deux points spécifiés. Les deux sommets du [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) créé seront égaux aux points _point1_ et _point2_ fournis. Il s'agit généralement des sommets opposés. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Crée et renvoie une copie gonflée du [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié. La copie est agrandie du montant indiqué. Le rectangle original reste inchangé. |
| [inflate(size)](#inflate_size_9) | Agrandit ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) du montant spécifié. |
| [inflate(x, y)](#inflate_x_y_10) | Agrandit cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) du montant spécifié. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Crée et renvoie une copie gonflée du [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié. La copie est agrandie du montant indiqué. Le rectangle original reste inchangé. |
| [intersect(a, b)](#intersect_a_b_12) | Renvoie un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vide est renvoyé. |
| [intersect(rect)](#intersect_rect_13) | Remplace ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) par l'intersection de lui-même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | Renvoie un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vide est renvoyé. |
| [intersects_with(rect)](#intersects_with_rect_15) | Détermine si ce rectangle intersecte _rect_. |
| normalize() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
| [offset(pos)](#offset_pos_16) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(x, y)](#offset_x_y_17) | Ajuste la position de ce rectangle du montant spécifié. |
| [union(a, b)](#union_a_b_18) | Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initialise une nouvelle instance de la classe RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initialise une nouvelle instance de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Un [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Un [SizeF](/imaging/python-net/aspose.imaging/sizef/) qui représente la largeur et la hauteur de la région rectangulaire. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initialise une nouvelle instance de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle. |
| width | float | La largeur du rectangle. |
| height | float | La hauteur du rectangle. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Détermine si le point spécifié est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point représenté par le paramètre _point_ est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); sinon false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si la région rectangulaire représentée par _rect_ est entièrement contenue dans la région rectangulaire représentée par ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); sinon false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Détermine si le point spécifié est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point défini par _x_ et _y_ est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); sinon false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Détermine si le point spécifié est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point représenté par le paramètre _point_ est contenu dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); sinon false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

Détermine si la région rectangulaire représentée par _rect_ est entièrement contenue dans cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si la région rectangulaire représentée par _rect_ est entièrement contenue dans la région rectangulaire représentée par ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); sinon false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crée une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gauche | float | La coordonnée x du coin supérieur gauche de la région rectangulaire. |
| haut | float | La coordonnée y du coin supérieur gauche de la région rectangulaire. |
| droite | float | La coordonnée x du coin inférieur droit de la région rectangulaire. |
| bas | float | La coordonnée y du coin inférieur droit de la région rectangulaire. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le nouveau [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que cette méthode crée. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Crée un nouveau [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) à partir de deux points spécifiés. Les deux sommets du [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) créé seront égaux aux points _point1_ et _point2_ fournis. Il s'agit généralement des sommets opposés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le premier [Point](/imaging/python-net/aspose.imaging/point/) pour le nouveau rectangle. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le deuxième [Point](/imaging/python-net/aspose.imaging/point/) pour le nouveau rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) nouvellement créé. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Crée et renvoie une copie gonflée du [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié. La copie est agrandie du montant indiqué. Le rectangle original reste inchangé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à copier. Ce rectangle n'est pas modifié. |
| x | float | La quantité d'agrandissement de la copie du rectangle horizontalement. |
| y | float | La quantité d'agrandissement de la copie du rectangle verticalement. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) agrandi. |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Agrandit ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La quantité d'agrandissement de ce rectangle. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Agrandit cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La quantité d'agrandissement de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) horizontalement. |
| y | float | La quantité d'agrandissement de cette structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) verticalement. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Crée et renvoie une copie gonflée du [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifié. La copie est agrandie du montant indiqué. Le rectangle original reste inchangé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à copier. Ce rectangle n'est pas modifié. |
| x | float | La quantité d'agrandissement de la copie du rectangle horizontalement. |
| y | float | La quantité d'agrandissement de la copie du rectangle verticalement. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) agrandi. |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

Renvoie un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vide est renvoyé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un premier rectangle à intersecter. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un second rectangle à intersecter. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une troisième structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) dont la taille représente la zone de chevauchement des deux rectangles spécifiés. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Remplace ce [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) par l'intersection de lui-même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle à intersecter. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

Renvoie un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) vide est renvoyé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un premier rectangle à intersecter. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un second rectangle à intersecter. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une troisième structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) dont la taille représente la zone de chevauchement des deux rectangles spécifiés. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Détermine si ce rectangle intersecte _rect_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie vrai s'il y a une quelconque intersection. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La quantité de décalage de l'emplacement. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La quantité de décalage horizontal de l'emplacement. |
| y | float | La quantité de décalage vertical de l'emplacement. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un premier rectangle à unir. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Un deuxième rectangle à unir. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une troisième structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui contient les deux rectangles formant l'union. |


