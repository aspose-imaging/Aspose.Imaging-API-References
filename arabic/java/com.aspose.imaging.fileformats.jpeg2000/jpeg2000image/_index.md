---
title: "Jpeg2000Image"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "قم بمعالجة ملفات صور JPEG2000 JP2 بفعالية باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تدعم مجموعة من أعماق البت لكل بكسل ومعالجة سلسة لبيانات XMP الوصفية التي تحتوي على معلومات الصورة الأساسية."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

قم بمعالجة ملفات صور JPEG2000 (JP2) بفعالية باستخدام واجهة برمجة التطبيقات الخاصة بنا، التي تدعم مجموعة من أعماق البت لكل بكسل ومعالجة سلسة لبيانات XMP الوصفية التي تحتوي على معلومات الصورة الأساسية. مع إمكانيات الضغط بدون فقد، احرص على جودة صورة مثالية مع الحفاظ على سلامة الملف، مما يمكنك من تخصيص صور JP2 وفقًا لمواصفاتك الدقيقة بسهولة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | ابدأ العمل مع الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) عن طريق إنشاء مثيل جديد باستخدام المسار إلى الصورة التي تريد تحميلها. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | ابدأ بسهولة مع الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) بإنشاء مثيل جديد يتضمن كلًا من مسار الملف ومعامل البت لكل بكسل المطلوب. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | قم بتهيئة مثيل جديد بسهولة للفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) عن طريق توفير كائن تدفق. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | قم بإنشاء مثيل جديد للفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) باستخدام تدفق لتحميل الصورة، مع معاملات البت لكل بكسل. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | أنشئ مثيلًا جديدًا للفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)، مع تحديد معلمات العرض والارتفاع. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | أنشئ كائنًا جديدًا من [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)، مع توفير معلمات العرض والارتفاع وخيارات الصورة. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | أنشئ مثيلًا جديدًا للفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) مع معلمات للعرض والارتفاع وعدد البتات. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | أنشئ فئة جديدة من [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) باستخدام صورة نقطية. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | قم بتهيئة مثيل جديد من [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) باستخدام صورة نقطية ومعاملات البت لكل بكسل. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | استرجع تنسيق ملف الصورة. |
| [getRawDataFormat()](#getRawDataFormat--) | تسترجع هذه الخاصية تنسيق البيانات الخام للصورة. |
| [getRawLineSize()](#getRawLineSize--) | تسترجع هذه الخاصية حجم سطر واحد من بيانات الصورة الخام بالبايت. |
| [getWidth()](#getWidth--) | تُعيد هذه الخاصية عرض الصورة بالبكسل. |
| [getHeight()](#getHeight--) | تسترجع هذه الخاصية ارتفاع الصورة بالبكسل. |
| [getBitsPerPixel()](#getBitsPerPixel--) | تُعيد هذه الخاصية عمق الصورة، مقاسًا بالبتات لكل بكسل (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | تتيح لك هذه الخاصية استرجاع أو تعديل الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | تتيح لك هذه الخاصية استرجاع أو تعديل الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | توفر هذه الخاصية الوصول إلى الدقة العمودية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | توفر هذه الخاصية الوصول إلى الدقة العمودية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). |
| [getComments()](#getComments--) | تسمح هذه الخاصية باسترجاع أو تحديث التعليقات المرتبطة بالصورة. |
| [setComments(String[] value)](#setComments-java.lang.String---) | تسمح هذه الخاصية باسترجاع أو تحديث التعليقات المرتبطة بالصورة. |
| [getCodec()](#getCodec--) | تسترجع هذه الخاصية برنامج الترميز JPEG2000 المرتبط بالصورة. |
| [getOriginalOptions()](#getOriginalOptions--) | استرجع خيارات الصورة بناءً على إعدادات الملف الأصلي. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// حمّل صورة JPEG2000.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // حفظ إلى PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


ابدأ العمل مع الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) عن طريق تهيئة نسخة جديدة باستخدام مسار الصورة التي تريد تحميلها. يتيح هذا المُنشئ وصولًا سهلًا إلى صور JPEG2000، مما يبسط عملية تحميل ومعالجة ملفات الصور. من خلال توفير مسار الملف، يمكنك البدء بسرعة في معالجة وتعديل صور JPEG2000 في تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


ابدأ بسهولة مع الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) بإنشاء نسخة جديدة باستخدام كل من مسار الملف ومعامل البتات لكل بكسل المطلوب. يتيح هذا المُنشئ ضبط عملية تحميل الصورة بدقة، مما يضمن التوافق مع صيغ الصور المختلفة وإعدادات الجودة. بفضل هذه المرونة، يمكنك إدارة وتعديل صور JPEG2000 بفعالية وفقًا لمتطلباتك الخاصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية |
| bitsPerPixel | int | عدد البتات لكل بكسل. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


قم بتهيئة نسخة جديدة بسهولة من الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) عن طريق توفير كائن تدفق. يبسط هذا المُنشئ عملية تحميل صور JPEG2000 مباشرةً من التدفقات، مقدماً مرونة وسهولة في التعامل مع بيانات الصور من مصادر مختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


قم بتهيئة نسخة جديدة من الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) باستخدام تدفق لتحميل الصورة، بالإضافة إلى معلمات البتات لكل بكسل. يوفر هذا المُنشئ مرونة من خلال السماح لك بتحديد كل من مصدر بيانات الصورة والبتات لكل بكسل المطلوبة، مما يمنح تحكمًا أدق في عملية تحميل الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |
| bitsPerPixel | int | عدد البتات لكل بكسل. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


أنشئ نسخة جديدة من الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)، مع تحديد معايير العرض والارتفاع. يتيح هذا المُنشئ تهيئة صورة JPEG2000 بأبعاد محددة، وهو مفيد في الحالات التي تحتاج فيها إلى إنشاء صورة بحجم معين برمجيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة |
| الارتفاع | int | ارتفاع الصورة |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


أنشئ كائنًا جديدًا من الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)، مع توفير معايير العرض والارتفاع وخيارات الصورة. يتيح هذا المُنشئ إنشاء صور JPEG2000 بأبعاد محددة وخيارات إضافية، مما يوفر مرونة في توليد الصور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة |
| الارتفاع | int | ارتفاع الصورة |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | الخيارات. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


أنشئ نسخة جديدة من الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) مع معايير للعرض والارتفاع وعدد البتات. يتيح هذا المُنشئ إنشاء صور JPEG2000 بأبعاد محددة وعمق بتات مختلف، مما يوفر مرونة لتلبية احتياجات التصوير المتنوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة |
| الارتفاع | int | ارتفاع الصورة |
| bitsCount | int | عدد البتات. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


أنشئ نسخة جديدة من الفئة [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) باستخدام صورة نقطية. يُسهل هذا المُنشئ إنشاء صورة JPEG2000 من صورة نقطية موجودة، مقدماً تكاملًا سلسًا وتحويلًا بين صيغ الصور المختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


قم بتهيئة نسخة جديدة من [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) باستخدام صورة نقطية ومعلمات البتات لكل بكسل. يتيح هذا المُنشئ تحكمًا دقيقًا في جودة وحجم صورة JPEG2000 الناتجة، مما يجعله مثاليًا للسيناريوهات التي تكون فيها التخصيصات ضرورية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة التي سيتم تهيئة بيانات البكسل ولوحة الألوان بها. |
| bitsPerPixel | int | عدد البتات لكل بكسل. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع تنسيق ملف الصورة. توفر هذه الخاصية معلومات حول تنسيق ملف الصورة. استخدم هذه الخاصية لتحديد تنسيق ملف الصورة برمجيًا، مما يسهل المعالجة والتعامل المناسب بناءً على تنسيق الملف.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


تسترجع هذه الخاصية تنسيق البيانات الخام للصورة. توفر معلومات حول كيفية تخزين بيانات البكسل في الذاكرة. استخدم هذه الخاصية لفهم تنسيق البيانات الأساسي للصورة، وهو ما قد يكون حاسمًا للعديد من عمليات معالجة الصور مثل تحويل الألوان أو الضغط أو فك الضغط.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


تسترجع هذه الخاصية حجم سطر واحد من البيانات الخام للصورة بوحدات البايت. تشير إلى مقدار الذاكرة التي يشغلها صف واحد من البكسلات في تنسيق البيانات الخام للصورة. فهم حجم السطر الخام أمر أساسي للمهام مثل تخصيص الذاكرة، ومعالجة البيانات، وخوارزميات معالجة الصور التي تعمل على خطوط الصورة الفردية.

**Returns:**
int - حجم السطر الخام بالبايت.
### getWidth() {#getWidth--}
```
public int getWidth()
```


تُعيد هذه الخاصية عرض الصورة بالبكسل. توفر معلومة أساسية حول أبعاد الصورة، وهي ضرورية للعديد من مهام معالجة الصور مثل تغيير الحجم، والقص، والتصيير.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


تسترجع هذه الخاصية ارتفاع الصورة بالبكسل. تُعد معلومات أساسية لفهم الأبعاد العمودية للصورة، وتساعد في مهام تعديل الصور المختلفة مثل تغيير الحجم، والقص، والتصيير. يتيح الوصول إلى هذه الخاصية للمستخدمين معرفة الحجم العمودي للصورة، مما يمكّن من تخطيط وعرض دقيق في التطبيقات.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


تُعيد هذه الخاصية عمق الصورة، مقاسًا بالبتات لكل بكسل (bpp). تشير إلى مقدار معلومات اللون المخزنة في كل بكسل من الصورة. فهم عمق الصورة أمر حاسم لتحديد دقة الألوان وجودة الصورة. باستخدام هذه المعلومات، يمكن للمستخدمين تقدير مستوى التفاصيل وغنى الألوان الموجودة في الصورة.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


تتيح لك هذه الخاصية استرجاع أو تعديل الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). يمكن أن يؤثر تعديل هذه الدقة على حجم وجودة الصورة عند طباعتها أو عرضها. من خلال ضبط الدقة الأفقية، يمكن للمستخدمين تحسين الصورة لأجهزة الإخراج أو التطبيقات المحددة، مما يضمن أفضل النتائج البصرية الممكنة.

**Returns:**
double - الدقة الأفقية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // احصل على الدقة الأفقية والعمودية لـ Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بالبكسل لكل بوصة: 72.0
// الدقة العمودية، بالبكسل لكل بوصة: 72.0
// تعيين قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بالبكسل لكل بوصة: 72.0
// الدقة العمودية، بالبكسل لكل بوصة: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


تتيح لك هذه الخاصية استرجاع أو تعديل الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). يمكن أن يؤثر تعديل هذه الدقة على حجم وجودة الصورة عند طباعتها أو عرضها. من خلال ضبط الدقة الأفقية، يمكن للمستخدمين تحسين الصورة لأجهزة الإخراج أو التطبيقات المحددة، مما يضمن أفضل النتائج البصرية الممكنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | الدقة الأفقية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


