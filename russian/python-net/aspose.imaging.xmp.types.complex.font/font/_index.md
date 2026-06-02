---
title: "Класс Font"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.xmp.types.complex.font/font/
---

**Summary:** Represents XMP Font.

**Module:** [aspose.imaging.xmp.types.complex.font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/)

**Full Name:** aspose.imaging.xmp.types.complex.font.Font

**Inheritance:** IXmpType, ComplexTypeBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font()](#Font__1) | Инициализирует новый экземпляр класса [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/). |
| [Font(font_family)](#Font_font_family_2) | Инициализирует новый экземпляр класса [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| child_font_files | string[] | r/w | Получает или задает массив имен файлов шрифтов, составляющих составной шрифт. |
| font_face | string | r/w | Получает или задает гарнитуру шрифта. |
| font_family | string | r/w | Получает или задает семейство шрифтов. |
| font_file_name | string | r/w | Получает или задает имя файла шрифта без полного пути. |
| имя_шрифта | string | r/w | Получает или задает имя шрифта PostScript. |
| font_type | string | r/w | Получает или задает тип шрифта. |
| is_composite | bool | r/w | Получает или задает значение, указывающее, является ли этот шрифт составным. |
| namespace_uri | string | r | Получает URI пространства имён по умолчанию. |
| prefix | string | r | Получает префикс. |
| version | string | r/w | Получает или задает версию шрифта. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |
| [get_xmp_representation()](#get_xmp_representation__2) | Получает строковое значение в формате XMP. |


### Constructor: Font() {#Font__1}


```
 Font() 
```

Инициализирует новый экземпляр класса [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/).

### Constructor: Font(font_family) {#Font_font_family_2}


```
 Font(font_family) 
```

Инициализирует новый экземпляр класса [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_family | string | Семейство шрифтов. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object | Клонирование по членам. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Получает строковое значение в формате XMP.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает строковое значение в формате XMP. |


