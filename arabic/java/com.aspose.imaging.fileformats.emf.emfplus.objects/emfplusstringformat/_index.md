---
title: "EmfPlusStringFormat"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusStringFormat يحدد عمليات تعديل عرض تخطيط النص وتحديد اللغة."
type: docs
weight: 74
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

يحدد كائن EmfPlusStringFormat تخطيط النص، وتعديلات العرض، وتحديد اللغة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | يحصل أو يضبط كائن EmfPlusLanguageIdentifier الذي يحدد اللغة المستخدمة للأرقام الرقمية في السلسلة. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | يحصل أو يضبط كائن EmfPlusLanguageIdentifier الذي يحدد اللغة المستخدمة للأرقام الرقمية في السلسلة. |
| [getDigitSubstitution()](#getDigitSubstitution--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة استبدال الأرقام الرقمية في السلسلة وفقًا للمنطقة أو اللغة. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة استبدال الأرقام الرقمية في السلسلة وفقًا للمنطقة أو اللغة. |
| [getFirstTabOffset()](#getFirstTabOffset--) | يحصل أو يضبط قيمة عائمة 32 بت تحدد عدد الفراغات بين بداية سطر النص وأول موضع تبويب. |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | يحصل أو يضبط قيمة عائمة 32 بت تحدد عدد الفراغات بين بداية سطر النص وأول موضع تبويب. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد نوع المعالجة التي تُجرى على السلسلة عندما يُصادف بادئة اختصار لوحة المفاتيح (أي علامة العطف). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد نوع المعالجة التي تُجرى على السلسلة عندما يُصادف بادئة اختصار لوحة المفاتيح (أي علامة العطف). |
| [getLanguage()](#getLanguage--) | يحصل أو يضبط كائن EmfPlusLanguageIdentifier (القسم 2.2.2.23) الذي يحدد اللغة المستخدمة للسلسلة. |
| [setLanguage(short value)](#setLanguage-short-) | يحصل أو يضبط كائن EmfPlusLanguageIdentifier (القسم 2.2.2.23) الذي يحدد اللغة المستخدمة للسلسلة. |
| [getLeadingMargin()](#getLeadingMargin--) | يحصل أو يضبط قيمة عائمة 32 بت تحدد طول الفراغ الذي يُضاف إلى الموضع الابتدائي للسلسلة. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | يحصل أو يضبط قيمة عائمة 32 بت تحدد طول الفراغ الذي يُضاف إلى الموضع الابتدائي للسلسلة. |
| [getLineAlign()](#getLineAlign--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة محاذاة السلسلة عموديًا داخل مستطيل التخطيط. |
| [setLineAlign(int value)](#setLineAlign-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة محاذاة السلسلة عموديًا داخل مستطيل التخطيط. |
| [getRangeCount()](#getRangeCount--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد كائنات EmfPlusCharacterRange (القسم 2.2.2.8) المعرفة في حقل StringFormatData. |
| [setRangeCount(int value)](#setRangeCount-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد كائنات EmfPlusCharacterRange (القسم 2.2.2.8) المعرفة في حقل StringFormatData. |
| [getStringAlignment()](#getStringAlignment--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة محاذاة السلسلة أفقيًا داخل مستطيل التخطيط. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة محاذاة السلسلة أفقيًا داخل مستطيل التخطيط. |
| [getStringFormatData()](#getStringFormatData--) | يحصل أو يضبط كائن EmfPlusStringFormatData (القسم 2.2.2.44) الذي يحدد بيانات تخطيط النص الاختيارية. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | يحصل أو يضبط كائن EmfPlusStringFormatData (القسم 2.2.2.44) الذي يحدد بيانات تخطيط النص الاختيارية. |
| [getStringFormatFlags()](#getStringFormatFlags--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد خيارات تخطيط النص للتنسيق والقص ومعالجة الخط. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد خيارات تخطيط النص للتنسيق والقص ومعالجة الخط. |
| [getTabstopCount()](#getTabstopCount--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد مواضع التبويب المعرفة في حقل StringFormatData. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد مواضع التبويب المعرفة في حقل StringFormatData. |
| [getTracking()](#getTracking--) | يحصل أو يضبط قيمة عائمة 32 بت تحدد نسبة المسافة الأفقية المخصصة لكل حرف في سلسلة محددة إلى عرض الحرف المحدد بواسطة الخط. |
| [setTracking(float value)](#setTracking-float-) | يحصل أو يضبط قيمة عائمة 32 بت تحدد نسبة المسافة الأفقية المخصصة لكل حرف في سلسلة محددة إلى عرض الحرف المحدد بواسطة الخط. |
| [getTrailingMargin()](#getTrailingMargin--) | يحصل أو يضبط قيمة عائمة 32 بت تحدد طول الفراغ الذي يُترك بعد السلسلة. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | يحصل أو يضبط قيمة عائمة 32 بت تحدد طول الفراغ الذي يُترك بعد السلسلة. |
| [getTrimming()](#getTrimming--) | يحصل أو يضبط يحدد كيفية قص الأحرف من سلسلة كبيرة جدًا بحيث لا تتسع داخل مستطيل التخطيط. |
| [setTrimming(int value)](#setTrimming-int-) | يحصل أو يضبط يحدد كيفية قص الأحرف من سلسلة كبيرة جدًا بحيث لا تتسع داخل مستطيل التخطيط. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


يحصل أو يضبط كائن EmfPlusLanguageIdentifier الذي يحدد اللغة المستخدمة للأرقام الرقمية في السلسلة. على سبيل المثال، إذا كانت هذه السلسلة تحتوي على أرقام عربية، يجب أن يحتوي هذا الحقل على معرف لغة يحدد لغة عربية.

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


يحصل أو يضبط كائن EmfPlusLanguageIdentifier الذي يحدد اللغة المستخدمة للأرقام الرقمية في السلسلة. على سبيل المثال، إذا كانت هذه السلسلة تحتوي على أرقام عربية، يجب أن يحتوي هذا الحقل على معرف لغة يحدد لغة عربية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة استبدال الأرقام الرقمية في السلسلة وفقًا للمنطقة أو اللغة. يجب أن تكون هذه القيمة معرفة في تعداد StringDigitSubstitution (القسم 2.1.1.30).

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة استبدال الأرقام الرقمية في السلسلة وفقًا للمنطقة أو اللغة. يجب أن تكون هذه القيمة معرفة في تعداد StringDigitSubstitution (القسم 2.1.1.30).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


يحصل أو يضبط قيمة عائمة 32 بت تحدد عدد الفراغات بين بداية سطر النص وأول موضع تبويب.

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


يحصل أو يضبط قيمة عائمة 32 بت تحدد عدد الفراغات بين بداية سطر النص وأول موضع تبويب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد نوع المعالجة التي تُجرى على السلسلة عندما يُصادف بادئة اختصار لوحة المفاتيح (أي علامة العطف). أساسًا، يحدد هذا الحقل ما إذا كان سيتم عرض بادئات اختصارات لوحة المفاتيح المتعلقة بالنص. يجب أن تكون القيمة معرفة في تعداد HotkeyPrefix (القسم 2.1.1.14).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد نوع المعالجة التي تُجرى على السلسلة عندما يُصادف بادئة اختصار لوحة المفاتيح (أي علامة العطف). أساسًا، يحدد هذا الحقل ما إذا كان سيتم عرض بادئات اختصارات لوحة المفاتيح المتعلقة بالنص. يجب أن تكون القيمة معرفة في تعداد HotkeyPrefix (القسم 2.1.1.14).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


يحصل أو يضبط كائن EmfPlusLanguageIdentifier (القسم 2.2.2.23) الذي يحدد اللغة المستخدمة للسلسلة.

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


يحصل أو يضبط كائن EmfPlusLanguageIdentifier (القسم 2.2.2.23) الذي يحدد اللغة المستخدمة للسلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


يحصل أو يضبط قيمة عائمة 32 بت تحدد طول الفراغ الذي يُضاف إلى الموضع الابتدائي للسلسلة. القيمة الافتراضية هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


يحصل أو يضبط قيمة عائمة 32 بت تحدد طول الفراغ الذي يُضاف إلى الموضع الابتدائي للسلسلة. القيمة الافتراضية هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة محاذاة السلسلة عموديًا داخل مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد طريقة محاذاة السلسلة عموديًا داخل مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد كائنات EmfPlusCharacterRange (القسم 2.2.2.8) المعرفة في حقل StringFormatData.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد كائنات EmfPlusCharacterRange (القسم 2.2.2.8) المعرفة في حقل StringFormatData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية محاذاة السلسلة أفقياً في مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment (القسم 2.1.1.29).

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية محاذاة السلسلة أفقياً في مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringAlignment (القسم 2.1.1.29).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


يحصل أو يضبط كائن EmfPlusStringFormatData (القسم 2.2.2.44) الذي يحدد بيانات تخطيط النص الاختيارية.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


يحصل أو يضبط كائن EmfPlusStringFormatData (القسم 2.2.2.44) الذي يحدد بيانات تخطيط النص الاختيارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد خيارات تخطيط النص للتنسيق والقص ومعالجة الخط. يجب أن تتكوّن هذه القيمة من أعلام StringFormat (القسم 2.1.2.8).

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد خيارات تخطيط النص للتنسيق والقص ومعالجة الخط. يجب أن تتكوّن هذه القيمة من أعلام StringFormat (القسم 2.1.2.8).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد مواضع التبويب المعرفة في حقل StringFormatData.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد عدد مواضع التبويب المعرفة في حقل StringFormatData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


يحصل أو يعيّن قيمة عائمة 32 بت تحدد نسبة المسافة الأفقية المخصصة لكل حرف في سلسلة محددة إلى عرض الحرف المحدد بالخط. القيم الكبيرة لهذه الخاصية تحدد مساحة واسعة بين الأحرف؛ القيم الأقل من 1 قد تتسبب في تداخل الأحرف. القيمة الافتراضية هي 1.03؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 1.00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


يحصل أو يعيّن قيمة عائمة 32 بت تحدد نسبة المسافة الأفقية المخصصة لكل حرف في سلسلة محددة إلى عرض الحرف المحدد بالخط. القيم الكبيرة لهذه الخاصية تحدد مساحة واسعة بين الأحرف؛ القيم الأقل من 1 قد تتسبب في تداخل الأحرف. القيمة الافتراضية هي 1.03؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 1.00.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


يحصل أو يعيّن قيمة عائمة 32 بت تحدد طول المسافة التي تُترك بعد السلسلة. القيمة الافتراضية هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


يحصل أو يعيّن قيمة عائمة 32 بت تحدد طول المسافة التي تُترك بعد السلسلة. القيمة الافتراضية هي 1/6 بوصة؛ بالنسبة للخطوط الطباعية، القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


يحصل أو يعيّن يحدد كيفية قص الأحرف من سلسلة كبيرة جداً لتناسب مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringTrimming (القسم 2.1.1.31).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


يحصل أو يعيّن يحدد كيفية قص الأحرف من سلسلة كبيرة جداً لتناسب مستطيل التخطيط. يجب أن تكون هذه القيمة معرفة في تعداد StringTrimming (القسم 2.1.1.31).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

