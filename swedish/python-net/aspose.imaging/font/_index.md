---
title: "Font-klass"
type: docs
weight: 4830
url: /sv/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), och fontstilen till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och stil. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek, stil och enhet. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek, stil, enhet och teckenuppsättning. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och enhet. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), och stilen sätts till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) som använder den angivna befintliga [Font](/imaging/python-net/aspose.imaging/font/) och [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)‑enumerationen. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bold | bool | r | Hämtar ett värde som indikerar om detta [Font](/imaging/python-net/aspose.imaging/font/) är fet. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | Hämtar ett bytevärde som specificerar teckenuppsättningen som detta [Font](/imaging/python-net/aspose.imaging/font/) använder. |
| italic | bool | r | Hämtar ett värde som indikerar om detta [Font](/imaging/python-net/aspose.imaging/font/) är kursivt. |
| name | string | r | Hämtar typsnittets namn för detta [Font](/imaging/python-net/aspose.imaging/font/). |
| size | float | r | Hämtar em-storleken för detta [Font](/imaging/python-net/aspose.imaging/font/) mätt i de enheter som anges av egenskapen [Font.unit](/imaging/python-net/aspose.imaging/font/). |
| strikeout | bool | r | Hämtar ett värde som indikerar om detta [Font](/imaging/python-net/aspose.imaging/font/) specificerar ett horisontellt streck genom typsnittet. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | Hämtar stilinformation för detta [Font](/imaging/python-net/aspose.imaging/font/). |
| underline | bool | r | Hämtar ett värde som indikerar om detta [Font](/imaging/python-net/aspose.imaging/font/) är understruket. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | Hämtar måttenheten för detta [Font](/imaging/python-net/aspose.imaging/font/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) som använder den angivna befintliga [Font](/imaging/python-net/aspose.imaging/font/) och [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)‑enumerationen. |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), och fontstilen till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och stil. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och enhet. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), och stilen sätts till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [deep_clone()](#deep_clone__5) | Skapar en exakt djup kopia av detta [Font](/imaging/python-net/aspose.imaging/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), och fontstilen till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken, i punkter, för det nya typsnittet. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och stil. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken, i punkter, för det nya typsnittet. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) för det nya typsnittet. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek, stil och enhet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken för det nya typsnittet i de enheter som anges av parametern _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) för det nya typsnittet. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) för det nya typsnittet. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek, stil, enhet och teckenuppsättning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken för det nya typsnittet i de enheter som anges av parametern _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) för det nya typsnittet. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) för det nya typsnittet. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | En teckenuppsättning att använda för detta typsnitt. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och enhet. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), och stilen sätts till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken för det nya typsnittet i de enheter som anges av parametern _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) för det nya typsnittet. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) som använder den angivna befintliga [Font](/imaging/python-net/aspose.imaging/font/) och [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)‑enumerationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Det befintliga [Font](/imaging/python-net/aspose.imaging/font/) som den nya [Font](/imaging/python-net/aspose.imaging/font/) ska skapas från. |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) att tillämpa på det nya [Font](/imaging/python-net/aspose.imaging/font/). Flera värden i [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)‑enumerationen kan kombineras med OR‑operatorn. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) som använder den angivna befintliga [Font](/imaging/python-net/aspose.imaging/font/) och [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)‑enumerationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Det befintliga [Font](/imaging/python-net/aspose.imaging/font/) som den nya [Font](/imaging/python-net/aspose.imaging/font/) ska skapas från. |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) att tillämpa på det nya [Font](/imaging/python-net/aspose.imaging/font/). Flera värden i [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)‑enumerationen kan kombineras med OR‑operatorn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), och fontstilen till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken, i punkter, för det nya typsnittet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och stil. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken, i punkter, för det nya typsnittet. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) för det nya typsnittet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Initierar en ny [Font](/imaging/python-net/aspose.imaging/font/) med en angiven storlek och enhet. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), och stilen sätts till [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Em-storleken för det nya typsnittet i de enheter som anges av parametern _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) för det nya typsnittet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Skapar en exakt djup kopia av detta [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som denna metod skapar. |


