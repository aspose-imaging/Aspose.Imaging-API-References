---
title: "PngLoadOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات تحميل png."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

خيارات تحميل png.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | ينشئ مثيلاً جديدًا من الفئة `PngLoadOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [strict mode]. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [strict mode]. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


ينشئ مثيلاً جديدًا من الفئة `PngLoadOptions`.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [strict mode].

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان [strict mode].
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [strict mode].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان [strict mode]. |


**Example: The following example shows how to read PNG file : a strict mode.**
المثال التالي يوضح كيفية قراءة ملف PNG : وضع صارم. يسمح الوضع الصارم باكتشاف المشكلات المحتملة : صور PNG، مثل كتل البيانات غير المعروفة، أو نهاية غير متوقعة للملف. لا يزال يمكن فتح مثل هذه الملفات : الوضع الافتراضي (غير الصارم) بواسطة Aspose.Imaging ومن قبل عارضات الملفات الشائعة أيضًا. ومع ذلك، أي محاولة لفتحها : الوضع الصارم تتسبب في استثناء مطابق.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// الوضع الافتراضي (غير صارم) - قراءة ناجحة.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// الوضع الصارم - ImageLoadException : نهاية غير متوقعة للملف.
com.aspose.imaging.Image image2 = com.aspose.imaging.Image.load(inputImage, new com.aspose.imaging.imageloadoptions.PngLoadOptions() {{
    setStrictMode(true);
    }});
                
try {
    image2.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image2.close();
}
```

