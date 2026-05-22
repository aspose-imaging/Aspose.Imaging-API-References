---
title: "字体类"
type: docs
weight: 4830
url: /zh/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | 使用指定的大小初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)，字体样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。 |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | 使用指定的大小和样式初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)。 |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | 使用指定的大小、样式和单位初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | 使用指定的大小、样式、单位和字符集初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | 使用指定的大小和单位初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。 |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | 初始化一个使用指定现有 [Font](/imaging/python-net/aspose.imaging/font/) 和 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) 枚举的新 [Font](/imaging/python-net/aspose.imaging/font/)。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bold | bool | r | 获取一个值，指示此 [Font](/imaging/python-net/aspose.imaging/font/) 是否为粗体。 |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | 获取一个字节值，指定此 [Font](/imaging/python-net/aspose.imaging/font/) 使用的字符集。 |
| italic | bool | r | 获取一个值，指示此 [Font](/imaging/python-net/aspose.imaging/font/) 是否为斜体。 |
| name | string | r | 获取此 [Font](/imaging/python-net/aspose.imaging/font/) 的字体名称。 |
| size | float | r | 获取此 [Font](/imaging/python-net/aspose.imaging/font/) 的 em 大小，使用由 [Font.unit](/imaging/python-net/aspose.imaging/font/) 属性指定的单位进行测量。 |
| strikeout | bool | r | 获取一个值，指示此 [Font](/imaging/python-net/aspose.imaging/font/) 是否指定在字体上加水平线。 |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | 获取此 [Font](/imaging/python-net/aspose.imaging/font/) 的样式信息。 |
| underline | bool | r | 获取一个值，指示此 [Font](/imaging/python-net/aspose.imaging/font/) 是否带下划线。 |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | 获取此 [Font](/imaging/python-net/aspose.imaging/font/) 的度量单位。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | 初始化一个使用指定现有 [Font](/imaging/python-net/aspose.imaging/font/) 和 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) 枚举的新 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | 使用指定的大小初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)，字体样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。 |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | 使用指定的大小和样式初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)。 |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | 使用指定的大小和单位初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。 |
| [deep_clone()](#deep_clone__5) | 创建此 [Font](/imaging/python-net/aspose.imaging/font/) 的精确深拷贝。 |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

使用指定的大小初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)，字体样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小（以点为单位）。 |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

使用指定的大小和样式初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小（以点为单位）。 |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | 新字体的 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)。 |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

使用指定的大小、样式和单位初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小，使用 _unit_ 参数指定的单位。 |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | 新字体的 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)。 |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 新字体的 [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/)。 |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

使用指定的大小、样式、单位和字符集初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小，使用 _unit_ 参数指定的单位。 |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | 新字体的 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)。 |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 新字体的 [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/)。 |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | 此字体使用的字符集。 |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

使用指定的大小和单位初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小，使用 _unit_ 参数指定的单位。 |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 新字体的 [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/)。 |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

初始化一个使用指定现有 [Font](/imaging/python-net/aspose.imaging/font/) 和 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) 枚举的新 [Font](/imaging/python-net/aspose.imaging/font/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | 用于创建新 [Font](/imaging/python-net/aspose.imaging/font/) 的现有 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | 要应用于新 [Font](/imaging/python-net/aspose.imaging/font/) 的 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)。可以使用 OR 运算符组合 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) 枚举的多个值。 |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

初始化一个使用指定现有 [Font](/imaging/python-net/aspose.imaging/font/) 和 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) 枚举的新 [Font](/imaging/python-net/aspose.imaging/font/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | 用于创建新 [Font](/imaging/python-net/aspose.imaging/font/) 的现有 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | 要应用于新 [Font](/imaging/python-net/aspose.imaging/font/) 的 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)。可以使用 OR 运算符组合 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) 枚举的多个值。 |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

使用指定的大小初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)，字体样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小（以点为单位）。 |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

使用指定的大小和样式初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小（以点为单位）。 |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | 新字体的 [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

使用指定的大小和单位初始化一个新的 [Font](/imaging/python-net/aspose.imaging/font/)。字符集设置为 [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/)，样式设置为 [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_name | string | [Font](/imaging/python-net/aspose.imaging/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em 大小，使用 _unit_ 参数指定的单位。 |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 新字体的 [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

创建此 [Font](/imaging/python-net/aspose.imaging/font/) 的精确深拷贝。

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | 此方法创建的 [Font](/imaging/python-net/aspose.imaging/font/)。 |


