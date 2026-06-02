---
title: "OtgImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "معالجة ملفات صور رسم قالب OpenDocument (OTG) باستخدام واجهة برمجة التطبيقات الخاصة بنا مع الاستفادة من تنسيق XML الخاص بـ OpenDocument مع محتوى الرسومات لتسهيل التلاعب."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

معالجة ملفات صور رسم قالب OpenDocument (OTG) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع الاستفادة من تنسيق XML الخاص بـ OpenDocument مع محتوى الرسومات لتسهيل التلاعب. قم بتحليل المستندات بسهولة، وتخصيص ألوان الخلفية، وضبط أبعاد الصفحات، مما يضمن تحكمًا مثاليًا ومرونة لمشاريع رسوماتك المتجهة OTG.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | قم بتهيئة كائن [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) جديد عن طريق توفير حاوية تدفق وخيارات التحميل. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | أنشئ كائنًا جديدًا من فئة [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) عن طريق تزويده بحاوية تدفق. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | توفر هذه الخاصية الوصول إلى تنسيق ملف OTG، وتقدم رؤى حاسمة حول نوع البيانات المضمنة داخل ملف الصورة. |
| [getPages()](#getPages--) | تسترجع مجموعة الصفحات المرتبطة بالصورة، مما يتيح للمطورين الوصول إلى كل صفحة على حدة ومعالجتها بكفاءة. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


قم بتهيئة كائن [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) جديد عن طريق توفير حاوية تدفق وخيارات التحميل. يتيح هذا المُنشئ للمطورين تحميل صور OTG من التدفقات بكفاءة مع تحديد تكوينات تحميل مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | المجرى. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


أنشئ كائنًا جديدًا من فئة [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) عن طريق تزويده بحاوية تدفق. يتيح هذا المُنشئ للمطورين إنشاء صور OTG مباشرةً من حاويات التدفق، مما يبسط عملية التعامل مع بيانات صور OTG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


توفر هذه الخاصية الوصول إلى تنسيق ملف OTG، وتقدم رؤى حاسمة حول نوع البيانات المضمنة داخل ملف الصورة. تُعد نقطة مرجعية أساسية للمطورين، مما يتيح لهم التعامل بفعالية مع ملفات OTG داخل تطبيقاتهم. باستخدام هذه الخاصية، يمكنك تحديد تنسيق ملف الصورة بدقة، مما يسهل التكامل السلس ومعالجة ملفات OTG في أنظمة البرمجيات الخاصة بهم.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


تسترجع مجموعة الصفحات المرتبطة بالصورة، مما يتيح للمطورين الوصول إلى كل صفحة على حدة ومعالجتها بكفاءة. تسهّل هذه الخاصية التنقل السلس عبر الصفحات للقيام بعمليات مختلفة، مما يعزز وظائف وتنوع تطبيقات معالجة الصور.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.
