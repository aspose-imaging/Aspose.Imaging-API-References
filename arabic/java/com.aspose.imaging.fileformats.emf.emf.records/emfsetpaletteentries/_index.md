---
title: "EmfSetPaletteEntries"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETPALETTEENTRIES يحدد قيم ألوان RGB في نطاق من الإدخالات لكائن LogPalette الموجود في القسم 2.2.17."
type: docs
weight: 134
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

السجل EMR\_SETPALETTEENTRIES يعرّف قيم ألوان RGB في مجموعة من الإدخالات لكائن LogPalette الموجود (القسم 2.2.17).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSetPaletteEntries`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhPal()](#getIhPal--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للوحة الألوان. |
| [setIhPal(int value)](#setIhPal-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للوحة الألوان. |
| [getStart()](#getStart--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس الإدخال الأول لتعيينه. |
| [setStart(int value)](#setStart-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس الإدخال الأول لتعيينه. |
| [getNumberofEntries()](#getNumberofEntries--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الإدخالات. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الإدخالات. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | يحصل أو يعيّن مصفوفة من كائنات LogPaletteEntry (القسم 2.2.18)، بطول NumberOfEntries، التي تحدد بيانات إدخال لوحة الألوان. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | يحصل أو يعيّن مصفوفة من كائنات LogPaletteEntry (القسم 2.2.18)، بطول NumberOfEntries، التي تحدد بيانات إدخال لوحة الألوان. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSetPaletteEntries`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للوحة الألوان.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس الإدخال الأول لتعيينه.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس الإدخال الأول لتعيينه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الإدخالات.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الإدخالات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


يحصل أو يعيّن مصفوفة من كائنات LogPaletteEntry (القسم 2.2.18)، بطول NumberOfEntries، التي تحدد بيانات إدخال لوحة الألوان. لا تحتوي أعضاء \"Values\" على أي قيم.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


يحصل أو يعيّن مصفوفة من كائنات LogPaletteEntry (القسم 2.2.18)، بطول NumberOfEntries، التي تحدد بيانات إدخال لوحة الألوان. لا تحتوي أعضاء \"Values\" على أي قيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

