---
title: "PsdOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إنشاء صور وثيقة فوتوشوب PSD باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تقدم خيارات متعددة مع إصدارات تنسيق مختلفة وطرق ضغط ووضعيات ألوان وعدد البتات لكل قناة لون."
type: docs
weight: 40
url: /ar/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

إنشاء صور وثيقة فوتوشوب (PSD) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع خيارات متعددة تشمل إصدارات تنسيق مختلفة، وطرق ضغط، ووضعيات ألوان، وعدد البتات لكل قناة لون. التعامل بسلاسة مع حاويات بيانات التعريف XMP، مما يضمن معالجة شاملة للصور باستخدام ميزات تنسيق PSD مثل طبقات الصورة، أقنعة الطبقة، ومعلومات الملف للتخصيص والإبداع في تصاميمك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | ينشئ مثيلاً جديدًا من الفئة `PsdOptions`. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | ينشئ مثيلاً جديدًا من الفئة `PsdOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | احصل أو اضبط حاوية بيانات XMP |
| [getVersion()](#getVersion--) | يحصل أو يضبط إصدار ملف PSD. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يضبط إصدار ملف PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | يحصل أو يضبط طريقة ضغط PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | يحصل أو يضبط طريقة ضغط PSD. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على إصدار تنسيق الملف. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | يضبط إصدار تنسيق الملف. |
| [getColorMode()](#getColorMode--) | يحصل أو يضبط وضع لون PSD. |
| [setColorMode(short value)](#setColorMode-short-) | يحصل أو يضبط وضع لون PSD. |
| [getChannelBitsCount()](#getChannelBitsCount--) | يحصل أو يضبط عدد البتات لكل قناة لون. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | يحصل أو يضبط عدد البتات لكل قناة لون. |
| [getChannelsCount()](#getChannelsCount--) | يحصل على عدد قنوات اللون. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | يضبط عدد قنوات اللون. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | يحصل على قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فيها فتحها في Adobe Photoshop بعد المعالجة (غالبًا بسبب طبقات النص المرتبطة بخطوط مفقودة). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | يضبط قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فيها فتحها في Adobe Photoshop بعد المعالجة (غالبًا بسبب طبقات النص المرتبطة بخطوط مفقودة). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | يحصل على قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | يضبط قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى. |
| [getVectorizationOptions()](#getVectorizationOptions--) | يحصل على خيارات تحويل PSD إلى متجهات. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | يضبط خيارات تحويل PSD إلى متجهات. |

## Example: This example demonstrates the use of Aspose.
يوضح هذا المثال كيفية استخدام Aspose.Imaging لواجهة برمجة تطبيقات Java لتحويل الصور إلى تنسيق PSD. لتحقيق هذا الهدف، يقوم المثال بتحميل صورة موجودة ثم حفظها مرة أخرى بتنسيق PSD.
``` java

// إنشاء نسخة من فئة الصورة وتهيئتها بملف موجود عبر مسار الملف.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // إنشاء نسخة من فئة PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // تعيين CompressionMethod إلى RLE.
    // ملاحظة: CompressionMethod المدعومة الأخرى هي CompressionMethod.RAW [بدون ضغط].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // تعيين ColorMode إلى GrayScale.
    // ملاحظة: ColorModes المدعومة الأخرى هي ColorModes.Bitmap و ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // حفظ الصورة على القرص باستخدام إعدادات PsdOptions المقدمة.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليين فقط. سيتم عرض هاتين الصفحتين كطبقات في ملف PSD الناتج.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


ينشئ مثيلاً جديدًا من الفئة `PsdOptions`.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


ينشئ مثيلاً جديدًا من الفئة `PsdOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | الخيارات. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


احصل أو اضبط حاوية بيانات XMP

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يحصل أو يضبط إصدار ملف PSD.

القيمة: إصدار ملف PSD.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يحصل أو يضبط إصدار ملف PSD.

القيمة: إصدار ملف PSD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // تعريف تدرج خطي أزرق شفاف.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // ملء صورة PNG بالتدرج الخطى الأزرق الشفاف.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // سيتم استخدام الخيارات التالية لحفظ صورة PNG بتنسيق PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // عدد البتات لكل قناة.
    saveOptions.setChannelBitsCount((byte) 8);

    // عدد القنوات. قناة واحدة لكل مكوّن لوني R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // وضع اللون
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // بدون ضغط.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // الإصدار الافتراضي هو 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // يسمح ضغط RLE بتقليل حجم الصورة الناتجة.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // قد يبدو الإخراج هكذا:
    // حجم صورة PSD مع ضغط RAW: 40090.
    // حجم صورة PSD مع ضغط RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


يحصل أو يضبط طريقة ضغط PSD.

القيمة: طريقة الضغط.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


يحصل أو يضبط طريقة ضغط PSD.

القيمة: طريقة الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |


**Example: This example demonstrates the use of Aspose.**
يوضح هذا المثال كيفية استخدام Aspose.Imaging لواجهة برمجة تطبيقات Java لتحويل الصور إلى تنسيق PSD. لتحقيق هذا الهدف، يقوم المثال بتحميل صورة موجودة ثم حفظها مرة أخرى بتنسيق PSD.
``` java

