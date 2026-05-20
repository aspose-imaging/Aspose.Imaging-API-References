---
title: "DicomOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لإنشاء تنسيق صورة نقطية DICOM في مجال التصوير الرقمي والاتصالات الطبية هي أداة متخصصة مصممة لتطبيقات الأجهزة الطبية."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.imageoptions/dicomoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DicomOptions extends ImageOptionsBase
```

واجهة برمجة التطبيقات لإنشاء تنسيق صورة نقطية DICOM (التصوير الرقمي والاتصالات في الطب) هي أداة متخصصة موجهة لتطبيقات الأجهزة الطبية. تمكّن من إنشاء صور DICOM بسلاسة، وهو أمر حاسم لتخزين البيانات الطبية واحتواء معلومات التعريف الحيوية. مع ميزات لضبط الضغط، وتحديد أنواع الألوان، وتضمين بيانات تعريف XMP، يمكن للمطورين ضمان الامتثال والمرونة في إدارة صور DICOM لأغراض التصوير الطبي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DicomOptions()](#DicomOptions--) | يُنشئ مثيلاً جديدًا من الفئة [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions). |
| [DicomOptions(DicomOptions options)](#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompression()](#getCompression--) | يسترجع الضغط. |
| [setCompression(Compression value)](#setCompression-com.aspose.imaging.fileformats.dicom.Compression-) | يعيّن الضغط. |
| [getColorType()](#getColorType--) | يحصل على نوع اللون. |
| [setColorType(int value)](#setColorType-int-) | يضبط نوع اللون. |

## Example: The following example shows export to DICOM file format (single and multipage).

``` java
String fileName = "sample.jpg";
String inputFileNameSingle = fileName;
String inputFileNameMultipage = "multipage.tif";
String outputFileNameSingleDcm = "output.dcm";
String outputFileNameMultipageDcm = "outputMultipage.dcm";

// العينة البرمجية التالية تحول صورة JPEG إلى تنسيق ملف DICOM
try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileNameSingle))
{
    image.save(outputFileNameSingleDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}

// يدعم تنسيق DICOM الصور متعددة الصفحات. يمكنك تحويل صور GIF أو TIFF إلى DICOM بنفس طريقة صور JPEG.
try(com.aspose.imaging.Image imageMultiple = com.aspose.imaging.Image.load(inputFileNameMultipage))
{
    imageMultiple.save(outputFileNameMultipageDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // ارسم شيئًا باستخدام الرسومات المتجهة
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // احفظ بكسلات الصورة المرسومة. أصبحت الآن على الصفحة الأولى من صورة Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // أضف بضع صفحات بعد ذلك، مما يجعلها أغمق
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // أضف بضع صفحات أمام الصفحة الرئيسية، مما يجعلها أكثر إشراقًا
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // احفظ الصورة متعددة الصفحات التي تم إنشاؤها إلى ملف الإخراج
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomOptions() {#DicomOptions--}
```
public DicomOptions()
```


يُنشئ مثيلاً جديدًا من الفئة [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions).

### DicomOptions(DicomOptions options) {#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-}
```
public DicomOptions(DicomOptions options)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) |  |

### getCompression() {#getCompression--}
```
public final Compression getCompression()
```


يسترجع الضغط.

القيمة: الضغط.

**Returns:**
[Compression](../../com.aspose.imaging.fileformats.dicom/compression) - the compression.
### setCompression(Compression value) {#setCompression-com.aspose.imaging.fileformats.dicom.Compression-}
```
public final void setCompression(Compression value)
```


يعيّن الضغط.

القيمة: الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Compression](../../com.aspose.imaging.fileformats.dicom/compression) | الضغط. |

### getColorType() {#getColorType--}
```
public final int getColorType()
```


يحصل على نوع اللون.

القيمة: نوع اللون.

**Returns:**
int - نوع اللون.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


يضبط نوع اللون.

القيمة: نوع اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نوع اللون. |


**Example: Use JPEG compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


**Example: Use JPEG 2000 compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


**Example: Use RLE compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


**Example: Change Color Type in DICOM compression.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

