---
title: "XmpPacketWrapper klass"
type: docs
weight: 480
url: /sv/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initierar en ny instans av [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) klass. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initierar en ny instans av [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Hämtar header‑processinstruktionen. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | Hämtar XMP‑metadata. Valfritt. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | Hämtar en array av [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) i XMP. |
| packages_count | int | r | Hämtar antalet paket i XMP-strukturen. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | Hämtar trailer‑processinstruktionen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Lägger till paketet. |
| clear_packages() | Tar bort alla [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) i XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Bestämmer om paketet finns i XMP‑omslaget. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Hämtar paketet efter namnrymds‑URI. |
| [get_xml_value()](#get_xml_value__4) | Konverterar XMP‑värde till XML‑representationen. |
| [remove_package(package)](#remove_package_package_5) | Tar bort XMP‑paketet. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initierar en ny instans av [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) klass.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initierar en ny instans av [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | XMP‑huvudet för processinstruktionen. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | XMP‑trailern för processinstruktionen. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | XMP‑metadata. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Lägger till paketet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Paketet. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Bestämmer om paketet finns i XMP‑omslaget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namespace_uri | string | Paketets schemauri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om paket med angiven namnrymds‑URI finns i XMP‑omslaget. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Hämtar paketet efter namnrymds‑URI.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namespace_uri | string | Paketets schemauri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Returnerar XMP‑paketet för angiven namnrymds‑URI. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Konverterar XMP‑värde till XML‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar konverterat XMP‑värde till XML. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Tar bort XMP‑paketet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Paketet. |

