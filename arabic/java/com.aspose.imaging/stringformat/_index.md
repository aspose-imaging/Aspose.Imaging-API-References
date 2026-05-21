---
title: "StringFormat"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يُغَلِّف معلومات تنسيق النص مثل محاذاة الاتجاه وإيقافات الجدولة، وتعديلات العرض مثل إدراج النقاط الثلاثية واستبدال الأرقام الوطنية وميزات OpenType."
type: docs
weight: 112
url: /ar/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

يُغَلِّف معلومات تنسيق النص (مثل المحاذاة، الاتجاه وإيقافات الجدولة) وتعديلات العرض (مثل إدراج النقاط الثلاثية واستبدال الأرقام الوطنية) وميزات OpenType. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [StringFormat()](#StringFormat--) | ينشئ كائنًا جديدًا من النوع `com.aspose.imaging.StringFormat`. |
| [StringFormat(int options)](#StringFormat-int-) | ينشئ كائنًا جديدًا من النوع `com.aspose.imaging.StringFormat` باستخدام تعداد `com.aspose.imaging.StringFormatFlags` المحدد واللغة. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | ينشئ كائنًا جديدًا من النوع `com.aspose.imaging.StringFormat` من الكائن الموجود `com.aspose.imaging.StringFormat` المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | يحصل على كائن افتراضي عام من النوع `com.aspose.imaging.StringFormat`. |
| [getGenericTypographic()](#getGenericTypographic--) | يحصل على كائن نمط نص عام `com.aspose.imaging.StringFormat`. |
| [getFormatFlags()](#getFormatFlags--) | يحصل على تعداد `com.aspose.imaging.StringFormatFlags` يحتوي على معلومات التنسيق. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | يضبط تعداد `com.aspose.imaging.StringFormatFlags` يحتوي على معلومات التنسيق. |
| [getAlignment()](#getAlignment--) | يحصل على معلومات محاذاة النص على المستوى العمودي. |
| [setAlignment(int value)](#setAlignment-int-) | يضبط معلومات محاذاة النص على المستوى العمودي. |
| [getLineAlignment()](#getLineAlignment--) | يحصل على محاذاة السطر على المستوى الأفقي. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | يضبط محاذاة السطر على المستوى الأفقي. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | يحصل على كائن `com.aspose.imaging.HotkeyPrefix` لهذا الكائن `com.aspose.imaging.StringFormat`. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | يضبط كائن `com.aspose.imaging.HotkeyPrefix` لهذا الكائن `com.aspose.imaging.StringFormat`. |
| [getTrimming()](#getTrimming--) | يحصل على تعداد `com.aspose.imaging.StringTrimming` لهذا الكائن `com.aspose.imaging.StringFormat`. |
| [setTrimming(int value)](#setTrimming-int-) | يضبط تعداد `com.aspose.imaging.StringTrimming` لهذا الكائن `com.aspose.imaging.StringFormat`. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | يحصل على الطريقة المستخدمة لاستبدال الأرقام. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | يضبط الطريقة المستخدمة لاستبدال الأرقام. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | يحصل على اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [getFirstTabOffset()](#getFirstTabOffset--) | يحصل على عدد المسافات بين بداية سطر النص وأول موضع تبويب. |
| [getTabStops()](#getTabStops--) | يحصل على مصفوفة من المسافات بين مواضع التبويب بالوحدات المحددة بواسطة الخاصية `P:Aspose.Imaging.getGraphics().PageUnit`. |
| [getCustomCharIdent()](#getCustomCharIdent--) | يحصل على معرف الحرف المخصص. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | يضبط معرف الحرف المخصص. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذا الكائن `com.aspose.imaging.StringFormat`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | يضبط مواضع التبويب لهذا الكائن `com.aspose.imaging.StringFormat`. |
| [toString()](#toString--) | يحوّل هذا الكائن `com.aspose.imaging.StringFormat` إلى سلسلة قابلة للقراءة البشرية. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


ينشئ كائنًا جديدًا من النوع `com.aspose.imaging.StringFormat`.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


ينشئ كائنًا جديدًا من النوع `com.aspose.imaging.StringFormat` باستخدام تعداد `com.aspose.imaging.StringFormatFlags` المحدد واللغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خيارات | int | تعداد `com.aspose.imaging.StringFormatFlags` للكائن الجديد `com.aspose.imaging.StringFormat`. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


ينشئ كائنًا جديدًا من النوع `com.aspose.imaging.StringFormat` من الكائن الموجود `com.aspose.imaging.StringFormat` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | الكائن `com.aspose.imaging.StringFormat` الذي يُستخدم لتهيئة الكائن الجديد `com.aspose.imaging.StringFormat`. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


يحصل على كائن افتراضي عام من النوع `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


يحصل على كائن نمط نص عام `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


يحصل على تعداد `com.aspose.imaging.StringFormatFlags` يحتوي على معلومات التنسيق.

**Returns:**
int - تعداد `com.aspose.imaging.StringFormatFlags` يحتوي على معلومات التنسيق.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


يضبط تعداد `com.aspose.imaging.StringFormatFlags` يحتوي على معلومات التنسيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد `com.aspose.imaging.StringFormatFlags` يحتوي على معلومات التنسيق. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


يحصل على معلومات محاذاة النص على المستوى العمودي.

**Returns:**
int - تعداد `com.aspose.imaging.StringAlignment` يحدد معلومات محاذاة النص.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


يضبط معلومات محاذاة النص على المستوى العمودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد `com.aspose.imaging.StringAlignment` يحدد معلومات محاذاة النص. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


يحصل على محاذاة السطر على المستوى الأفقي.

**Returns:**
int - تعداد `com.aspose.imaging.StringAlignment` يمثل محاذاة السطر.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


يضبط محاذاة السطر على المستوى الأفقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد `com.aspose.imaging.StringAlignment` يمثل محاذاة السطر. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


يحصل على كائن `com.aspose.imaging.HotkeyPrefix` لهذا الكائن `com.aspose.imaging.StringFormat`.

**Returns:**
int - كائن `com.aspose.imaging.HotkeyPrefix` لهذا الكائن `com.aspose.imaging.StringFormat`، القيمة الافتراضية هي `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


يضبط كائن `com.aspose.imaging.HotkeyPrefix` لهذا الكائن `com.aspose.imaging.StringFormat`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | كائن `com.aspose.imaging.HotkeyPrefix` لهذا الكائن `com.aspose.imaging.StringFormat`، القيمة الافتراضية هي `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


يحصل على تعداد `com.aspose.imaging.StringTrimming` لهذا الكائن `com.aspose.imaging.StringFormat`.

**Returns:**
int - تعداد `com.aspose.imaging.StringTrimming` يوضح كيفية تقليم النص المرسوم بهذا الكائن `com.aspose.imaging.StringFormat` عندما يتجاوز حدود مستطيل التخطيط.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


يضبط تعداد `com.aspose.imaging.StringTrimming` لهذا الكائن `com.aspose.imaging.StringFormat`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد `com.aspose.imaging.StringTrimming` يوضح كيفية تقليم النص المرسوم بهذا الكائن `com.aspose.imaging.StringFormat` عندما يتجاوز حدود مستطيل التخطيط. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


يحصل على الطريقة المستخدمة لاستبدال الأرقام.

**Returns:**
int - قيمة تعداد `com.aspose.imaging.StringDigitSubstitute` تحدد كيفية استبدال الأحرف في سلسلة لا يمكن عرضها لأنها غير مدعومة من الخط الحالي.

تم تقديم الدالة setter للطريقة القديمة SetDigitSubstitution.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


يضبط الطريقة المستخدمة لاستبدال الأرقام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | قيمة تعداد `com.aspose.imaging.StringDigitSubstitute` تحدد كيفية استبدال الأحرف في سلسلة لا يمكن عرضها لأنها غير مدعومة من الخط الحالي. |

تم تقديم الدالة setter للطريقة القديمة SetDigitSubstitution. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


يحصل على اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية.

**Returns:**
int - معرف لغة دعم اللغة الوطنية (NLS) يحدد اللغة التي ستُستخدم عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. يمكنك تمرير خاصية `P:System.Globalization.CultureInfo.LCID` لكائن `System.Globalization.CultureInfo` كمعرف لغة NLS. على سبيل المثال، افترض أنك أنشأت وضبطت إعداد محلي "ar-EG". إذا مررت `com.aspose.imaging.StringDigitSubstitute.Traditional` إلى الطريقة `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`، فستُستبدل الأرقام العربية-الهندية بالأرقام الغربية عند العرض.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | معرف لغة دعم اللغة الوطنية (NLS) يحدد اللغة التي ستُستخدم عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. يمكنك تمرير خاصية `P:System.Globalization.CultureInfo.LCID` لكائن `System.Globalization.CultureInfo` كمعرف لغة NLS. على سبيل المثال، افترض أنك أنشأت وضبطت إعداد محلي "ar-EG". إذا مررت `com.aspose.imaging.StringDigitSubstitute.Traditional` إلى الطريقة `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`، فستُستبدل الأرقام العربية-الهندية بالأرقام الغربية عند العرض. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


يحصل على عدد المسافات بين بداية سطر النص وأول موضع تبويب.

**Returns:**
float - إزاحة التبويب الأولى.

تم تقديم الخاصية للطريقة المحذوفة GetTabStops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


يحصل على مصفوفة من المسافات بين مواضع التبويب بالوحدات المحددة بواسطة الخاصية `P:Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - نقاط التبويب.

تم تقديم الخاصية للطريقة المحذوفة GetTabStops.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


يحصل على معرف الحرف المخصص.

القيمة: معرف الحرف المخصص.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


يضبط معرف الحرف المخصص.

القيمة: معرف الحرف المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | معرف الحرف المخصص. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


ينشئ نسخة عميقة من هذا الكائن `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


يضبط مواضع التبويب لهذا الكائن `com.aspose.imaging.StringFormat`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstTabOffset | float | عدد المسافات بين بداية سطر النص وأول نقطة تبويب. |
| tabStops | float[] | مصفوفة من المسافات بين نقاط التبويب بالوحدات المحددة بواسطة خاصية `com.aspose.imaging.Graphics.PageUnit`. |

### toString() {#toString--}
```
public String toString()
```


يحوّل هذا الكائن `com.aspose.imaging.StringFormat` إلى سلسلة قابلة للقراءة البشرية.

**Returns:**
java.lang.String - تمثيل نصي لهذا الكائن `com.aspose.imaging.StringFormat`.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن الآخر. |

**Returns:**
boolean - نتيجة مقارنة المساواة.
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int - رمز التجزئة.