توفر هذه الخاصية الوصول إلى الدقة العمودية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). يمكن أن يؤثر تعديل هذه الدقة على جودة وحجم الصورة عند طباعتها أو عرضها. من خلال ضبط الدقة العمودية، يمكن للمستخدمين تحسين الصورة لأجهزة إخراج أو تطبيقات مختلفة، مما يضمن تصييرًا بصريًا مثاليًا.

**Returns:**
double - الدقة العمودية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // احصل على الدقة الأفقية والعمودية لـ Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بالبكسل لكل بوصة: 72.0
// الدقة العمودية، بالبكسل لكل بوصة: 72.0
// تعيين قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بالبكسل لكل بوصة: 72.0
// الدقة العمودية، بالبكسل لكل بوصة: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


توفر هذه الخاصية الوصول إلى الدقة العمودية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، مقاسة بالبكسل لكل بوصة (PPI). يمكن أن يؤثر تعديل هذه الدقة على جودة وحجم الصورة عند طباعتها أو عرضها. من خلال ضبط الدقة العمودية، يمكن للمستخدمين تحسين الصورة لأجهزة إخراج أو تطبيقات مختلفة، مما يضمن تصييرًا بصريًا مثاليًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | الدقة العمودية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة في استدعاء واحد. |

### getComments() {#getComments--}
```
public String[] getComments()
```


