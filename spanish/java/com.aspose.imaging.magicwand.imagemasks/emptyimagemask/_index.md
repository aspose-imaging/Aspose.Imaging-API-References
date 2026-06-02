---
title: "EmptyImageMask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Describe una máscara vacía no abstracta."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Describe una máscara vacía no abstracta.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Inicializa una nueva instancia de la clase [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) con el ancho y alto especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Obtiene los límites de la parte seleccionada de la máscara, en píxeles. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtiene la opacidad del píxel especificado. |
| [inflate(int size)](#inflate-int-) | Infla esta máscara en la cantidad especificada. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la máscara con el rectángulo especificado. |
| [deepClone()](#deepClone--) | Crea un nuevo objeto que es una copia de la instancia actual. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Inicializa una nueva instancia de la clase [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) con el ancho y alto especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | Ancho de la máscara. |
| height | int | Altura de la máscara. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Obtiene los límites de la parte seleccionada de la máscara, en píxeles.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Obtiene la opacidad del píxel especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
boolean - true si el píxel especificado es opaco; de lo contrario, false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Infla esta máscara en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | La cantidad para inflar esta máscara. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Recorta la máscara con el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo especificado. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea un nuevo objeto que es una copia de la instancia actual.

**Returns:**
java.lang.Object - Un nuevo objeto que es una copia de esta instancia.
