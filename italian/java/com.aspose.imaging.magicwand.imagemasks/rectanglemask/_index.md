---
title: "RectangleMask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive una maschera rettangolare."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Descrive una maschera rettangolare.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Inizializza una nuova istanza della classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con il punto in alto a sinistra specificato, larghezza e altezza. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con il rettangolo specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Restituisce i limiti della parte selezionata della maschera, in pixel. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ottiene l'opacità del pixel specificato. |
| [inflate(int size)](#inflate-int-) | Espande questa maschera dell'importo specificato. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia la maschera con il rettangolo specificato. |
| [deepClone()](#deepClone--) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nuova maschera usando lo strumento magic wand basata sul tono e sul colore del pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Unisci la maschera esistente con quella specificata creata dallo strumento magic wand
            .union(new MagicWandSettings(416, 387))
            // Inverti la maschera esistente
            .invert()
            // Sottrai la maschera specificata creata dallo strumento magic wand con soglia specificata dalla maschera esistente
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Sottrai quattro maschere rettangolari specificate dalla maschera esistente una alla volta
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Sfuma la maschera con le impostazioni specificate
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applica la maschera all'immagine
            .apply();

    // Salva immagine
    image.save(outputFilePath);
}

```

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Inizializza una nuova istanza della classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con il punto in alto a sinistra specificato, larghezza e altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto in alto a sinistra dell'area selezionata. |
| y | int | La coordinata y del punto in alto a sinistra dell'area selezionata. |
| width | int | Larghezza dell'area selezionata. |
| height | int | Altezza dell'area selezionata. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Inizializza una nuova istanza della classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Area selezionata specificata come rettangolo. |

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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns:**
java.lang.Object - Un nuovo oggetto che è una copia di questa istanza.
