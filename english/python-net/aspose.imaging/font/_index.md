---
title: Font Class
type: docs
weight: 200
url: /python-net/aspose.imaging/font/
---

Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.Font

**Assembly:**  Aspose.Imaging Version: 23.5.6

The Font type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Font(prototype, new_style)|Initializes a new instance of the Font class|
|Font(font_name, em_size)|Initializes a new instance of the Font class|
|Font(font_name, em_size, style)|Initializes a new instance of the Font class|
|Font(font_name, em_size, unit)|Initializes a new instance of the Font class|
|Font(font_name, em_size, style, unit, character_set)|Initializes a new instance of the Font class|
|Font(font_name, em_size, style, unit)|Initializes a new instance of the Font class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|bold|Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) is bold.|
|character_set|Gets a byte value that specifies the character set that this [Font](/imaging/python-net/aspose.imaging/font/) uses.|
|italic|Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) is italic.|
|name|Gets the face name of this [Font](/imaging/python-net/aspose.imaging/font/).|
|strikeout|Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) specifies a horizontal line through the font.|
|underline|Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) is underlined.|
|style|Gets style information for this [Font](/imaging/python-net/aspose.imaging/font/).|
|size|Gets the em-size of this [Font](/imaging/python-net/aspose.imaging/font/) measured in the units specified by the [unit](/imaging/python-net/aspose.imaging/font/) property.|
|unit|Gets the unit of measure for this [Font](/imaging/python-net/aspose.imaging/font/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_prototype(prototype, new_style)|Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) that uses the specified existing [Font](/imaging/python-net/aspose.imaging/font/) and [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumeration.|
|create_with_size(font_name, em_size)|Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the graphics unit to [POINT](/imaging/python-net/aspose.imaging/graphicsunit/), the font style to [REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).|
|create_with_size_style(font_name, em_size, style)|Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size and style. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the graphics unit to [POINT](/imaging/python-net/aspose.imaging/graphicsunit/).|
|create_with_size_unit(font_name, em_size, unit)|Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size and unit. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the style is set to [REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).|
|deep_clone()|Creates an exact deep copy of this [Font](/imaging/python-net/aspose.imaging/font/).|
