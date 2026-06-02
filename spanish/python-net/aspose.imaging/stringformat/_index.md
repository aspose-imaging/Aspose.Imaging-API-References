---
title: "Clase StringFormat"
type: docs
weight: 7370
url: /es/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partir del objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existente especificado. |
| [StringFormat(options)](#StringFormat_options_3) | Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con la enumeración [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) y el idioma especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Obtiene o establece la información de alineación del texto en el plano vertical. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece la identificación del carácter personalizado. |
| digit_substitution_language | int | r/w | Obtiene o establece el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Obtiene o establece el método que se usará para la sustitución de dígitos. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| first_tab_offset | float | r | Obtiene el número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Obtiene o establece una enumeración [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) que contiene información de formato. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Obtiene un objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) genérico predeterminado. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Obtiene un objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) tipográfico genérico. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Obtiene o establece el objeto [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) para este objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Obtiene o establece la alineación de la línea en el plano horizontal. |
| tab_stops | float[] | r | Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Obtiene o establece la enumeración [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) para este objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con la enumeración [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) y el idioma especificados. |
| [create_from_format(format)](#create_from_format_format_2) | Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partir del objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existente especificado. |
| [deep_clone()](#deep_clone__3) | Crea una clonación profunda de este objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Establece tabulaciones para este objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partir del objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existente especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | El objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) del cual inicializar el nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con la enumeración [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) y el idioma especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | La enumeración [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) para el nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con la enumeración [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) y el idioma especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | La enumeración [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) para el nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Inicializa un nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partir del objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existente especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | El objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) del cual inicializar el nuevo objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Crea una clonación profunda de este objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | La clonación profunda del actual [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Establece tabulaciones para este objeto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| first_tab_offset | float | El número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| tab_stops | float[] | Una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |

