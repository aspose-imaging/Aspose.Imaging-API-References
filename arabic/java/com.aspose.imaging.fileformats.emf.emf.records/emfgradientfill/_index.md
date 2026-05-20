---
title: "EmfGradientFill"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_GRADIENTFILL يحدد تعبئة المستطيلات أو المثلثات بتدرجات اللون."
type: docs
weight: 65
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

السجل EMR\_GRADIENTFILL يحدد ملء المستطيلات أو المثلثات بتدرجات لونية.

سجل EMR\\_GRADIENTFILL الذي يحدد أن رؤوس المثلث الثلاثة يجب أن تملأ الشكل بتدرجات ناعمة للألوان.[85] سجل EMR\\_GRADIENTFILL الذي يحدد أن رؤوس المستطيل العلوية اليسرى والسفلية اليمنى يجب أن تملأ الشكل بتدرجات ناعمة للون. هناك وضعا تعبئة تدرج في تعداد GradientFill يمكن استخدامها عند رسم مستطيل. في وضع GRADIENT\\_FILL\\_RECT\\_H، يُملأ المستطيل من اليسار إلى اليمين. في وضع GRADIENT\\_FILL\\_RECT\\_V، يُملأ المستطيل من الأعلى إلى الأسفل. ملاحظة يجب أن يتجاهل سجل EMR\\_GRADIENTFILL حقول Alpha في كائنات TriVertex. يمكن استخدام سجل EMR\\_ALPHABLEND (القسم 2.3.1.1) الذي يتبع مباشرة سجل EMR\\_GRADIENTFILL لتطبيق تدرج شفافية ألفا على المنطقة المملوءة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا للفئة `EmfGradientFill`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا محيطًا، بوحدات الجهاز شاملة-شاملة. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا محيطًا، بوحدات الجهاز شاملة-شاملة. |
| [getNVer()](#getNVer--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد الرؤوس. |
| [setNVer(int value)](#setNVer-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد الرؤوس. |
| [getNTri()](#getNTri--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد المستطيلات أو المثلثات التي سيتم تعبئتها. |
| [setNTri(int value)](#setNTri-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد المستطيلات أو المثلثات التي سيتم تعبئتها. |
| [getUlMode()](#getUlMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد وضع تعبئة التدرج. |
| [setUlMode(int value)](#setUlMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد وضع تعبئة التدرج. |
| [getVertexData()](#getVertexData--) | يحصل أو يعيّن الكائنات التي تحدد رؤوس إما المستطيلات أو المثلثات والألوان التي تتCorrespond لها. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | يحصل أو يعيّن الكائنات التي تحدد رؤوس إما المستطيلات أو المثلثات والألوان التي تتCorrespond لها. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


ينشئ مثيلًا جديدًا للفئة `EmfGradientFill`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا محيطًا، بوحدات الجهاز شاملة-شاملة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا محيطًا، بوحدات الجهاز شاملة-شاملة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد الرؤوس.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد الرؤوس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد المستطيلات أو المثلثات التي سيتم تعبئتها.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد المستطيلات أو المثلثات التي سيتم تعبئتها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد وضع ملء التدرج. يجب أن تكون القيمة ضمن تعداد GradientFill (القسم 2.1.15).

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد وضع ملء التدرج. يجب أن تكون القيمة ضمن تعداد GradientFill (القسم 2.1.15).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


يحصل أو يعيّن الكائنات التي تحدد رؤوس إما المستطيلات أو المثلثات والألوان التي تتCorrespond لها.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


يحصل أو يعيّن الكائنات التي تحدد رؤوس إما المستطيلات أو المثلثات والألوان التي تتCorrespond لها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

