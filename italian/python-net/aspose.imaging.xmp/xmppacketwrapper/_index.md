---
title: "Classe XmpPacketWrapper"
type: docs
weight: 480
url: /it/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Inizializza una nuova istanza della classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Inizializza una nuova istanza della classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Ottiene l'istruzione di elaborazione dell'intestazione. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | Ottiene i metadati XMP. Opzionale. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | Ottiene l'array di [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) all'interno di XMP. |
| packages_count | int | r | Ottiene la quantità di pacchetti all'interno della struttura XMP. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | Ottiene l'istruzione di elaborazione del trailer. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Aggiunge il pacchetto. |
| clear_packages() | Rimuove tutti i [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) all'interno di XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Determina se il pacchetto esiste nel wrapper XMP. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Ottiene il pacchetto per URI dello spazio dei nomi. |
| [get_xml_value()](#get_xml_value__4) | Converte il valore XMP nella rappresentazione XML. |
| [remove_package(package)](#remove_package_package_5) | Rimuove il pacchetto XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Inizializza una nuova istanza della classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Inizializza una nuova istanza della classe [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | L'intestazione XMP dell'istruzione di elaborazione. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | Il trailer XMP dell'istruzione di elaborazione. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | I metadati XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Aggiunge il pacchetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Il pacchetto. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Determina se il pacchetto esiste nel wrapper XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| namespace_uri | string | URI dello schema del pacchetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce true se il pacchetto con l'URI dello spazio dei nomi specificato esiste nel wrapper XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Ottiene il pacchetto per URI dello spazio dei nomi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| namespace_uri | string | L'URI dello schema del pacchetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Restituisce il pacchetto XMP per l'URI dello spazio dei nomi specificato. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converte il valore XMP nella rappresentazione XML.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore XMP convertito in XML. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Rimuove il pacchetto XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Il pacchetto. |

