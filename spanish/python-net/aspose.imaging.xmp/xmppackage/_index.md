---
title: "Clase XmpPackage"
type: docs
weight: 460
url: /es/python-net/aspose.imaging.xmp/xmppackage/
---

**Summary:** Represents base abstraction for XMP package.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackage

**Inheritance:** IXmlValue

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| count | int | r | Obtiene el recuento de claves XMP. |
| namespace_uri | string | r | Obtiene el URI del espacio de nombres. |
| prefix | string | r | Obtiene el prefijo. |
| xml_namespace | string | r | Obtiene el espacio de nombres XML. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Agrega el valor a la clave especificada. |
| [add_value(key, value)](#add_value_key_value_2) | Agrega el valor a la clave especificada. |
| clear() | Borra esta instancia. |
| [contains_key(key)](#contains_key_key_3) | Determina si esta colección contiene la clave especificada. |
| [get_prop_value(key)](#get_prop_value_key_4) | Obtiene el objeto con la clave especificada. |
| [get_xml_value()](#get_xml_value__5) | Convierte el valor XMP a la representación XML. |
| [remove(key)](#remove_key_6) | Elimina el valor con la clave especificada. |
| [set_prop_value(key, value)](#set_prop_value_key_value_7) | Obtiene o establece el objeto con la clave especificada. |
| [set_value(key, value)](#set_value_key_value_8) | Establece el valor. |
| [set_value(key, value)](#set_value_key_value_9) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Establece el valor del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_11) | Obtiene el valor por la _clave_. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Agrega el valor a la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | string | El valor al que agregar. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Agrega el valor a la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | System.Object | El valor al que agregar. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Determina si esta colección contiene la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave a comprobar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | **True** si el contiene la clave especificada; de lo contrario, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Obtiene el objeto con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave que identifica el valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object | Devuelve el objeto con la clave especificada. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Convierte el valor XMP a la representación XML.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a la representación XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Elimina el valor con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor eliminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve verdadero si el valor con la clave especificada fue eliminado. |


### Method: set_prop_value(key, value) {#set_prop_value_key_value_7}


```
 set_prop_value(key, value) 
```

Obtiene o establece el objeto con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave que identifica el valor. |
| valor | System.Object | El objeto con la clave especificada. |

### Method: set_value(key, value) {#set_value_key_value_8}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | El valor al que agregar. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | El valor al que establecer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_11}


```
 try_get_value(key, value) 
```

Obtiene el valor por la _clave_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave del elemento XMP. |
| valor | System.Object | El valor XMP. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | **True**, si el contiene la _key_; de lo contrario, **False**. |


