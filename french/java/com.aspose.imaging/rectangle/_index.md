---
title: "Rectangle"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle."
type: docs
weight: 93
url: /fr/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialise une nouvelle instance de la structure `com.aspose.imaging.Rectangle` avec l'emplacement et la taille spécifiés. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Initialise une nouvelle instance de la structure `com.aspose.imaging.Rectangle` avec l'emplacement et la taille spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure `com.aspose.imaging.Rectangle` dont les valeurs `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` et `com.aspose.imaging.Rectangle.Height` sont définies à zéro. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Crée un nouveau `Rectangle` à partir de deux points spécifiés. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Convertit la structure `com.aspose.imaging.RectangleF` spécifiée en une structure `com.aspose.imaging.Rectangle` en arrondissant les valeurs de `com.aspose.imaging.RectangleF` au nombre entier supérieur suivant. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Convertit le `com.aspose.imaging.RectangleF` spécifié en un `com.aspose.imaging.Rectangle` en tronquant les valeurs de `com.aspose.imaging.RectangleF`. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Convertit le `com.aspose.imaging.RectangleF` spécifié en un `com.aspose.imaging.Rectangle` en arrondissant les valeurs du `com.aspose.imaging.RectangleF` aux entiers les plus proches. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Crée et renvoie une copie gonflée de la structure `com.aspose.imaging.Rectangle` spécifiée. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Renvoie une troisième structure `com.aspose.imaging.Rectangle` qui représente l’intersection de deux autres structures `com.aspose.imaging.Rectangle`. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Obtient une structure `com.aspose.imaging.Rectangle` qui contient l’union de deux structures `com.aspose.imaging.Rectangle`. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Teste si deux structures `com.aspose.imaging.Rectangle` ont la même position et la même taille. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Teste si deux structures `com.aspose.imaging.Rectangle` diffèrent de position ou de taille. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Crée une structure `com.aspose.imaging.Rectangle` avec les emplacements de bord spécifiés. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [getSize()](#getSize--) | Obtient ou définit la taille de ce `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Obtient ou définit la taille de ce `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [setX(int value)](#setX-int-) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [setY(int value)](#setY-int-) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [getWidth()](#getWidth--) | Obtient la largeur de cette structure `com.aspose.imaging.Rectangle`. |
| [setWidth(int value)](#setWidth-int-) | Définit la largeur de cette structure `com.aspose.imaging.Rectangle`. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de cette structure `com.aspose.imaging.Rectangle`. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit la hauteur de cette structure `com.aspose.imaging.Rectangle`. |
| [getLeft()](#getLeft--) | Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [setLeft(int value)](#setLeft-int-) | Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.Rectangle`. |
| [getTop()](#getTop--) | Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.Rectangle`. |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.Rectangle`. |
| [getRight()](#getRight--) | Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.X` et `com.aspose.imaging.Rectangle.Width` de cette structure `com.aspose.imaging.Rectangle`. |
| [setRight(int value)](#setRight-int-) | Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.X` et `com.aspose.imaging.Rectangle.Width` de cette structure `com.aspose.imaging.Rectangle`. |
| [getBottom()](#getBottom--) | Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.Y` et `com.aspose.imaging.Rectangle.Height` de cette structure `com.aspose.imaging.Rectangle`. |
| [setBottom(int value)](#setBottom-int-) | Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.Y` et `com.aspose.imaging.Rectangle.Height` de cette structure `com.aspose.imaging.Rectangle`. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si toutes les propriétés numériques de ce `com.aspose.imaging.Rectangle` ont une valeur de zéro. |
| [contains(int x, int y)](#contains-int-int-) | Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.Rectangle`. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.Rectangle`. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans cette structure `com.aspose.imaging.Rectangle`. |
| [inflate(int width, int height)](#inflate-int-int-) | Gonfle ce `com.aspose.imaging.Rectangle` du montant spécifié. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Gonfle ce `com.aspose.imaging.Rectangle` du montant spécifié. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Remplace ce `com.aspose.imaging.Rectangle` par l’intersection de lui-même et du `com.aspose.imaging.Rectangle` spécifié. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Détermine si ce rectangle intersecte `rect`. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(int x, int y)](#offset-int-int-) | Ajuste la position de ce rectangle du montant spécifié. |
| [normalize()](#normalize--) | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le côté supérieur inférieur au côté inférieur. |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si `obj` est une structure `com.aspose.imaging.Rectangle` avec la même position et la même taille que cette structure `com.aspose.imaging.Rectangle`. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette structure `com.aspose.imaging.Rectangle`. |
| [toString()](#toString--) | Convertit les attributs de cette `com.aspose.imaging.Rectangle` en une chaîne lisible par l'homme. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initialise une nouvelle instance de la structure `com.aspose.imaging.Rectangle` avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle. |
| width | int | La largeur du rectangle. |
| height | int | La hauteur du rectangle. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Initialise une nouvelle instance de la structure `com.aspose.imaging.Rectangle` avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` qui représente la largeur et la hauteur de la région rectangulaire. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Obtient une nouvelle instance de la structure `com.aspose.imaging.Rectangle` dont les valeurs `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` et `com.aspose.imaging.Rectangle.Height` sont définies à zéro.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crée un nouveau `Rectangle` à partir de deux points spécifiés. Les deux côtés verticaux du `Rectangle` créé seront égaux aux points `point1` et `point2` fournis. Il s'agit généralement des sommets opposés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Le premier `Point` pour le nouveau rectangle. |
| point2 | [Point](../../com.aspose.imaging/point) | Le deuxième `Point` pour le nouveau rectangle. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Convertit la structure `com.aspose.imaging.RectangleF` spécifiée en une structure `com.aspose.imaging.Rectangle` en arrondissant les valeurs de `com.aspose.imaging.RectangleF` au nombre entier supérieur suivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` à convertir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Convertit le `com.aspose.imaging.RectangleF` spécifié en un `com.aspose.imaging.Rectangle` en tronquant les valeurs de `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Le `com.aspose.imaging.RectangleF` à convertir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Convertit le `com.aspose.imaging.RectangleF` spécifié en un `com.aspose.imaging.Rectangle` en arrondissant les valeurs du `com.aspose.imaging.RectangleF` aux entiers les plus proches.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Le `com.aspose.imaging.RectangleF` à convertir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Crée et renvoie une copie gonflée de la structure `com.aspose.imaging.Rectangle` spécifiée. La copie est gonflée du montant indiqué. La structure `com.aspose.imaging.Rectangle` originale reste inchangée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le `com.aspose.imaging.Rectangle` avec lequel commencer. Ce rectangle n'est pas modifié. |
| x | int | Le montant pour gonfler horizontalement ce `com.aspose.imaging.Rectangle`. |
| y | int | Le montant pour gonfler verticalement ce `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Renvoie une troisième structure `com.aspose.imaging.Rectangle` qui représente l'intersection de deux autres structures `com.aspose.imaging.Rectangle`. S'il n'y a pas d'intersection, une `com.aspose.imaging.Rectangle` vide est renvoyée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Un premier rectangle à intersecter. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Un deuxième rectangle à intersecter. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Obtient une structure `com.aspose.imaging.Rectangle` qui contient l’union de deux structures `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Un premier rectangle à unir. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Un deuxième rectangle à unir. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Teste si deux structures `com.aspose.imaging.Rectangle` ont la même position et la même taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` qui se trouve à gauche de l'opérateur d'égalité. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` qui se trouve à droite de l'opérateur d'égalité. |

**Returns:**
boolean - Cet opérateur renvoie true si les deux structures `com.aspose.imaging.Rectangle` ont des propriétés `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` et `com.aspose.imaging.Rectangle.Height` égales.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Teste si deux structures `com.aspose.imaging.Rectangle` diffèrent de position ou de taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` qui se trouve à gauche de l'opérateur d'inégalité. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` qui se trouve à droite de l'opérateur d'inégalité. |

**Returns:**
boolean - Cet opérateur renvoie true si l'une des propriétés `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` ou `com.aspose.imaging.Rectangle.Height` des deux structures `com.aspose.imaging.Rectangle` est différente ; sinon false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Crée une structure `com.aspose.imaging.Rectangle` avec les emplacements de bord spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | int | La coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| haut | int | La coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |
| droite | int | La coordonnée x du coin inférieur droit de cette structure `com.aspose.imaging.Rectangle`. |
| bas | int | La coordonnée y du coin inférieur droit de cette structure `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | Un `Point` qui représente le coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |

### getSize() {#getSize--}
```
public Size getSize()
```


Obtient ou définit la taille de ce `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Obtient ou définit la taille de ce `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` qui représente la largeur et la hauteur de cette structure `com.aspose.imaging.Rectangle`. |

### getX() {#getX--}
```
public int getX()
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |

### getY() {#getY--}
```
public int getY()
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.Rectangle`. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La largeur de cette structure `com.aspose.imaging.Rectangle`.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Définit la largeur de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La largeur de cette structure `com.aspose.imaging.Rectangle`. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit la hauteur de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La hauteur de cette structure `com.aspose.imaging.Rectangle`.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit la hauteur de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La hauteur de cette structure `com.aspose.imaging.Rectangle`. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordonnée x du bord gauche de cette structure `com.aspose.imaging.Rectangle`.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée x du bord gauche de cette structure `com.aspose.imaging.Rectangle`. |

### getTop() {#getTop--}
```
public int getTop()
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordonnée y du bord supérieur de cette structure `com.aspose.imaging.Rectangle`.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée y du bord supérieur de cette structure `com.aspose.imaging.Rectangle`. |

### getRight() {#getRight--}
```
public int getRight()
```


Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.X` et `com.aspose.imaging.Rectangle.Width` de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordonnée x qui est la somme de `com.aspose.imaging.Rectangle.X` et `com.aspose.imaging.Rectangle.Width` de cette `com.aspose.imaging.Rectangle`.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.X` et `com.aspose.imaging.Rectangle.Width` de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée x qui est la somme de `com.aspose.imaging.Rectangle.X` et `com.aspose.imaging.Rectangle.Width` de cette `com.aspose.imaging.Rectangle`. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.Y` et `com.aspose.imaging.Rectangle.Height` de cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - La coordonnée y qui est la somme de `com.aspose.imaging.Rectangle.Y` et `com.aspose.imaging.Rectangle.Height` de cette `com.aspose.imaging.Rectangle`.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés `com.aspose.imaging.Rectangle.Y` et `com.aspose.imaging.Rectangle.Height` de cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée y qui est la somme de `com.aspose.imaging.Rectangle.Y` et `com.aspose.imaging.Rectangle.Height` de cette `com.aspose.imaging.Rectangle`. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si toutes les propriétés numériques de ce `com.aspose.imaging.Rectangle` ont une valeur de zéro.

**Returns:**
boolean - Cette propriété renvoie true si les propriétés `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X` et `com.aspose.imaging.Rectangle.Y` de cette `com.aspose.imaging.Rectangle` ont toutes la valeur zéro ; sinon, false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point défini par `x` et `y` est contenu dans cette structure `com.aspose.imaging.Rectangle` ; sinon false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `com.aspose.imaging.Point` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point représenté par `point` est contenu dans cette structure `com.aspose.imaging.Rectangle` ; sinon false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le `com.aspose.imaging.Rectangle` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si la région rectangulaire représentée par `rect` est entièrement contenue dans cette structure `com.aspose.imaging.Rectangle` ; sinon false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Gonfle ce `com.aspose.imaging.Rectangle` du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | Le montant pour gonfler horizontalement ce `com.aspose.imaging.Rectangle`. |
| height | int | Le montant pour gonfler verticalement ce `com.aspose.imaging.Rectangle`. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Gonfle ce `com.aspose.imaging.Rectangle` du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | La quantité d'expansion de ce rectangle. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Remplace ce `com.aspose.imaging.Rectangle` par l’intersection de lui-même et du `com.aspose.imaging.Rectangle` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le `com.aspose.imaging.Rectangle` avec lequel intersecter. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Détermine si ce rectangle intersecte `rect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle à tester. |

**Returns:**
boolean - Cette méthode renvoie true s'il y a une quelconque intersection, sinon false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Quantité pour décaler l'emplacement. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | Le décalage horizontal. |
| y | int | Le décalage vertical. |

### normalize() {#normalize--}
```
public void normalize()
```


Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le côté supérieur inférieur au côté inférieur.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si `obj` est une structure `com.aspose.imaging.Rectangle` avec la même position et la même taille que cette structure `com.aspose.imaging.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si `obj` est une structure `com.aspose.imaging.Rectangle` et que ses propriétés `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` et `com.aspose.imaging.Rectangle.Height` sont égales aux propriétés correspondantes de cette structure `com.aspose.imaging.Rectangle` ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette structure `com.aspose.imaging.Rectangle`.

**Returns:**
int - Un entier qui représente le code de hachage de ce rectangle.
### toString() {#toString--}
```
public String toString()
```


Convertit les attributs de cette `com.aspose.imaging.Rectangle` en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une chaîne qui contient la position, la largeur et la hauteur de cette structure `com.aspose.imaging.Rectangle`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
