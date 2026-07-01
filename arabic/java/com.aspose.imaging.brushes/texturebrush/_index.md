---
title: "TextureBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كل خاصية من فئة Aspose.Imaging.Brushes.TextureBrush هي كائن Aspose.Imaging.Brush يستخدم صورة لملء داخل الشكل."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.brushes/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

كل خاصية من فئة `Aspose.Imaging.Brushes.TextureBrush` هي كائن `Aspose.Imaging.Brush` يستخدم صورة لملء داخل الشكل. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.imaging.Image-) | يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.imaging.Image-int-) | يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-) | يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-) | يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-) | يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-) | يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getImage()](#getImage--) | يحصل على كائن `com.aspose.imaging.Image` المرتبط بهذا الكائن `com.aspose.imaging.brushes.TextureBrush`. |
| [getImageAttributes()](#getImageAttributes--) | يحصل على `ImageAttributes` المرتبط بهذا الـ `TextureBrush`. |
| [getImageRectangle()](#getImageRectangle--) | يحصل على `Rectangle` المرتبط بهذا الـ `TextureBrush`. |
### TextureBrush(Image image) {#TextureBrush-com.aspose.imaging.Image-}
```
public TextureBrush(Image image)
```


يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن `Aspose.Imaging.Image` الذي يستخدمه هذا الكائن `Aspose.Imaging.Brushes.TextureBrush` لملء الداخل. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.imaging.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن `Aspose.Imaging.Image` الذي يستخدمه هذا الكائن `Aspose.Imaging.Brushes.TextureBrush` لملء الداخل. |
| wrapMode | int | تعداد `Aspose.Imaging.WrapMode` يحدد كيفية تجانب هذا الكائن `Aspose.Imaging.Brushes.TextureBrush`. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن [Image](../../com.aspose.imaging/image) الذي يستخدمه هذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) لملء الداخل. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل [Rectangle](../../com.aspose.imaging/rectangle) يمثل المستطيل المحيط لهذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | كائن [ImageAttributes](../../com.aspose.imaging/imageattributes) يحتوي على معلومات إضافية حول الصورة المستخدمة بواسطة هذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن [Image](../../com.aspose.imaging/image) الذي يستخدمه هذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) لملء الداخل. |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل [Rectangle](../../com.aspose.imaging/rectangle) يمثل المستطيل المحيط لهذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة والمستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن [Image](../../com.aspose.imaging/image) الذي يستخدمه هذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) لملء الداخل. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل [RectangleF](../../com.aspose.imaging/rectanglef) يمثل المستطيل المحيط لهذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن [Image](../../com.aspose.imaging/image) الذي يستخدمه هذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush) لملء الداخل. |
| wrapMode | int | تعداد [WrapMode](../../com.aspose.imaging/wrapmode) يحدد كيفية تجانب هذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |
| destinationRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل [Rectangle](../../com.aspose.imaging/rectangle) يمثل المستطيل المحيط لهذا الكائن [TextureBrush](../../com.aspose.imaging.brushes/texturebrush). |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.imaging.Image-int-com.aspose.imaging.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن `Aspose.Imaging.Image` الذي يستخدمه هذا الكائن `Aspose.Imaging.Brushes.TextureBrush` لملء الداخل. |
| wrapMode | int | تعداد `Aspose.Imaging.WrapMode` يحدد كيفية تجانب هذا الكائن `Aspose.Imaging.Brushes.TextureBrush`. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `Aspose.Imaging.RectangleF` يمثل المستطيل المحيط لهذا الكائن `Aspose.Imaging.Brushes.TextureBrush`. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


يقوم بتهيئة نسخة جديدة من الفئة `Aspose.Imaging.Brushes.TextureBrush` التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | كائن `Aspose.Imaging.Image` الذي يستخدمه هذا الكائن `Aspose.Imaging.Brushes.TextureBrush` لملء الداخل. |
| destinationRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `Aspose.Imaging.RectangleF` يمثل المستطيل المحيط لهذا الكائن `Aspose.Imaging.Brushes.TextureBrush`. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | كائن `com.aspose.imaging.ImageAttributes` يحتوي على معلومات إضافية حول الصورة المستخدمة بواسطة هذا الكائن `Aspose.Imaging.Brushes.TextureBrush`. |

### getImage() {#getImage--}
```
public Image getImage()
```


يحصل على كائن `com.aspose.imaging.Image` المرتبط بهذا الكائن `com.aspose.imaging.brushes.TextureBrush`.

القيمة: كائن `com.aspose.imaging.Image` يمثل الصورة التي يستخدمها هذا الكائن `com.aspose.imaging.brushes.TextureBrush` لملء الأشكال.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


يحصل على `ImageAttributes` المرتبط بهذا الـ `TextureBrush`.

القيمة: الـ `ImageAttributes`.

**Returns:**
[ImageAttributes](../../com.aspose.imaging/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


يحصل على `Rectangle` المرتبط بهذا الـ `TextureBrush`.

القيمة: الـ `Rectangle`.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
