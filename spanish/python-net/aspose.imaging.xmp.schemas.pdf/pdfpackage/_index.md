---
title: "Clase PdfPackage"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Inicializa una nueva instancia de la clase [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/). |
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
| [set_keywords(keywords)](#set_keywords_keywords_7) | Establece las palabras clave. |
| [set_pdf_version(version)](#set_pdf_version_version_8) | Establece la versión del PDF. |
| [set_producer(producer)](#set_producer_producer_9) | Establece el nombre de la herramienta que creó el PDF. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Obtiene o establece el objeto con la clave especificada. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | Establece el trapped. |
| [set_value(key, value)](#set_value_key_value_12) | Establece el valor. |
| [set_value(key, value)](#set_value_key_value_13) | Establece el valor. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | Establece el valor del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | Obtiene el valor por la _clave_. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Inicializa una nueva instancia de la clase [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/).

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

Establece las palabras clave.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palabras clave | string | Las palabras clave. |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

Establece la versión del PDF.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| versión | string | Versión de PDF, por ejemplo: 1.0, 1.3 etc. |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

Establece el nombre de la herramienta que creó el PDF.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| productor | string | El nombre del productor. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

Obtiene o establece el objeto con la clave especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La clave que identifica el valor. |
| valor | System.Object | El objeto con la clave especificada. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

Establece el trapped.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| is_trapped | bool | si se establece en <c>true</c> el documento ha sido atrapado. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | El valor al que agregar. |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

Establece el valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | El valor al que agregar. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

Establece el valor del tipo XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | string | La representación en cadena de la clave que se identifica con el valor establecido. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | El valor al que establecer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


