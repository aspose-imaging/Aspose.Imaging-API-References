---
title: "EmfLogPenEx"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LogPenEx يحدد عرض النمط ولون القلم المنطقي الموسع."
type: docs
weight: 28
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

كائن LogPenEx يحدد النمط والعرض واللون لقلم منطقي موسع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | يحصل أو يعيّن نمط القلم |
| [setPenStyle(int value)](#setPenStyle-int-) | يحصل أو يعيّن نمط القلم |
| [getWidth()](#getWidth--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عرض الخط المرسوم بالقلم. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عرض الخط المرسوم بالقلم. |
| [getBrushStyle()](#getBrushStyle--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد نمط الفرشاة للقلم من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). |
| [setBrushStyle(int value)](#setBrushStyle-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد نمط الفرشاة للقلم من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | يحصل أو يعيّن نمط تظليل الفرشاة. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | يحصل أو يعيّن نمط تظليل الفرشاة. |
| [getNumStyleEntities()](#getNumStyleEntities--) | يحصل على عدد العناصر في المصفوفة المحددة في حقل StyleEntry. |
| [getStyleEntry()](#getStyleEntry--) | يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة غير الموقعية 32 بت تحدد أطوال الشرطات والفواصل في الخط المرسوم بهذا القلم، عندما تكون قيمة PenStyle هي نمط الخط PS\_USERSTYLE للقلم. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة غير الموقعية 32 بت تحدد أطوال الشرطات والفواصل في الخط المرسوم بهذا القلم، عندما تكون قيمة PenStyle هي نمط الخط PS\_USERSTYLE للقلم. |
| [getBrushDibPattern()](#getBrushDibPattern--) | يحصل أو يعيّن نمط dib للفرشاة. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن نمط dib للفرشاة. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


يحصل أو يعيّن نمط القلم

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


يحصل أو يعيّن نمط القلم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عرض الخط المرسوم بالقلم. إذا كان نوع القلم في حقل PenStyle هو PS\_GEOMETRIC، تكون هذه القيمة العرض بوحدات منطقية؛ وإلا يتم تحديد العرض بوحدات الجهاز. إذا كان نوع القلم في حقل PenStyle هو PS\_COSMETIC، يجب أن تكون هذه القيمة 0x00000001.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عرض الخط المرسوم بالقلم. إذا كان نوع القلم في حقل PenStyle هو PS\_GEOMETRIC، تكون هذه القيمة العرض بوحدات منطقية؛ وإلا يتم تحديد العرض بوحدات الجهاز. إذا كان نوع القلم في حقل PenStyle هو PS\_COSMETIC، يجب أن تكون هذه القيمة 0x00000001.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد نمط الفرشاة للقلم من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). إذا كان نوع القلم في حقل PenStyle هو PS\_GEOMETRIC، يجب أن تكون هذه القيمة إما BS\_SOLID أو BS\_HATCHED. يمكن أن تكون قيمة هذا الحقل BS\_NULL، ولكن فقط إذا كان نمط الخط المحدد في PenStyle هو PS\_NULL. يجب استخدام نمط BS\_NULL لتحديد فرشاة لا تأثير لها.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد نمط الفرشاة للقلم من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). إذا كان نوع القلم في حقل PenStyle هو PS\_GEOMETRIC، يجب أن تكون هذه القيمة إما BS\_SOLID أو BS\_HATCHED. يمكن أن تكون قيمة هذا الحقل BS\_NULL، ولكن فقط إذا كان نمط الخط المحدد في PenStyle هو PS\_NULL. يجب استخدام نمط BS\_NULL لتحديد فرشاة لا تأثير لها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8). تفسير هذا الحقل يعتمد على قيمة BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم.

القيمة: لون ARGB 32‑بت

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8). تفسير هذا الحقل يعتمد على قيمة BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم.

القيمة: لون ARGB 32‑بت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


يحصل أو يعيّن نمط تظليل الفرشاة. تعريف هذا الحقل يعتمد على قيمة BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


يحصل أو يعيّن نمط تظليل الفرشاة. تعريف هذا الحقل يعتمد على قيمة BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


يحصل على عدد العناصر في المصفوفة المحددة في حقل StyleEntry. يجب أن تكون هذه القيمة صفرًا إذا لم يحدد PenStyle PS\_USERSTYLE.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة غير الموقعية 32 بت تحدد أطوال الشرطات والفواصل في الخط المرسوم بهذا القلم، عندما تكون قيمة PenStyle هي نمط الخط PS\_USERSTYLE للقلم. تحتوي المصفوفة على عدد من الإدخالات يحدده NumStyleEntries، لكنها تُستعمل كما لو أنها تتكرر إلى ما لا نهاية. الإدخال الأول في المصفوفة يحدد طول الشَرطَة الأولى. الإدخال الثاني يحدد طول الفاصل الأول. بعد ذلك تتناوب أطوال الشرطات والفواصل. إذا كان نوع القلم في حقل PenStyle هو PS\_GEOMETRIC، تُحدد الأطوال بوحدات منطقية؛ وإلا تُحدد بوحدات الجهاز.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة غير الموقعية 32 بت تحدد أطوال الشرطات والفواصل في الخط المرسوم بهذا القلم، عندما تكون قيمة PenStyle هي نمط الخط PS\_USERSTYLE للقلم. تحتوي المصفوفة على عدد من الإدخالات يحدده NumStyleEntries، لكنها تُستعمل كما لو أنها تتكرر إلى ما لا نهاية. الإدخال الأول في المصفوفة يحدد طول الشَرطَة الأولى. الإدخال الثاني يحدد طول الفاصل الأول. بعد ذلك تتناوب أطوال الشرطات والفواصل. إذا كان نوع القلم في حقل PenStyle هو PS\_GEOMETRIC، تُحدد الأطوال بوحدات منطقية؛ وإلا تُحدد بوحدات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


يحصل أو يعيّن نمط dib للفرشاة.

القيمة: نمط الفرشاة dib.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن نمط dib للفرشاة.

القيمة: نمط الفرشاة dib.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

