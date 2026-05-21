---
title: "CdrImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لدعم تنسيق الصورة المتجهة CorelDRAW CDR هي مجموعة أدوات أساسية للمطورين الذين يعملون مع الرسومات المتجهة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

واجهة برمجة التطبيقات لدعم تنسيق صورة CorelDRAW CDR المتجهة هي مجموعة أدوات أساسية للمطورين الذين يعملون مع الرسومات المتجهة. تمكّن هذه الواجهة معالجة ملفات CDR بسلاسة، مما يسمح بتخزين ومعالجة عناصر متنوعة مثل النصوص، الخطوط، الأشكال، الصور، الألوان، والتأثيرات. بفضل قدراتها الشاملة، يمكن للمطورين العمل بفعالية مع تمثيلات المتجهات لمحتوى الصور، مما يضمن الدقة والمرونة في إنشاء وتحرير رسومات CorelDRAW المتجهة برمجيًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | ابدأ العمل مع الفئة [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) بسهولة عن طريق إنشاء نسخة جديدة باستخدام معلمات stream و loadOptions. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | ابدأ العمل مع الفئة [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) بسهولة عن طريق إنشاء نسخة جديدة باستخدام معلمات stream و loadOptions. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | استرجع الصفحة الافتراضية للصورة بسهولة باستخدام هذه الخاصية سهلة الاستخدام. |
| [isCached()](#isCached--) | حدد بسهولة ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة البيانات. |
| [getBitsPerPixel()](#getBitsPerPixel--) | استرجع عمق البت للصورة بسهولة باستخدام هذه الخاصية سهلة الاستخدام. |
| [getPageCount()](#getPageCount--) | استرجع أو حدّث إجمالي عدد صفحات الصورة بسهولة باستخدام هذه الخاصية البديهية. |
| [getPages()](#getPages--) | استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. |
| [getCdrDocument()](#getCdrDocument--) | استرجع أو حدّث مستند CDR بسهولة باستخدام هذه الخاصية البديهية. |
| [getFileFormat()](#getFileFormat--) | استرجع تنسيق ملف الصورة بسهولة باستخدام هذه الخاصية البديهية. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [cacheData()](#cacheData--) | قم بتخزين البيانات مؤقتًا بسهولة لمنع التحميل الإضافي من المصدر الأساسي باستخدام هذه الطريقة سهلة الاستخدام. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | خصّص لوحة ألوان الصورة باستخدام هذه الطريقة البديهية. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// حمّل صورة من ملف CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // هذه العملية تُخزن في الذاكرة المؤقتة الصفحة الافتراضية فقط.
    image.cacheData();

    // خزن جميع الصفحات في الذاكرة المؤقتة بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


ابدأ العمل مع الفئة [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) بسهولة عن طريق إنشاء نسخة جديدة باستخدام معلمات stream و loadOptions. هذه الطريقة مثالية للمطورين الذين يبحثون عن طريقة مريحة لتحميل صور CDR من مصادر بيانات متعددة مع تخصيص عملية التحميل حسب الحاجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


ابدأ العمل مع الفئة [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) بسهولة عن طريق إنشاء نسخة جديدة باستخدام معلمات stream و loadOptions. هذه الطريقة مثالية للمطورين الذين يبحثون عن طريقة مريحة لتحميل صور CDR من مصادر بيانات متعددة مع تخصيص عملية التحميل حسب الحاجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | com.aspose.ms.System.IO.Stream | المجرى. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


استرجع الصفحة الافتراضية للصورة بسهولة باستخدام هذه الخاصية سهلة الاستخدام. إنها مثالية للمطورين الذين يرغبون في الوصول السريع إلى الصفحة الرئيسية لصورتهم، مما يضمن تنقلًا وإدارةً فعّالة.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


حدد بسهولة ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة البيانات. هذه الميزة مثالية للمطورين الذين يسعون لتحسين الأداء من خلال الاستفادة من البيانات المخزنة مؤقتًا بفعالية، مما يضمن وصولًا أسرع إلى معلومات الكائن.

**Returns:**
منطقي - `true` إذا كانت بيانات الكائن مخزنة مؤقتًا؛ وإلا `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


استرجع عمق البت للصورة بسهولة باستخدام هذه الخاصية سهلة الاستخدام. مثالي للمطورين الذين يرغبون في تحديد مستوى التفاصيل أو عمق اللون الموجود في صورهم، مما يضمن معالجة دقيقة وتعديلًا فعالًا.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


استرجع أو حدّث إجمالي عدد صفحات الصورة بسهولة باستخدام هذه الخاصية البديهية. هذه الميزة مثالية للمطورين الذين يرغبون في إدارة الصور متعددة الصفحات بشكل ديناميكي، مما يضمن تنقلًا فعالًا وتلاعبًا بمحتوى الصورة.

**Returns:**
int - عدد الصفحات.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في الوصول إلى الصفحات الفردية داخل الصور متعددة الصفحات ومعالجتها، مع ضمان تنقل فعال ومعالجة.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


استرجع أو حدّث مستند CDR بسهولة باستخدام هذه الخاصية البديهية. هذه الميزة مثالية للمطورين الذين يرغبون في الوصول إلى مستند CDR أو تعديله، مما يضمن المرونة والكفاءة في تطبيقاتهم.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع تنسيق ملف الصورة بسهولة باستخدام هذه الخاصية البديهية. هذه الميزة مثالية للمطورين الذين يرغبون في تحديد تنسيق صورهم بشكل ديناميكي، مما يضمن التوافق والمعالجة الدقيقة في تطبيقاتهم.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

القيمة: عرض الصورة.

**Returns:**
int - عرض الصورة.
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

القيمة: ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
### cacheData() {#cacheData--}
```
public void cacheData()
```


قم بتخزين البيانات مؤقتًا بسهولة لمنع التحميل الإضافي من المصدر الأساسي باستخدام هذه الطريقة سهلة الاستخدام. هذه الميزة مثالية للمطورين الذين يسعون لتحسين الأداء من خلال تحميل البيانات مسبقًا، مما يضمن وصولًا أسرع وعملًا أكثر سلاسة في تطبيقاتهم. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// حمّل صورة من ملف CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // هذه العملية تُخزن في الذاكرة المؤقتة الصفحة الافتراضية فقط.
    image.cacheData();

    // خزن جميع الصفحات في الذاكرة المؤقتة بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


خصص لوحة ألوان الصورة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تطبيق أنماط ألوان محددة أو تعديلات بشكل ديناميكي، مع ضمان تحكم دقيق في المظهر البصري لصورهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

