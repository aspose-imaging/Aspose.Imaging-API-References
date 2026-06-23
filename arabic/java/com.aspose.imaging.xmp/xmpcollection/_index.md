---
title: "XmpCollection"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "مجموعة عناصر XMP."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

مجموعة عناصر XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | ينشئ مثيلاً جديدًا من الفئة [XmpCollection](../../com.aspose.imaging/xmp/xmpcollection). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | يضيف عنصرًا جديدًا. |
| [addObject(Object item)](#addObject-java.lang.Object-) | يضيف عنصر بيانات XMP. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | يضيف عنصرًا إلى المجموعة. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | ينسخ عناصر المجموعة إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على قيمة سلسلة XMP لهذا. |
| [getXmlValue()](#getXmlValue--) | يقوم بتحويل قيمة XMP إلى تمثيل XML. |
| [toString()](#toString--) | يرجع سلسلة XML تمثّل هذه الحالة. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


ينشئ مثيلاً جديدًا من الفئة [XmpCollection](../../com.aspose.imaging/xmp/xmpcollection).

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


يضيف عنصرًا جديدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| عنصر | java.lang.Object | العنصر الذي سيُضاف إلى قائمة العناصر. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


يضيف عنصر بيانات XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| عنصر | java.lang.Object | عنصر XMP. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


يزيل العنصر في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | المؤشر الصفري للعنصر الذي يجب إزالته. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


يضيف عنصرًا إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | الكائن الذي سيُضاف إلى المجموعة. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


ينسخ عناصر المجموعة إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | المصفوفة أحادية البعد التي هي وجهة العناصر المنسوخة من المجموعة. يجب أن تكون المصفوفة ذات فهرسة صفرية. |
| arrayIndex | int | الفهرس الصفري في المصفوفة حيث يبدأ النسخ. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


يحصل على قيمة سلسلة XMP لهذا.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


يقوم بتحويل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يُعيد قيمة XMP المحوّلة إلى تمثيل XML.
### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة XML تمثّل هذه الحالة.

**Returns:**
java.lang.String - سلسلة XML تمثّل هذه الحالة.
