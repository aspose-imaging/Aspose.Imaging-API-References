---
title: "IImageMask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Describe una máscara."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Describe una máscara.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSource()](#getSource--) | Obtiene la imagen fuente utilizada para crear esta máscara, si existe. |
| [getWidth()](#getWidth--) | Obtiene el ancho, en píxeles, de esta máscara. |
| [getHeight()](#getHeight--) | Obtiene la altura, en píxeles, de esta máscara. |
| [getBounds()](#getBounds--) | Obtiene los límites, en píxeles, de esta máscara. |
| [getSelectionBounds()](#getSelectionBounds--) | Obtiene los límites de la parte seleccionada de la máscara, en píxeles. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Comprueba si el píxel especificado es opaco. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Comprueba si el píxel especificado es transparente. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Obtiene la opacidad del píxel especificado con precisión de byte. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Obtiene la imagen fuente utilizada para crear esta máscara, si existe.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Obtiene el ancho, en píxeles, de esta máscara.

**Returns:**
int - el ancho, en píxeles, de esta máscara.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Obtiene la altura, en píxeles, de esta máscara.

**Returns:**
int - la altura, en píxeles, de esta máscara.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Obtiene los límites, en píxeles, de esta máscara.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Obtiene los límites de la parte seleccionada de la máscara, en píxeles.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


Comprueba si el píxel especificado es opaco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
boolean - true si el píxel especificado es opaco; de lo contrario, false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


Comprueba si el píxel especificado es transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
boolean - true si el píxel especificado es transparente; de lo contrario, false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


Obtiene la opacidad del píxel especificado con precisión de byte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
byte - Valor Byte, que representa la opacidad del píxel especificado.
