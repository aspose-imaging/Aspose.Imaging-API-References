---
title: "CircleMask Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.magicwand.imagemasks/circlemask/
---

**Summary:** Describes a circle mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.CircleMask

**Inheritance:** IImageMask, ImageMask

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CircleMask(center, radius)](#CircleMask_center_radius_1) | Initialisiert eine neue Instanz der [CircleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/circlemask/) Klasse mit dem angegebenen Mittelpunkt und Radius. |
| [CircleMask(x, y, radius)](#CircleMask_x_y_radius_2) | Initialisiert eine neue Instanz der [CircleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/circlemask/) Klasse mit dem angegebenen Mittelpunkt und Radius. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ermittelt die Begrenzungen, in Pixeln, dieser Maske. |
| height | int | r | Ermittelt die Höhe, in Pixeln, dieser Maske. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ermittelt die Begrenzungen, in Pixeln, dieser Maske. |
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
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Magic‑Wand‑Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem bereitgestellten. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Magic‑Wand‑Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [get(x, y)](#get_x_y_9) | Ermittelt die Deckkraft des angegebenen Pixels. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Ermittelt die Deckkraft des angegebenen Pixels mit Byte‑Präzision. |
| [get_feathered(settings)](#get_feathered_settings_11) | Ermittelt die Graustufenmaske, bei der der Rand mit den angegebenen Einstellungen verwischt wird. |
| [inflate(size)](#inflate_size_12) | Vergrößert diese Maske um den angegebenen Betrag. |
| [intersect(image, settings)](#intersect_image_settings_13) | Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [intersect(mask)](#intersect_mask_14) | Ermittelt die Schnittmenge der aktuellen Maske mit dem bereitgestellten. |
| [intersect(settings)](#intersect_settings_15) | Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [invert()](#invert__16) | Ermittelt die Invertierung der aktuellen Maske. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Überprüft, ob der angegebene Pixel undurchsichtig ist. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Überprüft, ob der angegebene Pixel transparent ist. |
| [subtract(image, settings)](#subtract_image_settings_19) | Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde, subtrahiert von der aktuellen Maske. |
| [subtract(mask)](#subtract_mask_20) | Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen. |
| [subtract(settings)](#subtract_settings_21) | Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf die Quelle der aktuellen Maske angewendet wurde, subtrahiert von der Maske. |
| [union(image, settings)](#union_image_settings_22) | Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [union(mask)](#union_mask_23) | Ermittelt die Vereinigung der aktuellen Maske mit dem Bereitgestellten. |
| [union(settings)](#union_settings_24) | Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde. |


### Constructor: CircleMask(center, radius) {#CircleMask_center_radius_1}


```
 CircleMask(center, radius) 
```

Initialisiert eine neue Instanz der [CircleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/circlemask/) Klasse mit dem angegebenen Mittelpunkt und Radius.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| center | [Point](/imaging/python-net/aspose.imaging/point/) | Der Mittelpunkt des ausgewählten Bereichs. |
| Radius | int | Radius des ausgewählten Bereichs. |

### Constructor: CircleMask(x, y, radius) {#CircleMask_x_y_radius_2}


```
 CircleMask(x, y, radius) 
```

Initialisiert eine neue Instanz der [CircleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/circlemask/) Klasse mit dem angegebenen Mittelpunkt und Radius.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des Mittelpunkts des ausgewählten Bereichs. |
| y | int | Die y-Koordinate des Mittelpunkts des ausgewählten Bereichs. |
| Radius | int | Radius des ausgewählten Bereichs. |

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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Ein zugeschnittener CircleMask oder ImageBitMask als ImageMask.<br/>            Da ein ImageBitMask zurückgegeben werden kann, wird ein Fluent-Aufruf empfohlen. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Eine ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Eine ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Magic‑Wand‑Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem bereitgestellten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Magic‑Wand‑Auswahl, die auf die Quelle der Maske angewendet wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Ermittelt die Deckkraft des angegebenen Pixels.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn der angegebene Pixel undurchsichtig ist; andernfalls false. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


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


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Ermittelt die Graustufenmaske, bei der der Rand mit den angegebenen Einstellungen verwischt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Weichzeichnungseinstellungen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) mit weichgezeichnetem Rand. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Vergrößert diese Maske um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | int | Der Betrag, um den diese Maske aufgebläht wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Eine aufgeblähte CircleMask als ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Ermittelt die Schnittmenge der aktuellen Maske mit dem bereitgestellten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Ermittelt die Invertierung der aktuellen Maske.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


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


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde, subtrahiert von der aktuellen Maske.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf die Quelle der aktuellen Maske angewendet wurde, subtrahiert von der Maske.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

Ermittelt die Vereinigung der aktuellen Maske mit dem Bereitgestellten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bereitgestellte Maske |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen für den Zauberstab. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


