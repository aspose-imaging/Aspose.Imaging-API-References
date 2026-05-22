---
title: "XmpPacketWrapper فئة"
type: docs
weight: 480
url: /ar/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | يُهيئ نسخة جديدة من الفئة [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | يُهيئ نسخة جديدة من الفئة [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | يحصل على تعليمات معالجة الرأس. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | يحصل على بيانات XMP الوصفيّة. اختياري. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | يحصل على مصفوفة من [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) داخل XMP. |
| packages_count | int | r | يحصل على عدد الحزم داخل بنية XMP. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | يحصل على تعليمات معالجة التذييل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | يضيف الحزمة. |
| clear_packages() | يزيل جميع [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) داخل XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | يحدد ما إذا كانت الحزمة موجودة في غلاف XMP. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | يحصل على الحزمة حسب مساحة الاسم URI. |
| [get_xml_value()](#get_xml_value__4) | يحوّل قيمة XMP إلى تمثيل XML. |
| [remove_package(package)](#remove_package_package_5) | يزيل حزمة XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

يُهيئ نسخة جديدة من الفئة [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

يُهيئ نسخة جديدة من الفئة [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | رأس XMP لتعليمات المعالجة. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | تذييل XMP لتعليمات المعالجة. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | بيانات XMP الوصفية. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

يضيف الحزمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | الحزمة. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

يحدد ما إذا كانت الحزمة موجودة في غلاف XMP.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| namespace_uri | string | مسار مخطط الحزمة URI. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | يرجع true إذا كانت الحزمة ذات مساحة الاسم المحددة URI موجودة في غلاف XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

يحصل على الحزمة حسب مساحة الاسم URI.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| namespace_uri | string | مسار مخطط الحزمة URI. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | يرجع حزمة XMP لمساحة الاسم URI المحددة. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

يحوّل قيمة XMP إلى تمثيل XML.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يرجع قيمة XMP المحوّلة إلى XML. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

يزيل حزمة XMP.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | الحزمة. |

