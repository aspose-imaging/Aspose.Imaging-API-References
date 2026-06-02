---
title: "IImageMask Classe"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Restituisce i limiti, in pixel, di questa maschera. |
| height | int | r | Restituisce l'altezza, in pixel, di questa maschera. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Restituisce i limiti della parte selezionata della maschera, in pixel. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Restituisce l'immagine sorgente utilizzata per creare questa maschera, se esiste. |
| width | int | r | Restituisce la larghezza, in pixel, di questa maschera. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Ottiene l'opacità del pixel specificato con precisione byte. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Verifica se il pixel specificato è opaco. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Verifica se il pixel specificato è trasparente. |


### Method: clone() {#clone__1}


```
 clone() 
```

Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


```
 get_byte_opacity(x, y) 
```

Ottiene l'opacità del pixel specificato con precisione byte.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | Valore byte, che rappresenta l'opacità del pixel specificato. |


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


```
 is_opaque(x, y) 
```

Verifica se il pixel specificato è opaco.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se il pixel specificato è opaco; altrimenti, false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


```
 is_transparent(x, y) 
```

Verifica se il pixel specificato è trasparente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se il pixel specificato è trasparente; altrimenti, false. |


