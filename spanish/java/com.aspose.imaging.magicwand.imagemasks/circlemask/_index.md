---
title: "CircleMask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Describe una máscara circular."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Describe una máscara circular.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Inicializa una nueva instancia de la clase [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con el punto central y el radio especificados. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Inicializa una nueva instancia de la clase [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con el punto central y el radio especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Obtiene los límites, en píxeles, de esta máscara. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtiene la opacidad del píxel especificado. |
| [inflate(int size)](#inflate-int-) | Infla esta máscara en la cantidad especificada. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la máscara con el rectángulo especificado. |
| [deepClone()](#deepClone--) | Crea un nuevo objeto que es una copia de la instancia actual. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Inicializa una nueva instancia de la clase [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con el punto central y el radio especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto central del área seleccionada. |
| y | int | La coordenada y del punto central del área seleccionada. |
| radius | int | Radio del área seleccionada. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Inicializa una nueva instancia de la clase [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) con el punto central y el radio especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | El punto central del área seleccionada. |
| radius | int | Radio del área seleccionada. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Obtiene los límites, en píxeles, de esta máscara.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea un nuevo objeto que es una copia de la instancia actual.

**Returns:**
java.lang.Object - Un nuevo objeto que es una copia de esta instancia.
