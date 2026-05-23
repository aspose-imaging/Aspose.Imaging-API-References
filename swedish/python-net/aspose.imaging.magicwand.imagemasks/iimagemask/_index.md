---
title: "IImageMask Klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

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
| [clone()](#clone__1) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Hämtar opaciteten för den angivna pixeln med byteprecision. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Kontrollerar om den angivna pixeln är ogenomskinlig. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Kontrollerar om den angivna pixeln är genomskinlig. |


### Method: clone() {#clone__1}


```
 clone() 
```

Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


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


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


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


