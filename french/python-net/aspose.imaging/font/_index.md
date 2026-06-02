---
title: "Classe Font"
type: docs
weight: 4830
url: /fr/python-net/aspose.imaging/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille spécifiée. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), le style de police sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille, un style et une unité spécifiés. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), le style est défini sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) qui utilise le [Font](/imaging/python-net/aspose.imaging/font/) existant spécifié et l'énumération [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bold | bool | r | Obtient une valeur indiquant si ce [Font](/imaging/python-net/aspose.imaging/font/) est en gras. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | r | Obtient une valeur octet qui spécifie le jeu de caractères utilisé par ce [Font](/imaging/python-net/aspose.imaging/font/). |
| italic | bool | r | Obtient une valeur indiquant si ce [Font](/imaging/python-net/aspose.imaging/font/) est en italique. |
| name | string | r | Obtient le nom de la police de ce [Font](/imaging/python-net/aspose.imaging/font/). |
| size | float | r | Obtient la taille en em de ce [Font](/imaging/python-net/aspose.imaging/font/) mesurée dans les unités spécifiées par la propriété [Font.unit](/imaging/python-net/aspose.imaging/font/). |
| strikeout | bool | r | Obtient une valeur indiquant si ce [Font](/imaging/python-net/aspose.imaging/font/) spécifie une ligne horizontale traversant la police. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | r | Obtient les informations de style pour ce [Font](/imaging/python-net/aspose.imaging/font/). |
| underline | bool | r | Obtient une valeur indiquant si ce [Font](/imaging/python-net/aspose.imaging/font/) est souligné. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r | Obtient l'unité de mesure de ce [Font](/imaging/python-net/aspose.imaging/font/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_1) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) qui utilise le [Font](/imaging/python-net/aspose.imaging/font/) existant spécifié et l'énumération [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_2) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille spécifiée. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), le style de police sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_3) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_4) | Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), le style est défini sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [deep_clone()](#deep_clone__5) | Crée une copie profonde exacte de ce [Font](/imaging/python-net/aspose.imaging/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille spécifiée. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), le style de police sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em, en points, de la nouvelle police. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em, en points, de la nouvelle police. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Le [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nouvelle police. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille, un style et une unité spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Le [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nouvelle police. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nouvelle police. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre _unit_. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Le [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nouvelle police. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nouvelle police. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Un jeu de caractères à utiliser pour cette police. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), le style est défini sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nouvelle police. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) qui utilise le [Font](/imaging/python-net/aspose.imaging/font/) existant spécifié et l'énumération [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Le [Font](/imaging/python-net/aspose.imaging/font/) existant à partir duquel créer le nouveau [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Le [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) à appliquer à la nouvelle [Font](/imaging/python-net/aspose.imaging/font/). Plusieurs valeurs de l'énumération [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) peuvent être combinées avec l'opérateur OR. |

### Method: create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_1}


```
 create_from_prototype(prototype, new_style) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) qui utilise le [Font](/imaging/python-net/aspose.imaging/font/) existant spécifié et l'énumération [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging/font/) | Le [Font](/imaging/python-net/aspose.imaging/font/) existant à partir duquel créer le nouveau [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Le [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) à appliquer à la nouvelle [Font](/imaging/python-net/aspose.imaging/font/). Plusieurs valeurs de l'énumération [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) peuvent être combinées avec l'opérateur OR. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_2}


```
 create_with_size(font_name, em_size) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille spécifiée. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/), le style de police sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em, en points, de la nouvelle police. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_3}


```
 create_with_size_style(font_name, em_size, style) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em, en points, de la nouvelle police. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Le [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) de la nouvelle police. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_4}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Initialise un nouveau [Font](/imaging/python-net/aspose.imaging/font/) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/imaging/python-net/aspose.imaging/characterset/), le style est défini sur [FontStyle.REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/imaging/python-net/aspose.imaging/font/). |
| em_size | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre _unit_. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) de la nouvelle police. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) |  |


### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Crée une copie profonde exacte de ce [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging/font/) | Le [Font](/imaging/python-net/aspose.imaging/font/) que cette méthode crée. |


