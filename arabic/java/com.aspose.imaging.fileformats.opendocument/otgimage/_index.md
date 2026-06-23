---
title: "OtgImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "عالج ملفات صور رسومات قالب OpenDocument OTG باستخدام واجهة برمجة التطبيقات الخاصة بنا مستفيدًا من تنسيق OpenDocument XML مع محتوى الرسومات لتسهيل المعالجة."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

عالج ملفات صور رسومات قالب OpenDocument (OTG) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من تنسيق OpenDocument XML مع محتوى الرسومات لتسهيل المعالجة. قم بتحليل المستندات بسهولة، وتخصيص ألوان الخلفية، وضبط أبعاد الصفحات، لضمان تحكم أمثل ومرونة لمشاريع الرسومات المتجهة OTG الخاصة بك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | قم بتهيئة كائن [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) جديد عن طريق توفير حاوية تدفق وخيارات التحميل. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | أنشئ كائنًا جديدًا من فئة [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) عن طريق تزويد حاوية تدفق. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | توفر هذه الخاصية الوصول إلى تنسيق ملف OTG، وتقدم رؤى حاسمة حول نوع البيانات المضمنة داخل ملف الصورة. |
| [getPages()](#getPages--) | تسترجع مجموعة الصفحات المرتبطة بالصورة، مما يتيح لمطوري البرمجيات الوصول إلى كل صفحة على حدة ومعالجتها بكفاءة. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


قم بتهيئة كائن [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) جديد عن طريق توفير حاوية تدفق وخيارات التحميل. يتيح هذا المُنشئ للمطورين تحميل صور OTG من التدفقات بكفاءة مع تحديد تكوينات تحميل مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | التدفق. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


أنشئ كائنًا جديدًا من فئة [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) عن طريق تزويد حاوية تدفق. يتيح هذا المُنشئ للمطورين إنشاء صور OTG مباشرةً من حاويات التدفق، مما يبسط عملية التعامل مع بيانات صور OTG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


توفر هذه الخاصية الوصول إلى تنسيق ملف OTG، وتقدم رؤى حاسمة حول نوع البيانات المضمنة داخل ملف الصورة. تُعد نقطة مرجعية محورية لمطوري البرمجيات، مما يتيح لهم التعامل بفعالية مع ملفات OTG ضمن تطبيقاتهم. باستخدام هذه الخاصية، يمكنك تحديد الصيغة المحددة لملف الصورة، مما يسهل دمج ومعالجة ملفات OTG بسلاسة في أنظمة البرمجيات الخاصة بهم.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


تسترجع مجموعة الصفحات المرتبطة بالصورة، مما يتيح لمطوري البرمجيات الوصول إلى كل صفحة على حدة ومعالجتها بكفاءة. تُسهل هذه الخاصية التنقل السلس عبر الصفحات للقيام بعمليات مختلفة، مما يعزز وظائف وتنوع تطبيقات معالجة الصور.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.
