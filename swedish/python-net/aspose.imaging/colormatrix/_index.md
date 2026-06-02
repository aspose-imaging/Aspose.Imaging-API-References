---
title: "ColorMatrix-klass"
type: docs
weight: 1180
url: /sv/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initierar en ny instans av klassen [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initierar en ny instans av klassen [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) med elementen i den angivna matrisen _newColorMatrix_. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Antalet matrisdimensioner. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Antalet element i matrisdimensionen. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Det totala antalet element i matrisen. |
| matrix00 | float | r/w | Hämtar eller anger elementet i rad 0 (noll) och kolumn 0 i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix01 | float | r/w | Hämtar eller anger elementet i rad 0 (noll) och första kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix02 | float | r/w | Hämtar eller anger elementet i rad 0 (noll) och andra kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix03 | float | r/w | Hämtar eller anger elementet i rad 0 (noll) och tredje kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix04 | float | r/w | Hämtar eller anger elementet på rad 0 (noll) och fjärde kolumn i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix10 | float | r/w | Hämtar eller anger elementet på första raden och kolumn 0 (noll) i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix11 | float | r/w | Hämtar eller anger elementet på första raden och första kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix12 | float | r/w | Hämtar eller anger elementet på första raden och andra kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix13 | float | r/w | Hämtar eller anger elementet på första raden och tredje kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix14 | float | r/w | Hämtar eller anger elementet på första raden och fjärde kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix20 | float | r/w | Hämtar eller anger elementet på andra raden och kolumn 0 (noll) i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix21 | float | r/w | Hämtar eller anger elementet på andra raden och första kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix22 | float | r/w | Hämtar eller anger elementet på andra raden och andra kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix23 | float | r/w | Hämtar eller anger elementet på andra raden och tredje kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix24 | float | r/w | Hämtar eller anger elementet på andra raden och fjärde kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix30 | float | r/w | Hämtar eller anger elementet på tredje raden och kolumn 0 (noll) i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix31 | float | r/w | Hämtar eller anger elementet på tredje raden och första kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix32 | float | r/w | Hämtar eller anger elementet på tredje raden och andra kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix33 | float | r/w | Hämtar eller anger elementet på tredje raden och tredje kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix34 | float | r/w | Hämtar eller anger elementet på tredje raden och fjärde kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix40 | float | r/w | Hämtar eller anger elementet på fjärde raden och kolumn 0 (noll) i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix41 | float | r/w | Hämtar eller anger elementet på fjärde raden och första kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix42 | float | r/w | Hämtar eller anger elementet på fjärde raden och andra kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix43 | float | r/w | Hämtar eller anger elementet på fjärde raden och tredje kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix44 | float | r/w | Hämtar eller anger elementet på fjärde raden och fjärde kolumnen i denna [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Hämtar elementet på den angivna raden och kolumnen i [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [get_matrix()](#get_matrix__2) | Hämtar matrisens värden. |
| [set(row, column, value)](#set_row_column_value_3) | Anger elementet på den angivna raden och kolumnen i [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initierar en ny instans av klassen [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initierar en ny instans av klassen [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) med elementen i den angivna matrisen _newColorMatrix_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_matrix | System.Single[] | Värdena för elementen i den nya [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Hämtar elementet på den angivna raden och kolumnen i [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rad | int | Radnumret. |
| kolumn | int | Kolumnnumret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Elementet på den angivna raden och kolumnen. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Hämtar matrisens värden.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Single[] | Matrisens värdearray. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Anger elementet på den angivna raden och kolumnen i [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rad | int | Radnumret. |
| kolumn | int | Kolumnnumret. |
| värde | float | Elementet på den angivna raden och kolumnen. |

