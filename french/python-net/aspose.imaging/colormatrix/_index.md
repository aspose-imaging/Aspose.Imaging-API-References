---
title: "Classe ColorMatrix"
type: docs
weight: 1180
url: /fr/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initialise une nouvelle instance de la classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initialise une nouvelle instance de la classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) en utilisant les éléments de la matrice spécifiée _newColorMatrix_. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Le nombre de dimensions de la matrice. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Le nombre d'éléments dans la dimension de la matrice. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Le nombre total d'éléments dans la matrice. |
| matrix00 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix01 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix02 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix03 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix04 | float | r/w | Obtient ou définit l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix10 | float | r/w | Obtient ou définit l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix11 | float | r/w | Obtient ou définit l'élément à la première ligne et à la première colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix12 | float | r/w | Obtient ou définit l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix13 | float | r/w | Obtient ou définit l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix14 | float | r/w | Obtient ou définit l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix20 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix21 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix22 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix23 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix24 | float | r/w | Obtient ou définit l'élément à la deuxième ligne et à la quatrième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix30 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix31 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la première colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix32 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la deuxième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix33 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la troisième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix34 | float | r/w | Obtient ou définit l'élément à la troisième ligne et à la quatrième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix40 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix41 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et à la première colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix42 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et à la deuxième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix43 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et à la troisième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix44 | float | r/w | Obtient ou définit l'élément à la quatrième ligne et à la quatrième colonne de ce [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Obtient l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [get_matrix()](#get_matrix__2) | Obtient les valeurs de la matrice. |
| [set(row, column, value)](#set_row_column_value_3) | Définit l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initialise une nouvelle instance de la classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initialise une nouvelle instance de la classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) en utilisant les éléments de la matrice spécifiée _newColorMatrix_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | System.Single[] | Les valeurs des éléments pour le nouveau [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Obtient l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ligne | int | Le numéro de ligne. |
| colonne | int | Le numéro de colonne. |

**Returns**

| Type | Description |
| :- | :- |
| float | L'élément à la ligne et à la colonne spécifiées. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Obtient les valeurs de la matrice.

**Returns**

| Type | Description |
| :- | :- |
| System.Single[] | Le tableau des valeurs de la matrice. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Définit l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ligne | int | Le numéro de ligne. |
| colonne | int | Le numéro de colonne. |
| value | float | L'élément à la ligne et à la colonne spécifiées. |

