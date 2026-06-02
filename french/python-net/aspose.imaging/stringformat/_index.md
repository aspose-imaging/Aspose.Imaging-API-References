---
title: "Classe StringFormat"
type: docs
weight: 7370
url: /fr/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) à partir de l'objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existant spécifié. |
| [StringFormat(options)](#StringFormat_options_3) | Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) avec l'énumération [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) et la langue spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Obtient ou définit les informations d'alignement du texte sur le plan vertical. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit l'identifiant de caractère personnalisé. |
| digit_substitution_language | int | r/w | Obtient ou définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Obtient ou définit la méthode à utiliser pour la substitution des chiffres. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| first_tab_offset | float | r | Obtient le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Obtient ou définit une énumération [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) contenant des informations de formatage. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Obtient un objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) générique par défaut. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Obtient un objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) typographique générique. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Obtient ou définit l'objet [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) pour cet objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Obtient ou définit l'alignement de ligne sur le plan horizontal. |
| tab_stops | float[] | r | Obtient un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Obtient ou définit l'énumération [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) pour cet objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) avec l'énumération [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) et la langue spécifiées. |
| [create_from_format(format)](#create_from_format_format_2) | Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) à partir de l'objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existant spécifié. |
| [deep_clone()](#deep_clone__3) | Crée une copie profonde de cet objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Définit les arrêts de tabulation pour cet objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) à partir de l'objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | L'objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) à partir duquel initialiser le nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) avec l'énumération [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) et la langue spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | L'énumération [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) pour le nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) avec l'énumération [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) et la langue spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | L'énumération [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) pour le nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Initialise un nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) à partir de l'objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) existant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | L'objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) à partir duquel initialiser le nouvel objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Crée une copie profonde de cet objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | La copie profonde de l'objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) actuel. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Définit les arrêts de tabulation pour cet objet [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| first_tab_offset | float | Le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| tab_stops | float[] | Un tableau de distances entre les tabulations dans les unités spécifiées par la propriété [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |

