---
title: "EmfPlusSetTsGraphics"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetTSGraphics يحدد حالة سياق جهاز الرسومات لخادم الطرفية."
type: docs
weight: 67
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

سجل EmfPlusSetTSGraphics يحدد حالة سياق جهاز الرسومات لخادم الطرفية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusSetTsGraphics`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | يحصل على قيمة تشير إلى ما إذا كانت [basic vga colors]. |
| [getHavePalette()](#getHavePalette--) | يحصل على قيمة تشير إلى ما إذا كانت [have palette]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم الخط، بما في ذلك نوع مضاد التعرج للخط. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم الخط، بما في ذلك نوع مضاد التعرج للخط. |
| [getTextRenderHint()](#getTextRenderHint--) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم النص، بما في ذلك نوع مضاد التعرج للنص. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم النص، بما في ذلك نوع مضاد التعرج للنص. |
| [getCompositingMode()](#getCompositingMode--) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. |
| [getCompositingQuality()](#getCompositingQuality--) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد درجة التنعيم التي تُطبق على الخطوط والمنحنيات وحواف المناطق المملوءة لجعلها تبدو أكثر استمرارية أو محددة بحدة. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد درجة التنعيم التي تُطبق على الخطوط والمنحنيات وحواف المناطق المملوءة لجعلها تبدو أكثر استمرارية أو محددة بحدة. |
| [getRenderOriginX()](#getRenderOriginX--) | يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي الأفقي للأصل عند رسم أنماط النقاط وتدرجات الألوان. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي الأفقي للأصل عند رسم أنماط النقاط وتدرجات الألوان. |
| [getRenderOriginY()](#getRenderOriginY--) | يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي العمودي للأصل عند رسم أنماط النقاط وتدرجات الألوان. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي العمودي للأصل عند رسم أنماط النقاط وتدرجات الألوان. |
| [getTextContrast()](#getTextContrast--) | يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد قيمة تصحيح جاما المستخدمة في رسم النصوص المضادة للتعرج وClearType. |
| [setTextContrast(short value)](#setTextContrast-short-) | يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد قيمة تصحيح جاما المستخدمة في رسم النصوص المضادة للتعرج وClearType. |
| [getFilterType()](#getFilterType--) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد كيفية تنفيذ التحجيم، بما في ذلك التمدد والتقليص. |
| [setFilterType(byte value)](#setFilterType-byte-) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد كيفية تنفيذ التحجيم، بما في ذلك التمدد والتقليص. |
| [getPixelOffset()](#getPixelOffset--) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد الجودة العامة لعملية رسم الصورة والنص. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد الجودة العامة لعملية رسم الصورة والنص. |
| [getWorldToDevice()](#getWorldToDevice--) | يحصل أو يضبط كائن EmfPlusTransformMatrix 192 بت (القسم 2.2.2.47) يحدد التحويلات من مساحة العالم إلى مساحة الجهاز. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | يحصل أو يضبط كائن EmfPlusTransformMatrix 192 بت (القسم 2.2.2.47) يحدد التحويلات من مساحة العالم إلى مساحة الجهاز. |
| [getPalette()](#getPalette--) | يحصل أو يضبط كائن EmfPlusPalette اختياري. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | يحصل أو يضبط كائن EmfPlusPalette اختياري. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusSetTsGraphics`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


يحصل على قيمة تشير إلى ما إذا كان [basic vga colors]. إذا تم الضبط، فإن لوحة الألوان تحتوي فقط على ألوان VGA الأساسية.

القيمة: `true` إذا كان [basic vga colors]؛ وإلا `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


يحصل على قيمة تشير إلى ما إذا كان [have palette]. إذا تم الضبط، يحتوي هذا السجل على كائن EmfPlusPalette (القسم 2.2.2.28) في حقل Palette بعد بيانات حالة الرسومات.

القيمة: `true` إذا كان [have palette]؛ وإلا `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم الخط، بما في ذلك نوع مضاد التعرج للخط. يجب أن يكون معرفًا في تعداد SmoothingMode (القسم 2.1.1.28).

