---
title: "ImageGrayscaleMask klass"
type: docs
weight: 60
url: /sv/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Initierar en ny instans av klassen [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) med storleken på den angivna befintliga [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Angiven [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) kommer att lagras som källbild. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Initierar en ny instans av klassen [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) med den angivna bredden och höjden. |
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
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna. |
| [get(x, y)](#get_x_y_7) | Hämtar eller anger opaciteten för den angivna pixeln. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Hämtar opaciteten för den angivna pixeln med byteprecision. |
| [intersect(mask)](#intersect_mask_9) | Hämtar skärningspunkten mellan den aktuella masken och den angivna. |
| [invert()](#invert__10) | Hämtar inversionen av den aktuella masken. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Kontrollerar om den angivna pixeln är ogenomskinlig. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Kontrollerar om den angivna pixeln är genomskinlig. |
| [set(x, y, value)](#set_x_y_value_13) | Anger opaciteten för den angivna pixeln. |
| [subtract(mask)](#subtract_mask_14) | Hämtar subtraktionen av den angivna masken från den aktuella. |
| [union(mask)](#union_mask_15) | Union av två masker. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Initierar en ny instans av klassen [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) med storleken på den angivna befintliga [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Angiven [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) kommer att lagras som källbild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Källbild. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Initierar en ny instans av klassen [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) med den angivna bredden och höjden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Maskens bredd. |
| height | int | Höjd på masken. |

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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | En beskuren [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | En beskuren [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | En beskuren [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Ny [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Hämtar eller anger opaciteten för den angivna pixeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | Bytevärde; 0 om transparent; 255 om opak. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


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


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Hämtar skärningspunkten mellan den aktuella masken och den angivna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Ny [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Hämtar inversionen av den aktuella masken.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Ny [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


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


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Anger opaciteten för den angivna pixeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |
| värde | System.Byte | Bytevärde; 0 om transparent; 255 om opak. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Hämtar subtraktionen av den angivna masken från den aktuella.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Ny [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

Union av två masker.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Tillhandahållen mask |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Ny [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


