---
title: XmpPacketWrapper Class
type: docs
weight: 110
url: /python-net/api-reference/aspose.imaging.xmp/xmppacketwrapper/
---

Contains serialized xmp package including header and trailer.

**Namespace:** [aspose.imaging.xmp](/imaging/python-net/api-reference/aspose.imaging.xmp/)

**Full Class Name:** aspose.imaging.xmp.XmpPacketWrapper

**Assembly:**  Aspose.Imaging Version: 23.3.0

The XmpPacketWrapper type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|XmpPacketWrapper(header, trailer, xmp_meta)|Initializes a new instance of the XmpPacketWrapper class|
|XmpPacketWrapper()|Initializes a new instance of the [XmpPacketWrapper](/imaging/python-net/api-reference/aspose.imaging.xmp/xmppacketwrapper/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|header_pi|Gets the header processing instruction.|
|meta|Gets the XMP meta. Optional.|
|trailer_pi|Gets the trailer processing instruction.|
|packages|Gets array of [XmpPackage](/imaging/python-net/api-reference/aspose.imaging.xmp/xmppackage/) inside XMP.|
|packages_count|Gets amount of packages inside XMP structure.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|add_package(package)|Adds the package.|
|get_package(namespace_uri)|Gets package by namespace URI.|
|contains_package(namespace_uri)|Determines whethere package is exist in xmp wrapper.|
|remove_package(package)|Removes the XMP package.|
|clear_packages()|Removes all [XmpPackage](/imaging/python-net/api-reference/aspose.imaging.xmp/xmppackage/) inside XMP.|
