---
title: "Класс ColorantCmyk"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Инициализирует новый экземпляр класса [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class. |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Инициализирует новый экземпляр класса [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Максимальное значение цвета в CMYK колоренте. |
| COLOR_VALUE_MIN [static] | float | r | Минимальное значение цвета в CMYK колоренте. |
| black | float | r/w | Получает или задает значение черного компонента. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Получает или задает тип цвета. |
| cyan | float | r/w | Получает или задает значение компонента циана. |
| magenta | float | r/w | Получает или задает значение компонента магенты. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Получает [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Получает URI пространства имён по умолчанию. |
| prefix | string | r | Получает префикс. |
| swatch_name | string | r/w | Получает или задает имя образца. |
| yellow | float | r/w | Получает или задает значение компонента желтого. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |
| [get_xmp_representation()](#get_xmp_representation__2) | Получает строковое значение в формате XMP. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Инициализирует новый экземпляр класса [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class.

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Инициализирует новый экземпляр класса [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| black | float | Значение компонента черный. |
| cyan | float | Значение компонента цвета циана. |
| magenta | float | Значение компонента мажента. |
| yellow | float | Значение желтого компонента. |

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


