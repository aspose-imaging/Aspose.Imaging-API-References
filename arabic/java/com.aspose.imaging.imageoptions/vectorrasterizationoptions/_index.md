---
title: "VectorRasterizationOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات تحويل المتجه إلى نقطية."
type: docs
weight: 52
url: /ar/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

خيارات تمثيل المتجهات إلى رستر. يرجى ملاحظة أن [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) لن تستمد بعد الآن من [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) منذ إصدار Aspose.Imaging 24.12.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | يحصل على وضع التنعيم. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | يضبط وضع التنعيم. |
| [getBorderX()](#getBorderX--) | يحصل على أو يضبط الحد X. |
| [setBorderX(float value)](#setBorderX-float-) | يحصل على أو يضبط الحد X. |
| [getBorderY()](#getBorderY--) | يحصل على أو يضبط الحد Y. |
| [setBorderY(float value)](#setBorderY-float-) | يحصل على أو يضبط الحد Y. |
| [getCenterDrawing()](#getCenterDrawing--) | يحصل على قيمة تشير إلى ما إذا كان الرسم مركزيًا. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | يضبط قيمة تشير إلى ما إذا كان الرسم مركزيًا. |
| [getPageHeight()](#getPageHeight--) | يحصل على ارتفاع الصفحة. |
| [setPageHeight(float value)](#setPageHeight-float-) | يضبط ارتفاع الصفحة. |
| [getPageSize()](#getPageSize--) | يحصل على حجم الصفحة. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | يضبط حجم الصفحة. |
| [getPageWidth()](#getPageWidth--) | يحصل على عرض الصفحة. |
| [setPageWidth(float value)](#setPageWidth-float-) | يضبط عرض الصفحة. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يضبط لون الخلفية. |
| [getDrawColor()](#getDrawColor--) | يحصل على لون المقدمة. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | يضبط لون المقدمة. |
| [getTextRenderingHint()](#getTextRenderingHint--) | يحصل على تلميح عرض النص. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | يضبط تلميح عرض النص. |
| [getPositioning()](#getPositioning--) | يحصل على التموضع. |
| [setPositioning(int value)](#setPositioning-int-) | يضبط التموضع. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | يحصل على خريطة استبدال النص. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | يضبط خريطة استبدال النص. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | ينسخ هذه الحالة إلى `vectorRasterizationOptions`. |
| [deepClone()](#deepClone--) | ينشئ نسخة سطحية من الكائن. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


يحصل على وضع التنعيم.

**Returns:**
int - وضع التنعيم.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


يضبط وضع التنعيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع التنعيم. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل الصورة.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // من أجل تحويل SVG إلى نقطية، نحتاج إلى تحديد خيارات التحويل النقطي.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // تعيين اللون الافتراضي لخلفية صورة. القيمة الافتراضية هي الأبيض.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // تعيين حجم الصفحة
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // يتم تطبيق مضاد التعرجات على الخطوط والمنحنيات وحواف المناطق المملوءة.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز بدون التلميح.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // قلل حجم الصورة 10 مرات، أي أن حجم الإخراج سيكون 10٪ من الحجم الأصلي.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // حفظ إلى ملف PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


يحصل على أو يضبط الحد X.

**Returns:**
float - الحد X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


يحصل على أو يضبط الحد X.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | الحد X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


يحصل على أو يضبط الحد Y.

**Returns:**
float - الحد Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


يحصل على أو يضبط الحد Y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | الحد Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


يحصل على قيمة تشير إلى ما إذا كان الرسم مركزيًا.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان الرسم مركزيًا.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الرسم مركزيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان الرسم في المركز. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


يحصل على ارتفاع الصفحة.

**Returns:**
float - ارتفاع الصفحة.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


يضبط ارتفاع الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | ارتفاع الصفحة. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


يحصل على حجم الصفحة.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


يضبط حجم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | حجم الصفحة. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // حدد الهامش الأفقي
    rasterizationOptions.setBorderX(50);

    // حدد الهامش الرأسي
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


يحصل على عرض الصفحة.

**Returns:**
float - عرض الصفحة.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


يضبط عرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | عرض الصفحة. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الخلفية.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يضبط لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون خلفية. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // حدد الهامش الأفقي
    rasterizationOptions.setBorderX(50);

    // حدد الهامش الرأسي
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


يحصل على لون المقدمة.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


يضبط لون المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون أمامي. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


يحصل على تلميح عرض النص.

القيمة: تلميح عرض النص.

**Returns:**
int - تلميح عرض النص.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


يضبط تلميح عرض النص.

القيمة: تلميح عرض النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تلميح عرض النص. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل الصورة.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // من أجل تحويل SVG إلى نقطية، نحتاج إلى تحديد خيارات التحويل النقطي.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // تعيين اللون الافتراضي لخلفية صورة. القيمة الافتراضية هي الأبيض.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // تعيين حجم الصفحة
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // يتم تطبيق مضاد التعرجات على الخطوط والمنحنيات وحواف المناطق المملوءة.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز بدون التلميح.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // قلل حجم الصورة 10 مرات، أي أن حجم الإخراج سيكون 10٪ من الحجم الأصلي.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // حفظ إلى ملف PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


يحصل على التموضع.

القيمة: الموضع.

**Returns:**
int - الموضع.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


يضبط التموضع.

القيمة: الموضع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الموضع. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


يحصل على خريطة استبدال النص.

القيمة: خريطة استبدال النص.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - خريطة استبدال النص.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


يضبط خريطة استبدال النص.

القيمة: خريطة استبدال النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.HashMap<java.lang.String,java.lang.String> | خريطة استبدال النص. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


ينسخ هذه الحالة إلى `vectorRasterizationOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | خيارات تحويل المتجه إلى نقطية. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


ينشئ نسخة سطحية من الكائن.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
