---
title: "StringFormat Klasse"
type: docs
weight: 7370
url: /de/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt. |
| [StringFormat(format)](#StringFormat_format_2) | Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt aus dem angegebenen vorhandenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt. |
| [StringFormat(options)](#StringFormat_options_3) | Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt mit der angegebenen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) Aufzählung und Sprache. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Liest oder legt Textausrichtungsinformationen in der vertikalen Ebene fest. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder legt die benutzerdefinierte Zeichenkennung fest. |
| digit_substitution_language | int | r/w | Liest oder legt die Sprache fest, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Liest oder legt die Methode fest, die für die Ziffernersetzung verwendet wird. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| first_tab_offset | float | r | Liest die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Liest oder legt eine [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) Aufzählung fest, die Formatierungsinformationen enthält. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Liest ein generisches Standard-[StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Liest ein generisches typografisches [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Liest oder legt das [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) Objekt für dieses [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt fest. |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Liest oder legt die Zeilenausrichtung in der horizontalen Ebene fest. |
| tab_stops | float[] | r | Liest ein Array von Abständen zwischen Tabstopps in den durch die [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) Eigenschaft angegebenen Einheiten. |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Liest oder legt die [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) Aufzählung für dieses [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt mit der angegebenen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) Aufzählung und Sprache. |
| [create_from_format(format)](#create_from_format_format_2) | Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt aus dem angegebenen vorhandenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt. |
| [deep_clone()](#deep_clone__3) | Erstellt einen tiefen Klon dieses [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekts. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Legt Tabstopps für dieses [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt fest. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt aus dem angegebenen vorhandenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Das [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt, aus dem das neue [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt initialisiert wird. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt mit der angegebenen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) Aufzählung und Sprache.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Die [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) Aufzählung für das neue [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt. |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt mit der angegebenen [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) Aufzählung und Sprache.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Die [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) Aufzählung für das neue [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Initialisiert ein neues [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt aus dem angegebenen vorhandenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Das [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt, aus dem das neue [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt initialisiert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Erstellt einen tiefen Klon dieses [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekts.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Der tiefe Klon des aktuellen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Legt Tabstopps für dieses [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) Objekt fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| first_tab_offset | float | Die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp. |
| tab_stops | float[] | Ein Array von Abständen zwischen Tabstopps in den durch die [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) Eigenschaft angegebenen Einheiten. |

