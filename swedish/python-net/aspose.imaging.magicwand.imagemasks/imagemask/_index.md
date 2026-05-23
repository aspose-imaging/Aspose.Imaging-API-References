---
title: "ImageMask-klass"
type: docs
weight: 70
url: /sv/python-net/aspose.imaging.magicwand.imagemasks/imagemask/
---

**Summary:** Describes a binary image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageMask

**Inheritance:** IImageMask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar gränserna, i pixlar, för den här masken. |
| height | int | r | Hämtar höjden, i pixlar, för den här masken. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar gränserna för den valda delen av masken, i pixlar. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Hämtar källbilden som används för att skapa den här masken, om den finns. |
| width | int | r | Hämtar bredden, i pixlar, för den här masken. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| apply() | Applicerar det aktuella masken på källan [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), om den finns. |
| [apply_to(image)](#apply_to_image_1) | Applicerar det aktuella masken på den angivna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [clone()](#clone__2) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
| [crop(rectangle)](#crop_rectangle_3) | Beskär masken med den angivna rektangeln. |
| [crop(size)](#crop_size_4) | Beskär masken med den angivna storleken. |
| [crop(width, height)](#crop_width_height_5) | Beskär masken med den angivna bredden och höjden. |
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magiskt stavval som tillämpats på den angivna bilden. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magiskt stavval som tillämpats på maskens källa. |
| [get(x, y)](#get_x_y_9) | Hämtar opaciteten för den angivna pixeln. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Hämtar opaciteten för den angivna pixeln med byteprecision. |
| [get_feathered(settings)](#get_feathered_settings_11) | Hämtar gråskalemask med kanten mjukad med de angivna inställningarna. |
| [inflate(size)](#inflate_size_12) | Expanderar denna mask med den angivna mängden. |
| [intersect(image, settings)](#intersect_image_settings_13) | Hämtar skärningspunkten mellan den aktuella masken och resultatet av magic wand‑urval som tillämpats på den angivna bilden. |
| [intersect(mask)](#intersect_mask_14) | Hämtar skärningspunkten mellan den aktuella masken och den angivna. |
| [intersect(settings)](#intersect_settings_15) | Hämtar skärningspunkten mellan den aktuella masken och resultatet av magic wand‑urval som tillämpats på maskens källa. |
| [invert()](#invert__16) | Hämtar inversionen av den aktuella masken. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Kontrollerar om den angivna pixeln är ogenomskinlig. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Kontrollerar om den angivna pixeln är genomskinlig. |
| [subtract(image, settings)](#subtract_image_settings_19) | Hämtar resultatet av magic wand‑urval som tillämpats på den angivna bilden, subtraherat från den aktuella masken. |
| [subtract(mask)](#subtract_mask_20) | Hämtar subtraktionen av den angivna masken från den aktuella. |
| [subtract(settings)](#subtract_settings_21) | Hämtar resultatet av magic wand‑urval som tillämpats på källan till den aktuella masken, subtraherat från masken. |
| [union(image, settings)](#union_image_settings_22) | Hämtar unionen av den aktuella masken med resultatet av magic wand‑urval som tillämpats på den angivna bilden. |
| [union(mask)](#union_mask_23) | Hämtar unionen av den aktuella masken med den angivna. |
| [union(settings)](#union_settings_24) | Hämtar unionen av den aktuella masken med resultatet av magic wand‑urval som tillämpats på maskens källa. |


### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Applicerar det aktuella masken på den angivna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild att applicera masken på. |

### Method: clone() {#clone__2}


```
 clone() 
```

Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Object | Ett nytt objekt som är en kopia av den här instansen. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Beskär masken med den angivna rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den angivna rektangeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | En ImageMask. |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Beskär masken med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Den angivna storleken. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | En ImageMask. |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Beskär masken med den angivna bredden och höjden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Den angivna bredden. |
| height | int | Den angivna höjden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | En ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magiskt stavval som tillämpats på den angivna bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild för magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magiskt stavval som tillämpats på maskens källa.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Hämtar opaciteten för den angivna pixeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om den angivna pixeln är ogenomskinlig; annars falskt. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


```
 get_byte_opacity(x, y) 
```

Hämtar opaciteten för den angivna pixeln med byteprecision.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | Bytevärde som representerar opaciteten för den angivna pixeln. |


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Hämtar gråskalemask med kanten mjukad med de angivna inställningarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Inställningar för fjädring. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) med fjädrad kant. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Expanderar denna mask med den angivna mängden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| storlek | int | Mängden för att expandera denna mask. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | En ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Hämtar skärningspunkten mellan den aktuella masken och resultatet av magic wand‑urval som tillämpats på den angivna bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild för magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Hämtar skärningspunkten mellan den aktuella masken och den angivna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Hämtar skärningspunkten mellan den aktuella masken och resultatet av magic wand‑urval som tillämpats på maskens källa.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Hämtar inversionen av den aktuella masken.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


```
 is_opaque(x, y) 
```

Kontrollerar om den angivna pixeln är ogenomskinlig.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om den angivna pixeln är ogenomskinlig; annars falskt. |


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


```
 is_transparent(x, y) 
```

Kontrollerar om den angivna pixeln är genomskinlig.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om den angivna pixeln är genomskinlig; annars falskt. |


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

Hämtar resultatet av magic wand‑urval som tillämpats på den angivna bilden, subtraherat från den aktuella masken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild för magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

Hämtar subtraktionen av den angivna masken från den aktuella.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

Hämtar resultatet av magic wand‑urval som tillämpats på källan till den aktuella masken, subtraherat från masken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

Hämtar unionen av den aktuella masken med resultatet av magic wand‑urval som tillämpats på den angivna bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild för magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

Hämtar unionen av den aktuella masken med den angivna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

Hämtar unionen av den aktuella masken med resultatet av magic wand‑urval som tillämpats på maskens källa.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


