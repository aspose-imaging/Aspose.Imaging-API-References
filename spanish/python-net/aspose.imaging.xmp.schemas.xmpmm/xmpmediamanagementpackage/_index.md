---
title: "Clase XmpMediaManagementPackage"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpmm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Inicializa una nueva instancia de la clase [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/). |
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
| [add_value(key, value)](#add_value_key_value_1) | Agrega una propiedad de cadena. |
| [add_value(key, value)](#add_value_key_value_2) | Agrega una propiedad de cadena. |
| clear() | Borra esta instancia. |
| [contains_key(key)](#contains_key_key_3) | Determina si esta colección contiene la clave especificada. |
| [get_prop_value(key)](#get_prop_value_key_4) | Obtiene el objeto con la clave especificada. |
| [get_xml_value()](#get_xml_value__5) | Convierte el valor XMP a la representación XML. |
| [remove(key)](#remove_key_6) | Elimina el valor con la clave especificada. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_7) | Establece el derivado de. |
| [set_document_id(guid)](#set_document_id_guid_8) | Establece el identificador del documento. |
| [set_document_id(guid)](#set_document_id_guid_9) | Establece el identificador del documento. |
| [set_document_id_as_guid(guid)](#set_document_id_as_guid_guid_10) | Establece el identificador del documento. |
| [set_instance_id(guid)](#set_instance_id_guid_11) | Establece el id de la instancia. |
| [set_instance_id(guid)](#set_instance_id_guid_12) | Establece el id de la instancia. |
| [set_instance_id_as_guid(guid)](#set_instance_id_as_guid_guid_13) | Establece el id de la instancia. |
| [set_original_document_id(guid)](#set_original_document_id_guid_14) | Establece el id del documento original. |
| [set_original_document_id(guid)](#set_original_document_id_guid_15) | Establece el id del documento original. |
| [set_original_document_id_as_guid(guid)](#set_original_document_id_as_guid_guid_16) | Establece el id del documento original. |
| [set_prop_value(key, value)](#set_prop_value_key_value_17) | Obtiene o establece el objeto con la clave especificada. |
| [set_value(key, value)](#set_value_key_value_18) | Establece el valor. |
| [set_value(key, value)](#set_value_key_value_19) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_20) | Establece el valor del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_21) | Obtiene el valor por la _clave_. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Inicializa una nueva instancia de la clase [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/).

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Agrega una propiedad de cadena.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | string | El valor de cadena. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Agrega una propiedad de cadena.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | System.Object | El valor de cadena. |

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_7}


```
 set_derived_from(resource_ref) 
```

Establece el derivado de.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| resource_ref | [ResourceRef](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceref/resourceref/) | La referencia del recurso. |

### Method: set_document_id(guid) {#set_document_id_guid_8}


```
 set_document_id(guid) 
```

Establece el identificador del documento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | System.Guid | El identificador único. |

### Method: set_document_id(guid) {#set_document_id_guid_9}


```
 set_document_id(guid) 
```

Establece el identificador del documento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | string | El identificador único. |

### Method: set_document_id_as_guid(guid) {#set_document_id_as_guid_guid_10}


```
 set_document_id_as_guid(guid) 
```

Establece el identificador del documento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | System.Guid | El identificador único. |

### Method: set_instance_id(guid) {#set_instance_id_guid_11}


```
 set_instance_id(guid) 
```

Establece el id de la instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | System.Guid | El identificador único. |

### Method: set_instance_id(guid) {#set_instance_id_guid_12}


```
 set_instance_id(guid) 
```

Establece el id de la instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | string | El identificador único. |

### Method: set_instance_id_as_guid(guid) {#set_instance_id_as_guid_guid_13}


```
 set_instance_id_as_guid(guid) 
```

Establece el id de la instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | System.Guid | El identificador único. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_14}


```
 set_original_document_id(guid) 
```

Establece el id del documento original.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | System.Guid | El identificador único. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_15}


```
 set_original_document_id(guid) 
```

Establece el id del documento original.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | string | El identificador único. |

### Method: set_original_document_id_as_guid(guid) {#set_original_document_id_as_guid_guid_16}


```
 set_original_document_id_as_guid(guid) 
```

Establece el id del documento original.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | System.Guid | El identificador único. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_17}


```
 set_prop_value(key, value) 
```

Obtiene o establece el objeto con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave que identifica el valor. |
| valor | System.Object | El objeto con la clave especificada. |

### Method: set_value(key, value) {#set_value_key_value_18}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | El valor al que agregar. |

### Method: set_value(key, value) {#set_value_key_value_19}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_20}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | El valor al que establecer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_21}


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


