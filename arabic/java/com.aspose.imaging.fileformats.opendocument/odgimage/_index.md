---
title: "OdgImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تفاعل مع تنسيق ملف الصورة المتجهة OpenDocument Graphic ODG باستخدام واجهة برمجة التطبيقات الخاصة بنا، وهو تنسيق يُستخدم على نطاق واسع في تطبيقات OpenOffice وLibreOffice Draw لتخزين عناصر الرسم بصيغة متجهة."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

تفاعل مع تنسيق ملف الصورة المتجهة OpenDocument Graphic (ODG) باستخدام واجهة برمجة التطبيقات الخاصة بنا، وهو تنسيق يُستخدم على نطاق واسع في تطبيقات OpenOffice وLibreOffice Draw لتخزين عناصر الرسم بصيغة متجهة. قم بتحليل المستندات بسلاسة، والوصول إلى الصفحات، وتغيير حجم الصور وتدويرها، مما يضمن معالجة فعّالة وتخصيص ملفات ODG لتلبية متطلباتك الخاصة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | ابدأ إنشاء كائن من فئة [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) جديد ببدء نسخة جديدة. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | صُمم للتكامل السلس في حلول البرمجيات، يقوم مُنشئ [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) بتهيئة نسخة جديدة باستخدام حاوية تدفق. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | استرجع بسهولة قيمة تنسيق الملف باستخدام هذه الخاصية السهلة الاستخدام. |
| [getPages()](#getPages--) | من خلال استرجاع مجموعة الصفحات، تتيح هذه الخاصية الوصول إلى جميع الصفحات المرتبطة بصورة. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل الصورة.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // تحويل إلى OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // احصل على جميع الصفحات
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // قم ببعض معالجة الصورة.
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


ابدأ إنشاء كائن من فئة [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) جديد ببدء نسخة جديدة. استغل إمكانات حاوية التدفق المرفقة بمعلمات خيارات التحميل، وحافظ على مُنشئ متعدد الاستخدامات لتحميل الصور بسلاسة. يتيح هذا المُنشئ معالجة صور فعّالة، مع توفير تكوينات تحميل قابلة للتخصيص لتعزيز التكيف والأداء عبر سيناريوهات متنوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | المجرى. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


صُمم للتكامل السلس في حلول البرمجيات، يقوم مُنشئ [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) بتهيئة نسخة جديدة باستخدام حاوية تدفق. تضمن هذه الطريقة التعامل الفعّال مع بيانات صور ODG داخل بيئات البرمجيات، مع تحسين استهلاك الموارد وتسهيل سير عمل معالجة الصور بسلاسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية الصديقة للمستخدم. مثالية للمطورين الذين يبحثون عن وصول سريع إلى معلومات حول تنسيق الملف.

**Returns:**
long - قيمة تنسيق الملف
### getPages() {#getPages--}
```
public Image[] getPages()
```


من خلال استرجاع مجموعة الصفحات، تتيح هذه الخاصية الوصول إلى جميع الصفحات المرتبطة بصورة. عبر الوصول إلى هذه الخاصية، يمكن للمطورين التنقل عبر الصفحات الفردية، استرجاع صفحات محددة بناءً على فهرسها، أو تنفيذ عمليات دفعة على المجموعة بأكملها.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.
