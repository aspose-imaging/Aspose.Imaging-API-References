---
title: "Klasse TextureBrush"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild verwendet. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und den Wrap-Modus verwendet. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest das [Image](/imaging/python-net/aspose.imaging/image/)-Objekt, das mit diesem [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/)-Objekt verknüpft ist. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Liest die [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die mit diesem [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) verknüpft ist. |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liefert das [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) das mit diesem [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) verknüpft ist. |
| is_transform_changed | bool | r | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder<br/>            das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde aus Gründen der Abwärtskompatibilität mit GDI+ eingeführt. |
| opacity | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ruft eine Kopie des [Matrix](/imaging/python-net/aspose.imaging/matrix/) ab oder legt sie fest, die eine lokale geometrische Transformation für diesen [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) definiert. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Liest oder setzt eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die den Wrap-Modus für diesen [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und den Wrap-Modus verwendet. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet. |
| [deep_clone()](#deep_clone__8) | Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/), indem die angegebene [Matrix](/imaging/python-net/aspose.imaging/matrix/) vorangestellt wird. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge. |
| reset_transform() | Setzt die Eigenschaft [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) auf die Identität zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) Objekt, das zusätzliche Informationen über das von diesem [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt verwendete Bild enthält. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) Objekt, das zusätzliche Informationen über das von diesem [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt verwendete Bild enthält. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und den Wrap-Modus verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die festlegt, wie dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt gekachelt wird. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die festlegt, wie dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt gekachelt wird. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die festlegt, wie dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt gekachelt wird. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) Objekt, das zusätzliche Informationen über das von diesem [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt verwendete Bild enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) Objekt, das zusätzliche Informationen über das von diesem [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt verwendete Bild enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild und den Wrap-Modus verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die festlegt, wie dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt gekachelt wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die festlegt, wie dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt gekachelt wird. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Initialisiert eine neue Instanz der Klasse [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/), die das angegebene Bild, den Wrap-Modus und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das [Image](/imaging/python-net/aspose.imaging/image/) Objekt, mit dem dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Eine [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) Aufzählung, die festlegt, wie dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt gekachelt wird. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das begrenzende Rechteck für dieses [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) Objekt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Ein neuer [Brush](/imaging/python-net/aspose.imaging/brush/), der der Deep-Clone dieser [Brush](/imaging/python-net/aspose.imaging/brush/) Instanz ist. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/), indem die angegebene [Matrix](/imaging/python-net/aspose.imaging/matrix/) vorangestellt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, in welcher Reihenfolge die beiden Matrizen zu multiplizieren sind. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


```
 scale_transform(sx, sy, order) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) der angibt, ob die Skalierungsmatrix angehängt oder vorangestellt werden soll. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


```
 translate_transform(dx, dy, order) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

