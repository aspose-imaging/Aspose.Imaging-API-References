---
title: TextureBrush
second_title: Aspose.Imaging for Java API Reference
description: Each property of the Aspose.Imaging.Brushes.TextureBrush class is a Aspose.Imaging.Brush object that uses an image to fill the interior of a shape.
type: docs
weight: 18
url: /com.aspose.imaging.brushes/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Each property of the `Aspose.Imaging.Brushes.TextureBrush` class is a `Aspose.Imaging.Brush` object that uses an image to fill the interior of a shape. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.imaging.Image-) | Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.imaging.Image-int-) | Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image and wrap mode. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-) | Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image and bounding rectangle. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image and bounding rectangle. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-) | Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-) | Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-) | Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image, bounding rectangle, and image attributes. |
## Methods

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | Gets the `com.aspose.imaging.Image` object associated with this `com.aspose.imaging.brushes.TextureBrush` object. |
| [getImageAttributes()](#getImageAttributes--) | Gets the `ImageAttributes` associated with this `TextureBrush`. |
| [getImageRectangle()](#getImageRectangle--) | Gets the `Rectangle` associated with this `TextureBrush`. |
### TextureBrush(Image image) {#TextureBrush-com.aspose.imaging.Image-}
```
public TextureBrush(Image image)
```


Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Aspose.Imaging.Image` object with which this `Aspose.Imaging.Brushes.TextureBrush` object fills interiors. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.imaging.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Aspose.Imaging.Image` object with which this `Aspose.Imaging.Brushes.TextureBrush` object fills interiors. |
| wrapMode | int | A `Aspose.Imaging.WrapMode` enumeration that specifies how this `Aspose.Imaging.Brushes.TextureBrush` object is tiled. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The [Image](../../com.aspose.imaging/image) object with which this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object fills interiors. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | A [Rectangle](../../com.aspose.imaging/rectangle) structure that represents the bounding rectangle for this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | An [ImageAttributes](../../com.aspose.imaging/imageattributes) object that contains additional information about the image used by this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The [Image](../../com.aspose.imaging/image) object with which this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object fills interiors. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | A [Rectangle](../../com.aspose.imaging/rectangle) structure that represents the bounding rectangle for this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The [Image](../../com.aspose.imaging/image) object with which this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object fills interiors. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | A [RectangleF](../../com.aspose.imaging/rectanglef) structure that represents the bounding rectangle for this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Initializes a new instance of the [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The [Image](../../com.aspose.imaging/image) object with which this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object fills interiors. |
| wrapMode | int | A [WrapMode](../../com.aspose.imaging/wrapmode) enumeration that specifies how this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object is tiled. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | A [Rectangle](../../com.aspose.imaging/rectangle) structure that represents the bounding rectangle for this [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) object. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Aspose.Imaging.Image` object with which this `Aspose.Imaging.Brushes.TextureBrush` object fills interiors. |
| wrapMode | int | A `Aspose.Imaging.WrapMode` enumeration that specifies how this `Aspose.Imaging.Brushes.TextureBrush` object is tiled. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | A `Aspose.Imaging.RectangleF` structure that represents the bounding rectangle for this `Aspose.Imaging.Brushes.TextureBrush` object. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Initializes a new instance of the `Aspose.Imaging.Brushes.TextureBrush` class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Aspose.Imaging.Image` object with which this `Aspose.Imaging.Brushes.TextureBrush` object fills interiors. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | A `Aspose.Imaging.RectangleF` structure that represents the bounding rectangle for this `Aspose.Imaging.Brushes.TextureBrush` object. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | An `com.aspose.imaging.ImageAttributes` object that contains additional information about the image used by this `Aspose.Imaging.Brushes.TextureBrush` object. |

### getImage() {#getImage--}
```
public Image getImage()
```


Gets the `com.aspose.imaging.Image` object associated with this `com.aspose.imaging.brushes.TextureBrush` object.

Value: An `com.aspose.imaging.Image` object that represents the image with which this `com.aspose.imaging.brushes.TextureBrush` object fills shapes.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Gets the `ImageAttributes` associated with this `TextureBrush`.

Value: The `ImageAttributes`.

**Returns:**
[ImageAttributes](../../com.aspose.imaging/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Gets the `Rectangle` associated with this `TextureBrush`.

Value: The `Rectangle`.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
