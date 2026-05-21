---
title: "EmfPlusObject"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusObject يحدد كائنًا للاستخدام في عمليات الرسومات."
type: docs
weight: 42
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

يسجل EmfPlusObject يحدد كائنًا للاستخدام في عمليات الرسومات. يمكن لتعريف الكائن أن يمتد عبر سجلات متعددة، وهو ما يتم الإشارة إليه بقيمة حقل Flags.

سجل EmfPlusObject عام؛ يُستخدم لجميع أنواع الكائنات. القيم الخاصة بأنواع الكائنات المحددة موجودة في حقل ObjectData. يتم وصف نموذج مفاهيمي لإدارة كائنات الرسومات في Managing Graphics Objects (القسم 3.1.2).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusObject`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isContinuable()](#isContinuable--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للمتابعة. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للمتابعة. |
| [getObjectType()](#getObjectType--) | يحصل أو يعيّن نوع الكائن. |
| [setObjectType(byte value)](#setObjectType-byte-) | يحصل أو يعيّن نوع الكائن. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getTotalObjectSize()](#getTotalObjectSize--) | يحصل أو يعيّن الحجم الكلي للكائن. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | يحصل أو يعيّن الحجم الكلي للكائن. |
| [getObjectData()](#getObjectData--) | يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على بيانات لنوع الكائن المحدد في حقل Flags. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على بيانات لنوع الكائن المحدد في حقل Flags. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPlusObject`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للمتابعة. يشير إلى أن تعريف الكائن يستمر في سجل EmfPlusObject التالي. لا يتم تعيين هذه العلامة أبدًا في السجل النهائي الذي يحدد الكائن.

القيمة: `true` إذا كان هذا المثيل مضغوطاً؛ وإلا `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للمتابعة. يشير إلى أن تعريف الكائن يستمر في سجل EmfPlusObject التالي. لا يتم تعيين هذه العلامة أبدًا في السجل النهائي الذي يحدد الكائن.

القيمة: `true` إذا كان هذا المثيل مضغوطاً؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


يحصل أو يعيّن نوع الكائن.

القيمة: نوع الكائن.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


يحصل أو يعيّن نوع الكائن.

القيمة: نوع الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. الفهرس في جدول كائنات EMF+ لربطه بالكائن الذي أنشأه هذا السجل. يجب أن تكون القيمة بين الصفر و63 شاملًا.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. الفهرس في جدول كائنات EMF+ لربطه بالكائن الذي أنشأه هذا السجل. يجب أن تكون القيمة بين الصفر و63 شاملًا.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


يحصل أو يعيّن الحجم الكلي للكائن. إذا كان السجل قابلًا للمتابعة، عندما يتم تعيين بت المتابعة، سيكون هذا الحقل موجودًا. الكائنات المتابعة لديها سجلات EMF+ متعددة تبدأ بـ EmfPlusContineudObjectRecord. كل سجل EmfPlusContinuedObjectRecord سيحتوي على TotalObjectSize. بمجرد قراءة عدد البايتات المحدد بـ TotalObjectSize، لن يُعامل السجل EMF+ التالي كجزء من الكائن المتابع.

القيمة: الحجم الكلي للكائن.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


يحصل أو يعيّن الحجم الكلي للكائن. إذا كان السجل قابلًا للمتابعة، عندما يتم تعيين بت المتابعة، سيكون هذا الحقل موجودًا. الكائنات المتابعة لديها سجلات EMF+ متعددة تبدأ بـ EmfPlusContineudObjectRecord. كل سجل EmfPlusContinuedObjectRecord سيحتوي على TotalObjectSize. بمجرد قراءة عدد البايتات المحدد بـ TotalObjectSize، لن يُعامل السجل EMF+ التالي كجزء من الكائن المتابع.

القيمة: الحجم الكلي للكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على بيانات لنوع الكائن المحدد في حقل Flags. قد يختلف محتوى وتنسيق البيانات لكل نوع كائن. راجع تعريفات الكائنات الفردية في القسم 2.2.1 لمزيد من المعلومات.

القيمة: بيانات الكائن.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على بيانات لنوع الكائن المحدد في حقل Flags. قد يختلف محتوى وتنسيق البيانات لكل نوع كائن. راجع تعريفات الكائنات الفردية في القسم 2.2.1 لمزيد من المعلومات.

القيمة: بيانات الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

