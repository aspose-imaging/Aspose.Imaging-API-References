---
title: "EmfPlusHatchBrushData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusHatchBrushData يحدد نمط التهشير لفرشاة رسومية."
type: docs
weight: 45
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

كائن EmfPlusHatchBrushData يحدد نمط التهشير لفرشاة رسومية.

يتم تحديد فراشي الرسومات بواسطة كائنات `EmfPlusBrush` (القسم 2.2.1.1). فرشاة التهشير تُلوّن الخلفية وترسم نمطًا من الخطوط والنقاط والشرطات والمربعات وخطوط التهشير المتقاطعة فوق هذه الخلفية. تُعرّف فرشاة التهشير لونين: أحدهما للخلفية والآخر للنمط فوق الخلفية. يُطلق على لون الخلفية اسم لون الخلفية، وعلى لون النمط اسم لون المقدمة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لتلوين خلفية نمط التهشير. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لتلوين خلفية نمط التهشير. |
| [getForeArgb32Color()](#getForeArgb32Color--) | يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لرسم خطوط نمط التهشير. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لرسم خطوط نمط التهشير. |
| [getHatchStyle()](#getHatchStyle--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نمط تهشير الفرشاة. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نمط تهشير الفرشاة. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لتلوين خلفية نمط التهشير.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لتلوين خلفية نمط التهشير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لرسم خطوط نمط التهشير.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


يحصل أو يضبط كائن EmfPlusArgb 32‑بت يحدد اللون المستخدم لرسم خطوط نمط التهشير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نمط تهشير الفرشاة. يجب أن يكون معرفًا في تعداد `EmfPlusHatchStyle`.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نمط تهشير الفرشاة. يجب أن يكون معرفًا في تعداد `EmfPlusHatchStyle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

