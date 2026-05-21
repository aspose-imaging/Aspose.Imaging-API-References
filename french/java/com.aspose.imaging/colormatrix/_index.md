---
title: "ColorMatrix"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA."
type: docs
weight: 26
url: /fr/java/com.aspose.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA. Plusieurs méthodes de la classe [ImageAttributes](../../com.aspose.imaging/imageattributes) ajustent les couleurs de l'image en utilisant une matrice de couleur. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialise une nouvelle instance de la classe `Aspose.Imaging.ColorMatrix`. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialise une nouvelle instance de la classe `Aspose.Imaging.ColorMatrix` en utilisant les éléments de la matrice spécifiée `newColorMatrix`. |
## Champs

| Champ | Description |
| --- | --- |
| [MATRIX_DIMENSION_ELEMENTS_COUNT](#MATRIX-DIMENSION-ELEMENTS-COUNT) | Le nombre d'éléments dans la dimension de la matrice. |
| [MATRIX_DIMENSIONS_COUNT](#MATRIX-DIMENSIONS-COUNT) | Le nombre de dimensions de la matrice. |
| [MATRIX_TOTAL_ELEMENTS_COUNT](#MATRIX-TOTAL-ELEMENTS-COUNT) | Le nombre total d'éléments dans la matrice. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Obtient l'élément à la ligne 0 (zéro) et à la colonne 0 de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix00(float value)](#setMatrix00-float-) | Définit l'élément à la ligne 0 (zéro) et à la colonne 0 de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix01()](#getMatrix01--) | Obtient l'élément à la ligne 0 (zéro) et à la première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix01(float value)](#setMatrix01-float-) | Définit l'élément à la ligne 0 (zéro) et à la première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix02()](#getMatrix02--) | Obtient l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix02(float value)](#setMatrix02-float-) | Définit l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix03()](#getMatrix03--) | Obtient l'élément à la ligne 0 (zéro) et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix03(float value)](#setMatrix03-float-) | Définit l'élément à la ligne 0 (zéro) et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix04()](#getMatrix04--) | Obtient l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix04(float value)](#setMatrix04-float-) | Définit l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix10()](#getMatrix10--) | Obtient l'élément à la première ligne et à la colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix10(float value)](#setMatrix10-float-) | Définit l'élément à la première ligne et à la colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix11()](#getMatrix11--) | Obtient l'élément à la première ligne et à la première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix11(float value)](#setMatrix11-float-) | Définit l'élément à la première ligne et à la première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix12()](#getMatrix12--) | Obtient l'élément à la première ligne et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix12(float value)](#setMatrix12-float-) | Définit l'élément à la première ligne et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix13()](#getMatrix13--) | Obtient l'élément à la première ligne et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix13(float value)](#setMatrix13-float-) | Définit l'élément à la première ligne et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix14()](#getMatrix14--) | Obtient l'élément à la première ligne et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix14(float value)](#setMatrix14-float-) | Définit l'élément à la première ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix20()](#getMatrix20--) | Obtient l'élément à la deuxième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix20(float value)](#setMatrix20-float-) | Définit l'élément à la deuxième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix21()](#getMatrix21--) | Obtient l'élément à la deuxième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix21(float value)](#setMatrix21-float-) | Définit l'élément à la deuxième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix22()](#getMatrix22--) | Obtient l'élément à la deuxième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix22(float value)](#setMatrix22-float-) | Définit l'élément à la deuxième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix23()](#getMatrix23--) | Obtient l'élément à la deuxième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix23(float value)](#setMatrix23-float-) | Définit l'élément à la deuxième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix24()](#getMatrix24--) | Obtient l'élément à la deuxième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix24(float value)](#setMatrix24-float-) | Définit l'élément à la deuxième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix30()](#getMatrix30--) | Obtient l'élément à la troisième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix30(float value)](#setMatrix30-float-) | Définit l'élément à la troisième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix31()](#getMatrix31--) | Obtient l'élément à la troisième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix31(float value)](#setMatrix31-float-) | Définit l'élément à la troisième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix32()](#getMatrix32--) | Obtient l'élément à la troisième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix32(float value)](#setMatrix32-float-) | Définit l'élément à la troisième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix33()](#getMatrix33--) | Obtient l'élément à la troisième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix33(float value)](#setMatrix33-float-) | Définit l'élément à la troisième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix34()](#getMatrix34--) | Obtient l'élément à la troisième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix34(float value)](#setMatrix34-float-) | Définit l'élément à la troisième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix40()](#getMatrix40--) | Obtient l'élément à la quatrième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix40(float value)](#setMatrix40-float-) | Définit l'élément à la quatrième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix41()](#getMatrix41--) | Obtient l'élément à la quatrième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Définit l'élément à la quatrième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Obtient l'élément à la quatrième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix42(float value)](#setMatrix42-float-) | Définit l'élément à la quatrième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix43()](#getMatrix43--) | Obtient l'élément à la quatrième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix43(float value)](#setMatrix43-float-) | Définit l'élément à la quatrième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [getMatrix44()](#getMatrix44--) | Obtient l'élément à la quatrième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [setMatrix44(float value)](#setMatrix44-float-) | Définit l'élément à la quatrième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Obtient les valeurs de la matrice. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | newColorMatrix |
| [getMatrix()](#getMatrix--) | float[][] |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialise une nouvelle instance de la classe `Aspose.Imaging.ColorMatrix`.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialise une nouvelle instance de la classe `Aspose.Imaging.ColorMatrix` en utilisant les éléments de la matrice spécifiée `newColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| Les valeurs des éléments pour le nouveau `Aspose.Imaging.ColorMatrix`. | float - L'élément à la ligne 0 et colonne 0 de ce `Aspose.Imaging.ColorMatrix`. | L'élément à la ligne 0 et colonne 0 de ce `Aspose.Imaging.ColorMatrix`. |

### MATRIX_DIMENSION_ELEMENTS_COUNT {#MATRIX-DIMENSION-ELEMENTS-COUNT}
```
public static final int MATRIX_DIMENSION_ELEMENTS_COUNT
```


Le nombre d'éléments dans la dimension de la matrice.

### MATRIX_DIMENSIONS_COUNT {#MATRIX-DIMENSIONS-COUNT}
```
public static final int MATRIX_DIMENSIONS_COUNT
```


Le nombre de dimensions de la matrice.

### MATRIX_TOTAL_ELEMENTS_COUNT {#MATRIX-TOTAL-ELEMENTS-COUNT}
```
public static final int MATRIX_TOTAL_ELEMENTS_COUNT
```


Le nombre total d'éléments dans la matrice.

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Obtient l'élément à la ligne 0 (zéro) et à la colonne 0 de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la ligne 0 et première colonne de ce `Aspose.Imaging.ColorMatrix` .
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la colonne 0 de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la ligne 0 et première colonne de ce `Aspose.Imaging.ColorMatrix` . |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Obtient l'élément à la ligne 0 (zéro) et à la première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la ligne 0 et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la ligne 0 et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Obtient l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la ligne 0 et troisième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la ligne 0 et troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Obtient l'élément à la ligne 0 (zéro) et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la ligne 0 et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la ligne 0 et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Obtient l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la première ligne et colonne 0 de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la première ligne et colonne 0 de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Obtient l'élément à la première ligne et à la colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la première ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Définit l'élément à la première ligne et à la colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | float - L'élément à la première ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Obtient l'élément à la première ligne et à la première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
L'élément à la première ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Définit l'élément à la première ligne et à la première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la première ligne et de la première colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Obtient l'élément à la première ligne et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la première ligne et de la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Définit l'élément à la première ligne et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la première ligne et de la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Obtient l'élément à la première ligne et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la première ligne et de la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Définit l'élément à la première ligne et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la première ligne et de la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Obtient l'élément à la première ligne et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la première ligne et de la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Définit l'élément à la première ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la première ligne et de la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Obtient l'élément à la deuxième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la deuxième ligne et de la colonne 0 de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Définit l'élément à la deuxième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la deuxième ligne et de la colonne 0 de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Obtient l'élément à la deuxième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la deuxième ligne et de la première colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Définit l'élément à la deuxième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la deuxième ligne et de la première colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Obtient l'élément à la deuxième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la deuxième ligne et de la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Définit l'élément à la deuxième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la deuxième ligne et de la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Obtient l'élément à la deuxième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la deuxième ligne et de la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Définit l'élément à la deuxième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la deuxième ligne et de la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Obtient l'élément à la deuxième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la deuxième ligne et de la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Définit l'élément à la deuxième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la deuxième ligne et de la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Obtient l'élément à la troisième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la troisième ligne et de la colonne 0 de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Définit l'élément à la troisième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la troisième ligne et de la colonne 0 de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Obtient l'élément à la troisième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la troisième ligne et de la première colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Définit l'élément à la troisième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la troisième ligne et de la première colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Obtient l'élément à la troisième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la troisième ligne et de la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Définit l'élément à la troisième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la troisième ligne et de la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Obtient l'élément à la troisième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément de la troisième ligne et de la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Définit l'élément à la troisième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément de la troisième ligne et de la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Obtient l'élément à la troisième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la troisième ligne et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Définit l'élément à la troisième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la troisième ligne et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Obtient l'élément à la quatrième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la quatrième ligne et à la colonne 0 de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Définit l'élément à la quatrième ligne et colonne 0 (zéro) de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la quatrième ligne et à la colonne 0 de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Obtient l'élément à la quatrième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la quatrième ligne et à la première colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Définit l'élément à la quatrième ligne et première colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la quatrième ligne et à la première colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Obtient l'élément à la quatrième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la quatrième ligne et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Définit l'élément à la quatrième ligne et deuxième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la quatrième ligne et à la deuxième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Obtient l'élément à la quatrième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la quatrième ligne et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Définit l'élément à la quatrième ligne et troisième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la quatrième ligne et à la troisième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Obtient l'élément à la quatrième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - L'élément à la quatrième ligne et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Définit l'élément à la quatrième ligne et quatrième colonne de ce `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | L'élément à la quatrième ligne et à la quatrième colonne de ce `Aspose.Imaging.ColorMatrix`. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Obtient les valeurs de la matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ligne | int | Le numéro de ligne. |
| colonne | int | Le numéro de colonne. |

**Returns:**
float - L'élément à la ligne et à la colonne spécifiées.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


newColorMatrix

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ligne | int | Le numéro de ligne. |
| colonne | int | Le numéro de colonne. |
| valeur | float | La valeur |

### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


float[][]

**Returns:**
float[][] - Le tableau des valeurs de la matrice.
