---
title: "StringFormat 类"
type: docs
weight: 7370
url: /zh/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | 初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |
| [StringFormat(format)](#StringFormat_format_2) | 从指定的现有 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |
| [StringFormat(options)](#StringFormat_options_3) | 使用指定的 [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) 枚举和语言初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | 获取或设置垂直平面上的文本对齐信息。 |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置自定义字符标识。 |
| digit_substitution_language | int | r/w | 获取或设置在本地数字替换为西方数字时使用的语言。 |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | 获取或设置用于数字替换的方法。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| first_tab_offset | float | r | 获取文本行起始处与第一个制表位之间的空格数。 |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | 获取或设置包含格式信息的 [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) 枚举。 |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | 获取通用默认的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | 获取通用排版的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | 获取或设置此 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的 [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) 对象。 |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | 获取或设置水平平面上的行对齐方式。 |
| tab_stops | float[] | r | 获取由 [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) 属性指定单位的制表位之间距离的数组。 |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | 获取或设置此 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的 [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) 枚举。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | 使用指定的 [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) 枚举和语言初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |
| [create_from_format(format)](#create_from_format_format_2) | 从指定的现有 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |
| [deep_clone()](#deep_clone__3) | 创建此 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的深度克隆。 |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | 为此 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象设置制表位。 |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

从指定的现有 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 用于初始化新 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

使用指定的 [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) 枚举和语言初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | 新 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的 [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) 枚举。 |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

使用指定的 [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) 枚举和语言初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | 新 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的 [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) 枚举。 |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

从指定的现有 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象初始化一个新的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 用于初始化新 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象。 |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

创建此 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象的深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 当前 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 的深度克隆。 |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

为此 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) 对象设置制表位。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| first_tab_offset | float | 文本行起始处与第一个制表位之间的空格数。 |
| tab_stops | float[] | 一个数组，表示制表位之间的距离，单位由 [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) 属性指定。 |

