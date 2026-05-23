---
title: "XmpArray Clase"
type: docs
weight: 310
url: /es/python-net/aspose.imaging.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpArray

**Inheritance:** IXmpType, XmpCollection

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpArray(type, items)](#XmpArray_type_items_1) | Inicializa una nueva instancia de la clase [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| values | string[] | r | Obtiene el arreglo de valores dentro de [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(item)](#add_item_1) | Agrega un nuevo elemento. |
| [add_item(item)](#add_item_item_2) | Agrega un nuevo elemento. |
| [get_xml_value()](#get_xml_value__3) | Convierte el valor XMP a la representación XML. |
| [get_xmp_representation()](#get_xmp_representation__4) | Obtiene el valor de cadena XMP de este. |


### Constructor: XmpArray(type, items) {#XmpArray_type_items_1}


```
 XmpArray(type, items) 
```

Inicializa una nueva instancia de la clase [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype/) | El tipo de arreglo. |
| elementos | string[] | La lista de elementos. |

### Method: add(item) {#add_item_1}


```
 add(item) 
```

Agrega un nuevo elemento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| elemento | System.Object | El elemento que se añadirá a la lista de elementos. |

### Method: add_item(item) {#add_item_item_2}


```
 add_item(item) 
```

Agrega un nuevo elemento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| elemento | string | El elemento que se añadirá a la lista de elementos. |

### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Convierte el valor XMP a la representación XML.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a la representación XML. |


### Method: get_xmp_representation() {#get_xmp_representation__4}


```
 get_xmp_representation() 
```

Obtiene el valor de cadena XMP de este.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor de cadena contenido en formato XMP. |


