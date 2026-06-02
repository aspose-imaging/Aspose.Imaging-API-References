---
title: "Classe ColorMatrix"
type: docs
weight: 1180
url: /it/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Inizializza una nuova istanza della classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Inizializza una nuova istanza della classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) usando gli elementi nella matrice specificata _newColorMatrix_. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Il numero di dimensioni della matrice. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Il numero di elementi nella dimensione della matrice. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Il numero totale di elementi nella matrice. |
| matrix00 | float | r/w | Ottiene o imposta l'elemento alla riga 0 (zero) e colonna 0 di questo [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix01 | float | r/w | Ottiene o imposta l'elemento alla riga 0 (zero) e prima colonna di questo [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix02 | float | r/w | Ottiene o imposta l'elemento alla riga 0 (zero) e seconda colonna di questo [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix03 | float | r/w | Ottiene o imposta l'elemento alla riga 0 (zero) e terza colonna di questo [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix04 | float | r/w | Ottiene o imposta l'elemento alla riga 0 (zero) e alla quarta colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix10 | float | r/w | Ottiene o imposta l'elemento alla prima riga e alla colonna 0 (zero) di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix11 | float | r/w | Ottiene o imposta l'elemento alla prima riga e alla prima colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix12 | float | r/w | Ottiene o imposta l'elemento alla prima riga e alla seconda colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix13 | float | r/w | Ottiene o imposta l'elemento alla prima riga e alla terza colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix14 | float | r/w | Ottiene o imposta l'elemento alla prima riga e alla quarta colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix20 | float | r/w | Ottiene o imposta l'elemento alla seconda riga e alla colonna 0 (zero) di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix21 | float | r/w | Ottiene o imposta l'elemento alla seconda riga e alla prima colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix22 | float | r/w | Ottiene o imposta l'elemento alla seconda riga e alla seconda colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix23 | float | r/w | Ottiene o imposta l'elemento alla seconda riga e alla terza colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix24 | float | r/w | Ottiene o imposta l'elemento alla seconda riga e alla quarta colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix30 | float | r/w | Ottiene o imposta l'elemento alla terza riga e alla colonna 0 (zero) di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix31 | float | r/w | Ottiene o imposta l'elemento alla terza riga e alla prima colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix32 | float | r/w | Ottiene o imposta l'elemento alla terza riga e alla seconda colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix33 | float | r/w | Ottiene o imposta l'elemento alla terza riga e alla terza colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix34 | float | r/w | Ottiene o imposta l'elemento alla terza riga e alla quarta colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix40 | float | r/w | Ottiene o imposta l'elemento alla quarta riga e alla colonna 0 (zero) di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix41 | float | r/w | Ottiene o imposta l'elemento alla quarta riga e alla prima colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix42 | float | r/w | Ottiene o imposta l'elemento alla quarta riga e alla seconda colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix43 | float | r/w | Ottiene o imposta l'elemento alla quarta riga e alla terza colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix44 | float | r/w | Ottiene o imposta l'elemento alla quarta riga e alla quarta colonna di questa [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Ottiene l'elemento nella riga e colonna specificate nella [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [get_matrix()](#get_matrix__2) | Ottiene i valori della matrice. |
| [set(row, column, value)](#set_row_column_value_3) | Imposta l'elemento nella riga e colonna specificate nella [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Inizializza una nuova istanza della classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Inizializza una nuova istanza della classe [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) usando gli elementi nella matrice specificata _newColorMatrix_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_matrix | System.Single[] | I valori degli elementi per la nuova [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Ottiene l'elemento nella riga e colonna specificate nella [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| riga | int | Il numero della riga. |
| colonna | int | Il numero della colonna. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | L'elemento nella riga e colonna specificate. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Ottiene i valori della matrice.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Single[] | L'array dei valori della matrice. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Imposta l'elemento nella riga e colonna specificate nella [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| riga | int | Il numero della riga. |
| colonna | int | Il numero della colonna. |
| valore | float | L'elemento nella riga e colonna specificate. |

