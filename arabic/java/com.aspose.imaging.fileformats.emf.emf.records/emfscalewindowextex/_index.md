---
title: "EmfScaleWindowExtex"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EMR_SCALEWINDOWEXTEX يعيد تحديد النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة."
type: docs
weight: 114
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

سجل EMR\_SCALEWINDOWEXTEX يعيد تحديد النافذة لسياق جهاز التشغيل باستخدام النسب المكوّنة من المضاعفات والقواسم المحددة.

لا يمكن تغيير الامتداد إذا كان سياق الجهاز يستخدم وضع تخطيط ثابت المقياس. فقط MM\\_ISOTROPIC و MM\\_ANISOTROPIC ليسا ثابتين المقياس. يتم تعديل امتدادات النافذة كما يلي. xNewWE = (xOldWE \\* xNum) / xDenom yNewWE = (yOldWE \\* yNum) / yDenom
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfScaleWindowExtex`. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | يُنشئ مثيلاً جديدًا للفئة [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getXNum()](#getXNum--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف الأفقي. |
| [setXNum(int value)](#setXNum-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف الأفقي. |
| [getXDenom()](#getXDenom--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد القاسم الأفقي. |
| [setXDenom(int value)](#setXDenom-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد القاسم الأفقي. |
| [getYNum()](#getYNum--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف العمودي. |
| [setYNum(int value)](#setYNum-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف العمودي. |
| [getYDenom()](#getYDenom--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد القاسم العمودي. |
| [setYDenom(int value)](#setYDenom-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد القاسم العمودي. |
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfScaleWindowExtex`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


يُنشئ مثيلاً جديدًا للفئة [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف الأفقي. يجب ألا يكون صفرًا.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف الأفقي. يجب ألا يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المقسّم الأفقي. يجب ألا يكون صفرًا.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المقسّم الأفقي. يجب ألا يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف الرأسي. يجب ألا يكون صفرًا.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف الرأسي. يجب ألا يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المقسّم الرأسي. يجب ألا يكون صفرًا.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد المقسّم الرأسي. يجب ألا يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

