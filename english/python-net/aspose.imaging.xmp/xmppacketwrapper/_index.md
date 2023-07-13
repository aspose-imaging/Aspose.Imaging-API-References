---
title: XmpPacketWrapper Class
type: docs
weight: 460
url: /python-net/aspose.imaging.xmp/xmppacketwrapper/
---

Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Aspose.Imaging Version:** 23.6

The XmpPacketWrapper type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_0) | Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class. |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi) | r | Gets the header processing instruction. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta) | r/w | Gets the XMP meta. Optional. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi) | r | Gets the trailer processing instruction. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage) | r | Gets array of [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) inside XMP. |
| packages_count | int | r | Gets amount of packages inside XMP structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_2) | Adds the package. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Gets package by namespace URI. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_4) | Determines whethere package is exist in xmp wrapper. |
| [remove_package(package)](#remove_package_package_5) | Removes the XMP package. |
| clear_packages() | Removes all [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) inside XMP. |

### XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_0}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi) | The XMP header of processing instruction. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi) | The XMP trailer of processing instruction. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta) | The XMP metadata. |

### XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) class.

### add_package(package) {#add_package_package_2}


```
 add_package(package) 
```

Adds the package.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage) | The package. |

### get_package(namespace_uri) {#get_package_namespace_uri_3}


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
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage) | Returns the XMP package for specified namespace URI. |


### contains_package(namespace_uri) {#contains_package_namespace_uri_4}


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


### remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Removes the XMP package.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage) | The package. |

