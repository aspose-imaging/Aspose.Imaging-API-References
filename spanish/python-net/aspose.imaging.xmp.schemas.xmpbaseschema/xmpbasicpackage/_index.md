---
title: "XmpBasicPackage Clase"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Inicializa una nueva instancia de la [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) clase. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Inicializa una nueva instancia de la [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Rating valor máximo. |
| RATING_MIN [static] | int | r | Rating valor mínimo. |
| RATING_REJECTED [static] | int | r | Rating valor rechazado. |
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
| [set_created_date(created_date)](#set_created_date_created_date_7) | Agrega la fecha de creación del recurso. |
| [set_created_date(created_date)](#set_created_date_created_date_8) | Agrega la fecha de creación del recurso. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | Agrega la fecha de creación del recurso. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | Establece la herramienta creadora. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | Establece el identificador. |
| [set_label(label)](#set_label_label_12) | Establece la etiqueta. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Agrega la fecha de última modificación de los metadatos. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | Agrega la fecha de última modificación de los metadatos. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | Agrega la fecha de última modificación de los metadatos. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Agrega la fecha de última modificación del recurso. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | Agrega la fecha de última modificación del recurso. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | Agrega la fecha de última modificación del recurso. |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | Obtiene o establece el objeto con la clave especificada. |
| [set_rating(choise)](#set_rating_choise_20) | Establece la calificación. |
| [set_value(key, value)](#set_value_key_value_21) | Establece el valor. |
| [set_value(key, value)](#set_value_key_value_22) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | Establece el valor del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_24) | Obtiene el valor por la _clave_. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Inicializa una nueva instancia de la [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) clase.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Inicializa una nueva instancia de la [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) clase.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prefix | string | El prefijo. |
| namespace_uri | string | El URI del espacio de nombres. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Agrega la fecha de creación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| created_date | System.DateTime | Fecha de creación. |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

Agrega la fecha de creación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| created_date | string | Fecha de creación. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

Agrega la fecha de creación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| created_date | string | Fecha de creación. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

Establece la herramienta creadora.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| creator_tool | string | Nombre de la herramienta. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

Establece el identificador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| identificador | string[] | El identificador. |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

Establece la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| etiqueta | string | La etiqueta. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Agrega la fecha de última modificación de los metadatos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fecha_metadatos | System.DateTime | Fecha de metadatos. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

Agrega la fecha de última modificación de los metadatos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fecha_metadatos | string | Fecha de metadatos. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

Agrega la fecha de última modificación de los metadatos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fecha_metadatos | string | Fecha de metadatos. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Agrega la fecha de última modificación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| modified_date | System.DateTime | Fecha de última modificación. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

Agrega la fecha de última modificación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| modified_date | string | Fecha de última modificación. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

Agrega la fecha de última modificación del recurso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| modified_date | string | Fecha de última modificación. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

Obtiene o establece el objeto con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave que identifica el valor. |
| valor | System.Object | El objeto con la clave especificada. |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

Establece la calificación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| opción | int | De -1 a 5 |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | El valor al que agregar. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | El valor al que establecer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


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