تتيح هذه الخاصية استرجاع أو تحديث التعليقات المرتبطة بالصورة. توفر التعليقات معلومات إضافية حول محتوى الصورة، مثل الملاحظات، الوصف، أو البيانات الوصفية. قد يكون تعديل هذه التعليقات مفيدًا لتنظيم وتصنيف الصور، وكذلك لنقل تفاصيل مهمة إلى المشاهدين أو المستخدمين.

**Returns:**
java.lang.String[] - التعليقات.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


تتيح هذه الخاصية استرجاع أو تحديث التعليقات المرتبطة بالصورة. توفر التعليقات معلومات إضافية حول محتوى الصورة، مثل الملاحظات، الوصف، أو البيانات الوصفية. قد يكون تعديل هذه التعليقات مفيدًا لتنظيم وتصنيف الصور، وكذلك لنقل تفاصيل مهمة إلى المشاهدين أو المستخدمين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String[] | التعليقات. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


تسترجع هذه الخاصية برنامج الترميز JPEG2000 المرتبط بالصورة. برنامج الترميز JPEG2000 مسؤول عن ترميز وفك ترميز بيانات الصورة بتنسيق JPEG2000، موفرًا ضغطًا فعالًا مع الحفاظ على جودة عالية للصورة. قد يكون الوصول إلى هذا البرنامج مفيدًا لأداء عمليات معالجة صور متقدمة أو تحسين إعدادات ضغط الصورة وفقًا لمتطلبات محددة.

**Returns:**
int - برنامج الترميز.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


استرجع خيارات الصورة بناءً على إعدادات الملف الأصلي. تُعد هذه الطريقة مفيدة للحفاظ على عمق البتات وغيرها من معلمات الصورة الأصلية، مما يضمن التناسق ويحافظ على سلامة بيانات الصورة. يسهّل الوصول إلى هذه الخيارات التعامل السلس ومعالجة الصورة مع الاحتفاظ بخصائصها الأصلية. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
