---
title: "PointF"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une paire ordonnée de coordonnées x et y à virgule flottante qui définit un point dans un plan à deux dimensions."
type: docs
weight: 87
url: /fr/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Représente une paire ordonnée de coordonnées x et y à virgule flottante qui définit un point dans un plan à deux dimensions.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initialise une nouvelle instance de la structure `com.aspose.imaging.PointF` avec les coordonnées spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure `com.aspose.imaging.PointF` dont les valeurs `com.aspose.imaging.PointF.X` et `com.aspose.imaging.PointF.Y` sont définies à zéro. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translater un `com.aspose.imaging.PointF` par une `com.aspose.imaging.Size` donnée. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translater un `com.aspose.imaging.PointF` par le négatif d'une `com.aspose.imaging.Size` donnée. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translater le `com.aspose.imaging.PointF` par le `com.aspose.imaging.SizeF` spécifié. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translater un `com.aspose.imaging.PointF` par le négatif d'un `com.aspose.imaging.SizeF` spécifié. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Compare deux structures `com.aspose.imaging.PointF`. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Détermine si les coordonnées des points spécifiés ne sont pas égales. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translater un `com.aspose.imaging.PointF` donné par le `com.aspose.imaging.Size` spécifié. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translater un `com.aspose.imaging.PointF` par le négatif d'une taille spécifiée. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translater un `com.aspose.imaging.PointF` donné par un `com.aspose.imaging.SizeF` spécifié. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translater un `com.aspose.imaging.PointF` par le négatif d'une taille spécifiée. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce `com.aspose.imaging.PointF` est vide. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x de ce `com.aspose.imaging.PointF`. |
| [setX(float value)](#setX-float-) | Obtient ou définit la coordonnée x de ce `com.aspose.imaging.PointF`. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y de ce `com.aspose.imaging.PointF`. |
| [setY(float value)](#setY-float-) | Obtient ou définit la coordonnée y de ce `com.aspose.imaging.PointF`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Spécifie si ce `com.aspose.imaging.PointF` contient les mêmes coordonnées que le `System.Object` spécifié. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette structure `com.aspose.imaging.PointF`. |
| [toString()](#toString--) | Convertit ce `com.aspose.imaging.PointF` en une chaîne lisible par l'homme. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initialise une nouvelle instance de la structure `com.aspose.imaging.PointF` avec les coordonnées spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La position horizontale du point. |
| y | float | La position verticale du point. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Obtient une nouvelle instance de la structure `com.aspose.imaging.PointF` dont les valeurs `com.aspose.imaging.PointF.X` et `com.aspose.imaging.PointF.Y` sont définies à zéro.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Translater un `com.aspose.imaging.PointF` par une `com.aspose.imaging.Size` donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à traduire. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` qui spécifie la paire de nombres à ajouter aux coordonnées de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Translater un `com.aspose.imaging.PointF` par le négatif d'une `com.aspose.imaging.Size` donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` à traduire. |
| size | [Size](../../com.aspose.imaging/size) | Un `com.aspose.imaging.Size` qui spécifie les nombres à soustraire des coordonnées x et y du `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Translater le `com.aspose.imaging.PointF` par le `com.aspose.imaging.SizeF` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à traduire. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Le `com.aspose.imaging.SizeF` qui spécifie les nombres à ajouter aux coordonnées x et y du `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Translater un `com.aspose.imaging.PointF` par le négatif d'un `com.aspose.imaging.SizeF` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à traduire. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Le `com.aspose.imaging.SizeF` qui spécifie les nombres à soustraire des coordonnées de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Compare deux structures `com.aspose.imaging.PointF`. Le résultat indique si les valeurs des propriétés `com.aspose.imaging.PointF.X` et `com.aspose.imaging.PointF.Y` des deux structures `com.aspose.imaging.PointF` sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Un premier `com.aspose.imaging.PointF` à comparer. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Un deuxième `com.aspose.imaging.PointF` à comparer. |

**Returns:**
booléen - Vrai si les valeurs `com.aspose.imaging.PointF.X` et `com.aspose.imaging.PointF.Y` des premières et deuxièmes structures `com.aspose.imaging.PointF` sont égales ; sinon, faux.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Détermine si les coordonnées des points spécifiés ne sont pas égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Un premier `com.aspose.imaging.PointF` à comparer. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Un deuxième `com.aspose.imaging.PointF` à comparer. |

**Returns:**
booléen - Vrai pour indiquer que les valeurs `com.aspose.imaging.PointF.X` et `com.aspose.imaging.PointF.Y` de `point1` et `point2` ne sont pas égales ; sinon, faux.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Translater un `com.aspose.imaging.PointF` donné par le `com.aspose.imaging.Size` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à traduire. |
| size | [Size](../../com.aspose.imaging/size) | Le `com.aspose.imaging.Size` qui spécifie les nombres à ajouter aux coordonnées de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Translater un `com.aspose.imaging.PointF` par le négatif d'une taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à traduire. |
| size | [Size](../../com.aspose.imaging/size) | Le `com.aspose.imaging.Size` qui spécifie les nombres à soustraire des coordonnées de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Translater un `com.aspose.imaging.PointF` donné par un `com.aspose.imaging.SizeF` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à traduire. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Le `com.aspose.imaging.SizeF` qui spécifie les nombres à ajouter aux coordonnées de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Translater un `com.aspose.imaging.PointF` par le négatif d'une taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `com.aspose.imaging.PointF` à traduire. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Le `com.aspose.imaging.SizeF` qui spécifie les nombres à soustraire des coordonnées de `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si ce `com.aspose.imaging.PointF` est vide.

**Returns:**
booléen - Vrai si les deux `com.aspose.imaging.PointF.X` et `com.aspose.imaging.PointF.Y` sont 0 ; sinon, faux.
### getX() {#getX--}
```
public float getX()
```


Obtient ou définit la coordonnée x de ce `com.aspose.imaging.PointF`.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Obtient ou définit la coordonnée x de ce `com.aspose.imaging.PointF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getY() {#getY--}
```
public float getY()
```


Obtient ou définit la coordonnée y de ce `com.aspose.imaging.PointF`.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Obtient ou définit la coordonnée y de ce `com.aspose.imaging.PointF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Spécifie si ce `com.aspose.imaging.PointF` contient les mêmes coordonnées que le `System.Object` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`System.Object` à tester. |

**Returns:**
booléen - Cette méthode renvoie vrai si `obj` est un `com.aspose.imaging.PointF` et possède les mêmes coordonnées que ce `com.aspose.imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette structure `com.aspose.imaging.PointF`.

**Returns:**
int - Une valeur entière qui spécifie une valeur de hachage pour cette structure `com.aspose.imaging.PointF`.
### toString() {#toString--}
```
public String toString()
```


Convertit ce `com.aspose.imaging.PointF` en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une chaîne qui représente ce `com.aspose.imaging.PointF`.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
