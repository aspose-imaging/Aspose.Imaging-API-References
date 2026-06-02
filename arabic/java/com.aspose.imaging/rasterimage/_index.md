---
title: "RasterImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل صورة نقطية تدعم عمليات الرسومات النقطية."
type: docs
weight: 91
url: /ar/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

يمثل صورة نقطية تدعم عمليات الرسومات النقطية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [getUseRawData()](#getUseRawData--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [getUpdateXmpData()](#getUpdateXmpData--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | يحصل أو يضبط محول الألوان المفهرس |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | يحصل أو يضبط محول الألوان المفهرس |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | يحصل أو يضبط محول الألوان المخصص |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | يحصل أو يضبط محول الألوان المخصص |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس لوحة الألوان خارج النطاق |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس لوحة الألوان خارج النطاق |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| [getRawDataFormat()](#getRawDataFormat--) | يحصل على تنسيق البيانات الخام. |
| [getRawLineSize()](#getRawLineSize--) | يحصل على حجم السطر الخام بالبايت. |
| [isRawDataAvailable()](#isRawDataAvailable--) | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [getHorizontalResolution()](#getHorizontalResolution--) | يحصل أو يضبط الدقة الأفقية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | يحصل أو يضبط الدقة الأفقية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | يحصل أو يضبط الدقة العمودية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | يحصل أو يضبط الدقة العمودية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة من [RasterImage](../../com.aspose.imaging/rasterimage) لديها لون شفاف. |
| [hasAlpha()](#hasAlpha--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على لون الصورة الشفاف. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يضبط قيمة تشير إلى ما إذا كانت هذه الحالة من [RasterImage](../../com.aspose.imaging/rasterimage) لديها لون شفاف. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | يحصل على لون الصورة الشفاف. |
| [getImageOpacity()](#getImageOpacity--) | يحصل على شفافية هذه الصورة. |
| [removeMetadata()](#removeMetadata--) | يزيل بيانات التعريف لهذه الحالة من الصورة عن طريق ضبط قيمة `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) إلى `null`. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | يسترجع التاريخ والوقت عندما خضعت صورة المورد لأحدث تعديل. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | ينفّذ تمويهًا على الصورة الحالية. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | ينفّذ تمويهًا على الصورة الحالية. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسلات الجزئي. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسلات الجزئي. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | يحصل على مصفوفة بكسلات ARGB 32‑بت الافتراضية. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | يحصل على بكسل ARGB 32‑بت من الصورة. |
| [getPixel(int x, int y)](#getPixel-int-int-) | يحصل على بكسل الصورة. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | يضبط بكسل ARGB 32‑بت للصورة في الموضع المحدد. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | يضبط بكسل الصورة في الموضع المحدد. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | يكتب السطر الكامل للمسح إلى مؤشر سطر المسح المحدد. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | يكتب السطر الكامل للمسح إلى مؤشر سطر المسح المحدد. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | يحمّل بكسلات ARGB 32‑بت جزئيًا حسب الحزم. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | يحمّل البكسلات جزئيًا حسب الحزم. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | يحمّل بكسلات ARGB 32‑بت. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | يحمّل بكسلات ARGB 64‑بت. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | يحمّل البكسلات. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | يحمّل البكسلات بتنسيق CMYK. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | يحمّل البكسلات بتنسيق CMYK. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | يحمّل بيانات الصورة الخام باستخدام آلية المعالجة الجزئية. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | يحمّل البيانات الخام. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | يحفظ البيانات الخام. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | يحفظ بكسلات ARGB 32‑بت. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | يحفظ البكسلات. |
| [toBitmap()](#toBitmap--) | يحوّل صورة النقطية إلى bitmap. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | يحفظ البكسلات. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | يحفظ البكسلات. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | يضبط الدقة لهذه `RasterImage`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
| [autoRotate()](#autoRotate--) | يقوم تلقائيًا بتدوير الصورة بناءً على بيانات الاتجاه المستخرجة من بيانات Exif الوصفية. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | دوّر الصورة حول المركز. |
| [rotate(float angle)](#rotate-float-) | دوّر الصورة حول المركز. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا |
| [binarizeOtsu()](#binarizeOtsu--) | تحويل الصورة إلى ثنائية باستخدام عتبة Otsu |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع العتبة المستندة إلى الصورة المتكاملة |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع العتبة المستندة إلى الصورة المتكاملة |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | يمزج نسخة الصورة هذه مع صورة `overlay`. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | يمزج نسخة الصورة هذه مع صورة `overlay`. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | يمزج هذه النسخة من الصورة مع `overlay` مع قيمة ألفا == 255. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | يمزج هذه النسخة من الصورة مع `overlay`. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [normalizeHistogram()](#normalizeHistogram--) | يُعَدِّل هيستوجرام الصورة \\u2014 يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | تطبيع تلقائي متكيف للسطوع والتباين لكامل الصورة. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط سطوع الصورة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | تحسين تباين الصورة |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | إدراج توقيع رقمي يعتمد على كلمة المرور المقدمة داخل الصورة باستخدام steganography. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | ينفّذ فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقميًا، باستخدام كلمة المرور والعتبة المقدمة. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | ينفّذ فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقميًا، باستخدام كلمة المرور والعتبة المقدمة. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | تصحيح جاما للصورة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تصحيح جاما للصورة. |
| [getSkewAngle()](#getSkewAngle--) | يحصل على زاوية الميل. |
| [normalizeAngle()](#normalizeAngle--) | يعيد تطبيع الزاوية. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | يعيد تطبيع الزاوية. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | يفلتر المستطيل المحدد. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// أنشئ نسخة من GifOptions واضبط خصائصها المتنوعة بما في ذلك خاصية Source.
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// إنشاء نسخة من Image
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // احصل على بكسلات الصورة بتحديد المنطقة كحدود الصورة.
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // تكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل.
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // عيّن لون البكسل المفهرس إلى الأصفر.
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // عيّن لون البكسل المفهرس إلى الأزرق.
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // طبق تغييرات البكسل على الصورة.
    image.savePixels(image.getBounds(), pixels);

    // حفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا.

**Returns:**
منطقي - `true` إذا كان يجب ضرب مكونات الصورة مسبقًا؛ وإلا `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا كان يجب ضرب مكونات الصورة مسبقًا؛ وإلا `false`. |


**Example: The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // احفظ البكسلات لكامل الصورة.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // يتم تخزين البكسلات في الصورة الأصلية بصيغة غير مضاعفة مسبقًا.
    // يجب تحديد الخيار المقابل صراحةً للحصول على مكوّنات اللون المضاعفة مسبقًا.
    // يتم حساب مكوّنات اللون المضاعفة مسبقًا باستخدام الصيغ:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    rasterImage.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = rasterImage.loadPixels(rasterImage.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}
```

### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا.

**Returns:**
منطقي - `true` إذا تم استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا؛ وإلا `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا تم استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا؛ وإلا `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية.

**Returns:**
منطقي - `true` إذا تم تحديث بيانات XMP الوصفية؛ وإلا `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا تم تحديث بيانات XMP الوصفية؛ وإلا `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


يحصل أو يضبط محول الألوان المفهرس

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


يحصل أو يضبط محول الألوان المفهرس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | محول الألوان المفهرسة |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


يحصل أو يضبط محول الألوان المخصص

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


يحصل أو يضبط محول الألوان المخصص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | محول الألوان المخصص |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس لوحة الألوان خارج النطاق

**Returns:**
int - الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


يحصل أو يضبط فهرس الاحتياطي لاستخدامه عندما يكون فهرس لوحة الألوان خارج النطاق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة.

القيمة: `true` إذا تم استخدام اللوحة في الصورة؛ وإلا، `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


يحصل على تنسيق البيانات الخام.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// ملفات الصورة المراد تحميلها.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, القنوات المستخدمة: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, القنوات المستخدمة: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


يحصل على حجم السطر الخام بالبايت.

**Returns:**
int - حجم السطر الخام بالبايت.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا.

**Returns:**
منطقي - `true` إذا كان تحميل البيانات الخام هذا متاحًا؛ وإلا `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


يحصل أو يضبط الدقة الأفقية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`.

**Returns:**
double - الدقة الأفقية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // احصل على الدقة الأفقية والعمودية للصورة
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // قد يبدو الإخراج هكذا:
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 300.0
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 300.0
    // تعيين قيم الدقة إلى 96 نقطة في البوصة
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.0
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


يحصل أو يضبط الدقة الأفقية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | الدقة الأفقية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


يحصل أو يضبط الدقة العمودية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`.

**Returns:**
double - الدقة العمودية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // احصل على الدقة الأفقية والعمودية للصورة
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // قد يبدو الإخراج هكذا:
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 300.0
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 300.0
    // تعيين قيم الدقة إلى 96 نقطة في البوصة
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.0
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


يحصل أو يضبط الدقة العمودية، بوحدة بكسل لكل بوصة، لهذا `RasterImage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | الدقة العمودية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة من [RasterImage](../../com.aspose.imaging/rasterimage) لديها لون شفاف.

--------------------

الإصدار الأساسي يعيد فعليًا `` إذا لم يتم تجاوزها في تنفيذ محدد يدعم هذه الميزة. تُستخدم هذه الخاصية أساسًا بواسطة [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng)، [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png)، [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif)، [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) لتعيين لون شفاف إذا كانت الصورة لا تدعم الشفافية عبر قناة ألفا.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت هذه الحالة من [RasterImage](../../com.aspose.imaging/rasterimage) تحتوي على لون شفاف.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا.

**Returns:**
boolean - `true` إذا كان هذا الكائن يحتوي على ألفا؛ وإلا `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// ملفات الصورة المراد تحميلها.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, القنوات المستخدمة: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, القنوات المستخدمة: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


يحصل على لون الصورة الشفاف.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت هذه الحالة من [RasterImage](../../com.aspose.imaging/rasterimage) لديها لون شفاف.

--------------------

الإصدار الأساسي يعيد فعليًا `` إذا لم يتم تجاوزها في تنفيذ محدد يدعم هذه الميزة. تُستخدم هذه الخاصية أساسًا بواسطة [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng)، [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png)، [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif)، [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) لتعيين لون شفاف إذا كانت الصورة لا تدعم الشفافية عبر قناة ألفا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كانت هذه الحالة من [RasterImage](../../com.aspose.imaging/rasterimage) تحتوي على لون شفاف. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


يحصل على لون الصورة الشفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


يحصل على شفافية هذه الصورة.

**Returns:**
float - قيمة التعتيم بين 0.0 (شفاف تمامًا) و 1.0 (معتم تمامًا).
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


يزيل بيانات التعريف لهذه الحالة من الصورة عن طريق ضبط قيمة `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) إلى `null`.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


يسترجع التاريخ والوقت عندما خضعت صورة المورد لأحدث تعديل لها. توفر هذه الطريقة بيانات وصفية قيمة، مما يمكّن المستخدمين من تتبع وإدارة التحديثات لملف الصورة بفعالية. من خلال الوصول إلى هذه المعلومات، يمكن للمستخدمين ضمان سلامة وحداثة أصول الصور الخاصة بهم، مما يسهل اتخاذ قرارات مستنيرة بشأن استخدام الصورة وصيانتها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| useDefault | boolean | إذا تم تعيينه إلى `true` يستخدم المعلومات من FileInfo كقيمة افتراضية. |

**Returns:**
java.util.Date - التاريخ والوقت الذي تم فيه تعديل صورة المورد آخر مرة.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


ينفّذ تمويهًا على الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // قم بتنفيذ تدرّج العتبة باستخدام لوحة ألوان 4‑بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان ذات 1‑بت، 4‑بت و8‑بت فقط هي المدعومة حاليًا.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // قم بتنفيذ تدرّج Floyd باستخدام لوحة ألوان 1‑بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان ذات 1‑بت، 4‑بت و8‑بت فقط هي المدعومة حاليًا.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


ينفّذ تمويهًا على الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان المخصصة للتمويه. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسلات الجزئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للحصول على البكسلات له. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | محمل البكسلات الجزئي. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسلات الجزئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للحصول على البكسلات له. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | محمل البيانات الخام الجزئي. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | إعدادات البيانات الخام. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


يحصل على مصفوفة بكسلات ARGB 32‑بت الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للحصول على البكسلات له. |

**Returns:**
int[] - مصفوفة البكسلات الافتراضية.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


يحصل على مصفوفة البيانات الخام الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للحصول على البيانات الأولية. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | إعدادات البيانات الخام. |

**Returns:**
byte[] - مصفوفة البيانات الأولية الافتراضية.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


يحصل على بكسل ARGB 32‑بت من الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع البكسل على المحور x. |
| ص | int | موقع البكسل على المحور y. |

**Returns:**
int - بكسل ARGB 32‑بت للموقع المحدد.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // احصل على تمثيل عدد صحيح للون البكسل العلوي الأيسر في الصورة.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // للحصول على قيم مكونات اللون الفردية، قم بإزاحة قيمة اللون بعدد البتات المقابل.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// لون البكسل (0,0) هو A=255,R=0,G=0,B=0
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


يحصل على بكسل الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع البكسل على المحور x. |
| ص | int | موقع البكسل على المحور y. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // احصل على لون البكسل العلوي الأيسر في الصورة.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // احصل على قيم مكونات اللون الفردية
    int alpha = color.getA();
    int red = color.getR();
    int green = color.getG();
    int blue = color.getB();

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}
```

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


يضبط بكسل ARGB 32‑بت للصورة في الموضع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع البكسل على المحور x. |
| ص | int | موقع البكسل على المحور y. |
| argb32Color | int | بكسل ARGB 32‑بت للموقع المحدد. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // يضبط لون البكسل العلوي الأيسر.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // طريقة أخرى هي تمرير كائن من com.aspose.imaging.Color مباشرةً
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


يضبط بكسل الصورة في الموضع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع البكسل على المحور x. |
| ص | int | موقع البكسل على المحور y. |
| color | [Color](../../com.aspose.imaging/color) | لون البكسل للموقع المحدد. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // يضبط لون البكسل العلوي الأيسر.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // طريقة أخرى هي تمرير كائن من com.aspose.imaging.Color مباشرةً
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الصفري لخط المسح. |

**Returns:**
com.aspose.imaging.Color[] - مصفوفة قيم ألوان بكسلات خط المسح.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الصفري لخط المسح. |

**Returns:**
int[] - مصفوفة قيم ألوان ARGB 32‑بت لخط المسح.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


يكتب السطر الكامل للمسح إلى مؤشر سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الصفري لخط المسح. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | مصفوفة ألوان البكسلات للكتابة. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


يكتب السطر الكامل للمسح إلى مؤشر سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الصفري لخط المسح. |
| argb32Pixels | int[] | مصفوفة ألوان ARGB 32‑بت للكتابة. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


يحمّل بكسلات ARGB 32‑بت جزئيًا حسب الحزم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المطلوب. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | محمل بكسل ARGB 32‑بت. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
يوضح المثال التالي كيفية تحميل ومعالجة بكسلات صورة نقطية باستخدام معالج جزئي خاص بك. على سبيل المثال، اعتبر مشكلة عد البكسلات الشفافة بالكامل في صورة. من أجل عد البكسلات الشفافة باستخدام آلية التحميل الجزئي، يتم تقديم فئة منفصلة تسمى TransparentArgb32PixelCounter التي تُنفّذ com.aspose.imaging.IPartialArgb32PixelLoader.
``` java

// أولاً، قم بتنفيذ com.aspose.imaging.IPartialArgb32PixelLoader لحساب جميع البكسلات الشفافة تمامًا.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentArgb32PixelCounter implements com.aspose.imaging.IPartialArgb32PixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>                 *
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, int[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (int pixel : pixels) {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0) {
                this.count++;
            }
        }
    }
}

// فيما يلي مثال على استخدام العداد.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // أنشئ مثيلاً من com.aspose.imaging.IPartialArgb32PixelLoader ومرره إلى com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كالمعامل الأول لطريقة com.aspose.imaging.RasterImage.loadPartialArgb32Pixels.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// عدد البكسلات الشفافة تمامًا هو 55157
// العدد الإجمالي للبكسلات هو 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


يحمّل البكسلات جزئيًا حسب الحزم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المطلوب. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | محمل البكسلات. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
يوضح المثال التالي كيفية تحميل ومعالجة بكسلات صورة نقطية باستخدام معالج جزئي خاص بك. على سبيل المثال، ضع في اعتبارك مشكلة حساب البكسلات الشفافة تمامًا في صورة. من أجل حساب الشفافية باستخدام آلية التحميل الجزئي، يتم تقديم فئة منفصلة TransparentPixelCounter تنفّذ com.aspose.imaging.IPartialPixelLoader.
``` java

// أولاً، قم بتنفيذ com.aspose.imaging.IPartialPixelLoader لحساب جميع البكسلات الشفافة تمامًا.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelCounter implements com.aspose.imaging.IPartialPixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, com.aspose.imaging.Color[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (com.aspose.imaging.Color pixel : pixels) {
            if (pixel.getA() == 0) {
                this.count++;
            }
        }
    }
}

// فيما يلي مثال على استخدام العداد.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // أنشئ مثيلاً من com.aspose.imaging.IPartialPixelLoader ومرره إلى com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كالمعامل الأول لطريقة com.aspose.imaging.RasterImage.loadPartialPixels.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// عدد البكسلات الشفافة تمامًا هو 55157
// العدد الإجمالي للبكسلات هو 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


يحمّل بكسلات ARGB 32‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
int[] - مصفوفة البكسلات ARGB 32-بت المحمّلة.

**Example: The following example shows how to load and process pixels of a raster image.**
يوضح المثال التالي كيفية تحميل ومعالجة بكسلات صورة نقطية. تمثّل البكسلات كقيم صحيحة 32-بت. على سبيل المثال، ضع في اعتبارك مشكلة حساب البكسلات الشفافة تمامًا في صورة.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة com.aspose.imaging.RasterImage.loadArgb32Pixels.
    int[] pixels = rasterImage.loadArgb32Pixels(rasterImage.getBounds());

    int count = 0;
    for (int pixel : pixels) {
        int alpha = (pixel >> 24) & 0xff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.imaging.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


يحمّل بكسلات ARGB 64‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
long[] - مصفوفة البكسلات ARGB 64-بت المحمّلة.

**Example: The following example shows how to load and process pixels of a raster image.**
يوضح المثال التالي كيفية تحميل ومعالجة بكسلات صورة نقطية. تمثّل البكسلات كقيم صحيحة 64-بت. على سبيل المثال، ضع في اعتبارك مشكلة حساب البكسلات الشفافة تمامًا في صورة.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة com.aspose.imaging.RasterImage.loadArgb64Pixels.
    // لاحظ أن الصورة نفسها يجب أن تكون بدقة 16 بت لكل عينة، لأن com.aspose.imaging.RasterImage.loadArgb64Pixels لا يعمل مع 8 بت لكل عينة.
    // للعمل مع 8 بت لكل عينة، يرجى استخدام الطريقة القديمة الجيدة com.aspose.imaging.RasterImage.loadArgb32Pixels.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // لاحظ أن جميع مكوّنات اللون بما فيها ألفا ممثّلة بقيم 16-بت، لذا فإن القيم المسموح بها تقع في النطاق [0, 63535].
        long alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader) {#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-}
```
public final void loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)
```


يحمّل بكسلات ARGB 64‑بت جزئيًا حسب الحزم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المطلوب. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | محمل البكسلات ARGB 64-بت. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


يحمّل البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
com.aspose.imaging.Color[] - مصفوفة البكسلات المحمّلة.

**Example: The following example shows how to load and process pixels of a raster image.**
يوضح المثال التالي كيفية تحميل ومعالجة بكسلات صورة نقطية. على سبيل المثال، ضع في اعتبارك مشكلة حساب البكسلات الشفافة تمامًا في صورة.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة Aspose.Imaging.RasterImage.LoadPixels.
    com.aspose.imaging.Color[] pixels = rasterImage.loadPixels(rasterImage.getBounds());

    int count = 0;
    for (com.aspose.imaging.Color pixel : pixels) {
        if (pixel.getA() == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.imaging.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


يقوم بتحميل البكسلات بتنسيق CMYK. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية `loadCmyk32Pixels(Rectangle)`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
com.aspose.imaging.CmykColor[] - مصفوفة بكسلات CMYK المحملة.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


يحمّل البكسلات بتنسيق CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
int[] - بكسلات CMYK المحملة تُعرض كقيم صحيحة 32‑بت.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


يحمّل بيانات الصورة الخام باستخدام آلية المعالجة الجزئية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المنطقة المستطيلة المطلوبة في الصورة لتحميل البيانات منها. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | إعدادات البيانات الخام. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | محمل البيانات الخام. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
المثال التالي يوضح كيفية استخراج البكسلات من بيانات الصورة الخام باستخدام RawDataSettings. على سبيل المثال، اعتبر مشكلة عد البكسلات الشفافة تمامًا في الصورة.
``` java

// أولاً، نفّذ عدّادًا. في حالة البيانات الخام، قد يبدو العدّاد هكذا:
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelRawDataCounter implements com.aspose.imaging.IPartialRawDataLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * The raw data settings of the loaded image.
     */
    private com.aspose.imaging.RawDataSettings rawDataSettings;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Initializes a new instance of the <see TransparentPixelRawDataCounter /> class.</p>
     *
     * @param settings The raw data settings allow to extract color components from raw data.
     */
    public TransparentPixelRawDataCounter(com.aspose.imaging.RawDataSettings settings) {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end)// throws java.lang.Exception
    {
        int[] channelBits = this.rawDataSettings.getPixelDataFormat().getChannelBits();

        // يتم اعتبار الصيغ البسيطة فقط هنا لتبسيط الشيفرة.
        // لنأخذ في الاعتبار فقط الصور ذات 8 بت لكل عينة.
        for (int i = 0; i < channelBits.length; i++) {
            if (channelBits[i] != 8) {
                throw new java.lang.UnsupportedOperationException();
            }
        }

        switch (this.rawDataSettings.getPixelDataFormat().getPixelFormat()) {
            case com.aspose.imaging.PixelFormat.Rgb:
            case com.aspose.imaging.PixelFormat.Bgr: {
                if (channelBits.length == 4) {
                    // ARGB
                    for (int i = 0; i < data.length; i += 4) {
                        // قناة ألفا تُخزن في النهاية، بعد مكونات اللون.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // تدرج رمادي مع ألفا
                    for (int i = 0; i < data.length; i += 2) {
                        // قناة ألفا تُخزن في النهاية، بعد مكونات اللون.
                        if (data[i + 1] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            default:
                throw new java.lang.IllegalArgumentException("PixelFormat");
        }
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>                 *
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     * @param loadOptions   The load options.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end, com.aspose.imaging.LoadOptions loadOptions) {
        this.process(dataRectangle, data, start, end);
    }
}

// إليك المثال الرئيسي لاستخدام العدّاد
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// عدد البكسلات الشفافة تمامًا هو 55157
// العدد الإجمالي للبكسلات هو 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


يحمّل البيانات الخام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لتحميل البيانات الخام منه. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | حدود الصورة الوجهة. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | إعدادات البيانات الخام التي تُستخدم للبيانات المحملة. لاحظ أنه إذا لم تكن البيانات بالتنسيق المحدد فسيتم إجراء تحويل للبيانات. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | محمل البيانات الخام. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


يحفظ البيانات الخام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | البيانات الخام. |
| dataOffset | int | إزاحة البيانات الخام الابتدائية. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للبيانات الخام. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | إعدادات البيانات الخام التي توجد فيها البيانات. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


يحفظ بكسلات ARGB 32‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لحفظ البكسلات فيه. |
| بكسلات | int[] | مصفوفة بكسلات ARGB 32‑بت. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
المثال التالي يملأ المنطقة المركزية لصورة نقطية ببكسلات سوداء باستخدام طريقة com.aspose.imaging.RasterImage.saveArgb32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // المربع الأسود
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // ارسم المربع الأسود في مركز الصورة.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveArgb32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveArgb32Pixels.png");
} finally {
    image.dispose();
}
```

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


يحفظ البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | مصفوفة البكسلات. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
المثال التالي يملأ المنطقة المركزية لصورة نقطية بكسلات سوداء باستخدام الطريقة com.aspose.imaging.RasterImage.savePixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // المربع الأسود
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // ارسم المربع الأسود في مركز الصورة.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.savePixels(area, pixels);

    rasterImage.save(dir + "sample.SavePixels.png");
} finally {
    image.dispose();
}
```

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


يحوّل صورة النقطية إلى bitmap.

**Returns:**
java.awt.image.BufferedImage - البت ماب

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // معالجة البت ماب الأصلي لجافا.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


يحفظ البكسلات. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية `saveCmyk32Pixels(Rectangle, int[])`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | مصفوفة بكسلات CMYK. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


يحفظ البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لحفظ البكسلات فيه. |
| بكسلات | int[] | بكسلات CMYK معروضة كقيم صحيحة 32-بت. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
المثال التالي يملأ المنطقة المركزية لصورة نقطية بكسلات سوداء باستخدام الطريقة com.aspose.imaging.RasterImage.saveCmyk32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // احصل على تمثيل صحيح للون الأسود في مساحة ألوان CMYK.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // المربع الأسود.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // ارسم المربع الأسود في مركز الصورة.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveCmyk32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveCmyk32Pixels.png");
} finally {
    image.dispose();
}
```

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


يضبط الدقة لهذه `RasterImage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | الدقة الأفقية، بوحدات النقاط في البوصة، لـ `RasterImage`. |
| dpiY | double | الدقة العمودية، بوحدات النقاط في البوصة، لـ `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // احصل على الدقة الأفقية والعمودية للصورة
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // قد يبدو الإخراج هكذا:
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 300.0
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 300.0
    // تعيين قيم الدقة إلى 96 نقطة في البوصة
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.0
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


يضبط لوحة ألوان الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يحسن تجربة المستخدم ويزيل الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية الدوران الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المت varied.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


يعيد تحجيم الصورة باستخدام خيارات موسعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


دوّر الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم صورتك وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) وإلا سيبقى الأبعاد دون تغيير وتُدور محتويات الصورة الداخلية فقط. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


دوّر الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |


**Example: The following example binarizes a raster image with the predefined threshold.**
المثال التالي يحول صورة نقطية إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // قم بتحويل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


تحويل الصورة إلى ثنائية باستخدام عتبة Otsu


**Example: The following example binarizes a raster image with Otsu thresholding.**
المثال التالي يحول صورة نقطية إلى ثنائية باستخدام عتبة أوتسو. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // قم بتحويل الصورة إلى ثنائية باستخدام عتبة أوتسو.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع العتبة المستندة إلى الصورة المتكاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s بكسل متمركزة حول هذا البكسل. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع العتبة المستندة إلى الصورة المتكاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s بكسل متمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s × s بكسل متمركزة حول هذا البكسل. |


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
المثال التالي يحول صورة نقطية إلى ثنائية باستخدام خوارزمية عتبة برادلي التكيفية مع حجم النافذة المحدد. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // حوّل الصورة إلى ثنائية بفارق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-}
```
public final void blend(Point origin, RasterImage overlay, Rectangle overlayArea)
```


يمزج نسخة الصورة هذه مع صورة `overlay`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | أصل دمج صورة الخلفية. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة التراكب. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التراكب. |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


يمزج نسخة الصورة هذه مع صورة `overlay`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | أصل دمج صورة الخلفية. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة التراكب. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التراكب. |
| overlayAlpha | byte | قيمة ألفا للتراكب. |

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


يمزج هذه النسخة من الصورة مع `overlay` مع قيمة ألفا == 255.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | أصل دمج صورة الخلفية. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | الطبقة الفوقية |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


يمزج هذه النسخة من الصورة مع `overlay`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | أصل دمج صورة الخلفية. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | الطبقة الفوقية |
| overlayAlpha | byte | قيمة ألفا للتراكب. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


تحويل الصورة إلى تمثيلها بتدرج الرمادي


**Example: The following example transforms a colored raster image to its grayscale representation.**
المثال التالي يحول صورة نقطية ملونة إلى تمثيلها بالدرجات الرمادية. الصور الرمادية تتكون حصريًا من تدرجات اللون الرمادي وتحمل معلومات الشدة فقط.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


يُعَدِّل هيستوجرام الصورة \\u2014 يضبط قيم البكسل لاستخدام كامل النطاق المتاح.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


تطبيع تلقائي متكيف للسطوع والتباين لكامل الصورة.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


ضبط سطوع الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255, 255].
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


تحسين تباين الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // حدد قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


إدراج توقيع رقمي يعتمد على كلمة المرور المقدمة داخل الصورة باستخدام steganography.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور المستخدمة لتوليد بيانات التوقيع الرقمي |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور المستخدمة لاستخراج البيانات المدمجة. |

**Returns:**
int - قيمة النسبة المئوية للتشابه.
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


ينفّذ فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقميًا، باستخدام كلمة المرور والعتبة المقدمة.

--------------------

هذه الطريقة توفر أسرع كشف عن طريق الاستفادة من `GetSignPercentage`. بمجرد أن تفي البيانات المستخرجة بالحد المحدد، يتم تخطي خطوات استخراج إضافية تهدف إلى تحسين دقة الكشف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور للتحقق من التوقيع. |

**Returns:**
boolean - صحيح إذا كانت الصورة موقعة، وإلا خاطئ.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


ينفّذ فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقميًا، باستخدام كلمة المرور والعتبة المقدمة.

--------------------

هذه الطريقة توفر أسرع كشف عن طريق الاستفادة من `GetSignPercentage`. بمجرد أن تفي البيانات المستخرجة بالحد المحدد، يتم تخطي خطوات استخراج إضافية تهدف إلى تحسين دقة الكشف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور للتحقق من التوقيع. |
| percentageThreshold | int | الحد (بالنسبة المئوية)[0-100] الذي يحدد ما إذا كانت الصورة تعتبر موقعة. إذا لم يتم تحديده، سيتم تطبيق حد افتراضي (`75`). |

**Returns:**
boolean - صحيح إذا كانت الصورة موقعة، وإلا خاطئ.
### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


تصحيح جاما للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما لقناة الأحمر |
| gammaGreen | float | معامل غاما لقناة الأخضر |
| gammaBlue | float | معامل غاما لقناة اللون الأزرق |


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تعيين معاملات غاما الفردية لقنوات الأحمر والأخضر والأزرق.
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


تصحيح جاما للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما لقنوات الأحمر والأخضر والأزرق |


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تعيين معامل غاما لقنوات الأحمر والأخضر والأزرق.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


يحصل على زاوية الميل. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الميل أثناء المسح.

**Returns:**
float - زاوية الميل، بالدرجات.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الالتواء في المسح. تستخدم هذه الطريقة \#getSkewAngle.getSkewAngle و [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-) الطرق.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الالتواء في المسح. تستخدم هذه الطريقة \#rotate(float, boolean, Color).rotate(float, boolean, Color) الطرق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم صورتك وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) وإلا سيبقى الأبعاد دون تغيير وتُدور محتويات الصورة الداخلية فقط. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
الانحراف هو تشوه قد يظهر أثناء عملية مسح المستند عندما يتم تدوير النص/الصور في المستند بزاوية طفيفة. يمكن أن يكون له أسباب مختلفة لكن الأكثر شيوعاً هو أن الورقة تُنقل بشكل غير صحيح أثناء المسح. لذلك، تصحيح الانحراف هو عملية اكتشاف وإصلاح هذه المشكلة في الملفات الممسوحة (i.e. bitmap) بحيث تكون المستندات المصححة للانحراف تحتوي على النص/الصور بشكل صحيح ومُعدل أفقياً.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// تخلص من المسح المائل باستخدام المعلمات الافتراضية
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(inputFilePath);
try {
    // تصحيح الانحراف
    image.normalizeAngle(false /*do not resize*/, com.aspose.imaging.Color.getLightGray() /*background color*/);
    image.save(outputFilePath);
} finally {
    image.close();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


يفلتر المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح تمهيد ثنائي الجانب بحجم نواة 5 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح واينر حركي بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح شحذ بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | اللون القديم الذي سيتم استبداله. |
| oldColorDiff | byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| newColor | [Color](../../com.aspose.imaging/color) | اللون الجديد لاستبدال اللون القديم به. |

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
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال اللون القديم به. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


يستبدل جميع الألوان غير الشفافة باللون الجديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | اللون الجديد لاستبدال الألوان غير الشفافة به. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


يستبدل جميع الألوان غير الشفافة باللون الجديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة به. |

