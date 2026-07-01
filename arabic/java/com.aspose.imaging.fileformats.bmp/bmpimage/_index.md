---
title: "BmpImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمكنك التعامل بسهولة مع ملفات Bitmap BMP و Device Independent Bitma DIB مما يسهل التلاعب الفعال ومعالجة الصور النقطية."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

يمكنك التعامل بسهولة مع ملفات Bitmap (BMP) و Device Independent Bitmap (DIB)، مما يسهل التلاعب الفعال ومعالجة الصور النقطية. من خلال تنفيذ عمليات مختلفة على الصور، تُبسّط هذه API سير العمل، وتوفر للمطورين مجموعة أدوات موثوقة للعمل مع صيغ BMP و DIB في تطبيقاتهم البرمجية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | ابدأ باستخدام فئة BmpImage بسهولة مع هذا المُنشئ الذي يُنشئ مثيلاً جديدًا. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | أنشئ مثيلاً جديدًا لفئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة باستخدام هذا المُنشئ، مع تحديد المعلمات مثل المسار، bitsPerPixel، والضغط. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | ابدأ باستخدام فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة عن طريق تهيئة مثيل جديد بهذا المُنشئ، مع استخدام تدفق كمدخل. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | ابدأ العمل مع فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسلاسة بإنشاء مثيل جديد باستخدام تدفق، مع المعلمات المحددة مثل bitsPerPixel والضغط. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | أنشئ مثيلاً جديدًا لفئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة عن طريق تهيئته باستخدام كائن RasterImage. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | ابدأ العمل مع فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسلاسة بإنشاء مثيل جديد باستخدام rasterImage مع المعلمات المحددة مثل bitsPerPixel والضغط. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | ابدأ باستخدام فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة بإنشاء مثيل جديد مع معلمات العرض والارتفاع المحددة. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | ابدأ باستخدام فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسلاسة عن طريق تهيئة مثيل جديد مع معلمات مثل العرض، الارتفاع، عمق البت، واللوحة. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | أنشئ مثيلاً جديدًا لفئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة باستخدام هذا المُنشئ، مع تحديد المعلمات مثل العرض، الارتفاع، bitsPerPixel، واللوحة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | احصل بسرعة على التفاصيل الأساسية حول صورة البت ماب الخاصة بك باستخدام هذه الدالة البسيطة. |
| [getFileFormat()](#getFileFormat--) | استرجع بسهولة قيمة تنسيق الملف باستخدام هذه الخاصية سهلة الاستخدام. |
| [getRawDataFormat()](#getRawDataFormat--) | احصل بسهولة على تنسيق البيانات الخام الخاصة بك باستخدام هذه الدالة سهلة الاستخدام. |
| [getRawLineSize()](#getRawLineSize--) | احصل بسرعة على حجم كل سطر خام بالبايت باستخدام هذه الخاصية البسيطة. |
| [getCompression()](#getCompression--) | استرجع نوع الضغط المستخدم في الصورة بسهولة باستخدام هذه الخاصية. |
| [getWidth()](#getWidth--) | احصل على عرض الصورة بسهولة باستخدام هذه الخاصية. |
| [getHeight()](#getHeight--) | استرجع ارتفاع الصورة بسهولة باستخدام هذه الخاصية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | احصل على عدد البتات لكل بكسل في الصورة بسهولة باستخدام هذه الخاصية. |
| [getHorizontalResolution()](#getHorizontalResolution--) | تتيح لك هذه الخاصية بسهولة الحصول على أو تعيين الدقة الأفقية، المقاسة بالبكسل لكل بوصة، لكائن [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | تتيح لك هذه الخاصية بسهولة الحصول على أو تعيين الدقة الأفقية، المقاسة بالبكسل لكل بوصة، لكائن [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getVerticalResolution()](#getVerticalResolution--) | استرجع أو عيّن بسهولة الدقة العمودية، المقاسة بالبكسل لكل بوصة، لهذا الكائن [RasterImage](../../com.aspose.imaging/rasterimage) باستخدام هذه الخاصية. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | استرجع أو عيّن بسهولة الدقة العمودية، المقاسة بالبكسل لكل بوصة، لهذا الكائن [RasterImage](../../com.aspose.imaging/rasterimage) باستخدام هذه الخاصية. |
| [hasAlpha()](#hasAlpha--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | اضبط دقة الـ[RasterImage](../../com.aspose.imaging/rasterimage) الخاصة بك بسهولة باستخدام هذه الطريقة سهلة الاستخدام. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة البسيطة. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// إنشاء صورة BMP بحجم 100 × 100 بكسل.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // املأ الصورة بتدرج خطي بسيط من الأحمر إلى الأسود.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// تحميل صورة PNG من ملف.
try (Image pngImage = Image.load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا.
    // إذا كنت تريد تحديد هذا الوضع صراحةً، يجب تعيين خاصية Compression في BmpOptions إلى BitmapCompression.Bitfields.
    // طريقة ضغط BitmapCompression.Bitfields هي طريقة الضغط الافتراضية في BmpOptions.
    // لذلك يمكن تحقيق نفس نتيجة تصدير صورة Bmp مع الشفافية إما بإحدى الطرق التالية.
    // مع خيارات افتراضية ضمنية:
    pngImage.save(outputPathPng);
    // مع خيارات افتراضية صريحة:
    pngImage.save(outputPathBmp, new BmpOptions());
    // تحديد طريقة ضغط BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// تحميل صورة PNG من ملف.
try (Image pngImage = Image.load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا، ويتم ذلك باستخدام طريقة ضغط BitmapCompression.Bitfields.
    // لحفظ صورة BMP باستخدام طريقة ضغط Rgb، يجب تحديد BmpOptions مع خاصية Compression مضبوطة على BitmapCompression.Rgb.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


ابدأ باستخدام فئة BmpImage بسهولة مع هذا المُنشئ الذي يهيئ مثيلاً جديدًا. مثالي للمطورين الذين يرغبون في البدء بسرعة مع كائنات [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسرعة وكفاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار | java.lang.String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


أنشئ مثيلاً جديدًا لفئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة باستخدام هذا المُنشئ، مع تحديد المعلمات مثل المسار، bitsPerPixel، والضغط. مثالي للمطورين الذين يرغبون في تهيئة كائنات BmpImage بسرعة وكفاءة، مع تحكم دقيق في خصائص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار | java.lang.String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |
| bitsPerPixel | int | عدد البتات لكل بكسل. |
| ضغط | long | الضغط المراد استخدامه. |
| horizontalResolution | double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |
| verticalResolution | double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


ابدأ باستخدام فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة عن طريق إنشاء نسخة جديدة باستخدام هذا المُنشئ، مع استخدام تدفق كمدخل. مثالي للمطورين الذين يبحثون عن طريقة مريحة للعمل مع كائنات BmpImage من مصادر بيانات مختلفة، مما يضمن المرونة وسهولة التكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


ابدأ العمل مع فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسلاسة عن طريق إنشاء نسخة جديدة باستخدام تدفق، مع تحديد معلمات مثل bitsPerPixel و compression. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |
| bitsPerPixel | int | عدد البتات لكل بكسل. |
| ضغط | long | الضغط المراد استخدامه. |
| horizontalResolution | double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |
| verticalResolution | double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


أنشئ نسخة جديدة من فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة عن طريق تهيئتها باستخدام كائن RasterImage. مثالي للمطورين الذين يرغبون في تحويل الصور النقطية الحالية إلى تنسيق BmpImage بسلاسة، مما يضمن التوافق وسهولة التكامل في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة التي سيتم تهيئة بيانات البكسل واللوحة اللونية بها. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


ابدأ العمل مع فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسلاسة عن طريق إنشاء نسخة جديدة باستخدام rasterImage مع تحديد معلمات مثل bitsPerPixel و compression. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة التي سيتم تهيئة بيانات البكسل واللوحة اللونية بها. |
| bitsPerPixel | int | عدد البتات لكل بكسل. |
| ضغط | long | الضغط المراد استخدامه. |
| horizontalResolution | double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |
| verticalResolution | double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


ابدأ استخدام فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة عن طريق إنشاء نسخة جديدة مع تحديد معلمات العرض والارتفاع. مثالي للمطورين الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة، مما يضمن المرونة وسهولة التكامل في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


ابدأ باستخدام فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسلاسة عن طريق تهيئة نسخة جديدة مع معلمات مثل العرض، الارتفاع، عمق البت، واللوحة. مثالي للمطورين الذين يبحثون عن طريقة مباشرة لإنشاء كائنات BmpImage بأبعاد مخصصة وتكوينات لونية، مما يضمن المرونة والكفاءة في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |
| bitsPerPixel | int | عدد البتات لكل بكسل. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


أنشئ نسخة جديدة من فئة [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) بسهولة باستخدام هذا المُنشئ، مع تحديد معلمات مثل العرض، الارتفاع، bitsPerPixel، واللوحة. مثالي للمطورين الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة وتكوينات لونية، مما يضمن المرونة وسهولة التكامل في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |
| bitsPerPixel | int | عدد البتات لكل بكسل. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |
| ضغط | long | الضغط المراد استخدامه. |
| horizontalResolution | double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |
| verticalResolution | double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلاً عن القيمة المدخلة. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


احصل بسرعة على التفاصيل الأساسية حول صورة البت ماب الخاصة بك باستخدام هذه الدالة البسيطة. مثالي للمطورين الذين يحتاجون إلى استرجاع معلومات الرأس لصورهم.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//عدد ألوان اللوحة المطلوبة لعرض البت ماب: 0
//عدد ألوان اللوحة المستخدمة في البت ماب: 0
//ضغط البت ماب: 0
//ارتفاع البت ماب: 100
//عرض البت ماب: 100
//حجم البيانات الخام للبت ماب بالبايت: 40000
//عدد المستويات: 1
//الدقة الأفقية للبت ماب، بوحدة بكسل لكل متر: 0
//الدقة العمودية للبت ماب، بوحدة بكسل لكل متر: 0
//عدد البتات لكل بكسل: 32
//قناع البتات الإضافية: null
//حجم الرأس بالبايت: 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يمكنك بسهولة استرجاع قيمة تنسيق الملف باستخدام هذه الخاصية سهلة الاستخدام. مثالية للمطورين الذين يبحثون عن وصول سريع إلى معلومات حول تنسيق الملف.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// فئة المساعد المستخدمة في المثال الرئيسي أدناه.
class Utils {
    // طريقة المساعد للحصول على تمثيل نصي لصيغة الملف.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// إليك المثال الرئيسي
Utils utils = new Utils();

// إنشاء صورة BMP بدقة 32 بت بحجم 100 × 100 بكسل.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// إنشاء صورة BMP بعمق 24-bpp بحجم 100 × 100 بكسل.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// في معظم الحالات لا يدعم BMP قناة ألفا لذا من المحتمل أن يكون الناتج هكذا:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, used channels: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


احصل بسهولة على تنسيق البيانات الخام الخاصة بك باستخدام هذه الدالة السهلة الاستخدام. مثالي للمطورين الذين يرغبون في الوصول السريع إلى المعلومات الحيوية حول تنسيق بياناتهم.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//تنسيق البكسل: Rgb24Bpp، القنوات المستخدمة: 8,8,8
//حجم السطر الخام بالبايت: 1500
//ضغط البت ماب: 0
//عرض الـ bitmap: 500
//ارتفاع الـ bitmap: 500
//عدد البتات لكل بكسل: 24
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
//عيّن قيم الدقة إلى 96 نقطة في البوصة
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


احصل بسرعة على حجم كل سطر خام بالبايت باستخدام هذه الخاصية المبسطة. مثالي للمطورين الذين يحتاجون إلى معالجة بيانات الصورة الخام بكفاءة.

**Returns:**
عدد صحيح - حجم السطر الخام بالبايت.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//تنسيق البكسل: Rgb24Bpp، القنوات المستخدمة: 8,8,8
//حجم السطر الخام بالبايت: 1500
//ضغط البت ماب: 0
//عرض الـ bitmap: 500
//ارتفاع الـ bitmap: 500
//عدد البتات لكل بكسل: 24
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
//عيّن قيم الدقة إلى 96 نقطة في البوصة
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


استرجع نوع الضغط المستخدم للصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين الذين يحتاجون إلى الوصول السريع إلى معلومات حول ضغط الصورة.

**Returns:**
long - ضغط الصورة [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// فئة المساعد المستخدمة في المثال الرئيسي أدناه.
class Utils {
    // طريقة المساعد للحصول على تمثيل نصي لصيغة الملف.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// إليك المثال الرئيسي
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// إنشاء لوحة ألوان أحادية اللون تحتوي فقط على اللونين الأحمر والأخضر.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // إنشاء صورة BMP بعمق 8-bpp بحجم 100 × 100 بكسل.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // املأ الصورة بالكامل باللون الأحمر.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // احفظ الصورة إلى تدفق للحصول على حجم الصورة الناتج.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// قد يبدو الإخراج هكذا:
// الضغط=RGB
// عدد البتات لكل بكسل=8
// أبعاد الصورة=100 × 100
// حجم السطر الخام=100
// حجم الناتج بالبايت=11078
// ---------------------------------------------
// ضغط=RLE8
// عدد البتات لكل بكسل=8
// أبعاد الصورة=100 × 100
// حجم السطر الخام=100
// حجم الإخراج بالبايت=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


يمكنك الوصول إلى عرض الصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين الذين يبحثون عن معلومات سريعة حول أبعاد الصورة.

**Returns:**
int - عرض الصورة بالبكسل.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//تنسيق البكسل: Rgb24Bpp، القنوات المستخدمة: 8,8,8
//حجم السطر الخام بالبايت: 1500
//ضغط البت ماب: 0
//عرض الـ bitmap: 500
//ارتفاع الـ bitmap: 500
//عدد البتات لكل بكسل: 24
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
//عيّن قيم الدقة إلى 96 نقطة في البوصة
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


استرجع ارتفاع الصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى معلومات أبعاد الصورة.

**Returns:**
int - ارتفاع الصورة بالبكسل.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//تنسيق البكسل: Rgb24Bpp، القنوات المستخدمة: 8,8,8
//حجم السطر الخام بالبايت: 1500
//ضغط البت ماب: 0
//عرض الـ bitmap: 500
//ارتفاع الـ bitmap: 500
//عدد البتات لكل بكسل: 24
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
//عيّن قيم الدقة إلى 96 نقطة في البوصة
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يمكنك الوصول إلى عدد البتات لكل بكسل في الصورة بسهولة باستخدام هذه الخاصية. مثالي للمطورين الذين يبحثون عن معلومات سريعة حول جودة الصورة وعمقها.

**Returns:**
int - عدد بتات الصورة لكل بكسل.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//قد يبدو الإخراج هكذا:
//تنسيق البكسل: Rgb24Bpp، القنوات المستخدمة: 8,8,8
//حجم السطر الخام بالبايت: 1500
//ضغط البت ماب: 0
//عرض الـ bitmap: 500
//ارتفاع الـ bitmap: 500
//عدد البتات لكل بكسل: 24
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
//عيّن قيم الدقة إلى 96 نقطة في البوصة
//الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
//الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


تسمح لك هذه الخاصية بالحصول بسهولة أو ضبط الدقة الأفقية، المقاسة بالبكسل لكل بوصة، لكائن [RasterImage](../../com.aspose.imaging/rasterimage). مثالي للمطورين الذين يحتاجون إلى تحكم دقيق في دقة الصورة لتطبيقاتهم.

**Returns:**
مزدوج - الدقة الأفقية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة \#setResolution(double, double).setResolution(double, double) لتحديث قيم الدقة الاثنين في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بالبكسل لكل بوصة: 0.0
// الدقة العمودية، بالبكسل لكل بوصة: 0.0
// عيّن قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
// الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


تسمح لك هذه الخاصية بالحصول بسهولة أو ضبط الدقة الأفقية، المقاسة بالبكسل لكل بوصة، لكائن [RasterImage](../../com.aspose.imaging/rasterimage). مثالي للمطورين الذين يحتاجون إلى تحكم دقيق في دقة الصورة لتطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الدقة الأفقية. |

--------------------

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة \#setResolution(double, double).setResolution(double, double) لتحديث قيم الدقة الاثنين في استدعاء واحد. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


استرجع أو اضبط بسهولة الدقة العمودية، المقاسة بالبكسل لكل بوصة، لهذا الكائن [RasterImage](../../com.aspose.imaging/rasterimage) باستخدام هذه الخاصية. مثالي للمطورين الذين يتطلبون تحكمًا دقيقًا في دقة الصورة في تطبيقاتهم.

**Returns:**
مزدوج - الدقة العمودية.

--------------------

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة \#setResolution(double, double).setResolution(double, double) لتحديث قيم الدقة الاثنين في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بالبكسل لكل بوصة: 0.0
// الدقة العمودية، بالبكسل لكل بوصة: 0.0
// عيّن قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
// الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


استرجع أو اضبط بسهولة الدقة العمودية، المقاسة بالبكسل لكل بوصة، لهذا الكائن [RasterImage](../../com.aspose.imaging/rasterimage) باستخدام هذه الخاصية. مثالي للمطورين الذين يتطلبون تحكمًا دقيقًا في دقة الصورة في تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الدقة العمودية. |

--------------------

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة \#setResolution(double, double).setResolution(double, double) لتحديث قيم الدقة الاثنين في استدعاء واحد. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان لهذا الكائن ألفا.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


قم بضبط دقة [RasterImage](../../com.aspose.imaging/rasterimage) الخاص بك بسهولة باستخدام هذه الطريقة سهلة الاستخدام. مثالي للمطورين الذين يبحثون عن تحكم دقيق في دقة الصورة في تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | الدقة الأفقية، بوحدة النقاط لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | الدقة العمودية، بوحدة النقاط لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بالبكسل لكل بوصة: 0.0
// الدقة العمودية، بالبكسل لكل بوصة: 0.0
// عيّن قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بوحدة بكسل لكل بوصة: 96.012
// الدقة العمودية، بوحدة بكسل لكل بوصة: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة المباشرة. مثالي للمطورين الذين يبحثون عن وصول سريع إلى إعدادات الصورة الافتراضية أو التكوينات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعاملات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
