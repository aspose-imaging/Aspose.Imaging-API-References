---
title: "XmpRdfRoot Klasse"
type: docs
weight: 490
url: /de/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Initialisiert eine neue Instanz der [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) Klasse. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Fügt das Attribut hinzu. |
| clear_attributes() | Entfernt alle Attribute. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Liest das Attribut. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Ruft den Namespace-URI anhand eines bestimmten Präfixes ab. Das Präfix kann ohne xmlns beginnen. |
| [get_xml_value()](#get_xml_value__4) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Fügt den Namespace-URI anhand eines Präfixes hinzu. Das Präfix kann ohne xmlns beginnen. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Initialisiert eine neue Instanz der [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) Klasse.

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Fügt das Attribut hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Attribut | string | Das Attribut. |
| Wert | string | Der Wert. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Liest das Attribut.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Attribut | string | Das Attribut. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt das Attribut für den angegebenen Attributnamen zurück. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Ruft den Namespace-URI anhand eines bestimmten Präfixes ab. Das Präfix kann ohne xmlns beginnen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| prefix | string | Das Präfix. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt einen Paket‑Schema‑URI zurück. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den XMP-Wert als XML‑String zurück. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Fügt den Namespace-URI anhand eines Präfixes hinzu. Das Präfix kann ohne xmlns beginnen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| prefix | string | Das Präfix. |
| namespace_uri | string | Paket-Schema-URI. |

