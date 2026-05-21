---
title: "OdImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "المستند المفتوح"
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

المستند المفتوح
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | تسترجع الصفحة الافتراضية المرتبطة بالصورة، مما يوفر وصولًا أساسيًا إلى الصفحة الرئيسية ضمن مجموعة الصور. |
| [isCached()](#isCached--) | يحصل على قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة البيانات. |
| [getBitsPerPixel()](#getBitsPerPixel--) | تسترجع عدد البتات لكل بكسل في الصورة. |
| [getPageCount()](#getPageCount--) | يسترجع العدد الإجمالي للصفحات داخل الصورة. |
| [getOdMetadata()](#getOdMetadata--) | يسترجع البيانات الوصفية الخاصة بملفات OpenDocument. |
| [getRecords()](#getRecords--) | يسترجع سجلات OpenDocument المخزنة داخل الصورة. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


يسترجع الصفحة الافتراضية المرتبطة بالصورة، مما يوفر وصولًا أساسيًا إلى الصفحة الرئيسية ضمن مجموعة الصور. تُسهل هذه الخاصية التنقل ومعالجة بيانات الصورة، مما يعزز كفاءة سير عمل تطوير البرمجيات.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة منطقية تُشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة البيانات. تُعد هذه الخاصية مؤشرًا على التحسين، وتُحسّن الأداء من خلال تقليل عمليات الوصول المتكررة للبيانات.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يسترجع عدد البتات لكل بكسل في الصورة. تُوفر هذه الخاصية نظرة على مستوى التفاصيل وعمق الألوان المُمَثَّل في الصورة، مما يساعد في مهام معالجة الصور المختلفة والتحسينات.

**Returns:**
int - عدد البتات لكل بكسل في الصورة.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


يسترجع العدد الإجمالي للصفحات داخل الصورة. تُعد هذه الخاصية أساسية للتطبيقات التي تدير صورًا متعددة الصفحات، مما يتيح لها تحديد عدد الصفحات المتاحة للمعالجة أو العرض بدقة.

**Returns:**
int - عدد الصفحات.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


يسترجع البيانات الوصفية الخاصة بملفات OpenDocument. تُتيح هذه الخاصية الوصول إلى المعلومات الأساسية المدمجة داخل ملفات OD، مما يُسهل عمليات مختلفة مثل الاستخراج أو التعديل أو تحليل البيانات الوصفية.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


يسترجع سجلات OpenDocument المخزنة داخل الصورة. تُمنح هذه الخاصية الوصول إلى عناصر بيانات مُهيكلة محددة مدمجة داخل ملفات OpenDocument، مما يُسهل استرجاع أو معالجة المعلومات ذات الصلة لمزيد من المعالجة أو التحليل.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - السجلات.
