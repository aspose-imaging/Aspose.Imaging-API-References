---
title: "Класс StringFormat"
type: docs
weight: 7370
url: /ru/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) из указанного существующего объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [StringFormat(options)](#StringFormat_options_3) | Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) с указанным перечислением [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) и языком. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Получает или задает информацию о выравнивании текста по вертикали. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает пользовательский идентификатор символа. |
| digit_substitution_language | int | r/w | Получает или задает язык, используемый при замене локальных цифр на западные цифры. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Получает или задает метод, используемый для замены цифр. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| first_tab_offset | float | r | Получает количество пробелов между началом строки текста и первой табуляцией. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Получает или задает перечисление [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/), содержащее информацию о форматировании. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Получает общий объект по умолчанию [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Получает общий типографический объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Получает или задает объект [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) для этого объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Получает или задает выравнивание строк по горизонтали. |
| tab_stops | float[] | r | Получает массив расстояний между табуляциями в единицах, указанных свойством [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Получает или задает перечисление [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) для этого объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) с указанным перечислением [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) и языком. |
| [create_from_format(format)](#create_from_format_format_2) | Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) из указанного существующего объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [deep_clone()](#deep_clone__3) | Создает глубокую копию этого объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Устанавливает табуляцию для этого объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) из указанного существующего объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/), из которого инициализируется новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) с указанным перечислением [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) и языком.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Перечисление [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) для нового объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) с указанным перечислением [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) и языком.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Перечисление [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) для нового объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Инициализирует новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) из указанного существующего объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/), из которого инициализируется новый объект [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Создает глубокую копию этого объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Returns**

| Тип | Описание |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Глубокая копия текущего объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Устанавливает табуляцию для этого объекта [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| first_tab_offset | float | Количество пробелов между началом строки текста и первой табуляцией. |
| tab_stops | float[] | Массив расстояний между табуляциями в единицах, указанных свойством [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |

