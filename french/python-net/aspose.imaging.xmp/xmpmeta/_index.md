---
title: "Classe XmpMeta"
type: docs
weight: 440
url: /fr/python-net/aspose.imaging.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Initialise une nouvelle instance de la classe [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/). |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Initialise une nouvelle instance de la classe [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Obtient ou définit la version du toolkit Adobe Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Ajoute l'attribut. |
| clear_attributes() | Supprime tous les attributs. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Obtient l'attribut. |
| [get_xml_value()](#get_xml_value__3) | Convertit la valeur XMP en représentation XML. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Initialise une nouvelle instance de la classe [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/).

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Initialise une nouvelle instance de la classe [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| toolkit_version | string | Version du toolkit Adobe XMP. |

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


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Convertit la valeur XMP en représentation XML.

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie la valeur XMP convertie en représentation XML. |


