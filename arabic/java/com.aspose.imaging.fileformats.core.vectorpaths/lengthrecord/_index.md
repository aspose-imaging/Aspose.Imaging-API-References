---
title: "LengthRecord"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة سجل طول المسار الفرعي"
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

فئة سجل طول المسار الفرعي
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | يُنشئ مثيلًا جديدًا من الفئة [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
| [LengthRecord()](#LengthRecord--) | يُنشئ مثيلًا جديدًا من الفئة [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isClosed()](#isClosed--) | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا. |
| [setClosed(boolean value)](#setClosed-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا. |
| [isOpen()](#isOpen--) | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل مفتوحًا. |
| [setOpen(boolean value)](#setOpen-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا المثيل مفتوحًا. |
| [getRecordCount()](#getRecordCount--) | يحصل على عدد السجلات. |
| [setRecordCount(int value)](#setRecordCount-int-) | يضبط عدد السجلات. |
| [getType()](#getType--) | يحصل على النوع. |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | يحصل على عدد سجلات عقد bezier. |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | يضبط عدد سجلات عقد bezier. |
| [getPathOperations()](#getPathOperations--) | يحصل على عمليات المسار. |
| [setPathOperations(int value)](#setPathOperations-int-) | يضبط عمليات المسار. |
| [getShapeIndex()](#getShapeIndex--) | يحصل على فهرس الشكل الحالي للمسار في الطبقة. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | يضبط فهرس الشكل الحالي للمسار في الطبقة. |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


يُنشئ مثيلًا جديدًا من الفئة [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات السجل. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


يُنشئ مثيلًا جديدًا من الفئة [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا.

القيمة: `true` إذا كان هذا المثيل مغلقًا؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا.
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا.

القيمة: `true` إذا كان هذا المثيل مغلقًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا. |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


يحصل على قيمة تشير إلى ما إذا كان هذا المثيل مفتوحًا.

القيمة: `true` إذا كان هذا الكائن مفتوحًا؛ وإلا `false`.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان هذا الكائن مفتوحًا.
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان هذا المثيل مفتوحًا.

القيمة: `true` إذا كان هذا الكائن مفتوحًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان هذا الكائن مفتوحًا. |

### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


يحصل على عدد السجلات.

القيمة: عدد السجلات.

**Returns:**
int - عدد السجلات.
### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


يضبط عدد السجلات.

القيمة: عدد السجلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عدد السجلات. |

### getType() {#getType--}
```
public short getType()
```


يحصل على النوع.

القيمة: النوع.

**Returns:**
short - النوع.
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


يحصل على عدد سجلات عقد bezier.

**Returns:**
int - عدد سجلات عقد bezier.
### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


يضبط عدد سجلات عقد bezier.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عدد سجلات عقد bezier. |

### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


يحصل على عمليات المسار.

**Returns:**
int - عمليات المسار.
### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


يضبط عمليات المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عمليات المسار. |

### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


يحصل على فهرس الشكل الحالي للمسار في الطبقة.

**Returns:**
int - فهرس الشكل الحالي للمسار في الطبقة.
### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


يضبط فهرس الشكل الحالي للمسار في الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | فهرس الشكل الحالي للمسار في الطبقة. |