القيمة: وضع مضاد التعرج.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم الخط، بما في ذلك نوع مضاد التعرج للخط. يجب أن يكون معرفًا في تعداد SmoothingMode (القسم 2.1.1.28).

القيمة: وضع مضاد التعرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم النص، بما في ذلك نوع مضاد التعرج للنص. يجب أن يكون معرفًا في تعداد TextRenderingHint (القسم 2.1.1.32).

القيمة: تلميح رسم النص.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد جودة رسم النص، بما في ذلك نوع مضاد التعرج للنص. يجب أن يكون معرفًا في تعداد TextRenderingHint (القسم 2.1.1.32).

القيمة: تلميح رسم النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. يجب أن يكون قيمة في تعداد CompositingMode (القسم 2.1.1.5).

القيمة: وضع التركيب.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. يجب أن يكون قيمة في تعداد CompositingMode (القسم 2.1.1.5).

القيمة: وضع التركيب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد درجة التنعيم التي تُطبق على الخطوط والمنحنيات وحواف المناطق المملوءة لجعلها تبدو أكثر استمرارية أو محددة بحدة. يجب أن يكون قيمة في تعداد CompositingQuality (القسم 2.1.1.6).

القيمة: جودة التركيب.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 8 بت يحدد درجة التنعيم التي تُطبق على الخطوط والمنحنيات وحواف المناطق المملوءة لجعلها تبدو أكثر استمرارية أو محددة بحدة. يجب أن يكون قيمة في تعداد CompositingQuality (القسم 2.1.1.6).

القيمة: جودة التركيب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي الأفقي للأصل عند رسم أنماط النقاط وتدرجات الألوان.

القيمة: إحداثي X لأصل الرسم.

**Returns:**
قصير
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي الأفقي للأصل عند رسم أنماط النقاط وتدرجات الألوان.

القيمة: إحداثي X لأصل الرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي العمودي للأصل عند رسم أنماط النقاط وتدرجات الألوان.

القيمة: إحداثي Y لأصل الرسم.

**Returns:**
قصير
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 16 بت، وهو الإحداثي العمودي للأصل عند رسم أنماط النقاط وتدرجات الألوان.

القيمة: إحداثي Y لأصل الرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد قيمة تصحيح جاما المستخدمة في رسم النصوص المضادة للتعرج وClearType. يجب أن تكون هذه القيمة في النطاق من 0 إلى 12، شاملًا.

القيمة: تباين النص.

**Returns:**
قصير
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد قيمة تصحيح جاما المستخدمة في رسم النصوص المضادة للتعرج وClearType. يجب أن تكون هذه القيمة في النطاق من 0 إلى 12، شاملًا.

القيمة: تباين النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد كيفية تنفيذ التحجيم، بما في ذلك التمدد والانكماش. يجب أن يكون قيمة في تعداد FilterType (القسم 2.1.1.11).

القيمة: نوع الفلتر.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد كيفية تنفيذ التحجيم، بما في ذلك التمدد والانكماش. يجب أن يكون قيمة في تعداد FilterType (القسم 2.1.1.11).

القيمة: نوع الفلتر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد الجودة العامة للصورة وعملية عرض النص. يجب أن يكون قيمة في تعداد PixelOffsetMode (القسم 2.1.1.26).

القيمة: إزاحة البكسل.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 8 بت يحدد الجودة العامة للصورة وعملية عرض النص. يجب أن يكون قيمة في تعداد PixelOffsetMode (القسم 2.1.1.26).

القيمة: إزاحة البكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


يحصل أو يضبط كائن EmfPlusTransformMatrix 192 بت (القسم 2.2.2.47) يحدد التحويلات من مساحة العالم إلى مساحة الجهاز.

القيمة: العالم إلى الجهاز.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


يحصل أو يضبط كائن EmfPlusTransformMatrix 192 بت (القسم 2.2.2.47) يحدد التحويلات من مساحة العالم إلى مساحة الجهاز.

القيمة: العالم إلى الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


يحصل أو يضبط كائن EmfPlusPalette اختياري.

القيمة: لوحة الألوان.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


يحصل أو يضبط كائن EmfPlusPalette اختياري.

القيمة: لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

