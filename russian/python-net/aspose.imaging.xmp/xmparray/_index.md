---
title: "XmpArray Класс"
type: docs
weight: 310
url: /ru/python-net/aspose.imaging.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpArray

**Inheritance:** IXmpType, XmpCollection

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpArray(type, items)](#XmpArray_type_items_1) | Создает новый экземпляр [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) класса. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| values | string[] | r | Получает массив значений внутри [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(item)](#add_item_1) | Добавляет новый элемент. |
| [add_item(item)](#add_item_item_2) | Добавляет новый элемент. |
| [get_xml_value()](#get_xml_value__3) | Преобразует значение XMP в XML‑представление. |
| [get_xmp_representation()](#get_xmp_representation__4) | Получает строковое значение XMP данного объекта. |


### Constructor: XmpArray(type, items) {#XmpArray_type_items_1}


```
 XmpArray(type, items) 
```

Создает новый экземпляр [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype/) | Тип массива. |
| элементы | string[] | Список элементов. |

### Method: add(item) {#add_item_1}


```
 add(item) 
```

Добавляет новый элемент.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| элемент | System.Object | Элемент, который будет добавлен в список элементов. |

### Method: add_item(item) {#add_item_item_2}


```
 add_item(item) 
```

Добавляет новый элемент.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| элемент | string | Элемент, который будет добавлен в список элементов. |

### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Преобразует значение XMP в XML‑представление.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает значение XMP, преобразованное в представление XML. |


### Method: get_xmp_representation() {#get_xmp_representation__4}


```
 get_xmp_representation() 
```

Получает строковое значение XMP данного объекта.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает строковое значение в формате XMP. |


