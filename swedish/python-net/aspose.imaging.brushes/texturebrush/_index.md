---
title: "TextureBrush klass"
type: docs
weight: 90
url: /sv/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och omslagsläget. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar [Image](/imaging/python-net/aspose.imaging/image/) objektet som är associerat med detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Hämtar [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som är associerat med detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) som är associerad med detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| is_transform_changed | bool | r | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel genom att sätta transformationsmatrisen eller<br/>            anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| opacity | float | r/w | Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Ett värde på 0 betyder att penseln är helt synlig, ett värde på 1 betyder att penseln är helt ogenomskinlig. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger en kopia av [Matrix](/imaging/python-net/aspose.imaging/matrix/) som definierar en lokal geometrisk transformation för denna [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Hämtar eller anger en [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration som indikerar omslagsläget för detta [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och omslagsläget. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln. |
| [deep_clone()](#deep_clone__8) | Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer egenskapen [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Skalar den lokala geometriska transformen med de angivna värdena i den angivna ordningen. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) objekt som innehåller ytterligare information om bilden som används av detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) objekt som innehåller ytterligare information om bilden som används av detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och omslagsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | En [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) uppräkning som specificerar hur detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt upprepas. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | En [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) uppräkning som specificerar hur detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt upprepas. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | En [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) uppräkning som specificerar hur detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt upprepas. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) objekt som innehåller ytterligare information om bilden som används av detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) objekt som innehåller ytterligare information om bilden som används av detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden och omslagsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | En [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) uppräkning som specificerar hur detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt upprepas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | En [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) uppräkning som specificerar hur detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt upprepas. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) som använder den angivna bilden, omslagsläget och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Det [Image](/imaging/python-net/aspose.imaging/image/) objektet som detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | En [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) uppräkning som specificerar hur detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt upprepas. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln för detta [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) objekt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | En ny [Brush](/imaging/python-net/aspose.imaging/brush/) som är den djupa klonen av detta [Brush](/imaging/python-net/aspose.imaging/brush/)-instans. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för detta [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformen med de angivna värdena i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som anger om skalningsmatrisen ska läggas till eller föregås. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


```
 translate_transform(dx, dy, order) 
```

Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen (före eller efter) i vilken translationen ska tillämpas. |

