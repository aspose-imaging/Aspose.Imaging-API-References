---
title: "Size"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente la taille."
type: docs
weight: 104
url: /fr/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Représente la taille.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Initialise une nouvelle instance de la structure `Aspose.Imaging.Size` à partir du `Aspose.Imaging.Point` spécifié. |
| [Size(int width, int height)](#Size-int-int-) | Initialise une nouvelle instance de la structure `Aspose.Imaging.Size` à partir des dimensions spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure `Aspose.Imaging.Size` dont les valeurs `Aspose.Imaging.Size.Width` et `Aspose.Imaging.Size.Height` sont réglées à zéro. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Convertit le `Aspose.Imaging.Size` spécifié en `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Ajoute la largeur et la hauteur d'une structure `Aspose.Imaging.Size` à la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Soustrait la largeur et la hauteur d'une structure `Aspose.Imaging.Size` de la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Teste si deux structures `Aspose.Imaging.Size` sont égales. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Teste si deux structures `Aspose.Imaging.Size` sont différentes. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Convertit le `Aspose.Imaging.Size` spécifié en `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Ajoute la largeur et la hauteur d'une structure `Aspose.Imaging.Size` à la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Convertit la structure `Aspose.Imaging.SizeF` spécifiée en une structure `Aspose.Imaging.Size` en arrondissant les valeurs de la structure `Aspose.Imaging.Size` au prochain entier supérieur. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Soustrait la largeur et la hauteur d'une structure `Aspose.Imaging.Size` de la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Convertit la structure `Aspose.Imaging.SizeF` spécifiée en une structure `Aspose.Imaging.Size` en tronquant les valeurs de la structure `Aspose.Imaging.SizeF` au prochain entier inférieur. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Convertit la structure `Aspose.Imaging.SizeF` spécifiée en une structure `Aspose.Imaging.Size` en arrondissant les valeurs de la structure `Aspose.Imaging.SizeF` à l'entier le plus proche. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce `Aspose.Imaging.Size` a une largeur et une hauteur de 0. |
| [getWidth()](#getWidth--) | Obtient ou définit le composant horizontal de ce `Aspose.Imaging.Size`. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit le composant horizontal de ce `Aspose.Imaging.Size`. |
| [getHeight()](#getHeight--) | Obtient ou définit le composant vertical de ce `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit le composant vertical de ce `Aspose.Imaging.Size`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste pour voir si l'objet spécifié est un `Aspose.Imaging.Size` avec les mêmes dimensions que ce `Aspose.Imaging.Size`. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette structure `Aspose.Imaging.Size`. |
| [toString()](#toString--) | Crée une chaîne lisible par l'homme qui représente ce `Aspose.Imaging.Size`. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Initialise une nouvelle instance de la structure `Aspose.Imaging.Size` à partir du `Aspose.Imaging.Point` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le `Aspose.Imaging.Point` à partir duquel initialiser ce `Aspose.Imaging.Size`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialise une nouvelle instance de la structure `Aspose.Imaging.Size` à partir des dimensions spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | Le composant largeur du nouveau `Aspose.Imaging.Size`. |
| height | int | Le composant hauteur du nouveau `Aspose.Imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Obtient une nouvelle instance de la structure `Aspose.Imaging.Size` dont les valeurs `Aspose.Imaging.Size.Width` et `Aspose.Imaging.Size.Height` sont réglées à zéro.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Convertit le `Aspose.Imaging.Size` spécifié en `Aspose.Imaging.SizeF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Le `Aspose.Imaging.Size` à convertir. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Ajoute la largeur et la hauteur d'une structure `Aspose.Imaging.Size` à la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Le premier `Aspose.Imaging.Size` à ajouter. |
| size2 | [Size](../../com.aspose.imaging/size) | Le deuxième `Aspose.Imaging.Size` à ajouter. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Soustrait la largeur et la hauteur d'une structure `Aspose.Imaging.Size` de la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté gauche de l'opérateur de soustraction. |
| size2 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté droit de l'opérateur de soustraction. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Teste si deux structures `Aspose.Imaging.Size` sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté gauche de l'opérateur d'égalité. |
| size2 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté droit de l'opérateur d'égalité. |

**Returns:**
booléen - Vrai si `size1` et `size2` ont la même largeur et la même hauteur ; sinon, faux.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Teste si deux structures `Aspose.Imaging.Size` sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté gauche de l'opérateur d'inégalité. |
| size2 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté droit de l'opérateur d'inégalité. |

**Returns:**
booléen - Vrai si `size1` et `size2` diffèrent soit en largeur, soit en hauteur ; faux si `size1` et `size2` sont égaux.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Convertit le `Aspose.Imaging.Size` spécifié en `Aspose.Imaging.Point`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Le `Aspose.Imaging.Size` à convertir. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Ajoute la largeur et la hauteur d'une structure `Aspose.Imaging.Size` à la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Le premier `Aspose.Imaging.Size` à ajouter. |
| size2 | [Size](../../com.aspose.imaging/size) | Le deuxième `Aspose.Imaging.Size` à ajouter. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Convertit la structure `Aspose.Imaging.SizeF` spécifiée en une structure `Aspose.Imaging.Size` en arrondissant les valeurs de la structure `Aspose.Imaging.Size` au prochain entier supérieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La structure `Aspose.Imaging.SizeF` à convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Soustrait la largeur et la hauteur d'une structure `Aspose.Imaging.Size` de la largeur et la hauteur d'une autre structure `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté gauche de l'opérateur de soustraction. |
| size2 | [Size](../../com.aspose.imaging/size) | La structure `Aspose.Imaging.Size` du côté droit de l'opérateur de soustraction. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Convertit la structure `Aspose.Imaging.SizeF` spécifiée en une structure `Aspose.Imaging.Size` en tronquant les valeurs de la structure `Aspose.Imaging.SizeF` au prochain entier inférieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La structure `Aspose.Imaging.SizeF` à convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Convertit la structure `Aspose.Imaging.SizeF` spécifiée en une structure `Aspose.Imaging.Size` en arrondissant les valeurs de la structure `Aspose.Imaging.SizeF` à l'entier le plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | La structure `Aspose.Imaging.SizeF` à convertir. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si ce `Aspose.Imaging.Size` a une largeur et une hauteur de 0.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit le composant horizontal de ce `Aspose.Imaging.Size`.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit le composant horizontal de ce `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit le composant vertical de ce `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit le composant vertical de ce `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste pour voir si l'objet spécifié est un `Aspose.Imaging.Size` avec les mêmes dimensions que ce `Aspose.Imaging.Size`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` à tester. |

**Returns:**
booléen - Vrai si `obj` est un `Aspose.Imaging.Size` et possède la même largeur et la même hauteur que ce `Aspose.Imaging.Size` ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette structure `Aspose.Imaging.Size`.

**Returns:**
int - Une valeur entière qui spécifie une valeur de hachage pour cette structure `Aspose.Imaging.Size`.
### toString() {#toString--}
```
public String toString()
```


Crée une chaîne lisible par l'homme qui représente ce `Aspose.Imaging.Size`.

**Returns:**
java.lang.String - Une chaîne qui représente ce `Aspose.Imaging.Size`.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
