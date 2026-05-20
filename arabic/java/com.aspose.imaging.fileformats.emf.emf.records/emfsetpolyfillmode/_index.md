---
title: "EmfSetPolyFillMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETPOLYFILLMODE يحدد وضع ملء المضلع."
type: docs
weight: 136
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

سجل EMR\_SETPOLYFILLMODE يعرّف وضع تعبئة المضلع.

بشكل عام، تختلف الأوضاع فقط في الحالات التي يجب فيها ملء مضلع معقد ومتداخل؛ على سبيل المثال، مضلع خماسي الشكل يشكل نجمة خماسية النقاط مع مضلع خماسي في المركز. في مثل هذه الحالات، يجب أن يملأ وضع ALTERNATE كل منطقة مغلقة أخرى داخل المضلع (نقاط النجمة)، بينما يجب أن يملأ وضع WINDING جميع المناطق (نقاط النجمة والمضلع الخماسي). عندما يكون وضع الملء هو ALTERNATE، يجب ملء المسافة بين الجوانب ذات الأرقام الفردية والزوجية للمضلع في كل خط مسح. أي أن المسافة بين الجانب الأول والثاني يجب أن تُملأ، وكذلك بين الجانب الثالث والرابع، وهكذا. عندما يكون وضع الملء هو WINDING، يجب ملء أي منطقة لها قيمة winding غير صفرية. قيمة winding هي عدد المرات التي سيعود فيها القلم المستخدم لرسم المضلع حول المنطقة. اتجاه كل حافة من حواف المضلع ذو أهمية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | ينشئ مثيلاً جديداً من الفئة `EmfSetPolyFillMode`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع ملء المضلع ويجب أن يكون ضمن تعداد PolygonFillMode (القسم 2.1.27). |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع ملء المضلع ويجب أن يكون ضمن تعداد PolygonFillMode (القسم 2.1.27). |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfSetPolyFillMode`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


ينشئ مثيلاً جديداً من الفئة `EmfSetPolyFillMode`.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع ملء المضلع ويجب أن يكون ضمن تعداد PolygonFillMode (القسم 2.1.27).

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع ملء المضلع ويجب أن يكون ضمن تعداد PolygonFillMode (القسم 2.1.27).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

