---
title: "WebPOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إنشاء صور ويب نقطية حديثة بصيغة WebP باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع دعم قوي للضغط غير الفاقد والفقدان بالإضافة إلى قنوات ألفا وحلقات الرسوم المتحركة."
type: docs
weight: 53
url: /ar/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

إنشاء صور ويب نقطية حديثة بصيغة WebP باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع دعم قوي للضغط غير الفاقد والفقدان، بالإضافة إلى قنوات ألفا وحلقات الرسوم المتحركة. حسّن محتوى الويب الخاص بك بصور ديناميكية مع تحسين أحجام الملفات لزيادة سرعات التحميل وتحسين تجربة المستخدم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLossless()](#getLossless--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `WebPOptions` بدون فقدان. |
| [setLossless(boolean value)](#setLossless-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `WebPOptions` بدون فقدان. |
| [getQuality()](#getQuality--) | يحصل أو يعيّن الجودة. |
| [setQuality(float value)](#setQuality-float-) | يحصل أو يعيّن الجودة. |
| [getAnimLoopCount()](#getAnimLoopCount--) | يحصل أو يعيّن عدد حلقات الرسوم المتحركة. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | يحصل أو يعيّن عدد حلقات الرسوم المتحركة. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | يحصل أو يعيّن لون خلفية الرسوم المتحركة. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | يحصل أو يعيّن لون خلفية الرسوم المتحركة. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليتين فقط. سيتم عرض هاتين الصفحتين كإطارات متحركة في ملف WEBP الناتج.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `WebPOptions` بدون فقدان.

**Returns:**
منطقي - `true` إذا كان بدون فقدان؛ وإلا `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `WebPOptions` بدون فقدان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `true` إذا كان بدون فقدان؛ وإلا `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


يحصل أو يعيّن الجودة.

**Returns:**
عائم - الجودة.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


يحصل أو يعيّن الجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | الجودة. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


يحصل أو يعيّن عدد حلقات الرسوم المتحركة.

**Returns:**
عدد صحيح - عدد حلقات الرسوم المتحركة، 0 - لا نهائي.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


يحصل أو يعيّن عدد حلقات الرسوم المتحركة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عدد دورات الرسوم المتحركة، 0 - ما لا نهاية. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


يحصل أو يعيّن لون خلفية الرسوم المتحركة.

**Returns:**
long - لون خلفية الرسوم المتحركة.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


يحصل أو يعيّن لون خلفية الرسوم المتحركة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | لون خلفية الرسوم المتحركة. |

