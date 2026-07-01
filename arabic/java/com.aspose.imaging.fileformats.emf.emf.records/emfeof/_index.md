---
title: "EmfEof"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_EOF يشير إلى نهاية ملف الميتا ويحدد لوحة ألوان."
type: docs
weight: 48
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

سجل EMR\_EOF يشير إلى نهاية الملف التعريفي ويحدد لوحة ألوان.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfEof`. |
| [EmfEof()](#EmfEof--) | يُنشئ مثيلًا جديدًا من الفئة `EmfEof`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | يحصل على مخزن مؤقت اختياري يحتوي على بيانات لوحة الألوان، ولا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_EOF. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | يعيّن مخزنًا مؤقتًا اختياريًا يحتوي على بيانات لوحة الألوان، ولا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_EOF. |
| [getSizeLast()](#getSizeLast--) | يحصل على عدد صحيح غير موقع 32 بت يجب أن يكون مساويًا لـ Size ويجب أن يكون الحقل الأخير في السجل وبالتالي في ملف الميتا. |
| [setSizeLast(int value)](#setSizeLast-int-) | يضبط عددًا صحيحًا غير موقع 32 بت يجب أن يكون هو نفسه كـ Size ويجب أن يكون الحقل الأخير في السجل وبالتالي ملف التعريف. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfEof`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | السجل. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfEof`.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


يحصل على مخزن مؤقت اختياري يحتوي على بيانات لوحة الألوان، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_EOF. وبالتالي، الحقول في هذا المخزن التي تم تسميةها \"UndefinedSpace\" هي اختيارية ويجب تجاهلها. يجب أن يكون حجم هذا الحقل مضاعفًا لعدد 4 بايت.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


يضبط مخزنًا مؤقتًا اختياريًا يحتوي على بيانات لوحة الألوان، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_EOF. وبالتالي، الحقول في هذا المخزن التي تم تسميةها \"UndefinedSpace\" هي اختيارية ويجب تجاهلها. يجب أن يكون حجم هذا الحقل مضاعفًا لعدد 4 بايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


يحصل على عدد صحيح غير موقع 32 بت يجب أن يكون هو نفسه كـ Size ويجب أن يكون الحقل الأخير في السجل وبالتالي ملف التعريف. يجب أن تسبق كائنات LogPaletteEntry، إذا وجدت، هذا الحقل.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


يضبط عددًا صحيحًا غير موقع 32 بت يجب أن يكون هو نفسه كـ Size ويجب أن يكون الحقل الأخير في السجل وبالتالي ملف التعريف. يجب أن تسبق كائنات LogPaletteEntry، إذا وجدت، هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

