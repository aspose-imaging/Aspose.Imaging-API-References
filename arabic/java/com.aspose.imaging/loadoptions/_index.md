---
title: "LoadOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل خيارات التحميل."
type: docs
weight: 70
url: /ar/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

يمثل خيارات التحميل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | يحصل على وضع استعادة البيانات. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | يضبط وضع استعادة البيانات. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | يحصل على `Image` الخلفية `Color`. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | يضبط `Image` الخلفية `Color`. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | يحصل على قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | يضيف مصدر الخط المخصص لتوفير خطوط خاصة بالصورة. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | يحصل على قيمة تشير إلى ما إذا كان [معالجة الصور المتزامنة]. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | يضبط قيمة تشير إلى ما إذا كان [معالجة الصور المتزامنة]. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | يسترجع معالج حدث التقدم. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | يضبط معالج حدث التقدم. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


يحصل على وضع استعادة البيانات.

**Returns:**
int - وضع استعادة البيانات.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


يضبط وضع استعادة البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع استعادة البيانات. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


يحصل على `Image` الخلفية `Color`.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

عادةً ما يتم تعيين لون الخلفية كلما تعذر استعادة قيمة البكسل بسبب فساد البيانات.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


يضبط `Image` الخلفية `Color`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

عادةً ما يتم تعيين لون الخلفية كلما تعذر استعادة قيمة البكسل بسبب فساد البيانات. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


يحصل على قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


يضيف مصدر الخط المخصص لتوفير خطوط خاصة بالصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | دالة موفر مصدر الخط المخصص. |
| args | java.lang.Object[] | المعلمات. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الإيجابية تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int - تلميح حجم المخزن المؤقت الذي يُعرّف الحد الأقصى المسموح به لجميع المخازن المؤقتة الداخلية.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الإيجابية تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تلميح حجم المخزن المؤقت الذي يُعرّف الحد الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
يوضح المثال التالي كيفية تعيين حد الذاكرة عند تحميل صورة JPEG. حد الذاكرة هو الحد الأقصى المسموح به (بالميغابايت) لجميع المخازن الداخلية.
``` java
String workDir = "c:\\temp\\";
// تعيين حد الذاكرة إلى 50 ميغابايت للصورة المحملة المستهدفة
com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
loadOptions.setBufferSizeHint(50);
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(workDir + "inputFile.jpg", loadOptions);
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Baseline);
    jpegOptions.setQuality(100);
    image.save(workDir + "outputFile_Baseline.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);
    image.save(workDir + "outputFile_Progressive.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Lossless);
    jpegOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);
    jpegOptions.setBitsPerChannel((byte) 4);
    image.save(workDir + "outputFile_Lossless.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.JpegLs);
    jpegOptions.setJpegLsInterleaveMode(com.aspose.imaging.fileformats.jpeg.JpegLsInterleaveMode.None);
    jpegOptions.setJpegLsAllowedLossyError(3);
    jpegOptions.setJpegLsPreset(null);
    image.save(workDir + "outputFile_JpegLs.jpg", jpegOptions);
} finally {
    image.close();
}
```

### getConcurrentImageProcessing() {#getConcurrentImageProcessing--}
```
public final boolean getConcurrentImageProcessing()
```


يحصل على قيمة تشير إلى ما إذا كان [معالجة الصور المتزامنة].

القيمة: `true` إذا كان [معالجة الصور المتزامنة]؛ وإلا `false`.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان [معالجة الصور المتزامنة].
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [معالجة الصور المتزامنة].

القيمة: `true` إذا كان [معالجة الصور المتزامنة]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان [concurrent image processing]. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


يسترجع معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


يضبط معالج حدث التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | معالج حدث التقدم. |

