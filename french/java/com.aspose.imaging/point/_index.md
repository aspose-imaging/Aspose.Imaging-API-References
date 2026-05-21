---
title: "Point"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan à deux dimensions."
type: docs
weight: 86
url: /fr/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan à deux dimensions.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialise une nouvelle instance de la structure `Aspose.Imaging.Point` avec les coordonnées spécifiées. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | Initialise une nouvelle instance de la structure `Aspose.Imaging.Point` à partir de la structure `Aspose.Imaging.Size`. |
| [Point(int dw)](#Point-int-) | Initialise une nouvelle instance de la structure `Aspose.Imaging.Point` en utilisant des coordonnées spécifiées par une valeur entière. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure `Aspose.Imaging.Point` dont les valeurs `Aspose.Imaging.Point.X` et `Aspose.Imaging.Point.Y` sont définies à zéro. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Ajoute le `Aspose.Imaging.Size` spécifié au `Aspose.Imaging.Point` spécifié. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Renvoie le résultat de la soustraction du `Aspose.Imaging.Size` spécifié du `Aspose.Imaging.Point` spécifié. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Convertit le `Aspose.Imaging.PointF` spécifié en un `Aspose.Imaging.Point` en arrondissant les valeurs du `Aspose.Imaging.PointF` à l'entier supérieur suivant. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Convertit le `Aspose.Imaging.PointF` spécifié en un objet `Aspose.Imaging.Point` en arrondissant les valeurs du `Aspose.Imaging.Point` à l'entier le plus proche. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Convertit le `Aspose.Imaging.PointF` spécifié en un `Aspose.Imaging.Point` en tronquant les valeurs du `Aspose.Imaging.Point`. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Déplace un `Aspose.Imaging.Point` d'une `Aspose.Imaging.Size` donnée. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Déplace un `Aspose.Imaging.Point` du négatif d'une `Aspose.Imaging.Size` donnée. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Compare deux objets `Aspose.Imaging.Point`. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Compare deux objets `Aspose.Imaging.Point`. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Convertit la structure `Aspose.Imaging.Point` spécifiée en une structure `Aspose.Imaging.Size`. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Convertit la structure `Point` spécifiée en la structure `PointF`. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Déconstruit un objet Point emballé dans un objet long en valeurs entières X et Y séparées. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce `Aspose.Imaging.Point` est vide. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x de ce `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | Obtient ou définit la coordonnée x de ce `Aspose.Imaging.Point`. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y de ce `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | Obtient ou définit la coordonnée y de ce `Aspose.Imaging.Point`. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Déplace ce `Aspose.Imaging.Point` du `Aspose.Imaging.Point` spécifié. |
| [offset(int dx, int dy)](#offset-int-int-) | Déplace ce `Aspose.Imaging.Point` de la quantité spécifiée. |
| [equals(Object obj)](#equals-java.lang.Object-) | Spécifie si ce `Aspose.Imaging.Point` contient les mêmes coordonnées que le `System.Object` spécifié. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour ce `Aspose.Imaging.Point`. |
| [toLong()](#toLong--) | Convertit ce Point en une seule valeur long, contenant les coordonnées X et Y dans les bits supérieurs et inférieurs. |
| [toString()](#toString--) | Convertit ce `Aspose.Imaging.Point` en une chaîne lisible par l'homme. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initialise une nouvelle instance de la structure `Aspose.Imaging.Point` avec les coordonnées spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La position horizontale du point. |
| y | int | La position verticale du point. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


Initialise une nouvelle instance de la structure `Aspose.Imaging.Point` à partir de la structure `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Contient les nouvelles coordonnées du point. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialise une nouvelle instance de la structure `Aspose.Imaging.Point` en utilisant des coordonnées spécifiées par une valeur entière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dw | int | Un entier de 32 bits qui spécifie les coordonnées du nouveau point. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Obtient une nouvelle instance de la structure `Aspose.Imaging.Point` dont les valeurs `Aspose.Imaging.Point.X` et `Aspose.Imaging.Point.Y` sont définies à zéro.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Ajoute le `Aspose.Imaging.Size` spécifié au `Aspose.Imaging.Point` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Aspose.Imaging.Point` à ajouter. |
| size | [Size](../../com.aspose.imaging/size) | Le `Aspose.Imaging.Size` à ajouter au `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Renvoie le résultat de la soustraction du `Aspose.Imaging.Size` spécifié du `Aspose.Imaging.Point` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Aspose.Imaging.Point` à soustraire de. |
| size | [Size](../../com.aspose.imaging/size) | Le `Aspose.Imaging.Size` à soustraire du `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Convertit le `Aspose.Imaging.PointF` spécifié en un `Aspose.Imaging.Point` en arrondissant les valeurs du `Aspose.Imaging.PointF` à l'entier supérieur suivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `Aspose.Imaging.PointF` à convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Convertit le `Aspose.Imaging.PointF` spécifié en un objet `Aspose.Imaging.Point` en arrondissant les valeurs du `Aspose.Imaging.Point` à l'entier le plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `Aspose.Imaging.PointF` à convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Convertit le `Aspose.Imaging.PointF` spécifié en un `Aspose.Imaging.Point` en tronquant les valeurs du `Aspose.Imaging.Point`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `Aspose.Imaging.PointF` à convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Déplace un `Aspose.Imaging.Point` d'une `Aspose.Imaging.Size` donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Aspose.Imaging.Point` à translater. |
| size | [Size](../../com.aspose.imaging/size) | Un `Aspose.Imaging.Size` qui spécifie la paire de nombres à ajouter aux coordonnées du `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Déplace un `Aspose.Imaging.Point` du négatif d'une `Aspose.Imaging.Size` donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Aspose.Imaging.Point` à translater. |
| size | [Size](../../com.aspose.imaging/size) | Un `Aspose.Imaging.Size` qui spécifie la paire de nombres à soustraire des coordonnées du `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Compare deux objets `Aspose.Imaging.Point`. Le résultat indique si les valeurs des propriétés `Aspose.Imaging.Point.X` et `Aspose.Imaging.Point.Y` des deux objets `Aspose.Imaging.Point` sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Un premier `Aspose.Imaging.Point` à comparer. |
| point2 | [Point](../../com.aspose.imaging/point) | Un second `Aspose.Imaging.Point` à comparer. |

**Returns:**
booléen - True si les valeurs `Aspose.Imaging.Point.X` et `Aspose.Imaging.Point.Y` de `point1` et `point2` sont égales ; sinon, false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Compare deux objets `Aspose.Imaging.Point`. Le résultat indique si les valeurs des propriétés `Aspose.Imaging.Point.X` ou `Aspose.Imaging.Point.Y` des deux objets `Aspose.Imaging.Point` sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Un premier `Aspose.Imaging.Point` à comparer. |
| point2 | [Point](../../com.aspose.imaging/point) | Un second `Aspose.Imaging.Point` à comparer. |

**Returns:**
booléen - True si les valeurs de l'une ou l'autre des propriétés `Aspose.Imaging.Point.X` ou `Aspose.Imaging.Point.Y` de `point1` et `point2` diffèrent ; sinon, false.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Convertit la structure `Aspose.Imaging.Point` spécifiée en une structure `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Aspose.Imaging.Point` à convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Convertit la structure `Point` spécifiée en la structure `PointF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Point` à convertir. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Déconstruit un objet Point emballé dans un objet long en valeurs entières X et Y séparées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| packedPoint | long | L'objet Point empaqueté dans une valeur long. |
| x | int[] | La valeur X extraite du Point empaqueté. |
| y | int[] | La valeur Y extraite du Point empaqueté. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si ce `Aspose.Imaging.Point` est vide.

**Returns:**
booléen - True si les deux `Aspose.Imaging.Point.X` et `Aspose.Imaging.Point.Y` sont 0 ; sinon, false.
### getX() {#getX--}
```
public int getX()
```


Obtient ou définit la coordonnée x de ce `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtient ou définit la coordonnée x de ce `Aspose.Imaging.Point`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getY() {#getY--}
```
public int getY()
```


Obtient ou définit la coordonnée y de ce `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtient ou définit la coordonnée y de ce `Aspose.Imaging.Point`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Déplace ce `Aspose.Imaging.Point` du `Aspose.Imaging.Point` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Aspose.Imaging.Point` utilisé pour décaler ce `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Déplace ce `Aspose.Imaging.Point` de la quantité spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | int | Le montant pour décaler la coordonnée x. |
| dy | int | Le montant pour décaler la coordonnée y. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Spécifie si ce `Aspose.Imaging.Point` contient les mêmes coordonnées que le `System.Object` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` à tester. |

**Returns:**
booléen - True si `obj` est un `Aspose.Imaging.Point` et possède les mêmes coordonnées que ce `Aspose.Imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour ce `Aspose.Imaging.Point`.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### toLong() {#toLong--}
```
public final long toLong()
```


Convertit ce Point en une seule valeur long, contenant les coordonnées X et Y dans les bits supérieurs et inférieurs.

**Returns:**
long - L'objet Point empaqueté dans une valeur long.
### toString() {#toString--}
```
public String toString()
```


Convertit ce `Aspose.Imaging.Point` en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une `System.String` qui représente cette instance.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
