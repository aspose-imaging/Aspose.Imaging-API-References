---
title: "IImageMask Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

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
| [clone()](#clone__1) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Ermittelt die Deckkraft des angegebenen Pixels mit Byte‑Präzision. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Überprüft, ob der angegebene Pixel undurchsichtig ist. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Überprüft, ob der angegebene Pixel transparent ist. |


### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


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


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


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


