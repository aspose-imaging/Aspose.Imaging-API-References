---
title: "IImageMask Класс"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы, в пикселях, этой маски. |
| height | int | r | Получает высоту, в пикселях, этой маски. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы выбранной части маски в пикселях. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Получает исходное изображение, использованное для создания этой маски, если оно существует. |
| width | int | r | Получает ширину, в пикселях, этой маски. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт новый объект, являющийся копией текущего экземпляра. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Получает непрозрачность указанного пикселя с точностью до байта. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Проверяет, является ли указанный пиксель непрозрачным. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Проверяет, является ли указанный пиксель прозрачным. |


### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт новый объект, являющийся копией текущего экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


```
 get_byte_opacity(x, y) 
```

Получает непрозрачность указанного пикселя с точностью до байта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Значение байта, представляющее непрозрачность указанного пикселя. |


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


```
 is_opaque(x, y) 
```

Проверяет, является ли указанный пиксель непрозрачным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, если указанный пиксель непрозрачный; в противном случае — false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


```
 is_transparent(x, y) 
```

Проверяет, является ли указанный пиксель прозрачным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, если указанный пиксель прозрачный; в противном случае — false. |


