---
title: "Classe TextureBrush"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e la modalità di avvolgimento. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Ottiene l'oggetto [Image](/imaging/python-net/aspose.imaging/image/) associato a questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Ottiene il [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/) associato a questo [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) associato a questo [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta una copia di [Matrix](/imaging/python-net/aspose.imaging/matrix/) che definisce una trasformazione geometrica locale per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Ottiene o imposta un'enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che indica la modalità di avvolgimento per questo [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e la modalità di avvolgimento. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
| [deep_clone()](#deep_clone__8) | Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato. |
| reset_transform() | Reimposta la proprietà [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) a identità. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) è ripetuto. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) è ripetuto. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) è ripetuto. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) è ripetuto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) è ripetuto. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'oggetto [Image](/imaging/python-net/aspose.imaging/image/) con cui questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Una enumerazione [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) che specifica come questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) è ripetuto. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuovo [Brush](/imaging/python-net/aspose.imaging/brush/) che è la copia profonda di questa istanza [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, preponendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica in quale ordine moltiplicare le due matrici. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o pre-pendere la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


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

