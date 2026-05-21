---
title: "CircleMask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive una maschera circolare."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Descrive una maschera circolare.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Inizializza una nuova istanza della classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con il punto centrale e il raggio specificati. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Inizializza una nuova istanza della classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con il punto centrale e il raggio specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Restituisce i limiti, in pixel, di questa maschera. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ottiene l'opacità del pixel specificato. |
| [inflate(int size)](#inflate-int-) | Espande questa maschera dell'importo specificato. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia la maschera con il rettangolo specificato. |
| [deepClone()](#deepClone--) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Inizializza una nuova istanza della classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con il punto centrale e il raggio specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto centrale dell'area selezionata. |
| y | int | La coordinata y del punto centrale dell'area selezionata. |
| radius | int | Raggio dell'area selezionata. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Inizializza una nuova istanza della classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con il punto centrale e il raggio specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | Il punto centrale dell'area selezionata. |
| radius | int | Raggio dell'area selezionata. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Restituisce i limiti, in pixel, di questa maschera.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns:**
java.lang.Object - Un nuovo oggetto che è una copia di questa istanza.
