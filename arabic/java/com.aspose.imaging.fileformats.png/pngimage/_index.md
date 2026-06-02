---
title: "PngImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "معالجة صور رستر Portable Network Graphics PNG باستخدام واجهة برمجة التطبيقات المتعددة الاستخدامات التي تدعم مستويات الضغط ومختلف أعماق الألوان بما في ذلك الرمادي، اللون المفهرس، TrueColor والقنوات ألفا."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

معالجة صور رستر Portable Network Graphics (PNG) باستخدام واجهة برمجة التطبيقات المتعددة الاستخدامات، التي تدعم مستويات الضغط ومختلف أعماق الألوان بما في ذلك الرمادي، اللون المفهرس، TrueColor والقنوات ألفا. معالجة بيانات XMP الوصفية بسلاسة، مما يتيح إدارة شاملة لبيانات الصورة الوصفية، مع تحميل صور PNG بسهولة، إجراء تعديلات متنوعة، تطبيق الفلاتر، وتحويل الصور إلى صيغ ملفات أخرى لتحقيق أقصى قدر من المرونة والتخصيص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | إنشاء كائن جديد من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق توفير معلمات العرض والارتفاع. |
| [PngImage(String path)](#PngImage-java.lang.String-) | ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) باستخدام معلمة المسار لتحديد موقع ملف الصورة المراد تحميله. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق توفير صورة رستر كمعامل. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | يُهيئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) بتحديد مسار ملف الصورة ونوع اللون. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) بتحديد صورة رستر ونوع اللون. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق تهيئتها باستخدام تدفق. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | إنشاء نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)، مع تحديد معلمات العرض والارتفاع ونوع اللون المطلوبة. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | تهيئة نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)، مع دمج خيارات PNG إلى جانب معلمات العرض والارتفاع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | استرجاع قيمة البتات لكل بكسل للصورة. |
| [getHeight()](#getHeight--) | الحصول على ارتفاع الصورة بالبكسل. |
| [getHorizontalResolution()](#getHorizontalResolution--) | استرجاع أو تعديل الدقة الأفقية للصورة. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | استرجاع أو تعديل الدقة الأفقية للصورة. |
| [getFileFormat()](#getFileFormat--) | يسترجع تنسيق الملف المرتبط بنسخة الصورة. |
| [getRawDataFormat()](#getRawDataFormat--) | الوصول إلى تنسيق البيانات الخام للصورة. |
| [getVerticalResolution()](#getVerticalResolution--) | يوفر الوصول إلى الدقة العمودية للصورة. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | يوفر الوصول إلى الدقة العمودية للصورة. |
| [getWidth()](#getWidth--) | يسمح باسترجاع عرض الصورة بالبكسل، مما يوفر معلومات أساسية عن أبعادها. |
| [hasTransparentColor()](#hasTransparentColor--) | يُعيد قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [hasAlpha()](#hasAlpha--) | يرجع قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على قناة ألفا، التي تحدد شفافيتها. |
| [getTransparentColor()](#getTransparentColor--) | يسترجع اللون الشفاف للصورة إذا كان موجودًا. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يُعيد قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | يعدّل اللون الشفاف للصورة إذا كان موجودًا. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يسترجع قيمة منطقية تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [getBackgroundColor()](#getBackgroundColor--) | يسترجع لون الخلفية للصورة إذا تم تحديده. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | يسترجع قيمة منطقية تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يسترجع لون الخلفية للصورة إذا تم تحديده. |
| [getInterlaced()](#getInterlaced--) | يسترجع قيمة منطقية تشير إلى ما إذا كان الـ [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) متشابكًا، مما يحدد ما إذا كانت بيانات الصورة مخزنة بطريقة تدريجية لتحميل أو نقل أسرع. |
| [isInterlaced()](#isInterlaced--) | يحصل على قيمة تشير إلى ما إذا كانت نسخة الصورة هذه متشابكة. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// تحميل صورة PNG من ملف.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // حوّل الصورة إلى تمثيل رمادي
    pngImage.grayscale();

    // احفظ إلى ملف.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


قم بتهيئة كائن جديد من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق توفير معلمات العرض والارتفاع. يبسط هذا المُنشئ إنشاء صور PNG من خلال السماح للمطورين بتحديد الأبعاد مباشرة، مما يُسهل إدارة بيانات صور PNG بكفاءة داخل تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) باستخدام معامل المسار لتحديد موقع ملف الصورة الذي سيتم تحميله. يتيح هذا المُنشئ للمطورين إنشاء صور PNG بسهولة عن طريق تحميلها من ملف، مما يبسط عملية التعامل مع صور PNG في تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل صورة. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق توفير صورة نقطية كمعامل. يتيح هذا المُنشئ للمطورين تهيئة كائن صورة PNG مباشرة باستخدام صورة نقطية موجودة، مما يُسهل عملية التعامل مع صور PNG في تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


يُهيئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق تحديد مسار ملف الصورة ونوع اللون. يتيح هذا المُنشئ إنشاء صور PNG بسهولة من ملفات ذات أنواع ألوان مختلفة، مما يوفر مرونة في معالجة صيغ الصور المتنوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل صورة. |
| colorType | int | نوع اللون. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق تحديد صورة نقطية ونوع اللون. يتيح هذا المُنشئ للمطورين تحويل الصور النقطية مباشرة إلى صيغة PNG مع تحديد نوع اللون المطلوب، مما يوفر مرونة في تمثيل الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| colorType | int | نوع اللون. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


ينشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) عن طريق تهيئتها باستخدام تدفق. يتيح هذا المُنشئ للمطورين تحميل صور PNG مباشرة من تدفق، مما يوفر مرونة في استرجاع الصور من مصادر مختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | التدفق لتحميل صورة. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


أنشئ نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) مع تحديد معلمات العرض والارتفاع ونوع اللون المطلوبة. يتيح هذا المُنشئ إنشاء صور PNG بسرعة بأبعاد وتكوينات لون مخصصة، مما يُسهل توليد الصور بسلاسة لتطبيقات وسير عمل مختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |
| colorType | int | نوع اللون. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


قم بتهيئة نسخة جديدة من الفئة [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) مع دمج خيارات PNG إلى جانب معلمات العرض والارتفاع. يمنح هذا المُنشئ المطورين القدرة على إنشاء صور PNG بإعدادات وأبعاد قابلة للتخصيص، مما يوفر مرونة في توليد الصور لمجالات استخدام متنوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | خيارات PNG. |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


استرجع قيمة البتات لكل بكسل في الصورة. توفر هذه الخاصية معلومات حيوية حول عمق اللون في الصورة، مما يمكّن المطورين من فهم مستوى التفاصيل ودقة الألوان الموجودة في بيانات الصورة.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


احصل على ارتفاع الصورة بالبكسل. تُعيد هذه الخاصية البُعد العمودي للصورة، مما يسمح للمطورين بتحديد حجمها بالبكسل على المحور العمودي.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


استرجع أو عدّل الدقة الأفقية للصورة. تمثل هذه الخاصية عدد البكسلات لكل بوصة على المحور الأفقي للصورة. يمكن لتعديل هذه الدقة أن يؤثر على الحجم الفعلي للصورة عند طباعتها أو عرضها.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // احصل على الدقة الأفقية والعمودية لـ PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.0
//الدقة العمودية، بوحدات البكسل لكل بوصة: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


استرجع أو عدّل الدقة الأفقية للصورة. تمثل هذه الخاصية عدد البكسلات لكل بوصة على المحور الأفقي للصورة. يمكن لتعديل هذه الدقة أن يؤثر على الحجم الفعلي للصورة عند طباعتها أو عرضها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يسترجع تنسيق الملف المرتبط بنسخة الصورة. توفر هذه الخاصية معلومات أساسية حول نوع الملف، مما يتيح معالجة فعّالة بناءً على متطلبات التنسيق المحددة.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


يصل إلى تنسيق البيانات الخام للصورة. توفر هذه الخاصية نظرة على كيفية تنظيم بيانات الصورة داخليًا، مما قد يكون مفيدًا لمهام معالجة الصور المتقدمة أو تحويل الصيغ.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// صور PNG التي سيتم تحميلها.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


يوفر الوصول إلى الدقة العمودية للصورة. يمكن للمطورين استخدام هذه الخاصية لاسترجاع أو تعديل إعداد الدقة، الذي يُشير إلى عدد البكسلات لكل بوصة (PPI) على المحور العمودي للصورة.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // احصل على الدقة الأفقية والعمودية لـ PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.0
//الدقة العمودية، بوحدات البكسل لكل بوصة: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


يوفر الوصول إلى الدقة العمودية للصورة. يمكن للمطورين استخدام هذه الخاصية لاسترجاع أو تعديل إعداد الدقة، الذي يُشير إلى عدد البكسلات لكل بوصة (PPI) على المحور العمودي للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يسمح باسترجاع عرض الصورة بالبكسل، موفرًا معلومات أساسية حول أبعادها. تُستخدم هذه الخاصية بشكل متكرر من قبل المطورين لتحديد عرض الصورة، مما يمكّنهم من تنفيذ عمليات مختلفة بناءً على حجمها.

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يوفر قيمة منطقية تُشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. تُعد هذه الخاصية حيوية للتطبيقات التي تحتاج إلى معالجة الشفافية، مما يسمح للمطورين بتحديد ما إذا كانت هناك حاجة لمعالجة إضافية للتعامل مع المناطق الشفافة في الصورة.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


يعيد قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على قناة ألفا، والتي تحدد شفافيتها. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى التعامل مع الشفافية، مما يسمح للمطورين بتحديد ما إذا كان هناك حاجة إلى معالجة إضافية للتعامل مع المناطق الشفافة في الصورة.

**Returns:**
boolean - `true` إذا كان هذا الكائن يحتوي على ألفا؛ وإلا `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// فئة المساعدة
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// هنا المثال الرئيسي
Utils utils = new Utils();

// احصل على جميع أنواع ألوان PNG المدعومة.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// المخرجات تبدو هكذا:
// صورة PNG بتدرج الرمادي لا تدعم قناة ألفا
// صورة PNG بالألوان الحقيقية لا تدعم قناة ألفا
// صورة PNG بألوان مفهرسة لا تدعم قناة ألفا
// صورة PNG بتدرج الرمادي مع قناة ألفا تدعم قناة ألفا
// صورة PNG بالألوان الحقيقية مع قناة ألفا تدعم قناة ألفا
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


يسترجع اللون الشفاف للصورة إذا كان موجودًا. هذه الخاصية ذات قيمة للتطبيقات التي تتطلب معالجة دقيقة للمناطق الشفافة داخل الصور، مما يسمح للمطورين بالوصول إلى اللون الشفاف المحدد واستخدامه.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


يوفر قيمة منطقية تُشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. تُعد هذه الخاصية حيوية للتطبيقات التي تحتاج إلى معالجة الشفافية، مما يسمح للمطورين بتحديد ما إذا كانت هناك حاجة لمعالجة إضافية للتعامل مع المناطق الشفافة في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// إنشاء صورة PNG بألوان حقيقية بحجم 100×100 بكسل.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // سيتم اعتبار جميع البكسلات الحمراء شفافة بالكامل.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // ستحصل جميع البكسلات الشفافة على لون خلفية.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // املأ الصورة بالكامل باللون الأبيض.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // املأ الربع العلوي الأيسر من الصورة باللون الشفاف.
    // هذا يجعل الربع العلوي الأيسر ملونًا بلون الخلفية.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


يعدّل اللون الشفاف للصورة إذا كان موجودًا. هذه الخاصية ذات قيمة للتطبيقات التي تتطلب معالجة دقيقة للمناطق الشفافة داخل الصور، مما يسمح للمطورين بالوصول إلى اللون الشفاف المحدد واستخدامه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// إنشاء صورة PNG بألوان حقيقية بحجم 100×100 بكسل.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // سيتم اعتبار جميع البكسلات الحمراء شفافة بالكامل.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // ستحصل جميع البكسلات الشفافة على لون خلفية.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // املأ الصورة بالكامل باللون الأبيض.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // املأ الربع العلوي الأيسر من الصورة باللون الشفاف.
    // هذا يجعل الربع العلوي الأيسر ملونًا بلون الخلفية.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


يسترجع قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى تحديد ما إذا كانت الصورة تشمل لون خلفية، وهو ما قد يكون مهمًا لمهام معالجة مختلفة مثل التركيب، أو التصيير، أو التصدير.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يسترجع لون الخلفية للصورة إذا تم تحديده. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى تحديد وربما تعديل لون خلفية الصورة.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


يسترجع قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى تحديد ما إذا كانت الصورة تشمل لون خلفية، وهو ما قد يكون مهمًا لمهام معالجة مختلفة مثل التركيب، أو التصيير، أو التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// إنشاء صورة PNG بألوان حقيقية بحجم 100×100 بكسل.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // سيتم اعتبار جميع البكسلات الحمراء شفافة بالكامل.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // ستحصل جميع البكسلات الشفافة على لون خلفية.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // املأ الصورة بالكامل باللون الأبيض.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // املأ الربع العلوي الأيسر من الصورة باللون الشفاف.
    // هذا يجعل الربع العلوي الأيسر ملونًا بلون الخلفية.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يسترجع لون الخلفية للصورة إذا تم تحديده. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى تحديد وربما تعديل لون خلفية الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// إنشاء صورة PNG بألوان حقيقية بحجم 100×100 بكسل.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // سيتم اعتبار جميع البكسلات الحمراء شفافة بالكامل.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // ستحصل جميع البكسلات الشفافة على لون خلفية.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // املأ الصورة بالكامل باللون الأبيض.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // املأ الربع العلوي الأيسر من الصورة باللون الشفاف.
    // هذا يجعل الربع العلوي الأيسر ملونًا بلون الخلفية.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


يسترجع قيمة منطقية تشير إلى ما إذا كان الـ [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) متشابكًا، مما يحدد ما إذا كانت بيانات الصورة مخزنة بطريقة تدريجية لتحميل أو نقل أسرع.

**Returns:**
boolean - `true` إذا كان متشابكًا؛ وإلا `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


يحصل على قيمة تشير إلى ما إذا كانت نسخة الصورة هذه متشابكة.

القيمة: `true` إذا كانت نسخة الصورة هذه متشابكة؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت نسخة الصورة هذه متشابكة.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


يحصل على الخيارات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعلمات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام الطريقة `DataStreamSupporter.Save(string)`، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى الطريقة `Image.Save(string, ImageOptionsBase)` كمعامل ثاني.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
