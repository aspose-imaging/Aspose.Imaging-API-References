---
title: "StringFormat-klass"
type: docs
weight: 7370
url: /sv/python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt. |
| [StringFormat(format)](#StringFormat_format_2) | Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt från det angivna befintliga [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet. |
| [StringFormat(options)](#StringFormat_options_3) | Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt med den angivna [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) uppräkningen och språket. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Hämtar eller anger textjusteringsinformation på den vertikala planet. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger den anpassade teckenidentiteten. |
| digit_substitution_language | int | r/w | Hämtar eller anger språket som används när lokala siffror ersätts med västerländska siffror. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Hämtar eller anger metoden som ska användas för sifferersättning. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| first_tab_offset | float | r | Hämtar antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Hämtar eller anger en [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) uppräkning som innehåller formateringsinformation. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Hämtar ett generiskt standard [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Hämtar ett generiskt typografiskt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Hämtar eller anger [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) objektet för detta [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt. |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Hämtar eller anger radjusteringen på det horisontella planet. |
| tab_stops | float[] | r | Hämtar en array av avstånd mellan tabbstopp i de enheter som anges av egenskapen [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Hämtar eller anger [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) uppräkningen för detta [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt med den angivna [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) uppräkningen och språket. |
| [create_from_format(format)](#create_from_format_format_2) | Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt från det angivna befintliga [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet. |
| [deep_clone()](#deep_clone__3) | Skapar en djup klon av detta [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Anger tabbstopp för detta [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt från det angivna befintliga [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Det [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet som används för att initiera det nya [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt med den angivna [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) uppräkningen och språket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Den [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) uppräkningen för det nya [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet. |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt med den angivna [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) uppräkningen och språket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Den [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) uppräkningen för det nya [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Initierar ett nytt [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt från det angivna befintliga [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Det [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet som används för att initiera det nya [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objektet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Skapar en djup klon av detta [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Den djupa klonen av det aktuella [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Anger tabbstopp för detta [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| first_tab_offset | float | Antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| tab_stops | float[] | En matris med avstånd mellan tabbstopp i de enheter som anges av egenskapen [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/). |

