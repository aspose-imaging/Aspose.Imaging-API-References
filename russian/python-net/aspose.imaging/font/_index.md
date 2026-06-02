---
title: "Класс Font"
type: docs
weight: 4830
url: /ru/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), стиль шрифта — [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и стилем. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером, стилем и единицей. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером, стилем, единицей и набором символов. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и единицей. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), стиль устанавливается в [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) который использует указанный существующий [Font](/imaging/python-net/aspose.imaging/font/) и перечисление [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bold | bool | r | Получает значение, указывающее, является ли этот [Font](/imaging/python-net/aspose.imaging/font/) жирным. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | Получает байтовое значение, определяющее набор символов, используемый этим [Font](/imaging/python-net/aspose.imaging/font/). |
| italic | bool | r | Получает значение, указывающее, является ли этот [Font](/imaging/python-net/aspose.imaging/font/) курсивным. |
| name | string | r | Получает имя гарнитуры этого [Font](/imaging/python-net/aspose.imaging/font/). |
| size | float | r | Получает размер em этого [Font](/imaging/python-net/aspose.imaging/font/), измеренный в единицах, указанных свойством [Font.unit](/imaging/python-net/aspose.imaging/font/). |
| strikeout | bool | r | Получает значение, указывающее, задаёт ли этот [Font](/imaging/python-net/aspose.imaging/font/) горизонтальную линию через шрифт. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | Получает информацию о стиле для этого [Font](/imaging/python-net/aspose.imaging/font/). |
| underline | bool | r | Получает значение, указывающее, подчёркнут ли этот [Font](/imaging/python-net/aspose.imaging/font/). |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | Получает единицу измерения для этого [Font](/imaging/python-net/aspose.imaging/font/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) который использует указанный существующий [Font](/imaging/python-net/aspose.imaging/font/) и перечисление [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), стиль шрифта — [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и стилем. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и единицей. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), стиль устанавливается в [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [deep_clone()](#deep_clone__5) | Создаёт точную глубокую копию этого [Font](/imaging/python-net/aspose.imaging/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), стиль шрифта — [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в пунктах. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и стилем. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в пунктах. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) нового шрифта. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером, стилем и единицей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) нового шрифта. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) нового шрифта. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером, стилем, единицей и набором символов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) нового шрифта. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) нового шрифта. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Набор символов, используемый для этого шрифта. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и единицей. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), стиль устанавливается в [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) нового шрифта. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) который использует указанный существующий [Font](/imaging/python-net/aspose.imaging/font/) и перечисление [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Существующий [Font](/imaging/python-net/aspose.imaging/font/), из которого создаётся новый [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/), применяемый к новому [Font](/imaging/python-net/aspose.imaging/font/). Несколько значений перечисления [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) могут быть объединены оператором OR. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) который использует указанный существующий [Font](/imaging/python-net/aspose.imaging/font/) и перечисление [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Существующий [Font](/imaging/python-net/aspose.imaging/font/), из которого создаётся новый [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/), применяемый к новому [Font](/imaging/python-net/aspose.imaging/font/). Несколько значений перечисления [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) могут быть объединены оператором OR. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), стиль шрифта — [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в пунктах. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и стилем. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), графическая единица — [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в пунктах. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) нового шрифта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Инициализирует новый [Font](/imaging/python-net/aspose.imaging/font/) с указанным размером и единицей. Набор символов устанавливается в [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), стиль устанавливается в [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) нового шрифта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Создаёт точную глубокую копию этого [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/), создаваемый этим методом. |


