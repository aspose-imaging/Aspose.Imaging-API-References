---
title: "Classe PathGradientBrushBase"
type: docs
weight: 60
url: /it/python-net/aspose.imaging.brushes/pathgradientbrushbase/
---

**Summary:** Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with base path gradient functionality.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathGradientBrushBase

**Inheritance:** TransformBrush

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta il punto centrale del gradiente del percorso. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta il punto focale per la caduta del gradiente. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Ottiene il percorso grafico su cui è stato costruito questo pennello. |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene i punti del percorso su cui è stato costruito questo pennello. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta una copia di [Matrix](/imaging/python-net/aspose.imaging/matrix/) che definisce una trasformazione geometrica locale per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Ottiene o imposta un'enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che indica la modalità di avvolgimento per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato. |
| reset_transform() | Reimposta la proprietà [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a identità. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuovo [Brush](/imaging/python-net/aspose.imaging/brush/) che è la copia profonda di questa istanza [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica in quale ordine moltiplicare le due matrici. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o pre-pendere la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o anteporre la matrice di scaling. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

