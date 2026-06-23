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

نوع سجل الأساس Emf+.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusRecord`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |
| [getFlags()](#getFlags--) | يحصل على عدد صحيح غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [setFlags(short value)](#setFlags-short-) | يضبط عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [getSize()](#getSize--) | يحصل على عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المحاذاة إلى 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايتًا والبيانات الخاصة بالسجل. |
| [setSize(int value)](#setSize-int-) | يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المحاذاة إلى 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايتًا والبيانات الخاصة بالسجل. |
| [getDataSize()](#getDataSize--) | يحصل على عدد صحيح غير موقع 32‑بت يجب أن يحدد عدد البايتات المحاذاة إلى 32‑بت للبيانات في حقل RecordData التالي. |
| [setDataSize(int value)](#setDataSize-int-) | يضبط عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المحاذاة إلى 32‑بت للبيانات في حقل RecordData التالي. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusRecord`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getType() {#getType--}
```
public short getType()
```


يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل.

**Returns:**
قصير
### getFlags() {#getFlags--}
```
public short getFlags()
```


يحصل على عدد صحيح غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.

**Returns:**
short - العلامات.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


يضبط عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير | العلامات. |

### getSize() {#getSize--}
```
public int getSize()
```


يحصل على عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المحاذاة إلى 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايتًا والبيانات الخاصة بالسجل.

**Returns:**
int - الحجم.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يضبط عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المحاذاة إلى 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايتًا والبيانات الخاصة بالسجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الحجم. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


يحصل على عدد صحيح غير موقع 32‑بت يجب أن يحدد عدد البايتات المحاذاة إلى 32‑بت للبيانات في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايتًا.

**Returns:**
int - حجم البيانات.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


يضبط عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المحاذاة إلى 32‑بت للبيانات في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايتًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | حجم البيانات. |