// إنشاء نسخة من فئة الصورة وتهيئتها بملف موجود عبر مسار الملف.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // إنشاء نسخة من فئة PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // تعيين CompressionMethod إلى RLE.
    // ملاحظة: CompressionMethod المدعومة الأخرى هي CompressionMethod.RAW [بدون ضغط].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // تعيين ColorMode إلى GrayScale.
    // ملاحظة: ColorModes المدعومة الأخرى هي ColorModes.Bitmap و ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // حفظ الصورة على القرص باستخدام إعدادات PsdOptions المقدمة.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


يحصل على إصدار تنسيق الملف. يمكن أن يكون PSD أو PSB.

القيمة: إصدار تنسيق الملف.

**Returns:**
byte - نسخة تنسيق الملف.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


يضبط نسخة تنسيق الملف. يمكن أن تكون PSD أو PSB.

القيمة: إصدار تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | نسخة تنسيق الملف. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


يحصل أو يضبط وضع لون PSD.

القيمة: وضع اللون.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


يحصل أو يضبط وضع لون PSD.

القيمة: وضع اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |


**Example: This example demonstrates the use of Aspose.**
يوضح هذا المثال كيفية استخدام Aspose.Imaging لواجهة برمجة تطبيقات Java لتحويل الصور إلى تنسيق PSD. لتحقيق هذا الهدف، يقوم المثال بتحميل صورة موجودة ثم حفظها مرة أخرى بتنسيق PSD.
``` java

// إنشاء نسخة من فئة الصورة وتهيئتها بملف موجود عبر مسار الملف.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // إنشاء نسخة من فئة PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // تعيين CompressionMethod إلى RLE.
    // ملاحظة: CompressionMethod المدعومة الأخرى هي CompressionMethod.RAW [بدون ضغط].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // تعيين ColorMode إلى GrayScale.
    // ملاحظة: ColorModes المدعومة الأخرى هي ColorModes.Bitmap و ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // حفظ الصورة على القرص باستخدام إعدادات PsdOptions المقدمة.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


يحصل أو يضبط عدد البتات لكل قناة لون.

القيمة: عدد البتات لكل قناة لونية.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


يحصل أو يضبط عدد البتات لكل قناة لون.

القيمة: عدد البتات لكل قناة لونية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // تعريف تدرج خطي أزرق شفاف.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // ملء صورة PNG بالتدرج الخطى الأزرق الشفاف.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // سيتم استخدام الخيارات التالية لحفظ صورة PNG بتنسيق PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // عدد البتات لكل قناة.
    saveOptions.setChannelBitsCount((byte) 8);

    // عدد القنوات. قناة واحدة لكل مكوّن لوني R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // وضع اللون
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // بدون ضغط.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // الإصدار الافتراضي هو 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // يسمح ضغط RLE بتقليل حجم الصورة الناتجة.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // قد يبدو الإخراج هكذا:
    // حجم صورة PSD مع ضغط RAW: 40090.
    // حجم صورة PSD مع ضغط RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


يحصل على عدد قنوات اللون.

**Returns:**
short - عدد قنوات اللون.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


يضبط عدد قنوات اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short | عدد قنوات اللون. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // تعريف تدرج خطي أزرق شفاف.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // ملء صورة PNG بالتدرج الخطى الأزرق الشفاف.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // سيتم استخدام الخيارات التالية لحفظ صورة PNG بتنسيق PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // عدد البتات لكل قناة.
    saveOptions.setChannelBitsCount((byte) 8);

    // عدد القنوات. قناة واحدة لكل مكوّن لوني R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // وضع اللون
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // بدون ضغط.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // الإصدار الافتراضي هو 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // يسمح ضغط RLE بتقليل حجم الصورة الناتجة.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // قد يبدو الإخراج هكذا:
    // حجم صورة PSD مع ضغط RAW: 40090.
    // حجم صورة PSD مع ضغط RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


يحصل على قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، وفي الحالة الوحيدة التي لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). بعد استخدام هذا الخيار، يحتاج المستخدم إلى تنفيذ التالي في الملف المفتوح في Photoshop: القائمة "Text" -> "Process absent fonts". بعد هذه العملية سيظهر جميع النص مرة أخرى. يرجى ملاحظة أن هذه العملية قد تسبب بعض التغييرات النهائية في التخطيط.

**Returns:**
boolean - `true` إذا [remove global text engine resource]؛ وإلا `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، وفي الحالة الوحيدة التي لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). بعد استخدام هذا الخيار، يحتاج المستخدم إلى تنفيذ التالي في الملف المفتوح في Photoshop: القائمة "Text" -> "Process absent fonts". بعد هذه العملية سيظهر جميع النص مرة أخرى. يرجى ملاحظة أن هذه العملية قد تسبب بعض التغييرات النهائية في التخطيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا [remove global text engine resource]؛ وإلا `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


يحصل على قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى.

**Returns:**
boolean - `true` إذا [refresh image preview data]؛ وإلا `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا [refresh image preview data]؛ وإلا `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


يحصل على خيارات تحويل PSD إلى متجهات.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


يضبط خيارات تحويل PSD إلى متجهات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | خيارات تحويل PSD إلى متجهات. |

