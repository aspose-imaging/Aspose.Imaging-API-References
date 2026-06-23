---
title: "EmfScaleViewportExtex"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SCALEVIEWPORTEXTEX يعيد تحديد منطقة العرض لسياق الجهاز باستخدام النسب التي تتكون من المضاعفات والمقاسم المحددة."
type: docs
weight: 113
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

السجل EMR\_SCALEVIEWPORTEXTEX يعيد تحديد نافذة العرض لسياق الجهاز باستخدام النسب التي تكونها المضاعفات والقواسم المحددة.

لا يمكن تغيير الامتداد إذا كان سياق الجهاز يستخدم وضع تخطيط مقياس ثابت. فقط MM\_ISOTROPIC و MM\_ANISOTROPIC ليسا بمقياس ثابت. يتم تعديل امتدادات منطقة العرض كما يلي. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfScaleViewportExtex`. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | يُنشئ نسخة جديدة من الفئة [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getXNum()](#getXNum--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف الأفقي. |
| [setXNum(int value)](#setXNum-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف الأفقي. |
| [getXDenom()](#getXDenom--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم الأفقي. |
| [setXDenom(int value)](#setXDenom-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم الأفقي. |
| [getYNum()](#getYNum--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف العمودي. |
| [setYNum(int value)](#setYNum-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف العمودي. |
| [getYDenom()](#getYDenom--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم العمودي. |
| [setYDenom(int value)](#setYDenom-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم العمودي. |
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfScaleViewportExtex`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


يُنشئ نسخة جديدة من الفئة [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف الأفقي. لا يمكن أن يكون صفرًا.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف الأفقي. لا يمكن أن يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم الأفقي. لا يمكن أن يكون صفرًا.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم الأفقي. لا يمكن أن يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف العمودي. لا يمكن أن يكون صفرًا.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المضاعف العمودي. لا يمكن أن يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم العمودي. لا يمكن أن يكون صفرًا.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-bit يحدد المقسّم العمودي. لا يمكن أن يكون صفرًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

