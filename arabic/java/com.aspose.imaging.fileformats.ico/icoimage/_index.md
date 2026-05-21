---
title: "IcoImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعديل ملفات صور ICO بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تدعم صيغ ملفات متعددة وأنواع إطارات تشمل PNG و BMP."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

تعديل ملفات صور ICO بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، التي تدعم صيغ ملفات متعددة وأنواع إطارات تشمل PNG و BMP. قم بتخصيص إعدادات البتات لكل بكسل وتحديث أبعاد الصورة بسلاسة، مما يضمن تمثيلًا مثاليًا وتوافقًا لأيقوناتك عبر مختلف المنصات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | ابدأ إنشاء صورة ICO بسهولة باستخدام الفئة [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | صُممت للبساطة والكفاءة، تمكّنك الفئة [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) من إنشاء صور ICO بسهولة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | احصل على صيغة الملف بسهولة باستخدام هذه الخاصية، مما يتيح دمجًا سلسًا في سير عملك. |
| [getPageCount()](#getPageCount--) | احصل على نظرة فورية على بنية المستند باستخدام هذه الخاصية البسيطة. |
| [getPages()](#getPages--) | استرجع معلومات شاملة حول صفحات المستند بسهولة عبر هذه الخاصية. |
| [hasAlpha()](#hasAlpha--) | حدد ما إذا كان قناة ألفا موجودة في هذه الحالة باستخدام هذه الخاصية. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | قم بتوسيع صورة ICO الخاصة بك بإضافة إدخال صفحة صورة، مستفيدًا من [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | قم بإثراء صورة ICO الخاصة بك بسهولة عن طريق إدراج إدخال صفحة صورة باستخدام الإعدادات الافتراضية من [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | قم بتنويع صورة ICO الخاصة بك بسهولة عبر دمج إدخال صورة مخصص لاحتياجاتك باستخدام [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) المحدد. |
| [removePage(int index)](#removePage-int-) | قم بضبط صورة ICO الخاصة بك بدقة عن طريق إزالة إدخال صورة محدد يقع في `` المحدد داخل الملف. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


ابدأ إنشاء صورة ICO بسهولة باستخدام الفئة [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). يتيح لك هذا المُنشئ تهيئة نماذج جديدة من صور ICO عن طريق تحديد العرض والارتفاع ومعلمات خيارات الإنشاء. باستخدام هذا المُنشئ البسيط، يمكنك تخصيص صور ICO وفقًا لمواصفاتك الدقيقة، مما يضمن توافقًا سلسًا وجاذبية بصرية عبر مختلف المنصات والأجهزة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | خيارات إنشاء ICO. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


صُممت للبساطة والكفاءة، تمكّنك الفئة [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) من إنشاء صور ICO بسهولة. يقوم هذا المُنشئ بتهيئة نسخة جديدة من الفئة، موفرًا أساسًا قويًا لاحتياجاتك في معالجة الصور. سواءً كنت تطور تطبيقات أو تحسن واجهات المستخدم، تُبسّط الفئة [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) إدارة صور ICO، مما يتيح لك التركيز على تقديم تجارب استثنائية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الصورة. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | خيارات ICO. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع تنسيق الملف بسهولة باستخدام هذه الخاصية، مما يتيح دمجًا سلسًا في سير عملك. باستخدام هذه الخاصية، تحصل على معلومات حيوية حول تنسيق ملفك، مما يضمن التوافق والمعالجة الفعّالة.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


احصل على نظرة فورية على بنية المستند باستخدام هذه الخاصية البسيطة. عند استدعاء هذه الخاصية، تسترجع بسهولة العدد الإجمالي للصفحات الموجودة في الملف.

**Returns:**
int - عدد الصفحات.
### getPages() {#getPages--}
```
public Image[] getPages()
```


استرجع معلومات شاملة حول صفحات المستند بسهولة عبر هذه الخاصية. من خلال الوصول إلى هذه الخاصية، تحصل على مجموعة أو مصفوفة تحتوي على جميع الصفحات الموجودة في المستند.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


حدد ما إذا كانت قناة ألفا موجودة في هذه الحالة باستخدام هذه الخاصية. توفر طريقة سريعة للتحقق مما إذا كانت الصورة أو المستند يحتوي على قناة ألفا، وهو أمر حاسم لمهام معالجة الصور والعرض المختلفة. مثالية لضمان التوافق ومعالجة تأثيرات الشفافية في الصور أو المستندات.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان لهذا الكائن ألفا.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


قم بتوسيع صورة ICO الخاصة بك بإضافة إدخال صفحة صورة، مستفيدًا من [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). يدمج هذه الطريقة الصور النقطية بسلاسة في ملف ICO الخاص بك، محوّلةً إياها إلى تنسيق PNG عالي الجودة 32‑بت. مثالية لتعزيز ملفات ICO الخاصة بك بالصور النقطية مع ضمان التوافق الأمثل وجودة العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


قم بإثراء صورة ICO الخاصة بك بسهولة عن طريق إدراج إدخال صفحة صورة باستخدام الإعدادات الافتراضية من [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). تقوم هذه الطريقة بتحويل الصورة المدخلة إلى تنسيق PNG 32‑بت بسهولة، مما يضمن التوافق وعرضًا عالي الجودة داخل صورة ICO. مثالية لدمج صور PNG بسلاسة في ملفات ICO بسهولة وكفاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | الصورة. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


قم بتنويع صورة ICO الخاصة بك بسهولة عبر دمج إدخال صورة مخصص لاحتياجاتك باستخدام [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) المحدد. تدمج هذه الطريقة الصورة بسلاسة وفقًا لخياراتك المخصصة، مما يضمن المرونة والدقة في ملف ICO الخاص بك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | الصورة. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | خيارات ICO. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


قم بضبط صورة ICO الخاصة بك بدقة عن طريق إزالة إدخال صورة محدد يقع في `` المحدد داخل الملف. توفر هذه الطريقة تحكمًا دقيقًا في تكوين الصورة، مما يتيح لك تحسين ملف ICO بسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |

