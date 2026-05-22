---
title: "Classe XmpRdfRoot"
type: docs
weight: 490
url: /fr/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Initialise une nouvelle instance de la classe [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Ajoute l'attribut. |
| clear_attributes() | Supprime tous les attributs. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Obtient l'attribut. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Obtient l'URI de l'espace de noms par préfixe spécifique. Le préfixe peut commencer sans xmlns. |
| [get_xml_value()](#get_xml_value__4) | Convertit la valeur xmp en représentation xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Ajoute l'URI de l'espace de noms par préfixe. Le préfixe peut commencer sans xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Initialise une nouvelle instance de la classe [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/).

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Ajoute l'attribut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribut | string | L'attribut. |
| value | string | La valeur. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Obtient l'attribut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribut | string | L'attribut. |

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie l'attribut pour le nom d'attribut spécifié. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Obtient l'URI de l'espace de noms par préfixe spécifique. Le préfixe peut commencer sans xmlns.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| prefix | string | Le préfixe. |

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie l'URI du schéma du paquet. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Convertit la valeur xmp en représentation xml.

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie la valeur XMP convertie en chaîne XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Ajoute l'URI de l'espace de noms par préfixe. Le préfixe peut commencer sans xmlns.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| prefix | string | Le préfixe. |
| namespace_uri | string | URI du schéma du package. |

