---
title: "DxfOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "توفر واجهة برمجة التطبيقات لإنشاء صور متجهة بصيغة Drawing Interchange Format (DXF) حلولًا مخصصة لتوليد ملفات رسومات AutoCAD بدقة ومرونة."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

توفر واجهة برمجة التطبيقات لإنشاء صور متجهة بصيغة Drawing Interchange Format (DXF) حلولًا مخصصة لتوليد ملفات رسومات AutoCAD بدقة ومرونة. صُممت خصيصًا للعمل مع خطوط النص ومنحنيات بيزييه، حيث يمكن للمطورين معالجة هذه العناصر بفعالية، وعدّ نقاط بيزييه، وتحويل المنحنيات إلى خطوط متعددة النقاط لتصدير سلس، مما يضمن التوافق والوفاء في صور DXF المتجهة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | منشئ النسخ |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | عدد النقاط التي سيتم توليدها عند تحويل منحنيات بيزييه إلى خطوط متعددة النقاط، الحد الأدنى 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | عدد النقاط التي سيتم توليدها عند تحويل منحنيات بيزييه إلى خطوط متعددة النقاط، الحد الأدنى 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | يعمل عندما يتم تعيين \#textAsLines إلى `true`. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | يعمل عندما يتم تعيين \#textAsLines إلى `true`. |
| [getTextAsLines()](#getTextAsLines--) | ما إذا كان يجب تصدير النص كحدود تتكون من خطوط متعددة النقاط (افتراضي) أو ككيانات نصية قابلة للتحرير في AutoCAD. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | ما إذا كان يجب تصدير النص كحدود تتكون من خطوط متعددة النقاط (افتراضي) أو ككيانات نصية قابلة للتحرير في AutoCAD. |

## Example: This example demonstrates export to Dxf format

``` java

//إنشاء كائن Image وتهيئته بملف صورة موجود من موقع القرص
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


منشئ النسخ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | خيارات المصدر للنسخ |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


عدد النقاط التي سيتم توليدها عند تحويل منحنيات بيزييه إلى خطوط متعددة النقاط، الحد الأدنى 4. يُستخدم عندما يتم تعيين (/) و (/) كلاهما إلى `true`.

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


عدد النقاط التي سيتم توليدها عند تحويل منحنيات بيزييه إلى خطوط متعددة النقاط، الحد الأدنى 4. يُستخدم عندما يتم تعيين (/) و (/) كلاهما إلى `true`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


يعمل عندما يتم تعيين \#textAsLines إلى `true`. ما إذا كان يجب تحويل منحنيات بيزييه في حدود النص إلى خطوط متعددة النقاط.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


يعمل عندما يتم تعيين \#textAsLines إلى `true`. ما إذا كان يجب تحويل منحنيات بيزييه في حدود النص إلى خطوط متعددة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


ما إذا كان يجب تصدير النص كحدود تتكون من خطوط متعددة النقاط (افتراضي) أو ككيانات نصية قابلة للتحرير في AutoCAD. إذا تم تعيين هذا الخيار

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


ما إذا كان يجب تصدير النص كحدود تتكون من خطوط متعددة النقاط (افتراضي) أو ككيانات نصية قابلة للتحرير في AutoCAD. إذا تم تعيين هذا الخيار

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

