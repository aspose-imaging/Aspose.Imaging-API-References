---
title: "XmpPackage فئة"
type: docs
weight: 460
url: /ar/python-net/aspose.imaging.xmp/xmppackage/
---

**Summary:** Represents base abstraction for XMP package.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackage

**Inheritance:** IXmlValue

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| count | int | r | يحصل على عدد مفاتيح XMP. |
| namespace_uri | string | r | يسترجع مساحة الاسم URI. |
| prefix | string | r | يسترجع البادئة. |
| xml_namespace | string | r | يسترجع مساحة الاسم XML. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | يضيف القيمة إلى المفتاح المحدد. |
| [add_value(key, value)](#add_value_key_value_2) | يضيف القيمة إلى المفتاح المحدد. |
| clear() | يمسح هذا الكائن. |
| [contains_key(key)](#contains_key_key_3) | يحدد ما إذا كانت هذه المجموعة تحتوي على المفتاح المحدد. |
| [get_prop_value(key)](#get_prop_value_key_4) | يسترجع الكائن بالمفتاح المحدد. |
| [get_xml_value()](#get_xml_value__5) | يحوّل قيمة XMP إلى تمثيل XML. |
| [remove(key)](#remove_key_6) | إزالة القيمة بالمفتاح المحدد. |
| [set_prop_value(key, value)](#set_prop_value_key_value_7) | يسترجع أو يعيّن الكائن بالمفتاح المحدد. |
| [set_value(key, value)](#set_value_key_value_8) | يعيّن القيمة. |
| [set_value(key, value)](#set_value_key_value_9) | يعيّن القيمة. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | يعيّن قيمة نوع XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_11) | يسترجع القيمة حسب _key_. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

يضيف القيمة إلى المفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | string | القيمة للإضافة إلى. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

يضيف القيمة إلى المفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | System.Object | القيمة للإضافة إلى. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

يحدد ما إذا كانت هذه المجموعة تحتوي على المفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي سيتم فحصه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | **True** إذا كان   يحتوي على المفتاح المحدد؛ وإلا، **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

يسترجع الكائن بالمفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي يحدد القيمة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object | يعيد الكائن بالمفتاح المحدد. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

يحوّل قيمة XMP إلى تمثيل XML.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يعيد قيمة XMP محوّلة إلى تمثيل XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

إزالة القيمة بالمفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | التمثيل النصي للمفتاح الذي تم تحديده بالقيمة المحذوفة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | يعيد true إذا تمت إزالة القيمة ذات المفتاح المحدد. |


### Method: set_prop_value(key, value) {#set_prop_value_key_value_7}


```
 set_prop_value(key, value) 
```

يسترجع أو يعيّن الكائن بالمفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي يحدد القيمة. |
| القيمة | System.Object | الكائن بالمفتاح المحدد. |

### Method: set_value(key, value) {#set_value_key_value_8}


```
 set_value(key, value) 
```

يعيّن القيمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | القيمة للإضافة إلى. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

يعيّن القيمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | القيمة للإضافة إلى. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

يعيّن قيمة نوع XMP.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | التمثيل النصي للمفتاح الذي تم تحديده بالقيمة المعينة. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | القيمة لتعيينها إلى. |

### Method: try_get_value(key, value) {#try_get_value_key_value_11}


```
 try_get_value(key, value) 
```

يسترجع القيمة حسب _key_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | مفتاح عنصر XMP. |
| القيمة | System.Object | قيمة XMP. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | **True**, إذا كان يحتوي على _key_; وإلا **False**. |


