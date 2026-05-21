---
title: "ApngImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لتنسيق ملف صورة Animated PNG Animated Portable Network Graphics هي حل متعدد الاستخدامات للمطورين الذين يتطلعون إلى دمج محتوى متحرك في تطبيقاتهم."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

واجهة برمجة التطبيقات لتنسيق ملف صورة Animated PNG (Animated Portable Network Graphics) هي حل متعدد الاستخدامات للمطورين الذين يرغبون في دمج محتوى متحرك في تطبيقاتهم. توفر هذه الواجهة تحكمًا واسعًا في إعدادات الإطارات، مما يسمح للمستخدمين بتحديد معلمات خاصة بالإطار، بما في ذلك مدة الحلقة وإعدادات ملف PNG. باستخدام هذه الأداة الغنية بالميزات، يمكنك بسهولة إدارة وتحسين عرض صور APNG، واستيراد وتصدير الصور، مما يعزز الجوانب الديناميكية والتفاعلية لتطبيقاتك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | ابدأ العمل مع الفئة [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) عن طريق إنشاء نسخة جديدة بسهولة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | احصل بسرعة على معلومات حول تنسيق الملف باستخدام هذه الخاصية المريحة. |
| [getPageCount()](#getPageCount--) | استرجع إجمالي عدد الصفحات في ملف الصورة الخاص بك بسهولة باستخدام هذه الخاصية. |
| [getPages()](#getPages--) | يمكنك بسهولة الوصول إلى صفحات صورتك باستخدام هذه الخاصية المريحة. |
| [getNumPlays()](#getNumPlays--) | تحكم بسهولة في عدد مرات تكرار الرسوم المتحركة الخاصة بك باستخدام هذه الخاصية المتعددة الاستخدامات. |
| [setNumPlays(int value)](#setNumPlays-int-) | تحكم بسهولة في عدد مرات تكرار الرسوم المتحركة الخاصة بك باستخدام هذه الخاصية المتعددة الاستخدامات. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | قم بضبط مدة الإطار الافتراضية لإنشاء إطارات جديدة بسهولة باستخدام هذه الخاصية المرنة. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | قم بضبط مدة الإطار الافتراضية لإنشاء إطارات جديدة بسهولة باستخدام هذه الخاصية المرنة. |
| [getInterlaced()](#getInterlaced--) | حدد بسرعة ما إذا كان كائن [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) هذا متشابكًا باستخدام هذه الخاصية المريحة. |
| [getOriginalOptions()](#getOriginalOptions--) | استرجع الخيارات بناءً على إعدادات الملف الأصلي بسهولة باستخدام هذه الطريقة البديهية. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة البسيطة. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | احصل بسرعة على التاريخ والوقت عندما تم تعديل صورة المورد آخر مرة باستخدام هذه الطريقة السهلة الاستخدام. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | أضف صفحة جديدة إلى الصورة بسهولة باستخدام هذه الطريقة البديهية. |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | قم بتوسيع مجموعة الإطارات الخاصة بك بسهولة عن طريق إضافة إطار جديد في النهاية باستخدام هذه الطريقة البديهية. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | قم بتوسيع مجموعة الإطارات الخاصة بك بسلاسة عن طريق إلحاق إطار جديد إلى المجموعة باستخدام هذه الطريقة البديهية. |
| [insertFrame(int index)](#insertFrame-int-) | أدرج إطارًا جديدًا في مجموعة الإطارات الخاصة بك في الموقع المحدد بسهولة باستخدام هذه الطريقة البديهية. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | يدرج إطارًا جديدًا في مجموعة الإطارات الخاصة به عند الفهرس المحدد. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | يدرج إطارًا جديدًا في مجموعة الإطارات الخاصة به عند الفهرس المحدد. |
| [popFrameAt(int index)](#popFrameAt-int-) | قم بإزالة واسترجاع الإطار عند الفهرس المحدد من مجموعة الإطارات الخاصة بك باستخدام هذه الطريقة البديهية. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | قم بإزالة الإطار عند الفهرس المحدد من مجموعة الإطارات الخاصة بك بسلاسة باستخدام هذه الطريقة. |
| [removeAllFrames()](#removeAllFrames--) | امسح مجموعة الإطارات الخاصة بك عن طريق إزالة جميع الإطارات باستخدام هذه الطريقة البديهية. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | عيّن الصورة النقطية المحددة كالصورة الافتراضية للرسوم المتحركة الحالية بسهولة باستخدام هذه الطريقة. |
| [resetDefaultImage()](#resetDefaultImage--) | إزالة الصورة الافتراضية التي تم تعيينها مسبقًا باستخدام هذه الطريقة البديهية. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // تصدير إلى رسوم متحركة بصيغة APNG مع دورات حركة غير محدودة كإعداد افتراضي
    image.save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الحركة
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // إعداد مدة الإطار الافتراضية
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


ابدأ العمل مع الفئة [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) عن طريق تهيئة نسخة جديدة بسهولة. مثالي للمطورين الذين يرغبون في بدء استخدام كائنات ApngImage بسرعة وكفاءة في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | الخيارات. |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


احصل بسرعة على معلومات حول تنسيق الملف باستخدام هذه الخاصية المريحة. مثالي للمطورين الذين يحتاجون إلى استرجاع تفاصيل تنسيق ملفات Apng الخاصة بهم بسهولة.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع إجمالي عدد الصفحات في ملف الصورة الخاص بك بسهولة باستخدام هذه الخاصية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى معلومات عدد الصفحات.

القيمة: عدد الصفحات.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


الوصول بسهولة إلى صفحات صورتك باستخدام هذه الخاصية المريحة. مثالي للمطورين الذين يبحثون عن وصول سريع وسهل إلى الصفحات الفردية للتعديل.

القيمة: الصفحات.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


تحكم بسهولة في عدد مرات تكرار الرسوم المتحركة باستخدام هذه الخاصية المتعددة الاستخدامات. مثالي للمطورين الذين يسعون إلى تحكم دقيق في سلوك الرسوم المتحركة، مع دعم التكرار اللانهائي في حال كانت القيمة تساوي 0.

القيمة: عدد مرات التكرار.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


تحكم بسهولة في عدد مرات تكرار الرسوم المتحركة باستخدام هذه الخاصية المتعددة الاستخدامات. مثالي للمطورين الذين يسعون إلى تحكم دقيق في سلوك الرسوم المتحركة، مع دعم التكرار اللانهائي في حال كانت القيمة تساوي 0.

القيمة: عدد مرات التكرار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


قم بضبط مدة الإطار الافتراضية لإنشاء إطارات جديدة بسهولة باستخدام هذه الخاصية المرنة. مثالي للمطورين الذين يرغبون في تخصيص توقيت الإطارات بفعالية في رسومهم المتحركة.

القيمة: مدة الإطار الافتراضية، بالمللي ثانية.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


قم بضبط مدة الإطار الافتراضية لإنشاء إطارات جديدة بسهولة باستخدام هذه الخاصية المرنة. مثالي للمطورين الذين يرغبون في تخصيص توقيت الإطارات بفعالية في رسومهم المتحركة.

القيمة: مدة الإطار الافتراضية، بالمللي ثانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


حدد بسرعة ما إذا كان كائن [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) هذا متشابكًا باستخدام هذه الخاصية المريحة. مثالي للمطورين الذين يحتاجون إلى فحص حالة التشابك لصور PNG بسهولة.

القيمة: `true` إذا كان متشابكًا؛ وإلا `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


استرجع الخيارات بناءً على إعدادات الملف الأصلي بسهولة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في الوصول إلى الإعدادات واستخدامها بما يتوافق مع خصائص الملف الأصلي. يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة المبسطة. مثالي للمطورين الذين يبحثون عن وصول سريع إلى إعدادات صورة Apng الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعلمات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


احصل بسرعة على التاريخ والوقت عندما تم تعديل صورة المورد آخر مرة باستخدام هذه الطريقة السهلة الاستخدام. مثالي للمطورين الذين يحتاجون إلى تتبع التغييرات وإدارة الموارد بفعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| useDefault | boolean | إذا تم تعيينه إلى `true` يستخدم المعلومات من FileInfo كقيمة افتراضية. |

**Returns:**
java.util.Date - التاريخ والوقت الذي تم فيه تعديل صورة المورد آخر مرة.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


أضف صفحة جديدة إلى الصورة بسهولة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في توسيع محتوى ملفات الصور الخاصة بهم بشكل ديناميكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | الصفحة التي سيتم إضافتها. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

قم بإضافة إطار جديد إلى نهاية مجموعة الإطارات الخاصة بك بسهولة باستخدام هذه الطريقة المبسطة. مثالي للمطورين الذين يرغبون في توسيع مجموعة إطاراتهم بشكل ديناميكي للرسوم المتحركة ذات الصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


قم بتوسيع مجموعة إطاراتك بسهولة بإضافة إطار جديد إلى النهاية باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون لتعزيز رسومهم المتحركة للصور متعددة الإطارات بشكل ديناميكي. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة الإطار. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


قم بتوسيع مجموعة إطاراتك بسلاسة عن طريق إلحاق إطار جديد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إثراء رسومهم المتحركة للصور متعددة الإطارات. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة الإطار. |
| frameTime | long | مدة الإطار، بالمللي ثانية. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


قم بإدراج إطار جديد بسهولة في مجموعة إطاراتك في الموضع المحدد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون إلى تحكم دقيق في ترتيب الإطارات في رسومهم المتحركة للصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


يُدرج إطارًا جديدًا في مجموعة الإطارات الخاصة به عند الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة الإطار. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


يُدرج إطارًا جديدًا في مجموعة الإطارات الخاصة به عند الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة الإطار. |
| frameTime | long | مدة الإطار، بالمللي ثانية. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


قم بإزالة واسترجاع الإطار عند الفهرس المحدد من مجموعة إطاراتك باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون إلى إدارة فعّالة للإطارات في رسومهم المتحركة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


قم بإزالة الإطار عند الفهرس المحدد من مجموعة إطاراتك بسلاسة باستخدام هذه الطريقة. مثالي للمطورين الذين يسعون إلى إدارة مبسطة للإطارات في صورهم متعددة الإطارات. سيتم التخلص من الإطار المراد حذفه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


امسح مجموعة الإطارات الخاصة بك عن طريق إزالة جميع الإطارات باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يسعون لإعادة ضبط أو تحديث الرسوم المتحركة الخاصة بهم.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


عيّن الصورة النقطية المحددة كالصورة الافتراضية للرسوم المتحركة الحالية بسهولة باستخدام هذه الطريقة. مثالية للمطورين الذين يرغبون في تخصيص الصورة الافتراضية في رسومهم المتحركة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


أزل الصورة الافتراضية التي تم تعيينها مسبقًا باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يسعون لإعادة ضبط أو مسح الصورة الافتراضية في الرسوم المتحركة الخاصة بهم. بعد ذلك، تصبح الصورة الافتراضية هي الإطار الأول في مجموعة الإطارات الخاصة (لا يمكن حذفها باستخدام هذه الطريقة).

