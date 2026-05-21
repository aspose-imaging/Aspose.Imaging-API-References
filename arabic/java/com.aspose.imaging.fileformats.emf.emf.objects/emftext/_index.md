---
title: "EmfText"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmrText يحتوي على قيم لإخراج النص."
type: docs
weight: 35
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

كائن EmrText يحتوي على قيم لإخراج النص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getReference()](#getReference--) | يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد إحداثيات نقطة المرجع المستخدمة لتحديد موضع السلسلة. |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد إحداثيات نقطة المرجع المستخدمة لتحديد موضع السلسلة. |
| [getChars()](#getChars--) | يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد عدد الأحرف في السلسلة |
| [setChars(int value)](#setChars-int-) | يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد عدد الأحرف في السلسلة |
| [getOptions()](#getOptions--) | يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد كيفية استخدام المستطيل المحدد في حقل Rectangle. |
| [setOptions(int value)](#setOptions-int-) | يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد كيفية استخدام المستطيل المحدد في حقل Rectangle. |
| [getRectangle()](#getRectangle--) | يحصل أو يضبط كائن WMF RectL اختياري ([MS-WMF] القسم 2.2.2.19) يحدد مستطيل قص و/أو تغطية بوحدات منطقية. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | يحصل أو يضبط كائن WMF RectL اختياري ([MS-WMF] القسم 2.2.2.19) يحدد مستطيل قص و/أو تغطية بوحدات منطقية. |
| [getStringBuffer()](#getStringBuffer--) | يحصل أو يضبط مخزن سلسلة الأحرف UndefinedSpace1 (متغير): عدد اختياري من البايتات غير المستخدمة. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | يحصل أو يضبط مخزن سلسلة الأحرف UndefinedSpace1 (متغير): عدد اختياري من البايتات غير المستخدمة. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | يحصل على مخزن فهرس الرموز الاختياري. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | يضبط مخزن فهرس الرموز الاختياري. |
| [getDxBuffer()](#getDxBuffer--) | يحصل أو يضبط مخزن تباعد الأحرف الاختياري UndefinedSpace2 (متغير): عدد اختياري من البايتات غير المستخدمة. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | يحصل أو يضبط مخزن تباعد الأحرف الاختياري UndefinedSpace2 (متغير): عدد اختياري من البايتات غير المستخدمة. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد إحداثيات نقطة المرجع المستخدمة لتحديد موضع السلسلة. تُعرَّف نقطة المرجع بواسطة آخر سجل EMR\_SETTEXTALIGN (القسم 2.3.11.25). إذا لم يتم تعيين أي سجل من هذا النوع، يكون المحاذاة الافتراضية هي TA\_LEFT,TA\_TOP.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) الذي يحدد إحداثيات نقطة المرجع المستخدمة لتحديد موضع السلسلة. تُعرَّف نقطة المرجع بواسطة آخر سجل EMR\_SETTEXTALIGN (القسم 2.3.11.25). إذا لم يتم تعيين أي سجل من هذا النوع، يكون المحاذاة الافتراضية هي TA\_LEFT,TA\_TOP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد عدد الأحرف في السلسلة

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد عدد الأحرف في السلسلة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد كيفية استخدام المستطيل المحدد في حقل Rectangle. يمكن أن يكون هذا الحقل مزيجًا من أكثر من قيمة في تعداد ExtTextOutOptions (القسم 2.1.11).

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد كيفية استخدام المستطيل المحدد في حقل Rectangle. يمكن أن يكون هذا الحقل مزيجًا من أكثر من قيمة في تعداد ExtTextOutOptions (القسم 2.1.11).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


يحصل أو يضبط كائن WMF RectL اختياري ([MS-WMF] القسم 2.2.2.19) يحدد مستطيل قص و/أو تغطية بوحدات منطقية. يتم تطبيق هذا المستطيل على إخراج النص الذي يتم بواسطة السجل الحاوي.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


يحصل أو يضبط كائن WMF RectL اختياري ([MS-WMF] القسم 2.2.2.19) يحدد مستطيل قص و/أو تغطية بوحدات منطقية. يتم تطبيق هذا المستطيل على إخراج النص الذي يتم بواسطة السجل الحاوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


يحصل أو يضبط مخزن سلسلة الأحرف UndefinedSpace1 (متغير): عدد اختياري من البايتات غير المستخدمة. لا يُشترط أن يتبع حقل OutputString مباشرةً الجزء السابق من هذه البنية. OutputString (متغير): مصفوفة من الأحرف التي تحدد السلسلة المراد إخراجها. يتم تحديد موقع هذا الحقل بقيمة offString بالبايتات من بداية هذا السجل. يتم تحديد عدد الأحرف بقيمة Chars.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


يحصل أو يضبط مخزن سلسلة الأحرف UndefinedSpace1 (متغير): عدد اختياري من البايتات غير المستخدمة. لا يُشترط أن يتبع حقل OutputString مباشرةً الجزء السابق من هذه البنية. OutputString (متغير): مصفوفة من الأحرف التي تحدد السلسلة المراد إخراجها. يتم تحديد موقع هذا الحقل بقيمة offString بالبايتات من بداية هذا السجل. يتم تحديد عدد الأحرف بقيمة Chars.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


يحصل على مخزن فهرس الرموز الاختياري. إذا كان لدى الخيارات علامة ETO\_GLYPH\_INDEX، فإن رموز الأحرف في سلسلة النص المُخرَج هي في الواقع فهارس للرموز الحرفية في خط TrueType (تعداد ExtTextOutOptions 2.1.11). فهارس الرموز خاصة بالخط، لذا لعرض الأحرف الصحيحة أثناء التشغيل، يجب أن يكون الخط المستخدم متماثلًا مع الخط المستخدم لإنشاء الفهارس.

**Returns:**
int[] - مخزن فهرس الرموز الاختياري.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


يضبط مخزن فهرس الرموز الاختياري. إذا كان لدى الخيارات علامة ETO\_GLYPH\_INDEX، فإن رموز الأحرف في سلسلة النص المُخرَج هي في الواقع فهارس للرموز الحرفية في خط TrueType (تعداد ExtTextOutOptions 2.1.11). فهارس الرموز خاصة بالخط، لذا لعرض الأحرف الصحيحة أثناء التشغيل، يجب أن يكون الخط المستخدم متماثلًا مع الخط المستخدم لإنشاء الفهارس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | مخزن فهرس الرموز الاختياري. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


يحصل أو يضبط مخزن تباعد الأحرف الاختياري UndefinedSpace2 (متغير): عدد اختياري من البايتات غير المستخدمة. لا يُشترط أن يتبع حقل OutputDx مباشرةً الجزء السابق من هذه البنية. OutputDx (متغير): مصفوفة من الأعداد الصحيحة غير الموقعية بحجم 32 بت التي تحدد التباعد الناتج بين أصول خلايا الأحرف المتجاورة بوحدات منطقية. يتم تحديد موقع هذا الحقل بقيمة offDx بالبايتات من بداية هذا السجل. إذا تم تعريف التباعد، يحتوي هذا الحقل على نفس عدد القيم كعدد الأحرف في سلسلة الإخراج. إذا كان حقل Options لكائن EmrText يحتوي على علامة ETO\_PDY، فإن هذا المخزن يحتوي على ضعف عدد القيم مقارنةً بعدد الأحرف في سلسلة الإخراج، إزاحة أفقية وإزاحة عمودية لكل حرف، بهذا الترتيب. إذا تم تحديد ETO\_RTLREADING، تُرتّب الأحرف من اليمين إلى اليسار بدلاً من اليسار إلى اليمين. لا تؤثر أي خيارات أخرى على تفسير هذا الحقل.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


يحصل أو يضبط مخزن تباعد الأحرف الاختياري UndefinedSpace2 (متغير): عدد اختياري من البايتات غير المستخدمة. لا يُشترط أن يتبع حقل OutputDx مباشرةً الجزء السابق من هذه البنية. OutputDx (متغير): مصفوفة من الأعداد الصحيحة غير الموقعية بحجم 32 بت التي تحدد التباعد الناتج بين أصول خلايا الأحرف المتجاورة بوحدات منطقية. يتم تحديد موقع هذا الحقل بقيمة offDx بالبايتات من بداية هذا السجل. إذا تم تعريف التباعد، يحتوي هذا الحقل على نفس عدد القيم كعدد الأحرف في سلسلة الإخراج. إذا كان حقل Options لكائن EmrText يحتوي على علامة ETO\_PDY، فإن هذا المخزن يحتوي على ضعف عدد القيم مقارنةً بعدد الأحرف في سلسلة الإخراج، إزاحة أفقية وإزاحة عمودية لكل حرف، بهذا الترتيب. إذا تم تحديد ETO\_RTLREADING، تُرتّب الأحرف من اليمين إلى اليسار بدلاً من اليسار إلى اليمين. لا تؤثر أي خيارات أخرى على تفسير هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

