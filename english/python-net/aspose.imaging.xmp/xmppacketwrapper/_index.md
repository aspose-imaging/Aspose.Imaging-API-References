---
title: XmpPacketWrapper Class
type: docs
weight: 480
url: /python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Gets the header processing instruction. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | Gets the XMP meta. Optional. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | Gets array of [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) inside XMP. |
| packages_count | int | r | Gets amount of packages inside XMP structure. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | Gets the trailer processing instruction. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Adds the package. |
| clear_packages() | Removes all [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) inside XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Determines whethere package is exist in xmp wrapper. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Gets package by namespace URI. |
| [get_xml_value()](#get_xml_value__4) | Converts XMP value to the XML representation. |
| [remove_package(package)](#remove_package_package_5) | Removes the XMP package. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | The XMP header of processing instruction. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | The XMP trailer of processing instruction. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | The XMP metadata. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Adds the package.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | The package. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Determines whethere package is exist in xmp wrapper.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | string | Package schema uri. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if package with specified namespace Uri exist in XMP wrapper. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Gets package by namespace URI.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | string | The package schema URI. |

**Returns**

| Type | Description |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Returns the XMP package for specified namespace URI. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns converted XMP value to XML. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Removes the XMP package.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | The package. |

