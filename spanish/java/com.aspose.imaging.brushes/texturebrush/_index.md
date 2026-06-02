---
title: "TextureBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Cada propiedad de la clase Aspose.Imaging.Brushes.TextureBrush es un objeto Aspose.Imaging.Brush que utiliza una imagen para rellenar el interior de una forma."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.brushes/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Cada propiedad de la clase `Aspose.Imaging.Brushes.TextureBrush` es un objeto `Aspose.Imaging.Brush` que utiliza una imagen para rellenar el interior de una forma. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.imaging.Image-) | Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.imaging.Image-int-) | Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada y el modo de ajuste. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada y el rectángulo delimitador. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada y el rectángulo delimitador. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-) | Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-) | Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getImage()](#getImage--) | Obtiene el objeto `com.aspose.imaging.Image` asociado a este objeto `com.aspose.imaging.brushes.TextureBrush`. |
| [getImageAttributes()](#getImageAttributes--) | Obtiene el `ImageAttributes` asociado con este `TextureBrush`. |
| [getImageRectangle()](#getImageRectangle--) | Obtiene el `Rectangle` asociado con este `TextureBrush`. |
### TextureBrush(Image image) {#TextureBrush-com.aspose.imaging.Image-}
```
public TextureBrush(Image image)
```


Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto `Aspose.Imaging.Image` con el que este objeto `Aspose.Imaging.Brushes.TextureBrush` rellena los interiores. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.imaging.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto `Aspose.Imaging.Image` con el que este objeto `Aspose.Imaging.Brushes.TextureBrush` rellena los interiores. |
| wrapMode | int | Una enumeración `Aspose.Imaging.WrapMode` que especifica cómo se mosaica este objeto `Aspose.Imaging.Brushes.TextureBrush`. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto [Image](../../com.aspose.imaging/image) con el que este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) rellena los interiores. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Una estructura [Rectangle](../../com.aspose.imaging/rectangle) que representa el rectángulo delimitador de este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Un objeto [ImageAttributes](../../com.aspose.imaging/imageattributes) que contiene información adicional sobre la imagen utilizada por este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada y el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto [Image](../../com.aspose.imaging/image) con el que este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) rellena los interiores. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Una estructura [Rectangle](../../com.aspose.imaging/rectangle) que representa el rectángulo delimitador de este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada y el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto [Image](../../com.aspose.imaging/image) con el que este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) rellena los interiores. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura [RectangleF](../../com.aspose.imaging/rectanglef) que representa el rectángulo delimitador de este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Inicializa una nueva instancia de la clase [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto [Image](../../com.aspose.imaging/image) con el que este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) rellena los interiores. |
| wrapMode | int | Una enumeración [WrapMode](../../com.aspose.imaging/wrapmode) que especifica cómo se mosaica este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Una estructura [Rectangle](../../com.aspose.imaging/rectangle) que representa el rectángulo delimitador de este objeto [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto `Aspose.Imaging.Image` con el que este objeto `Aspose.Imaging.Brushes.TextureBrush` rellena los interiores. |
| wrapMode | int | Una enumeración `Aspose.Imaging.WrapMode` que especifica cómo se mosaica este objeto `Aspose.Imaging.Brushes.TextureBrush`. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura `Aspose.Imaging.RectangleF` que representa el rectángulo delimitador de este objeto `Aspose.Imaging.Brushes.TextureBrush`. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Inicializa una nueva instancia de la clase `Aspose.Imaging.Brushes.TextureBrush` que utiliza la imagen especificada, el rectángulo delimitador y los atributos de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | El objeto `Aspose.Imaging.Image` con el que este objeto `Aspose.Imaging.Brushes.TextureBrush` rellena los interiores. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura `Aspose.Imaging.RectangleF` que representa el rectángulo delimitador de este objeto `Aspose.Imaging.Brushes.TextureBrush`. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Un objeto `com.aspose.imaging.ImageAttributes` que contiene información adicional sobre la imagen utilizada por este objeto `Aspose.Imaging.Brushes.TextureBrush`. |

### getImage() {#getImage--}
```
public Image getImage()
```


Obtiene el objeto `com.aspose.imaging.Image` asociado a este objeto `com.aspose.imaging.brushes.TextureBrush`.

Valor: Un objeto `com.aspose.imaging.Image` que representa la imagen con la que este objeto `com.aspose.imaging.brushes.TextureBrush` rellena formas.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Obtiene el `ImageAttributes` asociado con este `TextureBrush`.

Valor: El `ImageAttributes`.

**Returns:**
[ImageAttributes](../../com.aspose.imaging/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Obtiene el `Rectangle` asociado con este `TextureBrush`.

Valor: El `Rectangle`.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
