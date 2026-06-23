---
title: "EmfPlusSetPageTransform"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetPageTransform يحدد عوامل التحجيم والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز."
type: docs
weight: 61
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

سجل EmfPlusSetPageTransform يحدد عوامل التحجيم والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusSetPageTransform`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | يحصل على وحدة القياس لإحداثيات مساحة الصفحة، من تعداد UnitType (القسم 2.1.1.33). |
| [getPageScale()](#getPageScale--) | يحصل أو يضبط قيمة عائمة 32‑بت تحدد عامل المقياس لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز. |
| [setPageScale(float value)](#setPageScale-float-) | يحصل أو يضبط قيمة عائمة 32‑بت تحدد عامل المقياس لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusSetPageTransform`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


يحصل على وحدة القياس لإحداثيات مساحة الصفحة، من تعداد UnitType (القسم 2.1.1.33). يجب ألا تكون هذه القيمة UnitTypeDisplay أو UnitTypeWorld.

القيمة: وحدة الصفحة.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


يحصل أو يضبط قيمة عائمة 32‑بت تحدد عامل المقياس لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز.

القيمة: مقياس الصفحة.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


يحصل أو يضبط قيمة عائمة 32‑بت تحدد عامل المقياس لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز.

القيمة: مقياس الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

