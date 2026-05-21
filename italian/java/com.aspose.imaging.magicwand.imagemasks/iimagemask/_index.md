---
title: "IImageMask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive una maschera."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Descrive una maschera.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSource()](#getSource--) | Restituisce l'immagine sorgente utilizzata per creare questa maschera, se esiste. |
| [getWidth()](#getWidth--) | Restituisce la larghezza, in pixel, di questa maschera. |
| [getHeight()](#getHeight--) | Restituisce l'altezza, in pixel, di questa maschera. |
| [getBounds()](#getBounds--) | Restituisce i limiti, in pixel, di questa maschera. |
| [getSelectionBounds()](#getSelectionBounds--) | Restituisce i limiti della parte selezionata della maschera, in pixel. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Verifica se il pixel specificato è opaco. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Verifica se il pixel specificato è trasparente. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Ottiene l'opacità del pixel specificato con precisione a byte. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Restituisce l'immagine sorgente utilizzata per creare questa maschera, se esiste.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Restituisce la larghezza, in pixel, di questa maschera.

**Returns:**
int - la larghezza, in pixel, di questa maschera.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Restituisce l'altezza, in pixel, di questa maschera.

**Returns:**
int - l'altezza, in pixel, di questa maschera.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Restituisce i limiti, in pixel, di questa maschera.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Restituisce i limiti della parte selezionata della maschera, in pixel.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


Verifica se il pixel specificato è opaco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
boolean - true se il pixel specificato è opaco; altrimenti, false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


Verifica se il pixel specificato è trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
boolean - true se il pixel specificato è trasparente; altrimenti, false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


Ottiene l'opacità del pixel specificato con precisione a byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
byte - Valore byte, che rappresenta l'opacità del pixel specificato.
