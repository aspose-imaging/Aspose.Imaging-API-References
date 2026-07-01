---
title: "DicomPage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إنها فئة للعمل مع ملفات DICOM من النوع متعدد الإطارات"
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

إنها فئة للعمل مع ملفات DICOM من النوع متعدد الإطارات
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | يُنشئ مثيلًا جديدًا من الفئة `DicomPage`. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | يُنشئ مثيلًا جديدًا من الفئة `DicomPage`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIndex()](#getIndex--) | يحصل على فهرس الصفحة الحالية. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |

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
        // ارسم شيئًا باستخدام الرسومات المتجهية
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

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


يُنشئ مثيلًا جديدًا من الفئة `DicomPage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | الصورة. |
| index | int | المؤشر. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من الفئة `DicomPage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | الصورة. |
| index | int | المؤشر. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


يحصل على فهرس الصفحة الحالية.

القيمة: الفهرس.

**Returns:**
int - فهرس الصفحة الحالية.
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

القيمة: عرض الصورة.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

القيمة: ارتفاع الصورة.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

القيمة: عدد البتات لكل بكسل في الصورة.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يحصل على قيمة تنسيق الملف

**Returns:**
long
