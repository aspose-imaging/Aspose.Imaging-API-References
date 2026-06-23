---
title: "WebPFrameBlock"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثّل سجل مفتاح فتح كتل webp."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

يمثّل سجل مفتاح فتح كتل webp.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | ينشئ نسخة جديدة من الفئة `WebPFrameBlock`. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | ينشئ نسخة جديدة من الفئة `WebPFrameBlock`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [hasAlpha()](#hasAlpha--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| [getDuration()](#getDuration--) | يحصل أو يضبط مدة الإطار. |
| [setDuration(short value)](#setDuration-short-) | يحصل أو يضبط مدة الإطار. |
| [getLeft()](#getLeft--) | يحصل أو يضبط موضع الإطار من اليسار. |
| [setLeft(short value)](#setLeft-short-) | يحصل أو يضبط موضع الإطار من اليسار. |
| [getTop()](#getTop--) | يحصل أو يضبط موضع الإطار من الأعلى. |
| [setTop(short value)](#setTop-short-) | يحصل أو يضبط موضع الإطار من الأعلى. |
| [getFrameTime()](#getFrameTime--) | يحصل على مدة الإطار. |
| [getFrameTop()](#getFrameTop--) | يحصل على إزاحة أعلى الإطار. |
| [getFrameLeft()](#getFrameLeft--) | يحصل على إزاحة يسار الإطار. |
| [getDisposalMethod()](#getDisposalMethod--) | يحصل على طريقة التخلص. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | يضبط طريقة التخلص. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | يحصل على القيمة التي تشير إلى ما إذا كان الإطار الحالي يدمج مع قيم ألفا للإطار السابق. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | يضبط القيمة التي تشير إلى ما إذا كان الإطار الحالي يدمج مع قيم ألفا للإطار السابق. |
| [getFullFrame()](#getFullFrame--) | يحصل على الإطار الكامل. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


ينشئ نسخة جديدة من الفئة `WebPFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


ينشئ نسخة جديدة من الفئة `WebPFrameBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | العرض. |
| height | int | الارتفاع. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

**Returns:**
int - عرض الصورة.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا.

**Returns:**
منطقي - `true` إذا كان لهذه الحالة ألفا؛ وإلا `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // إذا كان إطار TIFF النشط يحتوي على قناة ألفا، فسيُعتبر أن صورة TIFF بأكملها تحتوي على قناة ألفا.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


يحصل أو يضبط مدة الإطار.

**Returns:**
short - المدة.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


يحصل أو يضبط مدة الإطار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير | المدة. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


يحصل أو يضبط موضع الإطار من اليسار.

**Returns:**
short - اليسار.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


يحصل أو يضبط موضع الإطار من اليسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير | اليسار. |

### getTop() {#getTop--}
```
public short getTop()
```


يحصل أو يضبط موضع الإطار من الأعلى.

**Returns:**
short - الأعلى.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


يحصل أو يضبط موضع الإطار من الأعلى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير | الأعلى. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


يحصل على مدة الإطار.

**Returns:**
int - مدة الإطار.
### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


يحصل على إزاحة أعلى الإطار.

**Returns:**
int - إزاحة أعلى الإطار.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


يحصل على إزاحة يسار الإطار.

**Returns:**
int - إزاحة يسار الإطار.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


يحصل على طريقة التخلص.

**Returns:**
عدد صحيح - طريقة التخلص.
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


يضبط طريقة التخلص.

القيمة: طريقة التخلص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | طريقة التخلص. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


يحصل على القيمة التي تشير إلى ما إذا كان الإطار الحالي يدمج مع قيم ألفا للإطار السابق.

القيمة: `` إذا كان هذا الإطار يستخدم الدمج ألفا؛ وإلا، ``.

**Returns:**
boolean - القيمة التي تشير إلى ما إذا كان الإطار الحالي يتم دمجه مع قيم ألفا للإطار السابق.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


يضبط القيمة التي تشير إلى ما إذا كان الإطار الحالي يدمج مع قيم ألفا للإطار السابق.

القيمة: `` إذا كان هذا الإطار يستخدم الدمج ألفا؛ وإلا، ``.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | القيمة التي تشير إلى ما إذا كان الإطار الحالي يتم دمجه مع قيم ألفا للإطار السابق. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


يحصل على الإطار الكامل.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
