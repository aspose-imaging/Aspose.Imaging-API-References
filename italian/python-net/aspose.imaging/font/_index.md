---
title: "Classe Font"
type: docs
weight: 4830
url: /it/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione specificata. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), lo stile del font su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e uno stile specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione, uno stile e un'unità specificati. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione, uno stile, un'unità e un set di caratteri specificati. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e un'unità specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), lo stile è impostato su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) che utilizza il [Font](/imaging/python-net/aspose.imaging/font/) esistente specificato e l'enumerazione [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bold | bool | r | Restituisce un valore che indica se questo [Font](/imaging/python-net/aspose.imaging/font/) è in grassetto. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | Restituisce un valore byte che specifica il set di caratteri utilizzato da questo [Font](/imaging/python-net/aspose.imaging/font/). |
| italic | bool | r | Restituisce un valore che indica se questo [Font](/imaging/python-net/aspose.imaging/font/) è in corsivo. |
| name | string | r | Restituisce il nome del tipo di carattere di questo [Font](/imaging/python-net/aspose.imaging/font/). |
| size | float | r | Restituisce la dimensione em di questo [Font](/imaging/python-net/aspose.imaging/font/) misurata nelle unità specificate dalla proprietà [Font.unit](/imaging/python-net/aspose.imaging/font/). |
| strikeout | bool | r | Restituisce un valore che indica se questo [Font](/imaging/python-net/aspose.imaging/font/) specifica una linea orizzontale attraverso il carattere. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | Restituisce le informazioni di stile per questo [Font](/imaging/python-net/aspose.imaging/font/). |
| underline | bool | r | Restituisce un valore che indica se questo [Font](/imaging/python-net/aspose.imaging/font/) è sottolineato. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | Restituisce l'unità di misura per questo [Font](/imaging/python-net/aspose.imaging/font/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) che utilizza il [Font](/imaging/python-net/aspose.imaging/font/) esistente specificato e l'enumerazione [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione specificata. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), lo stile del font su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e uno stile specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e un'unità specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), lo stile è impostato su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [deep_clone()](#deep_clone__5) | Crea una copia profonda esatta di questo [Font](/imaging/python-net/aspose.imaging/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione specificata. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), lo stile del font su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em, in punti, del nuovo carattere. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e uno stile specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em, in punti, del nuovo carattere. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Il [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) del nuovo carattere. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione, uno stile e un'unità specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em del nuovo carattere nelle unità specificate dal parametro _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Il [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) del nuovo carattere. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Il [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) del nuovo carattere. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione, uno stile, un'unità e un set di caratteri specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em del nuovo carattere nelle unità specificate dal parametro _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Il [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) del nuovo carattere. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Il [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) del nuovo carattere. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Un set di caratteri da utilizzare per questo carattere. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e un'unità specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), lo stile è impostato su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em del nuovo carattere nelle unità specificate dal parametro _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Il [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) del nuovo carattere. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) che utilizza il [Font](/imaging/python-net/aspose.imaging/font/) esistente specificato e l'enumerazione [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Il [Font](/imaging/python-net/aspose.imaging/font/) esistente da cui creare il nuovo [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Il [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) da applicare al nuovo [Font](/imaging/python-net/aspose.imaging/font/). È possibile combinare più valori dell'enumerazione [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) con l'operatore OR. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) che utilizza il [Font](/imaging/python-net/aspose.imaging/font/) esistente specificato e l'enumerazione [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Il [Font](/imaging/python-net/aspose.imaging/font/) esistente da cui creare il nuovo [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Il [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) da applicare al nuovo [Font](/imaging/python-net/aspose.imaging/font/). È possibile combinare più valori dell'enumerazione [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) con l'operatore OR. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione specificata. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), lo stile del font su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em, in punti, del nuovo carattere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e uno stile specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unità grafica su [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em, in punti, del nuovo carattere. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Il [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) del nuovo carattere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Inizializza un nuovo [Font](/imaging/python-net/aspose.imaging/font/) usando una dimensione e un'unità specificati. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), lo stile è impostato su [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La dimensione em del nuovo carattere nelle unità specificate dal parametro _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Il [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) del nuovo carattere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Crea una copia profonda esatta di questo [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | Il [Font](/imaging/python-net/aspose.imaging/font/) che questo metodo crea. |


