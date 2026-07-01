---
title: "EmfLogBrushEx"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يعرّف كائن LogBrushEx لون النمط والنقشة لفرشاة مستقلة عن الجهاز."
type: docs
weight: 21
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

كائن LogBrushEx يحدد النمط واللون والنقشة لفرشاة مستقلة عن الجهاز.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نمط الفرشاة. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نمط الفرشاة. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | يحصل أو يعيّن كائن WMF ColorRef 32‑بت ([MS-WMF] القسم 2.2.2.8) يحدد لونًا. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | يحصل أو يعيّن كائن WMF ColorRef 32‑بت ([MS-WMF] القسم 2.2.2.8) يحدد لونًا. |
| [getBrushHatch()](#getBrushHatch--) | يحصل أو يعيّن حقلًا غير موقع 32‑بت يحتوي على بيانات تظليل الفرشاة. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | يحصل أو يعيّن حقلًا غير موقع 32‑بت يحتوي على بيانات تظليل الفرشاة. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نمط الفرشاة. يجب أن تكون القيمة تعدادًا من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). قيم الأنماط المدعومة في هذه البنية مُدرجة لاحقًا في هذا القسم. يجب استخدام نمط BS\_NULL لتحديد فرشاة لا تُحدث أي تأثير.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نمط الفرشاة. يجب أن تكون القيمة تعدادًا من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). قيم الأنماط المدعومة في هذه البنية مُدرجة لاحقًا في هذا القسم. يجب استخدام نمط BS\_NULL لتحديد فرشاة لا تُحدث أي تأثير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


يحصل أو يعيّن كائن WMF ColorRef 32‑بت ([MS-WMF] القسم 2.2.2.8) يحدد لونًا. تفسير هذا الحقل يعتمد على قيمة BrushStyle، كما هو موضح في الجدول التالي.

القيمة: لون ARGB 32‑بت

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


يحصل أو يعيّن كائن WMF ColorRef 32‑بت ([MS-WMF] القسم 2.2.2.8) يحدد لونًا. تفسير هذا الحقل يعتمد على قيمة BrushStyle، كما هو موضح في الجدول التالي.

القيمة: لون ARGB 32‑بت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


يحصل أو يعيّن حقلًا غير موقع 32‑بت يحتوي على بيانات تظليل الفرشاة. تفسيره يعتمد على قيمة BrushStyle،

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


يحصل أو يعيّن حقلًا غير موقع 32‑بت يحتوي على بيانات تظليل الفرشاة. تفسيره يعتمد على قيمة BrushStyle،

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

