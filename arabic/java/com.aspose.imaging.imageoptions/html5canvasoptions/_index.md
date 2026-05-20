---
title: "Html5CanvasOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أنشئ ملفات HTML5 Canvas بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تتيح لك دمج العناصر مثل النماذج والنصوص والصور والرسوم المتحركة والروابط بسلاسة."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

أنشئ ملفات HTML5 Canvas بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، مما يتيح لك دمج العناصر مثل النماذج، والنص، والصور، والرسوم المتحركة، والروابط بسلاسة. استفد من ميزات قوية تشمل دعم معرف الوسم وإعدادات الترميز، مما يضمن أداءً مثاليًا وتخصيصًا لمشاريع الويب الخاصة بك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | ينشئ مثيلاً جديدًا من الفئة [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions). |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | ينشئ مثيلاً جديدًا من الفئة `ImageOptionsBase`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | يحصل على معرف وسم الـ canvas. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | يضبط معرف وسم الـ canvas. |
| [getFullHtmlPage()](#getFullHtmlPage--) | يحصل على قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة. |
| [getEncoding()](#getEncoding--) | يحصل على الترميز. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يضبط الترميز. |

## Example: Any vector image (SVG, WMF, CMX, etc.
يمكن استخدام أي صورة متجهة (SVG، WMF، CMX، إلخ) كمصدر لصور Canvas الخاصة بك. يخلق الشيفرة التالية صورة Canvas بسيطة.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save("Canvas.html", options);
}
```


## Example: You can embed more than one Canvas image within HTML page or update already existing page.
يمكنك تضمين أكثر من صورة Canvas داخل صفحة HTML أو تحديث صفحة موجودة بالفعل. للقيام بذلك تحتاج إلى تصدير علامة Canvas فقط.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### Html5CanvasOptions() {#Html5CanvasOptions--}
```
public Html5CanvasOptions()
```


ينشئ مثيلاً جديدًا من الفئة [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions).

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


ينشئ مثيلاً جديدًا من الفئة `ImageOptionsBase`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | خيارات الصورة. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


يحصل على معرف وسم الـ canvas.

**Returns:**
java.lang.String - معرف علامة canvas.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


يضبط معرف وسم الـ canvas.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | معرف علامة canvas. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


يحصل على قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
يمكنك تضمين أكثر من صورة Canvas داخل صفحة HTML أو تحديث صفحة موجودة بالفعل. للقيام بذلك تحتاج إلى تصدير علامة Canvas فقط.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


يحصل على الترميز.

**Returns:**
java.nio.charset.Charset - الترميز.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


يضبط الترميز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset | الترميز. |

