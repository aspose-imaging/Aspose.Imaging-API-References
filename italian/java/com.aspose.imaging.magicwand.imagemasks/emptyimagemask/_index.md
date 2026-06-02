---
title: "EmptyImageMask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive una maschera vuota non astratta."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Descrive una maschera vuota non astratta.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Inizializza una nuova istanza della classe [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) con la larghezza e l'altezza specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Restituisce i limiti della parte selezionata della maschera, in pixel. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ottiene l'opacità del pixel specificato. |
| [inflate(int size)](#inflate-int-) | Espande questa maschera dell'importo specificato. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia la maschera con il rettangolo specificato. |
| [deepClone()](#deepClone--) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Inizializza una nuova istanza della classe [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) con la larghezza e l'altezza specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | Larghezza della maschera. |
| height | int | Altezza della maschera. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Restituisce i limiti della parte selezionata della maschera, in pixel.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Ottiene l'opacità del pixel specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
boolean - true se il pixel specificato è opaco; altrimenti, false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Espande questa maschera dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La quantità da gonfiare questa maschera. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Ritaglia la maschera con il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo specificato. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns:**
java.lang.Object - Un nuovo oggetto che è una copia di questa istanza.
