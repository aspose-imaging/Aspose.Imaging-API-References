---
title: "Classe XmpRdfRoot"
type: docs
weight: 490
url: /it/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Inizializza una nuova istanza della classe [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) . |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Aggiunge l'attributo. |
| clear_attributes() | Rimuove tutti gli attributi. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Ottiene l'attributo. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Ottiene l'URI dello spazio dei nomi per un prefisso specifico. Il prefisso può iniziare senza xmlns. |
| [get_xml_value()](#get_xml_value__4) | Converte il valore xmp nella rappresentazione xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Aggiunge l'URI dello spazio dei nomi per un prefisso. Il prefisso può iniziare senza xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Inizializza una nuova istanza della classe [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) .

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Aggiunge l'attributo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attributo | string | L'attributo. |
| valore | string | Il valore. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Ottiene l'attributo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attributo | string | L'attributo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce l'attributo per il nome dell'attributo specificato. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Ottiene l'URI dello spazio dei nomi per un prefisso specifico. Il prefisso può iniziare senza xmlns.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| prefix | string | Il prefisso. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce un URI dello schema del pacchetto. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converte il valore xmp nella rappresentazione xml.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore XMP convertito in stringa XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Aggiunge l'URI dello spazio dei nomi per un prefisso. Il prefisso può iniziare senza xmlns.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| prefix | string | Il prefisso. |
| namespace_uri | string | URI dello schema del pacchetto. |

