---
title: "EmfSelectPalette"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SELECTPALETTE يحدد لوحة ألوان منطقية لسياق جهاز التشغيل."
type: docs
weight: 117
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

سجل EMR\_SELECTPALETTE يحدد لوحة ألوان منطقية لسياق جهاز التشغيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSelectPalette`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhPal()](#getIhPal--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد إما فهرس كائن LogPalette (القسم 2.2.17) في جدول كائنات EMF أو القيمة DEFAULT\_PALETTE، والتي هي فهرس لوحة كائن مخزون من تعداد StockObject (القسم 2.1.31). |
| [setIhPal(int value)](#setIhPal-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد إما فهرس كائن LogPalette (القسم 2.2.17) في جدول كائنات EMF أو القيمة DEFAULT\_PALETTE، والتي هي فهرس لوحة كائن مخزون من تعداد StockObject (القسم 2.1.31). |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSelectPalette`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد إما فهرس كائن LogPalette (القسم 2.2.17) في جدول كائنات EMF أو القيمة DEFAULT\_PALETTE، والتي هي فهرس لوحة كائن مخزون من تعداد StockObject (القسم 2.1.31).

يجب ألا تكون هذه القيمة صفرًا أو فهرس أي كائن مخزون آخر.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد إما فهرس كائن LogPalette (القسم 2.2.17) في جدول كائنات EMF أو القيمة DEFAULT\_PALETTE، والتي هي فهرس لوحة كائن مخزون من تعداد StockObject (القسم 2.1.31).

يجب ألا تكون هذه القيمة صفرًا أو فهرس أي كائن مخزون آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

