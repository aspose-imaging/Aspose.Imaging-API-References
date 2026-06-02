---
title: "XmpPacketWrapper Sınıfı"
type: docs
weight: 480
url: /tr/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Yeni bir [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) sınıfı örneği başlatır. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Yeni bir [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Başlık işleme talimatını alır. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | XMP meta verisini alır. İsteğe bağlı. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | XMP içinde bulunan [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) dizisini alır. |
| packages_count | int | r | XMP yapısı içindeki paket sayısını alır. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | İşleme talimatının trailer'ını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Paketi ekler. |
| clear_packages() | XMP içinde tüm [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) öğelerini kaldırır. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Paketin xmp sarmalayıcısında mevcut olup olmadığını belirler. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Paketi namespace URI'sine göre alır. |
| [get_xml_value()](#get_xml_value__4) | XMP değerini XML temsiline dönüştürür. |
| [remove_package(package)](#remove_package_package_5) | XMP paketini kaldırır. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Yeni bir [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) sınıfı örneği başlatır.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Yeni bir [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | İşleme talimatının XMP başlığı. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | İşleme talimatının XMP trailer'ı. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | XMP meta verileri. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Paketi ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Paket. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Paketin xmp sarmalayıcısında mevcut olup olmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| namespace_uri | string | Paket şema uri'si. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen namespace Uri'ye sahip paket XMP sarmalayıcısında mevcutsa true döndürür. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Paketi namespace URI'sine göre alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| namespace_uri | string | Paket şema URI'si. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Belirtilen namespace URI için XMP paketini döndürür. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

XMP değerini XML temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Dönüştürülmüş XMP değerini XML olarak döndürür. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

XMP paketini kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Paket. |

