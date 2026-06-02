---
title: "Clase Font"
type: docs
weight: 4830
url: /es/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño especificado. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), y el estilo de fuente en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y estilo especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño, estilo y unidad especificados. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño, estilo, unidad y conjunto de caracteres especificados. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y unidad especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), y el estilo se establece en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) que utiliza el [Font](/imaging/python-net/aspose.imaging/font/) existente especificado y la enumeración [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bold | bool | r | Obtiene un valor que indica si este [Font](/imaging/python-net/aspose.imaging/font/) está en negrita. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | Obtiene un valor de byte que especifica el conjunto de caracteres que usa este [Font](/imaging/python-net/aspose.imaging/font/). |
| italic | bool | r | Obtiene un valor que indica si este [Font](/imaging/python-net/aspose.imaging/font/) está en cursiva. |
| name | string | r | Obtiene el nombre de la familia tipográfica de este [Font](/imaging/python-net/aspose.imaging/font/). |
| size | float | r | Obtiene el tamaño em de este [Font](/imaging/python-net/aspose.imaging/font/) medido en las unidades especificadas por la propiedad [Font.unit](/imaging/python-net/aspose.imaging/font/). |
| strikeout | bool | r | Obtiene un valor que indica si este [Font](/imaging/python-net/aspose.imaging/font/) especifica una línea horizontal a través de la fuente. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | Obtiene información de estilo para este [Font](/imaging/python-net/aspose.imaging/font/). |
| underline | bool | r | Obtiene un valor que indica si este [Font](/imaging/python-net/aspose.imaging/font/) está subrayado. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | Obtiene la unidad de medida de este [Font](/imaging/python-net/aspose.imaging/font/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) que utiliza el [Font](/imaging/python-net/aspose.imaging/font/) existente especificado y la enumeración [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño especificado. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), y el estilo de fuente en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y estilo especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y unidad especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), y el estilo se establece en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [deep_clone()](#deep_clone__5) | Crea una copia profunda exacta de este [Font](/imaging/python-net/aspose.imaging/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño especificado. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), y el estilo de fuente en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em, en puntos, de la nueva fuente. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y estilo especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em, en puntos, de la nueva fuente. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | El [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nueva fuente. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño, estilo y unidad especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | El [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nueva fuente. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | El [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nueva fuente. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño, estilo, unidad y conjunto de caracteres especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | El [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nueva fuente. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | El [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nueva fuente. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Un conjunto de caracteres para usar con esta fuente. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y unidad especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), y el estilo se establece en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | El [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nueva fuente. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) que utiliza el [Font](/imaging/python-net/aspose.imaging/font/) existente especificado y la enumeración [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | El [Font](/imaging/python-net/aspose.imaging/font/) existente del cual crear el nuevo [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | El [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) a aplicar al nuevo [Font](/imaging/python-net/aspose.imaging/font/). Se pueden combinar múltiples valores de la enumeración [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) con el operador OR. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) que utiliza el [Font](/imaging/python-net/aspose.imaging/font/) existente especificado y la enumeración [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | El [Font](/imaging/python-net/aspose.imaging/font/) existente del cual crear el nuevo [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | El [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) a aplicar al nuevo [Font](/imaging/python-net/aspose.imaging/font/). Se pueden combinar múltiples valores de la enumeración [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) con el operador OR. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño especificado. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), y el estilo de fuente en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em, en puntos, de la nueva fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y estilo especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em, en puntos, de la nueva fuente. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | El [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nueva fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Inicializa un nuevo [Font](/imaging/python-net/aspose.imaging/font/) usando un tamaño y unidad especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), y el estilo se establece en [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | El [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nueva fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Crea una copia profunda exacta de este [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | El [Font](/imaging/python-net/aspose.imaging/font/) que crea este método. |


