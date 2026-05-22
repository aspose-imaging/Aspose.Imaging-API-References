---
title: "فئة StringFormat"
type: docs
weight: 7370
url: /ar/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) استنادًا إلى كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الموجود المحدد. |
| [StringFormat(options)](#StringFormat_options_3) | ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) باستخدام تعداد [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) المحدد واللغة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | يحصل أو يضبط معلومات محاذاة النص على المستوى الرأسي. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يضبط معرف الحرف المخصص. |
| digit_substitution_language | int | r/w | يحصل أو يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | يحصل أو يضبط الطريقة المستخدمة لاستبدال الأرقام. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| first_tab_offset | float | r | يحصل على عدد المسافات بين بداية سطر النص وأول موضع تبويب. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | يحصل أو يضبط تعداد [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) الذي يحتوي على معلومات التنسيق. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | يحصل على كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) افتراضي عام. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | يحصل على كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) طباعي عام. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | يحصل أو يضبط كائن [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) لهذا كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | يحصل أو يضبط محاذاة السطر على المستوى الأفقي. |
| tab_stops | float[] | r | يحصل على مصفوفة من المسافات بين مواضع التبويب بالوحدات المحددة بواسطة خاصية [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | يحصل أو يضبط تعداد [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) لهذا كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) باستخدام تعداد [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) المحدد واللغة. |
| [create_from_format(format)](#create_from_format_format_2) | ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) استنادًا إلى كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الموجود المحدد. |
| [deep_clone()](#deep_clone__3) | ينشئ نسخة عميقة من هذا كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | يضبط مواضع التبويب لهذا كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) استنادًا إلى كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الموجود المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الذي يُستخدم لتهيئة كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الجديد. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) باستخدام تعداد [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) المحدد واللغة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | تعداد [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) لكائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الجديد. |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) باستخدام تعداد [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) المحدد واللغة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | تعداد [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) لكائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

ينشئ كائنًا جديدًا من [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) استنادًا إلى كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الموجود المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الذي يُستخدم لتهيئة كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

ينشئ نسخة عميقة من هذا كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Returns**

| نوع | الوصف |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | النسخة العميقة من كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الحالي. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

يضبط مواضع التبويب لهذا كائن [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| first_tab_offset | float | عدد المسافات بين بداية سطر النص وأول موضع تبويب. |
| tab_stops | float[] | مصفوفة من المسافات بين نقاط التبويب بالوحدات المحددة بواسطة خاصية [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |

