---
title: "الخط"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد تنسيقًا معينًا للنص بما في ذلك حجم الخط ونمطه وسماته."
type: docs
weight: 48
url: /ar/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

يحدد تنسيقًا معينًا للنص، بما في ذلك خط الوجه، الحجم، وسمات النمط. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` يستخدم الخط الموجود المحدد `com.aspose.imaging.Font` وتعداد `com.aspose.imaging.FontStyle`. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` باستخدام حجم محدد. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` باستخدام حجم ونمط محددين. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` باستخدام حجم، نمط، وحدة، ومجموعة أحرف محددة. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` باستخدام حجم، نمط، ووحدة محددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` باستخدام حجم ووحدة محددين. |
| [getBold()](#getBold--) | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` غامقًا. |
| [getCharacterSet()](#getCharacterSet--) | يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا `Font`. |
| [getItalic()](#getItalic--) | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` مائلًا. |
| [getName()](#getName--) | يحصل على اسم الوجه لهذا `Font`. |
| [getStrikeout()](#getStrikeout--) | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` يحدد خطًا أفقيًا عبر الخط. |
| [getUnderline()](#getUnderline--) | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` مسطرًا. |
| [getStyle()](#getStyle--) | يحصل على معلومات النمط لهذا `Font`. |
| [getSize()](#getSize--) | يحصل على حجم الـ em لهذا `Font` مقاسًا بالوحدات المحددة بواسطة الخاصية `P:Aspose.Imaging.Font.Unit`. |
| [getUnit()](#getUnit--) | يحصل على وحدة القياس لهذا `Font`. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة دقيقة من هذا `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | يشير إلى ما إذا كان الكائن المحدد هو `com.aspose.imaging.Font` وله نفس قيم الخصائص مثل هذا `com.aspose.imaging.Font`. |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لهذا `com.aspose.imaging.Font`. |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا `com.aspose.imaging.Font`. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
يوضح هذا المثال استخدام الفئة Font والفئة SolidBrush لرسم سلاسل نصية على سطح Image. ينشئ المثال صورة جديدة ويرسم أشكالًا باستخدام Figures و GraphicsPath.
``` java
//ينشئ مثيلًا من BmpOptions ويضبط خصائصه المتنوعة
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//أنشئ مثيلاً من FileCreateSource وعيّنه كخاصية Source لمثيل BmpOptions.
//المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//ينشئ مثيلاً من Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //ينشئ ويُهيئ مثيلاً من الفئة Graphics.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //يمسح سطح Graphics.
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //ينشئ مثيلاً من Font.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //أنشئ مثيلاً من SolidBrush بلون أحمر.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //ارسم String.
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // احفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` يستخدم الخط الموجود المحدد `com.aspose.imaging.Font` وتعداد `com.aspose.imaging.FontStyle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | الـ `com.aspose.imaging.Font` الموجود والذي يُنشأ منه الـ `com.aspose.imaging.Font` الجديد. |
| newStyle | int | الـ `com.aspose.imaging.FontStyle` لتطبيقه على الـ `com.aspose.imaging.Font` الجديد. يمكن دمج قيم متعددة من تعداد `com.aspose.imaging.FontStyle` باستخدام عامل OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


يُهيئ `com.aspose.imaging.Font` جديدًا باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى `F:Aspose.Imaging.CharacterSet.Default`، ووحدة الرسومات إلى `F:Aspose.Imaging.GraphicsUnit.Point`، ونمط الخط إلى `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم `com.aspose.imaging.Font`. |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


يفّعل إنشاء كائن جديد من `com.aspose.imaging.Font` باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى `F:Aspose.Imaging.CharacterSet.Default`، ووحدة الرسومات إلى `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم `com.aspose.imaging.Font`. |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |
| style | int | قيمة `com.aspose.imaging.FontStyle` للخط الجديد. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` باستخدام حجم، نمط، وحدة، ومجموعة أحرف محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم `com.aspose.imaging.Font`. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | قيمة `com.aspose.imaging.FontStyle` للخط الجديد. |
| unit | int | قيمة `com.aspose.imaging.GraphicsUnit` للخط الجديد. |
| characterSet | int | مجموعة أحرف لاستخدامها مع هذا الخط. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


يُنشئ كائنًا جديدًا من `com.aspose.imaging.Font` باستخدام حجم، نمط، ووحدة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم `com.aspose.imaging.Font`. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | قيمة `com.aspose.imaging.FontStyle` للخط الجديد. |
| unit | int | قيمة `com.aspose.imaging.GraphicsUnit` للخط الجديد. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


يفّعل إنشاء كائن جديد من `com.aspose.imaging.Font` باستخدام حجم ووحدة محددين. يتم تعيين مجموعة الأحرف إلى `F:Aspose.Imaging.CharacterSet.Default`، ويتم تعيين النمط إلى `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم `com.aspose.imaging.Font`. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| unit | int | قيمة `com.aspose.imaging.GraphicsUnit` للخط الجديد. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `Font` غامقًا.

**Returns:**
منطقي - True إذا كان هذا `Font` غامقًا؛ وإلا false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا `Font`.

**Returns:**
عدد صحيح - مجموعة أحرف يستخدمها هذا `Font`.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `Font` مائلًا.

**Returns:**
منطقي - True إذا كان هذا `Font` مائلًا؛ وإلا false.
### getName() {#getName--}
```
public String getName()
```


يحصل على اسم الوجه لهذا `Font`.

**Returns:**
java.lang.String - تمثيل نصي لاسم الوجه لهذا `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `Font` يحدد خطًا أفقيًا عبر الخط.

**Returns:**
منطقي - True إذا كان هذا `Font` يحتوي على خط أفقي عبره؛ وإلا false.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `Font` مسطرًا.

**Returns:**
منطقي - True إذا كان هذا `Font` تحته خط؛ وإلا false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


يحصل على معلومات النمط لهذا `Font`.

**Returns:**
عدد صحيح - تعداد `FontStyle` يحتوي على معلومات النمط لهذا `Font`.
### getSize() {#getSize--}
```
public float getSize()
```


يحصل على حجم الـ em لهذا `Font` مقاسًا بالوحدات المحددة بواسطة الخاصية `P:Aspose.Imaging.Font.Unit`.

**Returns:**
عدد عشري - حجم الـ em لهذا `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


يحصل على وحدة القياس لهذا `Font`.

**Returns:**
عدد صحيح - `GraphicsUnit` يمثل وحدة القياس لهذا `Font`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


ينشئ نسخة عميقة دقيقة من هذا `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يشير إلى ما إذا كان الكائن المحدد هو `com.aspose.imaging.Font` وله نفس قيم الخصائص مثل هذا `com.aspose.imaging.Font`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن المراد اختباره. |

**Returns:**
منطقي - True إذا كان معامل `obj` هو `com.aspose.imaging.Font` وله نفس قيم الخصائص مثل هذا `com.aspose.imaging.Font`؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على رمز التجزئة لهذا `com.aspose.imaging.Font`.

**Returns:**
عدد صحيح - رمز التجزئة لهذا `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا `com.aspose.imaging.Font`.

**Returns:**
java.lang.String - سلسلة تمثل هذا `com.aspose.imaging.Font`.
