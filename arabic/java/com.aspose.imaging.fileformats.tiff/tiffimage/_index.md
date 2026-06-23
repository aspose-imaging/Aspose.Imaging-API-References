---
title: "TiffImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "معالجة صور TIFF النقطية بتنسيق Tagged Image File Format باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تقدم دعماً شاملاً لمختلف الدقات وإمكانيات تحرير متقدمة مثل تعديل بيانات EXIF والقنوات ألفا."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

معالجة صور TIFF النقطية بتنسيق Tagged Image File Format (TIFF) باستخدام واجهة برمجة التطبيقات الخاصة بنا، التي تقدم دعماً شاملاً لمختلف الدقات وإمكانيات تحرير متقدمة مثل تعديل بيانات EXIF والقنوات ألفا. قم بتطبيع الزوايا للصور الممسوحة، وتغيير الحجم، وتحويلها إلى تدرج الرمادي، وتطبيق الفلاتر، وتصحيحات جاما وتعديلات معلمات الصورة بسهولة. تعامل بسلاسة مع ملفات TIFF متعددة الإطارات، أنشئ مسارات رسومية، أضف أشكالاً، واحفظ الصور بسهولة إلى صيغ مختلفة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | تهيئة كائن جديد من الفئة [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage)، مع تحديد معامل الإطار. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | إنشاء نسخة جديدة من الفئة [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage)، مع توفير قائمة بالإطارات كمعامل. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | استرجاع قيمة تنسيق الملف المرتبط بالصورة. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | الإشارة إلى ما إذا كانت المكونات تتطلب الضرب المسبق، لضمان معالجة فعّالة للعناصر البصرية. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | الإشارة إلى ما إذا كانت المكونات تتطلب الضرب المسبق، لضمان معالجة فعّالة للعناصر البصرية. |
| [getByteOrder()](#getByteOrder--) | تبديل ترتيب البايتات لملفات TIFF بسلاسة، لضمان تحكم دقيق في تفسير البيانات. |
| [setByteOrder(int value)](#setByteOrder-int-) | تبديل ترتيب البايتات لملفات TIFF بسلاسة، لضمان تحكم دقيق في تفسير البيانات. |
| [getHorizontalResolution()](#getHorizontalResolution--) | استرجاع الدقة الأفقية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدة بيكسل لكل بوصة، مما يسهل الضبط الدقيق وقدرات العرض. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | تعديل الدقة الأفقية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدة بيكسل لكل بوصة، مما يسهل الضبط الدقيق وقدرات العرض. |
| [getVerticalResolution()](#getVerticalResolution--) | الوصول إلى الدقة العمودية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدة بيكسل لكل بوصة، مما يتيح ضبطاً دقيقاً وتحسينات في العرض. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | الوصول إلى الدقة العمودية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدة بيكسل لكل بوصة، مما يتيح ضبطاً دقيقاً وتحسينات في العرض. |
| [getActiveFrame()](#getActiveFrame--) | إدارة الإطار النشط بسلاسة، مما يسهل التنقل الديناميكي والتلاعب داخل السياق المحدد. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | إدارة الإطار النشط بسلاسة، مما يسهل التنقل الديناميكي والتلاعب داخل السياق المحدد. |
| [getFrames()](#getFrames--) | استرجع مصفوفة من كائنات [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)، مما يتيح وصولًا شاملاً ومعالجة للإطارات الفردية داخل صورة TIFF. |
| [getPageCount()](#getPageCount--) | استرجع العدد الإجمالي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. |
| [getPages()](#getPages--) | الوصول إلى صفحات المستند بسلاسة، مما يتيح تنقلًا ديناميكيًا ومعالجة داخل بنية المحتوى. |
| [hasAlpha()](#hasAlpha--) | حدد ما إذا كانت الصورة تحتوي على قناة ألفا، مما يوفر معلومات حيوية لعمليات العرض والتجميع. |
| [removeMetadata()](#removeMetadata--) | يزيل بيانات التعريف لكائن الصورة هذا عن طريق ضبط قيمة `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) إلى `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | استرجع الخيارات المستمدة من إعدادات الملف الأصلي، مما يسهل الحفاظ السلس على المعلمات الرئيسية مثل عمق البت وغيرها من السمات الأساسية للصورة الأصلية. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | أدمج صفحة جديدة في الصورة الحالية بسلاسة، مما يوسع محتواها وتنوعها. |
| [alignResolutions()](#alignResolutions--) | نفّذ طريقة المساعدة AlignResolutions لمزامنة الدقة الأفقية والعمودية، لضمان تجانس أبعاد الصورة. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | يحدد الدقة لـ [RasterImage](../../com.aspose.imaging/rasterimage) المحدد، مما يتيح تحكمًا دقيقًا في عرض الصورة وخصائصها. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | استخدم طريقة NormalizeAngle المصممة خصيصًا للمستندات النصية الممسوحة لتصحيح الانحرافات في المسحات، مما يضمن محاذاة دقيقة. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | أدمج الإطار المحدد بسلاسة في الصورة، مما يوسع محتواها وتنوعها. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | أضف الإطارات من الصورة المحددة بسلاسة إلى الإطار الحالي، مما يجمع محتواها ويعزز مرونة التركيب. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | دمج مصفوفة الإطارات بسلاسة في الصورة، مما يغني محتواها وتنوعها. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | أدرج الإطار الجديد في الفهرس المحدد داخل تسلسل الإطارات، لضمان تحكم دقيق في ترتيب الإطارات. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | استبدل الإطار في الموضع المحدد بإطار آخر بسلاسة، مما يسهل إدارة إطارات ديناميكية داخل تسلسل الصورة. |
| [removeFrame(int index)](#removeFrame-int-) | أزل الإطار المحدد بفهرسه من تسلسل الصورة بسهولة، مما يبسط إدارة الإطارات داخل تطبيقك. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | أزل الإطار المحدد من تسلسل الصورة بكفاءة، مما يسهل إدارة إطارات مبسطة داخل تطبيقك. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | قم بعملية تغيير حجم متناسبة على الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع أثناء تعديل أبعادها. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | اضبط عرض الصورة مع الحفاظ على نسبة أبعادها، لضمان تغيير حجم متناسب لتقديم بصري مثالي. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | قم بضبط متناسب لارتفاع الصورة، مع الحفاظ على نسبة أبعادها لضمان تكامل بصري ثابت. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | نفّذ تدويرًا أو انعكاسًا أو مزيجًا من العمليتين حصريًا على الإطار النشط. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | نفّذ تمويهًا على الصورة الحالية لتحسين جودتها البصرية وتقليل آثار تدرج الألوان. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قص الصورة باستخدام منطقة مستطيلة محددة، مما يتيح اختيارًا دقيقًا للمحتوى المطلوب. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | نفّذ قصًا على الصورة عن طريق تحديد إزاحات في الاتجاهات اليسرى، اليمنى، العليا والسفلى. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | طبق التحويل إلى ثنائي على الصورة باستخدام عتبة محددة مسبقًا، لتحويلها إلى صورة ثنائية ذات مناطق أمامية وخلفية متميزة. |
| [binarizeOtsu()](#binarizeOtsu--) | استخدم طريقة عتبة أوتسو لإجراء التحويل إلى ثنائي على الصورة، مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على هيستوغرام الصورة. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | تنفيذ التحويل إلى ثنائي على الصورة باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بتدرج الرمادي، وتحويلها إلى صورة ذات قناة واحدة حيث يمثل كل بكسل الشدة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تطبيق تصحيح جاما على الصورة، وضبط شدة البكسلات لتحقيق توازن الألوان المطلوب. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | إجراء تصحيح جاما على الصورة باستخدام معاملات فردية لقنوات الأحمر والأخضر والأزرق، مما يتيح ضبطًا دقيقًا لتوازن الألوان والتباين. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | تنفيذ تعديل `brightness` للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | عزز التباين في [الصورة](../../com.aspose.imaging/image) المثيل، مع تضخيم الفروق بين المناطق الفاتحة والداكنة. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | تصفية المحتوى داخل المستطيل المحدد، وتطبيق مرشح معالجة صورة مخصص لتعزيز أو تعديل المنطقة المختارة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | ضبط حجم الصورة بناءً على الإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد، نسبة العرض إلى الارتفاع، وسلوك التحجيم. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // إنشاء GraphicsPath باستخدام PathResources من صورة TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // ارسم خطًا أحمر واحفظ الصورة
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // إنشاء شكل مستطيل لـ GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // إنشاء GraphicsPath باستخدام الشكل الخاص بنا
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // تعيين PathResources باستخدام GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // احفظ الصورة
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


تهيئة كائن جديد من الفئة [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage)، مع تحديد معامل الإطار. يسهّل هذا المُنشئ إنشاء مثيل TiffImage، مما يسمح للمطورين بتحديد الإطار الذي سيتم تحميله أو معالجته، وتبسيط مهام معالجة صور Tiff داخل تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | إطار TIFF لتهيئة الصورة به. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


إنشاء مثيل جديد من الفئة [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage)، مع توفير قائمة بالإطارات كمعامل. يتيح هذا المُنشئ تهيئة كائن TiffImage بعدة إطارات، مما يسهل التعامل الفعال ومعالجة تسلسلات صور TIFF داخل تطبيقات البرمجيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | الإطارات. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجاع قيمة تنسيق الملف المرتبط بالصورة. تُعد هذه الخاصية جانبًا حاسمًا في استرجاع بيانات تعريف الصورة، مما يسمح لتطبيقات البرمجيات بتحديد وتفسير تنسيق بيانات الصورة بكفاءة.

**Returns:**
long - قيمة تنسيق الملف
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


الإشارة إلى ما إذا كانت المكونات تحتاج إلى الضرب المسبق، لضمان معالجة فعّالة للعناصر البصرية. تحسين عمليات العرض عن طريق تبديل هذه الخاصية، وتبسيط سير عمل الرسومات لأداء محسن.

**Returns:**
boolean - `true` إذا كان يجب ضرب المكونات مسبقًا؛ وإلا `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


الإشارة إلى ما إذا كانت المكونات تحتاج إلى الضرب المسبق، لضمان معالجة فعّالة للعناصر البصرية. تحسين عمليات العرض عن طريق تبديل هذه الخاصية، وتبسيط سير عمل الرسومات لأداء محسن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `true` إذا كان يجب ضرب المكونات مسبقًا؛ وإلا `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

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

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // احفظ البكسلات لكامل الصورة.
    image.savePixels(image.getBounds(), colors);

    // يتم تخزين البكسلات في الصورة الأصلية بصيغة غير مضاعفة مسبقًا.
    // يجب تحديد الخيار المقابل صراحةً للحصول على مكوّنات اللون المضاعفة مسبقًا.
    // يتم حساب مكوّنات اللون المضاعفة مسبقًا باستخدام الصيغ:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//سيظهر الناتج كما يلي:
//اللون الأصلي: Color [A=127, R=255, G=0, B=0]
//اللون المسبق الضرب: Color [A=127, R=127, G=0, B=0]
//اللون الأصلي: Color [A=127, R=0, G=255, B=0]
//اللون المسبق الضرب: Color [A=127, R=0, G=127, B=0]
//اللون الأصلي: Color [A=127, R=0, G=0, B=255]
//اللون المسبق الضرب: Color [A=127, R=0, G=0, B=127]
//اللون الأصلي: Color [A=127, R=255, G=255, B=0]
//اللون المسبق الضرب: Color [A=127, R=127, G=127, B=0]
//اللون الأصلي: Color [A=127, R=255, G=0, B=255]
//اللون المسبق الضرب: Color [A=127, R=127, G=0, B=127]
//اللون الأصلي: Color [A=127, R=0, G=255, B=255]
//اللون المسبق الضرب: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


قم بتبديل ترتيب البايت لملفات TIFF بسلاسة، مع ضمان تحكم دقيق في تفسير البيانات. مكن تطبيقاتك من المرونة للتكيف مع مواصفات الملفات المتنوعة، مما يعزز التوافق والكفاءة في معالجة البيانات.

**Returns:**
int - ترتيب البايت لملف TIFF.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


قم بتبديل ترتيب البايت لملفات TIFF بسلاسة، مع ضمان تحكم دقيق في تفسير البيانات. مكن تطبيقاتك من المرونة للتكيف مع مواصفات الملفات المتنوعة، مما يعزز التوافق والكفاءة في معالجة البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | ترتيب البايت لملف TIFF. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


استرجع الدقة الأفقية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدات البكسل لكل بوصة، مما يسهل الضبط الدقيق وإمكانيات العرض. احصل على بيانات تعريف الصورة الأساسية بسهولة، مما يمكّن سير عمل معالجة الصور المبسط لتجارب مستخدم محسّنة.

**Returns:**
مزدوج - الدقة الأفقية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // احصل على الدقة الأفقية والعمودية لـ TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 96.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


يعدّل الدقة الأفقية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدات البكسل لكل بوصة، مما يسهل الضبط الدقيق وإمكانيات العرض. احصل على بيانات تعريف الصورة الأساسية بسهولة، مما يمكّن سير عمل معالجة الصور المبسط لتجارب مستخدم محسّنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الدقة الأفقية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


احصل على الدقة العمودية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدات البكسل لكل بوصة، مما يتيح ضبطًا دقيقًا وتحسينات في العرض. استخدم بيانات الصورة الأساسية بسهولة لتبسيط سير عمل معالجة الصور، وضمان جودة وأداء فائقين في تطبيقاتك.

**Returns:**
مزدوج - الدقة العمودية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // احصل على الدقة الأفقية والعمودية لـ TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 96.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


احصل على الدقة العمودية للصورة المحددة [Image](../../com.aspose.imaging/image) بوحدات البكسل لكل بوصة، مما يتيح ضبطًا دقيقًا وتحسينات في العرض. استخدم بيانات الصورة الأساسية بسهولة لتبسيط سير عمل معالجة الصور، وضمان جودة وأداء فائقين في تطبيقاتك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الدقة العمودية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


قم بإدارة الإطار النشط بسلاسة، مما يسهل التنقل الديناميكي والتلاعب داخل السياق المحدد. مكن تطبيقك من التفاعل بفعالية مع المحتوى المتعدد الوسائط، مما يعزز تفاعل المستخدم والإنتاجية.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.addFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. لنقم بإزالته.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // لا تنسَ التخلص من الإطار إذا لم تقم بإضافته إلى TiffImage آخر.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


قم بإدارة الإطار النشط بسلاسة، مما يسهل التنقل الديناميكي والتلاعب داخل السياق المحدد. مكن تطبيقك من التفاعل بفعالية مع المحتوى المتعدد الوسائط، مما يعزز تفاعل المستخدم والإنتاجية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | الإطار النشط. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.addFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. لنقم بإزالته.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // لا تنسَ التخلص من الإطار إذا لم تقم بإضافته إلى TiffImage آخر.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


استرجع مصفوفة من كائنات [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)، مما يتيح وصولًا شاملاً وتلاعبًا بالإطارات الفردية داخل صورة TIFF. استغل قوة هذه المصفوفة لتبسيط سير عمل معالجة الصور، وضمان تحكم دقيق وتحسين المحتوى البصري.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] - مصفوفة [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe).

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.addFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. لنقم بإزالته.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // لا تنسَ التخلص من الإطار إذا لم تقم بإضافته إلى TiffImage آخر.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع العدد الإجمالي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. دمج هذه الوظيفة لتعزيز تجربة المستخدم، وتمكين وصول سلس إلى هياكل المستند الشاملة.

**Returns:**
int - عدد الصفحات.
### getPages() {#getPages--}
```
public Image[] getPages()
```


احصل على صفحات المستند بسلاسة، مما يتيح تنقلًا ديناميكيًا وتلاعبًا داخل هيكل المحتوى. مكن تطبيقك من وصول فعال إلى الصفحات الفردية، مما يسهل معالجة المستندات المبسطة وتعزيز تفاعل المستخدم.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


تحديد ما إذا كانت الصورة تحتوي على قناة ألفا، مما يوفر معلومات حاسمة لعمليات العرض والتجميع. دمج هذه الميزة لتحسين سير عمل معالجة الصور البصرية، وضمان تمثيل دقيق ومعالجة العناصر الشفافة.

**Returns:**
منطقي - `true` إذا كان هناك قناة ألفا.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // إذا كان إطار TIFF النشط يحتوي على قناة ألفا، فسيُعتبر أن صورة TIFF بأكملها تحتوي على قناة ألفا.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


يزيل بيانات التعريف لكائن الصورة هذا عن طريق ضبط قيمة `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) إلى `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


استرجاع الخيارات المستمدة من إعدادات الملف الأصلي، مما يسهل الحفاظ السلس على المعلمات الرئيسية مثل عمق البت وغيرها من السمات الأساسية للصورة الأصلية. استخدم هذه الطريقة للحفاظ على الدقة والاتساق في مهام معالجة الصور، وضمان الحصول على نتائج مثالية دون تعديلات غير ضرورية. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بدقة 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-)، سيتم إنتاج صورة PNG ناتجة بدقة 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بدقة 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


دمج صفحة جديدة في الصورة الحالية بسلاسة، مما يوسع محتواها وتنوعها. استخدم هذه الطريقة لتعزيز تكوين المستند وإدارته، مما يتيح التعامل الفعال مع الصور متعددة الصفحات داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | الصفحة المراد إضافتها. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


تنفيذ طريقة المساعدة AlignResolutions لمزامنة الدقة الأفقية والعمودية، وضمان التوحيد في أبعاد الصورة. تسهل هذه الوظيفة سير عمل معالجة الصور المبسط من خلال توحيد معلمات الدقة، وتحسين الجودة البصرية والاتساق عبر مختلف المنصات والأجهزة.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


يحدد الدقة لـ [RasterImage](../../com.aspose.imaging/rasterimage) المحدد، مما يتيح تحكمًا دقيقًا في عرض الصورة وخصائصها. دمج هذه الوظيفة لتحسين المخرجات البصرية وضمان التوافق مع مجموعة متنوعة من أجهزة ومنصات الإخراج، مما يعزز تجربة المستخدم العامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | الدقة الأفقية، بوحدة النقاط لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | الدقة العمودية، بوحدة النقاط لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // احصل على الدقة الأفقية والعمودية لـ TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 96.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


استخدم طريقة NormalizeAngle المصممة خصيصًا للمستندات النصية الممسوحة ضوئيًا لتصحيح المسحات المائلة، وضمان محاذاة دقيقة. دمج هذه الوظيفة بسلاسة في سير عمل معالجة النصوص لتعزيز قابلية قراءة المستند وجودته، وتحسين الكفاءة العامة في مهام التعرف على النص وتحليله. تستخدم هذه الطريقة أساليب [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) و [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) وإلا سيبقى الأبعاد دون تغيير وتُدوَّر محتويات الصورة الداخلية فقط. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


دمج الإطار المحدد بسلاسة في الصورة، مما يوسع محتواها وتنوعها. استخدم هذه الطريقة لتعزيز تكوين الصورة وإدارتها، مما يتيح التعامل الفعال مع الصور متعددة الإطارات داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | الإطار المراد إضافته. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.addFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. لنقم بإزالته.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // لا تنسَ التخلص من الإطار إذا لم تقم بإضافته إلى TiffImage آخر.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


إضافة الإطارات من الصورة المحددة بسلاسة إلى الإطار الحالي، مع دمج محتواها وتعزيز مرونة التكوين. دمج هذه الطريقة لتبسيط إدارة الإطارات وتعديلها داخل تطبيقك، مما يسهل التعامل الفعال مع الصور متعددة الإطارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | الصورة المصدر. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


دمج مصفوفة الإطارات بسلاسة في الصورة، مما يثري محتواها وتنوعها. استخدم هذه الطريقة لتعزيز تكوين الصورة وإدارتها، وتمكين التعامل الفعال مع الصور متعددة الإطارات داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | مصفوفة الإطارات المراد إضافتها |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


إدراج الإطار الجديد في الفهرس المحدد ضمن تسلسل الإطارات، مع ضمان تحكم دقيق في ترتيب الإطارات. استخدم هذه الطريقة لإدارة تسلسلات الإطارات بفعالية، وتسهيل التعديل الديناميكي وتنظيم محتوى الصورة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الـ `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | الإطار للإدراج. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


استبدال الإطار في الموضع المحدد بإطار آخر بسلاسة، مما يسهل إدارة الإطارات الديناميكية ضمن تسلسل الصورة. دمج هذه الطريقة لتعزيز المرونة والدقة في تعديل الإطارات، وضمان تنظيم وعرض مثالي لمحتوى الصورة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | موضع الإطار المستند إلى الصفر. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | الإطار المراد استبداله. |

ملاحظة: لا تنسَ إغلاق/تحرير الإطار إذا لم تقم بإضافته إلى صورة TiffImage أخرى. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


قم بإزالة الإطار المحدد بواسطة فهرسه من تسلسل الصور بسهولة، مما يبسط إدارة الإطارات داخل تطبيقك. دمج هذه الوظيفة لتعزيز الكفاءة والدقة في معالجة الإطارات، وتسهيل التنظيم السلس وعرض محتوى الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | index | int | فهرس الإطار المراد إزالته. |

--------------------

ملاحظة: لا تنسَ تحرير الإطار إذا لم تقم بإضافته إلى صورة TiffImage أخرى. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.addFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. لنقم بإزالته.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // لا تنسَ التخلص من الإطار إذا لم تقم بإضافته إلى TiffImage آخر.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


قم بإزالة الإطار المحدد من تسلسل الصور بفعالية، مما يسهل إدارة الإطارات داخل تطبيقك. دمج هذه الوظيفة لتعزيز الدقة والمرونة في معالجة الإطارات، وضمان تنظيم وعرض سلس لمحتوى الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | الإطار المراد إزالته. |

--------------------

ملاحظة: لا تنسَ تحرير الإطار إذا لم تقم بإضافته إلى صورة TiffImage أخرى. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


قم بإجراء عملية تغيير حجم متناسبة على الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع أثناء تعديل أبعادها. استخدم هذه الطريقة لتكبير الصور ديناميكياً داخل تطبيقك، مما يضمن تمثيلًا بصريًا ثابتًا لسلامة المحتوى. سيقوم تغيير الحجم المتناسب بتغيير حجم كل إطار وفق النسبة `newWidth`/العرض و `newHeight`/الارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


قم بضبط عرض الصورة مع الحفاظ على نسبة الأبعاد، لضمان تغيير حجم متناسب لتقديم بصري أمثل. استخدم هذه الطريقة لتكبير الصور ديناميكياً داخل تطبيقك، مما يسهل عرضًا ثابتًا وجذابًا عبر مختلف سياقات العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
يحمّل هذا المثال صورة TIFF ويعيد تحجيمها بشكل متناسب باستخدام طرق تحجيم مختلفة. يتم تحديد العرض فقط، ويتم حساب الارتفاع تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


قم بإجراء تعديل متناسب لارتفاع الصورة، مع الحفاظ على نسبة الأبعاد لضمان تكامل بصري ثابت. استخدم هذه الطريقة لتكبير الصور ديناميكياً داخل تطبيقك، مما يضمن عرضًا أمثل عبر منصات وأجهزة متنوعة دون الإضرار بجودة المحتوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
يحمّل هذا المثال صورة TIFF ويعيد تحجيمها بشكل متناسب باستخدام طرق تحجيم مختلفة. يتم تحديد الارتفاع فقط، ويتم حساب العرض تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


قم بإجراء تدوير أو انعكاس، أو مزيج من العمليتين، حصريًا على الإطار النشط. تتيح هذه الطريقة معالجة دقيقة للإطارات الفردية داخل تسلسل الصور، مما يعزز المرونة في تحرير الصور وتكوينها داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع التدوير والانعكاس. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// هذه فئة مساعدة.
class Utils {
    // يحصل على تمثيل نصي لنوع القلب الدوراني.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// إليك المثال الرئيسي
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // قم بالدوران، والقلّب، واحفظ إلى ملف الإخراج.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


نفّذ التدرج الضوضائي على الصورة الحالية لتحسين جودتها البصرية وتقليل آثار تدرج الألوان. دمج هذه الطريقة في سير عمل معالجة الصور لضمان انتقالات ألوان أكثر سلاسة، مما ينتج مظهرًا عامًّا محسّنًا ووضوحًا أعلى للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان المخصصة للتمويه. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // نفّذ تلوين بالعتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زادت عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // نفّذ تلوين فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - أسود وأبيض.
    // كلما زادت عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قم بقص الصورة باستخدام منطقة مستطيلة محددة، مما يتيح اختيارًا دقيقًا للمحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لإزالة المناطق غير المرغوبة بكفاءة والتركيز على التفاصيل الأساسية، مما يعزز الوضوح العام وتكوين الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |


**Example: The following example crops a TIFF image.**
المثال التالي يقتطع صورة TIFF. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // قص الصورة. منطقة القص هي المنطقة المركزية المستطيلة للصورة.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


قم بقص الصورة عن طريق تحديد إزاحات إلى اليسار، اليمين، الأعلى، والأسفل. تمكّن هذه الطريقة من اختيار الجزء المطلوب من الصورة بدقة، مما يسهل إزالة المناطق غير المرغوبة والتركيز على المحتوى الأساسي. دمج هذه الوظيفة في خط أنابيب معالجة الصور لتعزيز الوضوح والتكوين حسب الحاجة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | int | الإزاحة اليسرى. |
| rightShift | int | الإزاحة اليمنى. |
| topShift | int | الإزاحة العلوية. |
| bottomShift | int | الإزاحة السفلية. |


**Example: The following example crops a TIFF image.**
المثال التالي يقتطع صورة TIFF. يتم تحديد منطقة القص عبر هوامش اليسار، الأعلى، اليمين، والأسفل.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // اقتطع مرة أخرى. اضبط هامشًا بنسبة 10٪ من حجم الصورة.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // احفظ الصورة المقتطعة بصيغة PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


طبق التحويل إلى صورة ثنائية على الصورة باستخدام عتبة محددة مسبقًا، مما يحولها إلى صورة ثنائية ذات مناطق أمامية وخلفية متميزة. دمج هذه الطريقة في سير عمل معالجة الصور لتسهيل مهام التجزئة واستخراج الميزات، مما يعزز دقة وكفاءة تحليل الصور داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 لها، وإلا 0. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
المثال التالي يحول صورة TIFF إلى صورة ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
    // إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من 127، سيتم تعيين قيمة 255 له، وإلا ستكون 0.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


استخدم طريقة أوتسو لتحديد العتبة لإجراء التحويل إلى صورة ثنائية، حيث يتم تحديد قيمة العتبة المثلى تلقائيًا بناءً على هيستوجرام الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تجزئة واستخراج ميزات فعّالة، مما يعزز دقة وموثوقية مهام تحليل الصور داخل تطبيقك.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
المثال التالي يحول صورة TIFF إلى صورة ثنائية باستخدام طريقة أوتسو لتحديد العتبة. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // حوّل الصورة إلى ثنائية باستخدام عتبة أوتسو.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


طبق التحويل إلى صورة ثنائية على الصورة باستخدام خوارزمية العتبة التكيفية لبرايدلي مع تحديد العتبة عبر الصورة المتكاملة. تقوم هذه المقاربة بحساب عتبات محلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام اللاحقة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
المثال التالي يحول صورة TIFF إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع حجم النافذة المحدد. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // حوّل الصورة إلى ثنائية بفرق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


حوّل الصورة إلى تمثيلها بتدرج الرمادي، محولاً إياها إلى صورة ذات قناة واحدة حيث يمثل كل بكسل الشدة. دمج هذه الطريقة في خط أنابيب معالجة الصور الخاص بك لتبسيط التحليل وتعزيز التوافق مع الخوارزميات القائمة على تدرج الرمادي، مما يسهل مهام الرؤية الحاسوبية وتحليل الصور المختلفة داخل تطبيقك.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
المثال التالي يحول صورة TIFF ملونة إلى تمثيلها بتدرج الرمادي. صور تدرج الرمادي تتكون حصراً من درجات اللون الرمادي وتحمل معلومات الشدة فقط.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


طبق تصحيح جاما على الصورة، معدلاً شدة البكسلات لتحقيق توازن الألوان المطلوب. أدمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز جودة العرض وتحسين دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما للقنوات الحمراء والخضراء والزرقاء |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تعيين معامل غاما للقنوات الحمراء والخضراء والزرقاء.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


قم بأداء تصحيح جاما على الصورة باستخدام معاملات منفصلة لقنوات الأحمر والأخضر والأزرق، مما يتيح ضبطاً دقيقاً لتوازن الألوان والتباين. دمج هذه الطريقة في خط أنابيب معالجة الصور الخاص بك لتحقيق تحكم دقيق في عرض الألوان وتعزيز الدقة البصرية داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما للقناة الحمراء |
| gammaGreen | float | معامل غاما للقناة الخضراء |
| gammaBlue | float | معامل غاما للقناة الزرقاء |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تعيين معاملات غاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


نفّذ تعديل `brightness` للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز الوضوح وتحسين الجودة البصرية للصور داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255، 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


عزّز التباين في كائن [Image](../../com.aspose.imaging/image)، مضخمًا الفروق بين المناطق الفاتحة والداكنة. دمج هذه الوظيفة لتحسين الوضوح البصري والجودة العامة للصورة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // حدد قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f، 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


صَفِّ المحتوى داخل المستطيل المحدد، مطبقًا مرشح معالجة صور مخصص لتعزيز أو تعديل المنطقة المختارة. دمج هذه الطريقة في سير عمل تعديل الصور الخاص بك لتحقيق تحسينات أو تحولات مستهدفة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تطبيق مرشح متوسط بحجم مستطيل 5 على الصورة بالكامل.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تطبيق مرشح تنعيم ثنائي الجانب بحجم نواة 5 على الصورة بالكامل.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تطبيق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تطبيق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بالكامل.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تطبيق مرشح حركة واينر بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // تطبيق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


اضبط حجم الصورة بناءً على الإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد، نسبة العرض إلى الارتفاع، وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق عمليات تغيير حجم مخصصة تتناسب مع المتطلبات الخاصة لتطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// الخوارزمية التكيفية المستندة إلى الدالة الكسرية الموزونة والمختلطة واستيفاء lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// المرشح المستطيل الصغير
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// عدد الألوان في لوحة الألوان.
resizeSettings.setEntriesCount(256);

// لم يتم استخدام تقليل ألوان الصورة
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// طريقة إقليدية
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات تكيفية.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // احفظ إلى PNG
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

