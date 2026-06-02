---
title: "XmpPackage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل التجريد الأساسي لحزمة XMP."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

يمثل التجريد الأساسي لحزمة XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | يُنشئ مثيلاً جديداً من الفئة `XmpPackage`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | يحصل على مساحة الاسم XML. |
| [getPrefix()](#getPrefix--) | يحصل على البادئة. |
| [getNamespaceUri()](#getNamespaceUri--) | يحصل على URI مساحة الاسم. |
| [getKeys()](#getKeys--) | يحصل على المفاتيح في حزمة XMP. |
| [getCount()](#getCount--) | يحصل على عدد مفاتيح XMP. |
| [containsKey(String key)](#containsKey-java.lang.String-) | يحدد ما إذا كانت هذه المجموعة تحتوي على المفتاح المحدد. |
| [get_Item(String key)](#get-Item-java.lang.String-) | يحصل أو يضبط الـ `Object` بالمفتاح المحدد. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | يضبط الـ `Object` بالمفتاح المحدد. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | يضيف القيمة إلى المفتاح المحدد. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | يضيف القيمة إلى المفتاح المحدد. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | يحصل على القيمة بواسطة الـ `key`. |
| [remove(String key)](#remove-java.lang.String-) | إزالة القيمة بالمفتاح المحدد. |
| [clear()](#clear--) | يمسح هذا المثيل. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | يضبط القيمة. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | يضبط القيمة. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | يضبط قيمة نوع XMP. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [iterator()](#iterator--) | يرجع عدّادًا يتنقل عبر المجموعة. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


يُنشئ مثيلاً جديداً من الفئة `XmpPackage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بادئة | java.lang.String | البادئة. |
| namespaceUri | java.lang.String | URI مساحة الاسم. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


يحصل على مساحة الاسم XML.

القيمة: مساحة الاسم XML.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


يحصل على البادئة.

القيمة: البادئة.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


يحصل على URI مساحة الاسم.

القيمة: معرف URI لمساحة الاسم.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


يحصل على المفاتيح في حزمة XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


يحصل على عدد مفاتيح XMP.

**Returns:**
int - عدد مفاتيح XMP.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


يحدد ما إذا كانت هذه المجموعة تحتوي على المفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي سيتم فحصه. |

**Returns:**
boolean - `true` إذا كانت المجموعة تحتوي على المفتاح المحدد؛ وإلا `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


يحصل أو يضبط الـ `Object` بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي يحدد القيمة. |

**Returns:**
java.lang.Object - يرجع الـ `Object` بالمفتاح المحدد.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


يضبط الـ `Object` بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي يحدد القيمة. |
| القيمة | java.lang.Object | قيمة الـ `Object`. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


يضيف القيمة إلى المفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | java.lang.String | القيمة التي سيُضاف إليها. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


يضيف القيمة إلى المفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | java.lang.Object | القيمة التي سيُضاف إليها. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


يحصل على القيمة بواسطة الـ `key`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | مفتاح عنصر XMP. |
| القيمة | java.lang.Object[] | قيمة XMP. |

**Returns:**
boolean - `true` إذا كانت المجموعة تحتوي على `key`؛ وإلا `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


إزالة القيمة بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يُحدَّد بالقيمة التي تم إزالتها. |

**Returns:**
boolean - يرجع true إذا تمت إزالة القيمة بالمفتاح المحدد.
### clear() {#clear--}
```
public void clear()
```


يمسح هذا المثيل.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


يضبط القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | القيمة التي سيُضاف إليها. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


يضبط القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | القيمة التي سيُضاف إليها. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


يضبط قيمة نوع XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يُحدَّد بالقيمة المحددة. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | القيمة التي سيُضبط عليها. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يُعيد قيمة XMP المحوّلة إلى تمثيل XML.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


يرجع عدّادًا يتنقل عبر المجموعة.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - `T:System.Collections.Generic.IEnumerator\`1` يمكن استخدامه للتنقل عبر المجموعة.
