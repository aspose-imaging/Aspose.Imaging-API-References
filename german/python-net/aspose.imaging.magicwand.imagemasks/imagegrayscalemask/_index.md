---
title: "ImageGrayscaleMask Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Initialisiert eine neue Instanz der [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) Klasse mit der Größe des angegebenen vorhandenen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Das angegebene [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) wird als Quellbild gespeichert. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Initialisiert eine neue Instanz der [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) Klasse mit der angegebenen Breite und Höhe. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ermittelt die Begrenzungen, in Pixeln, dieser Maske. |
| height | int | r | Ermittelt die Höhe, in Pixeln, dieser Maske. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ermittelt die Begrenzungen des ausgewählten Teils der Maske, in Pixeln. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Ermittelt das Quellbild, das zur Erstellung dieser Maske verwendet wurde, falls vorhanden. |
| width | int | r | Ermittelt die Breite, in Pixeln, dieser Maske. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| apply() | Wendet die aktuelle Maske auf die [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Quelle an, falls vorhanden. |
| [apply_to(image)](#apply_to_image_1) | Wendet die aktuelle Maske auf das angegebene [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) an. |
| [clone()](#clone__2) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
| [crop(rectangle)](#crop_rectangle_3) | Beschneidet die Maske mit dem angegebenen Rechteck. |
| [crop(size)](#crop_size_4) | Beschneidet die Maske mit der angegebenen Größe. |
| [crop(width, height)](#crop_width_height_5) | Beschneidet die Maske mit der angegebenen Breite und Höhe. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem bereitgestellten. |
| [get(x, y)](#get_x_y_7) | Liest oder setzt die Deckkraft des angegebenen Pixels. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Ermittelt die Deckkraft des angegebenen Pixels mit Byte‑Präzision. |
| [intersect(mask)](#intersect_mask_9) | Ermittelt die Schnittmenge der aktuellen Maske mit dem bereitgestellten. |
| [invert()](#invert__10) | Ermittelt die Invertierung der aktuellen Maske. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Überprüft, ob der angegebene Pixel undurchsichtig ist. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Überprüft, ob der angegebene Pixel transparent ist. |
| [set(x, y, value)](#set_x_y_value_13) | Setzt die Deckkraft des angegebenen Pixels. |
| [subtract(mask)](#subtract_mask_14) | Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen. |
| [union(mask)](#union_mask_15) | Vereinigung von zwei Masken. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Initialisiert eine neue Instanz der [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) Klasse mit der Größe des angegebenen vorhandenen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Das angegebene [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) wird als Quellbild gespeichert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Quellbild. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Initialisiert eine neue Instanz der [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) Klasse mit der angegebenen Breite und Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Breite der Maske. |
| height | int | Höhe der Maske. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Wendet die aktuelle Maske auf das angegebene [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild, auf das die Maske angewendet wird. |

### Method: clone() {#clone__2}


```
 clone() 
```

Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object | Ein neues Objekt, das eine Kopie dieser Instanz ist. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Beschneidet die Maske mit dem angegebenen Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das angegebene Rechteck. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Eine beschnittene [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Beschneidet die Maske mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Die angegebene Größe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Eine beschnittene [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Beschneidet die Maske mit der angegebenen Breite und Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die angegebene Breite. |
| height | int | Die angegebene Höhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Eine beschnittene [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem bereitgestellten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Neue [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Liest oder setzt die Deckkraft des angegebenen Pixels.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Byte-Wert; 0 wenn transparent; 255 wenn undurchsichtig. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


```
 get_byte_opacity(x, y) 
```

Ermittelt die Deckkraft des angegebenen Pixels mit Byte‑Präzision.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Byte‑Wert, der die Deckkraft des angegebenen Pixels darstellt. |


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Ermittelt die Schnittmenge der aktuellen Maske mit dem bereitgestellten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Neue [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Ermittelt die Invertierung der aktuellen Maske.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Neue [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


```
 is_opaque(x, y) 
```

Überprüft, ob der angegebene Pixel undurchsichtig ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn der angegebene Pixel undurchsichtig ist; andernfalls false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


```
 is_transparent(x, y) 
```

Überprüft, ob der angegebene Pixel transparent ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn der angegebene Pixel transparent ist; andernfalls false. |


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Setzt die Deckkraft des angegebenen Pixels.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |
| Wert | System.Byte | Byte-Wert; 0 wenn transparent; 255 wenn undurchsichtig. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Neue [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

Vereinigung von zwei Masken.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Neue [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


