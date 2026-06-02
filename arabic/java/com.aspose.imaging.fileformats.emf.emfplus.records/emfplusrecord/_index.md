---
title: "EmfPlusRecord"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع سجل Emf الأساسي."
type: docs
weight: 46
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

نوع السجل الأساسي Emf+.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusRecord`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحصل على عدد صحيح غير موقع 16-بت يحدد نوع السجل. |
| [getFlags()](#getFlags--) | يحصل على عدد صحيح غير موقع 16-بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [setFlags(short value)](#setFlags-short-) | يعيّن عددًا صحيحًا غير موقع 16-بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [getSize()](#getSize--) | يحصل على عدد صحيح غير موقع 32-بت يحدد عدد البايتات المحاذاة إلى 32-بت في السجل بالكامل، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [setSize(int value)](#setSize-int-) | يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات المحاذاة إلى 32-بت في السجل بالكامل، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل. |
| [getDataSize()](#getDataSize--) | يحصل على عدد صحيح غير موقع 32-bit\\u2013aligned يحدد عدد البايتات للبيانات في حقل RecordData الذي يلي. |
| [setDataSize(int value)](#setDataSize-int-) | يعيّن عددًا صحيحًا غير موقع 32-bit\\u2013aligned يحدد عدد البايتات للبيانات في حقل RecordData الذي يلي. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPlusRecord`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getType() {#getType--}
```
public short getType()
```


يحصل على عدد صحيح غير موقع 16-بت يحدد نوع السجل.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


يحصل على عدد صحيح غير موقع 16-بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.

**Returns:**
short - العلامات.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


يعيّن عددًا صحيحًا غير موقع 16-بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short | العلامات. |

### getSize() {#getSize--}
```
public int getSize()
```


يحصل على عدد صحيح غير موقع 32-بت يحدد عدد البايتات المحاذاة إلى 32-بت في السجل بالكامل، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل.

**Returns:**
int - الحجم.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات المحاذاة إلى 32-بت في السجل بالكامل، بما في ذلك رأس السجل 12 بايت والبيانات الخاصة بالسجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الحجم. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


يحصل على عدد صحيح غير موقع 32-bit\u2013aligned يجب أن يحدد عدد البايتات للبيانات في حقل RecordData الذي يلي. هذا العدد لا يشمل رأس السجل الذي حجمه 12 بايت.

**Returns:**
int - حجم البيانات.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


يضبط عددًا صحيحًا غير موقع 32-bit\u2013aligned يجب أن يحدد عدد البايتات للبيانات في حقل RecordData الذي يلي. هذا العدد لا يشمل رأس السجل الذي حجمه 12 بايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | حجم البيانات. |

