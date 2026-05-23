---
title: "XmpPacketWrapper Klasse"
type: docs
weight: 480
url: /de/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initialisiert eine neue Instanz der [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) Klasse. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initialisiert eine neue Instanz der [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Liest die Header-Verarbeitungsanweisung. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | Liest die XMP-Metadaten. Optional. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | Liest ein Array von [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) innerhalb von XMP. |
| packages_count | int | r | Ermittelt die Anzahl der Pakete innerhalb der XMP-Struktur. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | Ermittelt die Verarbeitungsanweisung des Trailers. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Fügt das Paket hinzu. |
| clear_packages() | Entfernt alle [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) innerhalb von XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Bestimmt, ob ein Paket im XMP-Wrapper existiert. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Ermittelt das Paket anhand des Namespace-URI. |
| [get_xml_value()](#get_xml_value__4) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [remove_package(package)](#remove_package_package_5) | Entfernt das XMP-Paket. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initialisiert eine neue Instanz der [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) Klasse.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initialisiert eine neue Instanz der [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | Der XMP-Header der Verarbeitungsanweisung. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | Der XMP-Trailer der Verarbeitungsanweisung. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | Die XMP-Metadaten. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Fügt das Paket hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Das Paket. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Bestimmt, ob ein Paket im XMP-Wrapper existiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| namespace_uri | string | Paket-Schema-URI. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Gibt true zurück, wenn ein Paket mit dem angegebenen Namespace-URI im XMP-Wrapper existiert. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Ermittelt das Paket anhand des Namespace-URI.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| namespace_uri | string | Der Paket-Schema-URI. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Gibt das XMP-Paket für den angegebenen Namespace-URI zurück. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den konvertierten XMP-Wert als XML zurück. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Entfernt das XMP-Paket.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Das Paket. |

