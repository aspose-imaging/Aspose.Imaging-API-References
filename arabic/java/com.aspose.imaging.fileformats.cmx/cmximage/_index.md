---
title: "CmxImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لتنسيق صورة المتجهات CMX من Corel Metafile Exchange مع دعم أوصاف البيانات الوصفية هي حل شامل للمطورين الذين يعملون مع ملفات CMX."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

واجهة برمجة التطبيقات لتنسيق صورة المتجهات Corel Metafile Exchange (CMX) مع دعم أوصاف البيانات الوصفية هي حل شامل للمطورين الذين يعملون مع ملفات CMX. تتيح هذه الواجهة تحميل صور CMX بسلاسة، واستخراج البيانات الوصفية مثل عدد البتات لكل بكسل، أبعاد الكائن، والمزيد. مع وظائف إضافية مثل تغيير الحجم، الدوران، ضبط اللوحات اللونية، والتحويل إلى صيغ أخرى، تمكّن هذه الواجهة المطورين من معالجة وتخصيص صور المتجهات CMX بفعالية لتلبية متطلبات تطبيقاتهم المحددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | ابدأ العمل مع الفئة [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) بسلاسة عن طريق إنشاء مثيل جديد باستخدام معلمات streamContainer و loadOptions. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | استرجع تنسيق الملف للصورة بسهولة باستخدام هذه الخاصية السهلة الاستخدام. |
| [getBitsPerPixel()](#getBitsPerPixel--) | استرجع عمق البت للصورة بسهولة باستخدام هذه الخاصية السهلة الاستخدام. |
| [getDefaultPage()](#getDefaultPage--) | استرجع الصفحة الافتراضية للصورة بسهولة باستخدام هذه الخاصية البديهية. |
| [isCached()](#isCached--) | حدد ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة البيانات. |
| [getWidthF()](#getWidthF--) | استرجع عرض الكائن بالبوصة باستخدام هذه الخاصية البديهية. |
| [getHeightF()](#getHeightF--) | احصل على ارتفاع الكائن، مقاسًا بالبوصة، بسهولة باستخدام هذه الخاصية السهلة الاستخدام. |
| [getDocument()](#getDocument--) | استرجع مستند CMX بسهولة باستخدام هذه الخاصية البديهية. |
| [getCmxPage()](#getCmxPage--) | استرجع صفحة CMX للصورة بسهولة باستخدام هذه الخاصية البديهية. |
| [getPageCount()](#getPageCount--) | استرجع العدد الإجمالي للصفحات في الصورة باستخدام هذه الخاصية البديهية. |
| [getPages()](#getPages--) | استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. |
| [cacheData()](#cacheData--) | قم بتخزين البيانات مؤقتًا لمنع التحميل الإضافي من المصدر الأساسي [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) باستخدام هذه الطريقة المريحة. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | خصص لوحة ألوان الصورة باستخدام هذه الطريقة البديهية. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// تحميل صورة من ملف CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // هذه العملية تخزن مؤقتًا الصفحة الافتراضية فقط.
    image.cacheData();

    // قم بتخزين جميع الصفحات مؤقتًا حتى لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


ابدأ العمل مع الفئة [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) بسلاسة عن طريق إنشاء مثيل جديد باستخدام معلمات streamContainer و loadOptions. مثالي للمطورين الذين يبحثون عن طريقة مريحة لتحميل صور CMX من مصادر بيانات مختلفة مع تخصيص عملية التحميل حسب الحاجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع تنسيق الملف للصورة بسهولة باستخدام هذه الخاصية السهلة الاستخدام. مثالي للمطورين الذين يرغبون في تحديد تنسيق صورهم بشكل ديناميكي، مما يضمن التوافق والمعالجة الدقيقة في تطبيقاتهم.

**Returns:**
long - تنسيق الملف [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


استرجع عمق البت للصورة بسهولة باستخدام هذه الخاصية السهلة الاستخدام. مثالي للمطورين الذين يرغبون في تحديد مستوى التفاصيل أو عمق اللون الموجود في صورهم، مما يضمن معالجة وتعديلًا دقيقًا.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


استرجع بسهولة الصفحة الافتراضية للصورة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يبحثون عن وصول سريع إلى الصفحة الرئيسية لصورتهم، مما يضمن تنقلاً وإدارةً فعالين.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


حدد ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة البيانات. مثالية للمطورين الذين يرغبون في تحسين الأداء من خلال الاستفادة من البيانات المخزنة مؤقتًا بكفاءة، مما يضمن وصولًا أسرع إلى معلومات الكائن.

**Returns:**
منطقي - `true` إذا كانت بيانات الكائن مخزنة مؤقتًا؛ وإلا `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


استرجع عرض الكائن بالبوصة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يحتاجون إلى قياسات دقيقة للكائنات في تطبيقاتهم، مما يضمن تخطيطًا وعرضًا دقيقين.

**Returns:**
float - عرض الكائن، بالبوصة.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


احصل بسهولة على ارتفاع الكائن، مقاسًا بالبوصة، باستخدام هذه الخاصية السهلة الاستخدام. مثالية للمطورين الذين يحتاجون إلى معلومات أبعاد دقيقة لتخطيط وعرض فعال في تطبيقاتهم.

**Returns:**
float - ارتفاع الكائن، بالبوصة.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


استرجع مستند CMX بسهولة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يرغبون في الوصول إلى صور CMX أو تعديلها، مما يضمن مرونة وكفاءة في تطبيقاتهم.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


استرجع بسهولة صفحة CMX للصورة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يبحثون عن وصول سريع إلى الصفحات الفردية داخل صور CMX، مما يضمن تنقلاً وإدارةً فعالين.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع إجمالي عدد صفحات الصورة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يرغبون في إدارة الصور متعددة الصفحات ديناميكيًا، مما يضمن تنقلاً فعالًا ومعالجة محتوى الصورة.

**Returns:**
int - عدد الصفحات.
### getPages() {#getPages--}
```
public Image[] getPages()
```


استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يرغبون في الوصول إلى الصفحات الفردية داخل الصور متعددة الصفحات ومعالجتها، مما يضمن تنقلاً فعالًا ومعالجة.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة من ملف CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // هذه العملية تخزن مؤقتًا الصفحة الافتراضية فقط.
    image.cacheData();

    // قم بتخزين جميع الصفحات مؤقتًا حتى لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


قم بتخزين البيانات مؤقتًا لمنع تحميل إضافي من المصدر الأساسي [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) باستخدام هذه الطريقة المريحة. مثالية للمطورين الذين يسعون لتحسين الأداء من خلال تحميل البيانات مسبقًا، مما يضمن وصولًا أسرع وعملًا أكثر سلاسة في تطبيقاتهم.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة من ملف CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // هذه العملية تخزن مؤقتًا الصفحة الافتراضية فقط.
    image.cacheData();

    // قم بتخزين جميع الصفحات مؤقتًا حتى لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
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


خصص لوحة ألوان الصورة باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يرغبون في تطبيق أنظمة ألوان أو تعديلات محددة ديناميكيًا، مما يضمن تحكمًا دقيقًا في المظهر البصري لصورهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

