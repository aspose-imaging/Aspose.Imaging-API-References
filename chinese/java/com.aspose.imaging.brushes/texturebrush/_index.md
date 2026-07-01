---
title: "TextureBrush"
second_title: "Aspose.Imaging for Java API 参考"
description: "Aspose.Imaging.Brushes.TextureBrush 类的每个属性都是一个 Aspose.Imaging.Brush 对象，用于使用图像填充形状的内部。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.brushes/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

`Aspose.Imaging.Brushes.TextureBrush` 类的每个属性都是一个 `Aspose.Imaging.Brush` 对象，用于使用图像填充形状的内部。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.imaging.Image-) | 初始化使用指定图像的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。 |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.imaging.Image-int-) | 初始化使用指定图像和平铺模式的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。 |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-) | 初始化使用指定图像、边界矩形和图像属性的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | 初始化使用指定图像和边界矩形的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | 初始化使用指定图像和边界矩形的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-) | 初始化使用指定图像、平铺模式和边界矩形的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。 |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-) | 初始化使用指定图像、平铺模式和边界矩形的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。 |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-) | 初始化使用指定图像、边界矩形和图像属性的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImage()](#getImage--) | 获取与此 `com.aspose.imaging.brushes.TextureBrush` 对象关联的 `com.aspose.imaging.Image` 对象。 |
| [getImageAttributes()](#getImageAttributes--) | 获取与此 `TextureBrush` 关联的 `ImageAttributes`。 |
| [getImageRectangle()](#getImageRectangle--) | 获取与此 `TextureBrush` 关联的 `Rectangle`。 |
### TextureBrush(Image image) {#TextureBrush-com.aspose.imaging.Image-}
```
public TextureBrush(Image image)
```


初始化使用指定图像的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 `Aspose.Imaging.Brushes.TextureBrush` 对象用于填充内部的 `Aspose.Imaging.Image` 对象。 |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.imaging.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


初始化使用指定图像和平铺模式的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 `Aspose.Imaging.Brushes.TextureBrush` 对象用于填充内部的 `Aspose.Imaging.Image` 对象。 |
| wrapMode | int | 一个指定此 `Aspose.Imaging.Brushes.TextureBrush` 对象平铺方式的 `Aspose.Imaging.WrapMode` 枚举。 |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


初始化使用指定图像、边界矩形和图像属性的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象用于填充内部的 [Image](../../com.aspose.imaging/image) 对象。 |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 一个表示此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象的边界矩形的 [Rectangle](../../com.aspose.imaging/rectangle) 结构。 |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | 一个包含此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象使用的图像的附加信息的 [ImageAttributes](../../com.aspose.imaging/imageattributes) 对象。 |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


初始化使用指定图像和边界矩形的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象用于填充内部的 [Image](../../com.aspose.imaging/image) 对象。 |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 一个表示此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象的边界矩形的 [Rectangle](../../com.aspose.imaging/rectangle) 结构。 |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


初始化使用指定图像和边界矩形的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象用于填充内部的 [Image](../../com.aspose.imaging/image) 对象。 |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象的边界矩形的 [RectangleF](../../com.aspose.imaging/rectanglef) 结构。 |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


初始化使用指定图像、平铺模式和边界矩形的 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象用于填充内部的 [Image](../../com.aspose.imaging/image) 对象。 |
| wrapMode | int | 一个指定此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象平铺方式的 [WrapMode](../../com.aspose.imaging/wrapmode) 枚举。 |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 一个表示此 [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) 对象的边界矩形的 [Rectangle](../../com.aspose.imaging/rectangle) 结构。 |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


初始化使用指定图像、平铺模式和边界矩形的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 `Aspose.Imaging.Brushes.TextureBrush` 对象用于填充内部的 `Aspose.Imaging.Image` 对象。 |
| wrapMode | int | 一个指定此 `Aspose.Imaging.Brushes.TextureBrush` 对象平铺方式的 `Aspose.Imaging.WrapMode` 枚举。 |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示此 `Aspose.Imaging.Brushes.TextureBrush` 对象的边界矩形的 `Aspose.Imaging.RectangleF` 结构。 |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


初始化使用指定图像、边界矩形和图像属性的 `Aspose.Imaging.Brushes.TextureBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 此 `Aspose.Imaging.Brushes.TextureBrush` 对象用于填充内部的 `Aspose.Imaging.Image` 对象。 |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示此 `Aspose.Imaging.Brushes.TextureBrush` 对象的边界矩形的 `Aspose.Imaging.RectangleF` 结构。 |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | 一个包含此 `Aspose.Imaging.Brushes.TextureBrush` 对象使用的图像的附加信息的 `com.aspose.imaging.ImageAttributes` 对象。 |

### getImage() {#getImage--}
```
public Image getImage()
```


获取与此 `com.aspose.imaging.brushes.TextureBrush` 对象关联的 `com.aspose.imaging.Image` 对象。

值：一个表示此 `com.aspose.imaging.brushes.TextureBrush` 对象用于填充形状的图像的 `com.aspose.imaging.Image` 对象。

**Returns:**
[Image](../../com.aspose.imaging/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


获取与此 `TextureBrush` 关联的 `ImageAttributes`。

值：`ImageAttributes`。

**Returns:**
[ImageAttributes](../../com.aspose.imaging/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


获取与此 `TextureBrush` 关联的 `Rectangle`。

值：`Rectangle`。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
