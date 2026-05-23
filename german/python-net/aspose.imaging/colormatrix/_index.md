---
title: "ColorMatrix-Klasse"
type: docs
weight: 1180
url: /de/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initialisiert eine neue Instanz der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) Klasse. |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initialisiert eine neue Instanz der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) Klasse unter Verwendung der Elemente der angegebenen Matrix _newColorMatrix_. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Die Anzahl der Matrixdimensionen. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Die Anzahl der Elemente in einer Matrixdimension. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Die Gesamtzahl der Elemente in der Matrix. |
| matrix00 | float | r/w | Liest oder setzt das Element in Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix01 | float | r/w | Liest oder setzt das Element in Zeile 0 (null) und erster Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix02 | float | r/w | Liest oder setzt das Element in Zeile 0 (null) und zweiter Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix03 | float | r/w | Liest oder setzt das Element in Zeile 0 (null) und dritter Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix04 | float | r/w | Liest oder setzt das Element in der 0 (null) Zeile und vierten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix10 | float | r/w | Liest oder setzt das Element in der ersten Zeile und 0 (null) Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix11 | float | r/w | Liest oder setzt das Element in der ersten Zeile und ersten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix12 | float | r/w | Liest oder setzt das Element in der ersten Zeile und zweiten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix13 | float | r/w | Liest oder setzt das Element in der ersten Zeile und dritten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix14 | float | r/w | Liest oder setzt das Element in der ersten Zeile und vierten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix20 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und 0 (null) Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix21 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und ersten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix22 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und zweiten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix23 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und dritten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix24 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und vierten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix30 | float | r/w | Liest oder setzt das Element in der dritten Zeile und 0 (null) Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix31 | float | r/w | Liest oder setzt das Element in der dritten Zeile und ersten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix32 | float | r/w | Liest oder setzt das Element in der dritten Zeile und zweiten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix33 | float | r/w | Liest oder setzt das Element in der dritten Zeile und dritten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix34 | float | r/w | Liest oder setzt das Element in der dritten Zeile und vierten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix40 | float | r/w | Liest oder setzt das Element in der vierten Zeile und 0 (null) Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix41 | float | r/w | Liest oder setzt das Element in der vierten Zeile und ersten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix42 | float | r/w | Liest oder setzt das Element in der vierten Zeile und zweiten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix43 | float | r/w | Liest oder setzt das Element in der vierten Zeile und dritten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix44 | float | r/w | Liest oder setzt das Element in der vierten Zeile und vierten Spalte dieser [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Liest das Element in der angegebenen Zeile und Spalte der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [get_matrix()](#get_matrix__2) | Liest die Matrixwerte. |
| [set(row, column, value)](#set_row_column_value_3) | Setzt das Element in der angegebenen Zeile und Spalte der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initialisiert eine neue Instanz der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) Klasse.

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initialisiert eine neue Instanz der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) Klasse unter Verwendung der Elemente der angegebenen Matrix _newColorMatrix_.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | System.Single[] | Die Werte der Elemente für die neue [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Liest das Element in der angegebenen Zeile und Spalte der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zeile | int | Die Zeilennummer. |
| Spalte | int | Die Spaltennummer. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Das Element in der angegebenen Zeile und Spalte. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Liest die Matrixwerte.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Single[] | Das Array der Matrixwerte. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Setzt das Element in der angegebenen Zeile und Spalte der [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zeile | int | Die Zeilennummer. |
| Spalte | int | Die Spaltennummer. |
| Wert | float | Das Element in der angegebenen Zeile und Spalte. |

