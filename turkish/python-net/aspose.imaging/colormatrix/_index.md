---
title: "ColorMatrix Sınıfı"
type: docs
weight: 1180
url: /tr/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Yeni bir [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) sınıfı örneği başlatır. |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Belirtilen _newColorMatrix_ matrisindeki öğeleri kullanarak yeni bir [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Matris boyutlarının sayısı. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Matris boyutundaki öğelerin sayısı. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Matrisin toplam öğe sayısı. |
| matrix00 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin 0 (sıfır) satır ve 0 sütunundaki öğeyi alır veya ayarlar. |
| matrix01 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin 0 (sıfır) satır ve ilk sütunundaki öğeyi alır veya ayarlar. |
| matrix02 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin 0 (sıfır) satır ve ikinci sütunundaki öğeyi alır veya ayarlar. |
| matrix03 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin 0 (sıfır) satır ve üçüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix04 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin 0 (sıfır) satır ve dördüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix10 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin birinci satır ve 0 (sıfır) sütunundaki öğeyi alır veya ayarlar. |
| matrix11 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin birinci satır ve birinci sütunundaki öğeyi alır veya ayarlar. |
| matrix12 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin birinci satır ve ikinci sütunundaki öğeyi alır veya ayarlar. |
| matrix13 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin birinci satır ve üçüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix14 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin birinci satır ve dördüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix20 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin ikinci satır ve 0 (sıfır) sütunundaki öğeyi alır veya ayarlar. |
| matrix21 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin ikinci satır ve birinci sütunundaki öğeyi alır veya ayarlar. |
| matrix22 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin ikinci satır ve ikinci sütunundaki öğeyi alır veya ayarlar. |
| matrix23 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin ikinci satır ve üçüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix24 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin ikinci satır ve dördüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix30 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin üçüncü satır ve 0 (sıfır) sütunundaki öğeyi alır veya ayarlar. |
| matrix31 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin üçüncü satır ve birinci sütunundaki öğeyi alır veya ayarlar. |
| matrix32 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin üçüncü satır ve ikinci sütunundaki öğeyi alır veya ayarlar. |
| matrix33 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin üçüncü satır ve üçüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix34 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin üçüncü satır ve dördüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix40 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin dördüncü satır ve 0 (sıfır) sütunundaki öğeyi alır veya ayarlar. |
| matrix41 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin dördüncü satır ve birinci sütunundaki öğeyi alır veya ayarlar. |
| matrix42 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin dördüncü satır ve ikinci sütunundaki öğeyi alır veya ayarlar. |
| matrix43 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin dördüncü satır ve üçüncü sütunundaki öğeyi alır veya ayarlar. |
| matrix44 | float | r/w | Bu [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) nesnesinin dördüncü satır ve dördüncü sütunundaki öğeyi alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Belirtilen satır ve sütundaki öğeyi [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) içinde alır. |
| [get_matrix()](#get_matrix__2) | Matris değerlerini alır. |
| [set(row, column, value)](#set_row_column_value_3) | Belirtilen satır ve sütundaki öğeyi [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) içinde ayarlar. |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Yeni bir [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) sınıfı örneği başlatır.

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Belirtilen _newColorMatrix_ matrisindeki öğeleri kullanarak yeni bir [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | System.Single[] | Yeni [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) öğelerinin değerleri. |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Belirtilen satır ve sütundaki öğeyi [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) içinde alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| satır | int | Satır numarası. |
| sütun | int | Sütun numarası. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Belirtilen satır ve sütundaki öğe. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Matris değerlerini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Single[] | Matris değerleri dizisi. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Belirtilen satır ve sütundaki öğeyi [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) içinde ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| satır | int | Satır numarası. |
| sütun | int | Sütun numarası. |
| değer | float | Belirtilen satır ve sütundaki öğe. |

