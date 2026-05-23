---
title: "XmpRdfRoot Clase"
type: docs
weight: 490
url: /es/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Inicializa una nueva instancia de la clase [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Agrega el atributo. |
| clear_attributes() | Elimina todos los atributos. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Obtiene el atributo. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Obtiene el URI del espacio de nombres por un prefijo específico. El prefijo puede comenzar sin xmlns. |
| [get_xml_value()](#get_xml_value__4) | Convierte el valor xmp a la representación xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Agrega el URI del espacio de nombres por prefijo. El prefijo puede comenzar sin xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Inicializa una nueva instancia de la clase [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/).

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Agrega el atributo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| atributo | string | El atributo. |
| valor | string | El valor. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Obtiene el atributo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| atributo | string | El atributo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el atributo para el nombre de atributo especificado. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Obtiene el URI del espacio de nombres por un prefijo específico. El prefijo puede comenzar sin xmlns.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prefix | string | El prefijo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve un URI del esquema del paquete. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Convierte el valor xmp a la representación xml.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a cadena XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Agrega el URI del espacio de nombres por prefijo. El prefijo puede comenzar sin xmlns.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prefix | string | El prefijo. |
| namespace_uri | string | URI del esquema del paquete. |

