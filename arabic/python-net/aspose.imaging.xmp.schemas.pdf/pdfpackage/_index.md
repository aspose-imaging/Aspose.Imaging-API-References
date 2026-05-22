---
title: "فئة PdfPackage"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | يُنشئ مثلاً جديداً من الفئة [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/). |
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
| [add_value(key, value)](#add_value_key_value_1) | يضيف خاصية نصية. |
| [add_value(key, value)](#add_value_key_value_2) | يضيف خاصية نصية. |
| clear() | يمسح هذا الكائن. |
| [contains_key(key)](#contains_key_key_3) | يحدد ما إذا كانت هذه المجموعة تحتوي على المفتاح المحدد. |
| [get_prop_value(key)](#get_prop_value_key_4) | يسترجع الكائن بالمفتاح المحدد. |
| [get_xml_value()](#get_xml_value__5) | يحوّل قيمة XMP إلى تمثيل XML. |
| [remove(key)](#remove_key_6) | إزالة القيمة بالمفتاح المحدد. |
| [set_keywords(keywords)](#set_keywords_keywords_7) | يضبط الكلمات المفتاحية. |
| [set_pdf_version(version)](#set_pdf_version_version_8) | يضبط نسخة PDF. |
| [set_producer(producer)](#set_producer_producer_9) | يضبط اسم الأداة التي أنشأت ملف Pdf. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | يسترجع أو يعيّن الكائن بالمفتاح المحدد. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | يضبط الحجز. |
| [set_value(key, value)](#set_value_key_value_12) | يعيّن القيمة. |
| [set_value(key, value)](#set_value_key_value_13) | يعيّن القيمة. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | يعيّن قيمة نوع XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | يسترجع القيمة حسب _key_. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

يُنشئ مثلاً جديداً من الفئة [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

يضيف خاصية نصية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | string | قيمة السلسلة. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

يضيف خاصية نصية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | System.Object | قيمة السلسلة. |

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

يضبط الكلمات المفتاحية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الكلمات المفتاحية | string | الكلمات المفتاحية. |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

يضبط نسخة PDF.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الإصدار | string | إصدار PDF، على سبيل المثال: 1.0، 1.3 إلخ. |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

يضبط اسم الأداة التي أنشأت ملف Pdf.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المنتج | string | اسم المنتج. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

يسترجع أو يعيّن الكائن بالمفتاح المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي يحدد القيمة. |
| القيمة | System.Object | الكائن بالمفتاح المحدد. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

يضبط الحجز.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| is_trapped | bool | إذا تم ضبطه على <c>true</c> فإن المستند قد تم حجزه. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

يعيّن القيمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | القيمة للإضافة إلى. |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

يعيّن القيمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | القيمة للإضافة إلى. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

يعيّن قيمة نوع XMP.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| key | string | التمثيل النصي للمفتاح الذي تم تحديده بالقيمة المعينة. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | القيمة لتعيينها إلى. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


