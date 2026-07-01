---
title: "ApngOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لإنشاء تنسيق ملف صورة متحركة Animated PNG (Animated Portable Network Graphics) هي أداة ديناميكية للمطورين الذين يسعون لإنشاء صور متحركة جذابة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

واجهة برمجة التطبيقات لإنشاء تنسيق ملف صورة Animated PNG (Animated Portable Network Graphics) هي أداة ديناميكية للمطورين الذين يسعون لتوليد صور متحركة جذابة. مع خيارات قابلة للتخصيص مثل مدة الإطار وعدد مرات التكرار، تتيح هذه الواجهة ضبط المحتوى المتحرك وفقًا للاحتياجات المحددة. سواءً كنت تنشئ رسومات ويب جذابة أو مرئيات تفاعلية، يمكنك الاستفادة من هذه الواجهة لدمج صور APNG بسلاسة مع تحكم دقيق في معلمات الرسوم المتحركة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | يُنشئ مثيلًا جديدًا من الفئة [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions). |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | يُنشئ مثيلًا جديدًا من الفئة `ApngOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | يحصل على عدد مرات تكرار الرسوم المتحركة. |
| [setNumPlays(int value)](#setNumPlays-int-) | يضبط عدد مرات تكرار الرسوم المتحركة. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | يحصل على مدة الإطار الافتراضية. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | يضبط مدة الإطار الافتراضية. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // تصدير إلى رسوم متحركة APNG مع دورات غير محدودة كإعداد افتراضي
    image.save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
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

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


يُنشئ مثيلًا جديدًا من الفئة [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions).

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


يُنشئ مثيلًا جديدًا من الفئة `ApngOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | خيارات PNG. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


يحصل على عدد مرات تكرار الرسوم المتحركة. 0 يدل على تكرار لا نهائي.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // تصدير إلى رسوم متحركة APNG مع دورات غير محدودة كإعداد افتراضي
    image.save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


يضبط عدد مرات تكرار الرسوم المتحركة. 0 يدل على تكرار لا نهائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // تصدير إلى رسوم متحركة APNG مع دورات غير محدودة كإعداد افتراضي
    image.save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


يحصل على مدة الإطار الافتراضية.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


يضبط مدة الإطار الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

