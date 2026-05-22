---
title: "XmpPacketWrapper Classe"
type: docs
weight: 480
url: /fr/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initialise une nouvelle instance de la classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initialise une nouvelle instance de la classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Obtient l'instruction de traitement de l'en-tête. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | Obtient les métadonnées XMP. Facultatif. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | Obtient le tableau de [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) à l'intérieur de XMP. |
| packages_count | int | r | Obtient le nombre de packages dans la structure XMP. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | Obtient l'instruction de traitement du trailer. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Ajoute le package. |
| clear_packages() | Supprime tous les [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) dans XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Détermine si le package existe dans l'enveloppe xmp. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Obtient le package par l'URI de l'espace de noms. |
| [get_xml_value()](#get_xml_value__4) | Convertit la valeur XMP en représentation XML. |
| [remove_package(package)](#remove_package_package_5) | Supprime le package XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initialise une nouvelle instance de la classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initialise une nouvelle instance de la classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | L'en-tête XMP de l'instruction de traitement. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | Le trailer XMP de l'instruction de traitement. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | Les métadonnées XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Ajoute le package.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Le package. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Détermine si le package existe dans l'enveloppe xmp.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| namespace_uri | string | URI du schéma du package. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie vrai si le package avec l'URI d'espace de noms spécifié existe dans l'enveloppe XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Obtient le package par l'URI de l'espace de noms.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| namespace_uri | string | L'URI du schéma du package. |

**Returns**

| Type | Description |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Renvoie le package XMP pour l'URI d'espace de noms spécifié. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Convertit la valeur XMP en représentation XML.

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie la valeur XMP convertie en XML. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Supprime le package XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Le package. |

