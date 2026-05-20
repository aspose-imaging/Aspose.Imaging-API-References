---
title: "RectangleF"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle."
type: docs
weight: 94
url: /fr/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialise une nouvelle instance de la structure `com.aspose.imaging.RectangleF` avec l'emplacement et la taille spécifiés. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Initialise une nouvelle instance de la structure `com.aspose.imaging.RectangleF` avec l'emplacement et la taille spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure `com.aspose.imaging.RectangleF` dont les valeurs `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` et `com.aspose.imaging.RectangleF.Height` sont définies à zéro. |
| [getLocation()](#getLocation--) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [getSize()](#getSize--) | Obtient ou définit la taille de ce `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Obtient ou définit la taille de ce `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [setX(float value)](#setX-float-) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [setY(float value)](#setY-float-) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de cette structure `com.aspose.imaging.RectangleF`. |
| [setWidth(float value)](#setWidth-float-) | Obtient ou définit la largeur de cette structure `com.aspose.imaging.RectangleF`. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de cette structure `com.aspose.imaging.RectangleF`. |
| [setHeight(float value)](#setHeight-float-) | Obtient ou définit la hauteur de cette structure `com.aspose.imaging.RectangleF`. |
| [getLeft()](#getLeft--) | Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [setLeft(float value)](#setLeft-float-) | Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.RectangleF`. |
| [getTop()](#getTop--) | Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.RectangleF`. |
| [setTop(float value)](#setTop-float-) | Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.RectangleF`. |
| [getRight()](#getRight--) | Obtient ou définit la coordonnée x qui est la somme de `com.aspose.imaging.RectangleF.X` et `com.aspose.imaging.RectangleF.Width` de cette structure `com.aspose.imaging.RectangleF`. |
| [setRight(float value)](#setRight-float-) | Obtient ou définit la coordonnée x qui est la somme de `com.aspose.imaging.RectangleF.X` et `com.aspose.imaging.RectangleF.Width` de cette structure `com.aspose.imaging.RectangleF`. |
| [getBottom()](#getBottom--) | Obtient ou définit la coordonnée y qui est la somme de `com.aspose.imaging.RectangleF.Y` et `com.aspose.imaging.RectangleF.Height` de cette structure `com.aspose.imaging.RectangleF`. |
| [setBottom(float value)](#setBottom-float-) | Obtient ou définit la coordonnée y qui est la somme de `com.aspose.imaging.RectangleF.Y` et `com.aspose.imaging.RectangleF.Height` de cette structure `com.aspose.imaging.RectangleF`. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si la propriété `com.aspose.imaging.RectangleF.Width` ou `com.aspose.imaging.RectangleF.Height` de ce `com.aspose.imaging.RectangleF` a une valeur de zéro. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Crée un nouveau `Rectangle` à partir de deux points spécifiés. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Crée et renvoie une copie gonflée de la structure `com.aspose.imaging.RectangleF` spécifiée. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Renvoie une structure `com.aspose.imaging.RectangleF` qui représente l'intersection de deux rectangles. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Crée le troisième rectangle le plus petit possible qui peut contenir les deux rectangles formant une union. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Teste si deux structures `com.aspose.imaging.RectangleF` ont la même position et la même taille. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Teste si deux structures `com.aspose.imaging.RectangleF` diffèrent en position ou en taille. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | Implémente l'opérateur \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | Implémente l'opérateur /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Convertit la structure `com.aspose.imaging.Rectangle` spécifiée en une structure `com.aspose.imaging.RectangleF`. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Crée une structure `com.aspose.imaging.RectangleF` avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés. |
| [normalize()](#normalize--) | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
| [contains(float x, float y)](#contains-float-float-) | Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.RectangleF`. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.RectangleF`. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans cette structure `com.aspose.imaging.RectangleF`. |
| [inflate(float x, float y)](#inflate-float-float-) | Agrandit cette structure `com.aspose.imaging.RectangleF` du montant spécifié. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Agrandit ce `com.aspose.imaging.RectangleF` du montant spécifié. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Remplace cette structure `com.aspose.imaging.RectangleF` par l'intersection d'elle-même et de la structure `com.aspose.imaging.RectangleF` spécifiée. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Détermine si ce rectangle intersecte `rect`. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(float x, float y)](#offset-float-float-) | Ajuste la position de ce rectangle du montant spécifié. |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si `obj` est un `com.aspose.imaging.RectangleF` avec la même position et la même taille que ce `com.aspose.imaging.RectangleF`. |
| [hashCode()](#hashCode--) | Obtient le code de hachage pour cette structure `com.aspose.imaging.RectangleF`. |
| [toString()](#toString--) | Convertit les attributs de ce `com.aspose.imaging.RectangleF` en une chaîne lisible par l'homme. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initialise une nouvelle instance de la structure `com.aspose.imaging.RectangleF` avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle. |
| width | float | La largeur du rectangle. |
| height | float | La hauteur du rectangle. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initialise une nouvelle instance de la structure `com.aspose.imaging.RectangleF` avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Un `com.aspose.imaging.SizeF` qui représente la largeur et la hauteur de la région rectangulaire. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Obtient une nouvelle instance de la structure `com.aspose.imaging.RectangleF` dont les valeurs `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` et `com.aspose.imaging.RectangleF.Height` sont définies à zéro.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Obtient ou définit la taille de ce `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Obtient ou définit la taille de ce `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getY() {#getY--}
```
public float getY()
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtient ou définit la largeur de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La largeur de cette structure `com.aspose.imaging.RectangleF`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Obtient ou définit la largeur de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtient ou définit la hauteur de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La hauteur de cette structure `com.aspose.imaging.RectangleF`.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Obtient ou définit la hauteur de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordonnée x du bord gauche de cette structure `com.aspose.imaging.RectangleF`.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Obtient ou définit la coordonnée x du bord gauche de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordonnée y du bord supérieur de cette structure `com.aspose.imaging.RectangleF`.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Obtient ou définit la coordonnée x qui est la somme de `com.aspose.imaging.RectangleF.X` et `com.aspose.imaging.RectangleF.Width` de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordonnée x qui est la somme de `com.aspose.imaging.RectangleF.X` et `com.aspose.imaging.RectangleF.Width` de cette structure `com.aspose.imaging.RectangleF`.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Obtient ou définit la coordonnée x qui est la somme de `com.aspose.imaging.RectangleF.X` et `com.aspose.imaging.RectangleF.Width` de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Obtient ou définit la coordonnée y qui est la somme de `com.aspose.imaging.RectangleF.Y` et `com.aspose.imaging.RectangleF.Height` de cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
float - La coordonnée y qui est la somme de `com.aspose.imaging.RectangleF.Y` et `com.aspose.imaging.RectangleF.Height` de cette structure `com.aspose.imaging.RectangleF`.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Obtient ou définit la coordonnée y qui est la somme de `com.aspose.imaging.RectangleF.Y` et `com.aspose.imaging.RectangleF.Height` de cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si la propriété `com.aspose.imaging.RectangleF.Width` ou `com.aspose.imaging.RectangleF.Height` de ce `com.aspose.imaging.RectangleF` a une valeur de zéro.

**Returns:**
boolean - Cette propriété renvoie true si la propriété `com.aspose.imaging.RectangleF.Width` ou `com.aspose.imaging.RectangleF.Height` de ce `com.aspose.imaging.RectangleF` a une valeur de zéro ; sinon, false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crée un nouveau `Rectangle` à partir de deux points spécifiés. Deux sommets du `Rectangle` créé seront égaux aux `point1` et `point2` fournis. Il s'agit généralement des sommets opposés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Le premier `Point` pour le nouveau rectangle. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Le deuxième `Point` pour le nouveau rectangle. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crée et renvoie une copie gonflée de la structure `com.aspose.imaging.RectangleF` spécifiée. La copie est gonflée du montant spécifié. Le rectangle original reste inchangé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Le `com.aspose.imaging.RectangleF` à copier. Ce rectangle n'est pas modifié. |
| x | float | Le montant pour gonfler la copie du rectangle horizontalement. |
| y | float | Le montant pour gonfler la copie du rectangle verticalement. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Renvoie une structure `com.aspose.imaging.RectangleF` qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, une `com.aspose.imaging.RectangleF` vide est renvoyée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Un premier rectangle à intersecter. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Un deuxième rectangle à intersecter. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crée le troisième rectangle le plus petit possible qui peut contenir les deux rectangles formant une union.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Un premier rectangle à unir. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Un deuxième rectangle à unir. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Teste si deux structures `com.aspose.imaging.RectangleF` ont la même position et la même taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` qui se trouve à gauche de l'opérateur d'égalité. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` qui se trouve à droite de l'opérateur d'égalité. |

**Returns:**
boolean - Cet opérateur renvoie true si les deux structures `com.aspose.imaging.RectangleF` spécifiées ont des propriétés `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` et `com.aspose.imaging.RectangleF.Height` égales.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Teste si deux structures `com.aspose.imaging.RectangleF` diffèrent en position ou en taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` qui se trouve à gauche de l'opérateur d'inégalité. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | La structure `com.aspose.imaging.RectangleF` qui se trouve à droite de l'opérateur d'inégalité. |

**Returns:**
boolean - Cet opérateur renvoie true si l'une des propriétés `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` ou `com.aspose.imaging.RectangleF.Height` des deux structures `com.aspose.imaging.RectangleF` est différente ; sinon false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implémente l'opérateur \*.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle. |
| multiplicateur | float | Le multiplicateur. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implémente l'opérateur /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle. |
| diviseur | float | Le diviseur. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Convertit la structure `com.aspose.imaging.Rectangle` spécifiée en une structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | La structure `com.aspose.imaging.Rectangle` à convertir. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Crée une structure `com.aspose.imaging.RectangleF` avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | float | La coordonnée x du coin supérieur gauche de la région rectangulaire. |
| haut | float | La coordonnée y du coin supérieur gauche de la région rectangulaire. |
| droite | float | La coordonnée x du coin inférieur droit de la région rectangulaire. |
| bas | float | La coordonnée y du coin inférieur droit de la région rectangulaire. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
booléen - Cette méthode renvoie true si le point défini par `x` et `y` est contenu dans cette structure `com.aspose.imaging.RectangleF` ; sinon false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Détermine si le point spécifié est contenu dans cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à tester. |

**Returns:**
booléen - Cette méthode renvoie true si le point représenté par le paramètre `point` est contenu dans cette structure `com.aspose.imaging.RectangleF` ; sinon false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans cette structure `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Le `com.aspose.imaging.RectangleF` à tester. |

**Returns:**
booléen - Cette méthode renvoie true si la région rectangulaire représentée par `rect` est entièrement contenue dans la région rectangulaire représentée par ce `com.aspose.imaging.RectangleF` ; sinon false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Agrandit cette structure `com.aspose.imaging.RectangleF` du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La quantité d'expansion horizontale de cette structure `com.aspose.imaging.RectangleF`. |
| y | float | La quantité d'expansion verticale de cette structure `com.aspose.imaging.RectangleF`. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Agrandit ce `com.aspose.imaging.RectangleF` du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La quantité d'expansion de ce rectangle. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Remplace cette structure `com.aspose.imaging.RectangleF` par l'intersection d'elle-même et de la structure `com.aspose.imaging.RectangleF` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle à intersecter. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Détermine si ce rectangle intersecte `rect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle à tester. |

**Returns:**
booléen - Cette méthode renvoie true s'il y a une quelconque intersection.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | La quantité de décalage de l'emplacement. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La quantité de décalage horizontal de l'emplacement. |
| y | float | La quantité de décalage vertical de l'emplacement. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si `obj` est un `com.aspose.imaging.RectangleF` avec la même position et la même taille que ce `com.aspose.imaging.RectangleF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si `obj` est un `com.aspose.imaging.RectangleF` et que ses propriétés X, Y, Width et Height sont égales aux propriétés correspondantes de ce `com.aspose.imaging.RectangleF` ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage pour cette structure `com.aspose.imaging.RectangleF`.

**Returns:**
int - Le code de hachage pour ce `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


Convertit les attributs de ce `com.aspose.imaging.RectangleF` en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une chaîne qui contient la position, la largeur et la hauteur de cette structure `com.aspose.imaging.RectangleF`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
