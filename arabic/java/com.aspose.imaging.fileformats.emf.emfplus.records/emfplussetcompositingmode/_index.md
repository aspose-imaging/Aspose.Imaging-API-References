---
title: "EmfPlusSetCompositingMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetCompositingMode يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية."
type: docs
weight: 58
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

سجل EmfPlusSetCompositingMode يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetCompositingMode`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | يحصل أو يضبط قيمة وضع التركيب، من تعداد CompositingMode (القسم 2.1.1.5). |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | يحصل أو يضبط قيمة وضع التركيب، من تعداد CompositingMode (القسم 2.1.1.5). |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetCompositingMode`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


يحصل أو يضبط قيمة وضع التركيب، من تعداد CompositingMode (القسم 2.1.1.5). يمكن التعبير عن التركيب كحالة دمج ألفا، والتي يمكن أن تكون مفعلة أو غير مفعلة.

القيمة: وضع التركيب.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


يحصل أو يضبط قيمة وضع التركيب، من تعداد CompositingMode (القسم 2.1.1.5). يمكن التعبير عن التركيب كحالة دمج ألفا، والتي يمكن أن تكون مفعلة أو غير مفعلة.

القيمة: وضع التركيب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

