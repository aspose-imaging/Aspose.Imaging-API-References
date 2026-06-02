---
title: "GifFrameBlock"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كتلة إطار GIF."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

كتلة إطار GIF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | تسمية امتداد الكتلة. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | حجم موصّف الصورة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | يحصل على لوحة الألوان المرتبطة. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | ينشئ العلامات. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getFrameTime()](#getFrameTime--) | يحصل على المدة. |
| [setFrameTime(int value)](#setFrameTime-int-) | يضبط المدة. |
| [getInterlaced()](#getInterlaced--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `GifFrameBlock` متشابك. |
| [isInterlaced()](#isInterlaced--) | يحصل على قيمة تشير إلى ما إذا كانت نسخة الصورة هذه متشابكة. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `GifFrameBlock` متشابك. |
| [isPaletteSorted()](#isPaletteSorted--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان مرتبة. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان مرتبة. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | يحصل أو يضبط بتات إطار GIF لكل بكسل. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | يحصل أو يضبط بتات إطار GIF لكل بكسل. |
| [getLeft()](#getLeft--) | يحصل أو يضبط موقع الصورة اليساري. |
| [setLeft(int value)](#setLeft-int-) | يحصل أو يضبط موقع الصورة اليساري. |
| [getTop()](#getTop--) | يحصل أو يضبط موقع الصورة العلوي. |
| [setTop(int value)](#setTop-int-) | يحصل أو يضبط موقع الصورة العلوي. |
| [getFrameTop()](#getFrameTop--) | يحوّل إلى p. |
| [getFrameLeft()](#getFrameLeft--) | يحصل على اليسار. |
| [getDisposalMethod()](#getDisposalMethod--) | يحصل على طريقة التخلص. |
| [getFlags()](#getFlags--) | يحصل أو يضبط العلامات. |
| [setFlags(byte value)](#setFlags-byte-) | يحصل أو يضبط العلامات. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | يحصل على قيمة تشير إلى ما إذا كان [use alpha blending]. |
| [getControlBlock()](#getControlBlock--) | يحصل على كتلة التحكم الرسومية المرتبطة بهذه الكتلة. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كان كتلة الإطار تحتوي على لون شفاف. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على اللون الشفاف لكتلة الإطار. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يحصل على قيمة تشير إلى ما إذا كان كتلة الإطار تحتوي على لون شفاف. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | يحصل على اللون الشفاف لكتلة الإطار. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على قيمة لون الخلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يضبط قيمة لون الخلفية. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط سطوع الصورة. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [getFullFrame()](#getFullFrame--) | يحصل على الإطار الكامل. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يعيد تحجيم هذا [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) المثيل. |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |
| العرض | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |
| العرض | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |
| isPaletteSorted | boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكًا. |
| bitsPerPixel | byte | عدد البتات لكل بكسل. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لتتهيئة بيانات بكسل الإطار ولوحة الألوان بها. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لتتهيئة بيانات بكسل الإطار ولوحة الألوان بها. |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لتتهيئة بيانات بكسل الإطار ولوحة الألوان بها. |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |
| isPaletteSorted | boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكًا. |
| lzwCodeSize | byte | عدد البتات لكل بكسل. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | دفق التحميل للصورة وتتهيئة بيانات بكسل الإطار ولوحة الألوان باستخدامه. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | دفق التحميل للصورة وتتهيئة بيانات بكسل الإطار ولوحة الألوان باستخدامه. |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | دفق التحميل للصورة وتتهيئة بيانات بكسل الإطار ولوحة الألوان باستخدامه. |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |
| isPaletteSorted | boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكًا. |
| lzwCodeSize | byte | عدد البتات لكل بكسل. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل الصورة وتتهيئة بيانات بكسل الإطار ولوحة الألوان باستخدامه. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل الصورة وتتهيئة بيانات بكسل الإطار ولوحة الألوان باستخدامه. |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


ينشئ مثيلاً جديدًا من الفئة `GifFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل الصورة وتتهيئة بيانات بكسل الإطار ولوحة الألوان باستخدامه. |
| يسار | int | موضع الصورة اليساري. |
| أعلى | int | موضع الصورة العلوي. |
| isPaletteSorted | boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكًا. |
| lzwCodeSize | byte | عدد البتات لكل بكسل. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


تسمية امتداد الكتلة.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


حجم موصّف الصورة.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


يحصل على لوحة الألوان المرتبطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الإطار. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الحاوية. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


ينشئ العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |
| isPaletteSorted | boolean | إذا تم تعيينه إلى `true` يتم فرز الألوان في لوحة الألوان. |
| isGifFrameInterlaced | boolean | إذا تم تعيينه إلى `true` تكون صورة إطار GIF متشابكة. |

**Returns:**
byte - العلامات التي تم إنشاؤها.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يحصل على قيمة تنسيق الملف

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

**Returns:**
int - عرض الصورة.
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


يحصل على المدة.

القيمة: المدة بالمللي ثانية.

**Returns:**
int - المدة.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


يضبط المدة.

القيمة: المدة بالمللي ثانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | المدة. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `GifFrameBlock` متشابك.

**Returns:**
boolean - `true` إذا كان متشابكًا؛ وإلا `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


يحصل على قيمة تشير إلى ما إذا كانت نسخة الصورة هذه متشابكة.

القيمة: `true` إذا كانت نسخة الصورة هذه متشابكة؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت نسخة الصورة هذه متشابكة.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `GifFrameBlock` متشابك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا كان متشابكًا؛ وإلا `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان مرتبة.

**Returns:**
boolean - `true` إذا كانت لوحة الألوان مرتبة؛ وإلا `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان مرتبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا كانت لوحة الألوان مرتبة؛ وإلا `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


يحصل أو يضبط بتات إطار GIF لكل بكسل.

**Returns:**
byte - بتات إطار GIF لكل بكسل.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


يحصل أو يضبط بتات إطار GIF لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | بتات إطار GIF لكل بكسل. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


يحصل أو يضبط موقع الصورة اليساري.

**Returns:**
int - موقع الصورة الأيسر.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


يحصل أو يضبط موقع الصورة اليساري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | موقع الصورة الأيسر. |

### getTop() {#getTop--}
```
public int getTop()
```


يحصل أو يضبط موقع الصورة العلوي.

**Returns:**
int - موقع الصورة العلوي.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


يحصل أو يضبط موقع الصورة العلوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | موقع الصورة العلوي. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


يحوّل إلى p.

القيمة: الأعلى.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


يحصل على اليسار.

القيمة: اليسار.

**Returns:**
int - اليسار.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


يحصل على طريقة التخلص.

**Returns:**
int - طريقة التخلص.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


يحصل أو يضبط العلامات.

**Returns:**
byte - العلامات.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


يحصل أو يضبط العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | العلامات. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


يحصل على قيمة تشير إلى ما إذا كان [use alpha blending].

القيمة: `true` إذا [use alpha blending]؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان [use alpha blending].
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


يحصل على كتلة التحكم الرسومية المرتبطة بهذه الكتلة.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كان كتلة الإطار تحتوي على لون شفاف.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


يحصل على اللون الشفاف لكتلة الإطار.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


يحصل على قيمة تشير إلى ما إذا كان كتلة الإطار تحتوي على لون شفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


يحصل على اللون الشفاف لكتلة الإطار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على قيمة لون الخلفية.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يضبط قيمة لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | قيمة للون الخلفية. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


ضبط سطوع الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oldColorArgb | int | قيمة ARGB للون القديم التي سيتم استبدالها. |
| oldColorDiff | byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال اللون القديم بها. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


يستبدل جميع الألوان غير الشفافة باللون الجديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة بها. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


يحصل على الإطار الكامل.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


يعيد تحجيم هذا [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) المثيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |

