---
title: "Font-Klasse"
type: docs
weight: 4830
url: /de/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), der Schriftstil auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe, einem Stil und einer Einheit. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe, einem Stil, einer Einheit und einem Zeichensatz. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, der Stil wird auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) gesetzt. |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/), das die angegebene vorhandene [Font](/imaging/python-net/aspose.imaging/font/) und die Aufzählung [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) verwendet. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bold | bool | r | Gibt einen Wert zurück, der angibt, ob diese [Font](/imaging/python-net/aspose.imaging/font/) fett ist. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | Gibt einen Byte-Wert zurück, der den Zeichensatz angibt, den diese [Font](/imaging/python-net/aspose.imaging/font/) verwendet. |
| italic | bool | r | Gibt einen Wert zurück, der angibt, ob diese [Font](/imaging/python-net/aspose.imaging/font/) kursiv ist. |
| name | string | r | Gibt den Schriftartnamen dieser [Font](/imaging/python-net/aspose.imaging/font/) zurück. |
| size | float | r | Gibt die Em-Größe dieser [Font](/imaging/python-net/aspose.imaging/font/) zurück, gemessen in den Einheiten, die durch die Eigenschaft [Font.unit](/imaging/python-net/aspose.imaging/font/) angegeben sind. |
| strikeout | bool | r | Gibt einen Wert zurück, der angibt, ob diese [Font](/imaging/python-net/aspose.imaging/font/) eine horizontale Linie durch die Schriftart angibt. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | Gibt Stilinformationen für diese [Font](/imaging/python-net/aspose.imaging/font/) zurück. |
| underline | bool | r | Gibt einen Wert zurück, der angibt, ob diese [Font](/imaging/python-net/aspose.imaging/font/) unterstrichen ist. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | Gibt die Maßeinheit für diese [Font](/imaging/python-net/aspose.imaging/font/) zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/), das die angegebene vorhandene [Font](/imaging/python-net/aspose.imaging/font/) und die Aufzählung [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) verwendet. |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), der Schriftstil auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, der Stil wird auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) gesetzt. |
| [deep_clone()](#deep_clone__5) | Erstellt eine exakte tiefe Kopie dieser [Font](/imaging/python-net/aspose.imaging/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), der Schriftstil auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe, in Punkten, der neuen Schriftart. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe, in Punkten, der neuen Schriftart. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Der [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) der neuen Schriftart. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe, einem Stil und einer Einheit.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe der neuen Schriftart in den durch den Parameter _unit_ angegebenen Einheiten. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Der [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) der neuen Schriftart. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) der neuen Schriftart. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe, einem Stil, einer Einheit und einem Zeichensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe der neuen Schriftart in den durch den Parameter _unit_ angegebenen Einheiten. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Der [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) der neuen Schriftart. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) der neuen Schriftart. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Ein zu dieser Schriftart zu verwendender Zeichensatz. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, der Stil wird auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) gesetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe der neuen Schriftart in den durch den Parameter _unit_ angegebenen Einheiten. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) der neuen Schriftart. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/), das die angegebene vorhandene [Font](/imaging/python-net/aspose.imaging/font/) und die Aufzählung [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Die vorhandene [Font](/imaging/python-net/aspose.imaging/font/), aus der die neue [Font](/imaging/python-net/aspose.imaging/font/) erstellt werden soll. |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Der [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/), der auf die neue [Font](/imaging/python-net/aspose.imaging/font/) angewendet werden soll. Mehrere Werte der Aufzählung [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) können mit dem ODER-Operator kombiniert werden. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/), das die angegebene vorhandene [Font](/imaging/python-net/aspose.imaging/font/) und die Aufzählung [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Die vorhandene [Font](/imaging/python-net/aspose.imaging/font/), aus der die neue [Font](/imaging/python-net/aspose.imaging/font/) erstellt werden soll. |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Der [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/), der auf die neue [Font](/imaging/python-net/aspose.imaging/font/) angewendet werden soll. Mehrere Werte der Aufzählung [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) können mit dem ODER-Operator kombiniert werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), der Schriftstil auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe, in Punkten, der neuen Schriftart. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe, in Punkten, der neuen Schriftart. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Der [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) der neuen Schriftart. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Initialisiert ein neues [Font](/imaging/python-net/aspose.imaging/font/) mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/) gesetzt, der Stil wird auf [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/) gesetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des Namens der [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Die Em-Größe der neuen Schriftart in den durch den Parameter _unit_ angegebenen Einheiten. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) der neuen Schriftart. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Erstellt eine exakte tiefe Kopie dieser [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | Die [Font](/imaging/python-net/aspose.imaging/font/), die diese Methode erstellt. |


