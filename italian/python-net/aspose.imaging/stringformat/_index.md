---
title: "Classe StringFormat"
type: docs
weight: 7370
url: /it/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partire dall'oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) esistente specificato. |
| [StringFormat(options)](#StringFormat_options_3) | Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con l'enumerazione [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) e la lingua specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Ottiene o imposta le informazioni di allineamento del testo sul piano verticale. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta l'identificatore del carattere personalizzato. |
| digit_substitution_language | int | r/w | Ottiene o imposta la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Ottiene o imposta il metodo da utilizzare per la sostituzione delle cifre. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| first_tab_offset | float | r | Ottiene il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Ottiene o imposta un'enumerazione [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) che contiene le informazioni di formattazione. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Ottiene un oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) predefinito generico. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Ottiene un oggetto tipografico generico [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Ottiene o imposta l'oggetto [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) per questo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Ottiene o imposta l'allineamento della linea sul piano orizzontale. |
| tab_stops | float[] | r | Ottiene un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Ottiene o imposta l'enumerazione [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) per questo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con l'enumerazione [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) e la lingua specificate. |
| [create_from_format(format)](#create_from_format_format_2) | Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partire dall'oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) esistente specificato. |
| [deep_clone()](#deep_clone__3) | Crea una copia profonda di questo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Imposta le tabulazioni per questo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partire dall'oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) esistente specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | L'oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) da cui inizializzare il nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con l'enumerazione [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) e la lingua specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | L'enumerazione [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) per il nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) con l'enumerazione [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) e la lingua specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | L'enumerazione [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) per il nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Inizializza un nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) a partire dall'oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) esistente specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | L'oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) da cui inizializzare il nuovo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Crea una copia profonda di questo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | La copia profonda dell'attuale [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Imposta le tabulazioni per questo oggetto [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| first_tab_offset | float | Il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| tab_stops | float[] | Un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |

