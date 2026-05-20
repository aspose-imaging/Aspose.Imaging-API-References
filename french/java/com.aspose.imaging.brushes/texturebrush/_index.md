---
title: "TextureBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Chaque propriété de la classe Aspose.Imaging.Brushes.TextureBrush est un objet Aspose.Imaging.Brush qui utilise une image pour remplir l'intérieur d'une forme."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.brushes/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Chaque propriété de la classe `Aspose.Imaging.Brushes.TextureBrush` est un objet `Aspose.Imaging.Brush` qui utilise une image pour remplir l'intérieur d'une forme. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.imaging.Image-) | Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.imaging.Image-int-) | Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée et le mode d'habillage. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée et le rectangle de délimitation. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée et le rectangle de délimitation. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée, le mode d'habillage et le rectangle de délimitation. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-) | Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée, le mode d'habillage et le rectangle de délimitation. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-) | Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImage()](#getImage--) | Obtient l'objet `com.aspose.imaging.Image` associé à cet objet `com.aspose.imaging.brushes.TextureBrush`. |
| [getImageAttributes()](#getImageAttributes--) | Obtient les `ImageAttributes` associés à ce `TextureBrush`. |
| [getImageRectangle()](#getImageRectangle--) | Obtient le `Rectangle` associé à ce `TextureBrush`. |
### TextureBrush(Image image) {#TextureBrush-com.aspose.imaging.Image-}
```
public TextureBrush(Image image)
```


Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet `Aspose.Imaging.Image` avec lequel cet objet `Aspose.Imaging.Brushes.TextureBrush` remplit les intérieurs. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.imaging.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée et le mode d'habillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet `Aspose.Imaging.Image` avec lequel cet objet `Aspose.Imaging.Brushes.TextureBrush` remplit les intérieurs. |
| wrapMode | int | Une énumération `Aspose.Imaging.WrapMode` qui spécifie comment cet objet `Aspose.Imaging.Brushes.TextureBrush` est carrelé. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet [Image](../../com.aspose.imaging/image) avec lequel cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) remplit les intérieurs. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Une structure [Rectangle](../../com.aspose.imaging/rectangle) qui représente le rectangle englobant de cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Un objet [ImageAttributes](../../com.aspose.imaging/imageattributes) qui contient des informations supplémentaires sur l'image utilisée par cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée et le rectangle de délimitation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet [Image](../../com.aspose.imaging/image) avec lequel cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) remplit les intérieurs. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Une structure [Rectangle](../../com.aspose.imaging/rectangle) qui représente le rectangle englobant de cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée et le rectangle de délimitation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet [Image](../../com.aspose.imaging/image) avec lequel cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) remplit les intérieurs. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure [RectangleF](../../com.aspose.imaging/rectanglef) qui représente le rectangle englobant de cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Initialise une nouvelle instance de la classe [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) qui utilise l'image spécifiée, le mode d'habillage et le rectangle de délimitation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet [Image](../../com.aspose.imaging/image) avec lequel cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) remplit les intérieurs. |
| wrapMode | int | Une énumération [WrapMode](../../com.aspose.imaging/wrapmode) qui spécifie comment cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) est carrelé. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Une structure [Rectangle](../../com.aspose.imaging/rectangle) qui représente le rectangle englobant de cet objet [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée, le mode d'habillage et le rectangle de délimitation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet `Aspose.Imaging.Image` avec lequel cet objet `Aspose.Imaging.Brushes.TextureBrush` remplit les intérieurs. |
| wrapMode | int | Une énumération `Aspose.Imaging.WrapMode` qui spécifie comment cet objet `Aspose.Imaging.Brushes.TextureBrush` est carrelé. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure `Aspose.Imaging.RectangleF` qui représente le rectangle englobant de cet objet `Aspose.Imaging.Brushes.TextureBrush`. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Initialise une nouvelle instance de la classe `Aspose.Imaging.Brushes.TextureBrush` qui utilise l'image spécifiée, le rectangle de délimitation et les attributs d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'objet `Aspose.Imaging.Image` avec lequel cet objet `Aspose.Imaging.Brushes.TextureBrush` remplit les intérieurs. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure `Aspose.Imaging.RectangleF` qui représente le rectangle englobant de cet objet `Aspose.Imaging.Brushes.TextureBrush`. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | Un objet `com.aspose.imaging.ImageAttributes` qui contient des informations supplémentaires sur l'image utilisée par cet objet `Aspose.Imaging.Brushes.TextureBrush`. |

### getImage() {#getImage--}
```
public Image getImage()
```


Obtient l'objet `com.aspose.imaging.Image` associé à cet objet `com.aspose.imaging.brushes.TextureBrush`.

Valeur : Un objet `com.aspose.imaging.Image` qui représente l'image avec laquelle cet objet `com.aspose.imaging.brushes.TextureBrush` remplit les formes.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Obtient les `ImageAttributes` associés à ce `TextureBrush`.

Valeur : les `ImageAttributes`.

**Returns:**
[ImageAttributes](../../com.aspose.imaging/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Obtient le `Rectangle` associé à ce `TextureBrush`.

Valeur : le `Rectangle`.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
