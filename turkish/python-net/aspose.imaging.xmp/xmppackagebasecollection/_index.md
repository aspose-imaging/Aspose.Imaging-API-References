---
title: "XmpPackageBaseCollection Sınıfı"
type: docs
weight: 470
url: /tr/python-net/aspose.imaging.xmp/xmppackagebasecollection/
---

**Summary:** Represents collection of [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackageBaseCollection

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection__1) | [XmpPackageBaseCollection](/imaging/python-net/aspose.imaging.xmp/xmppackagebasecollection/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| count | int | r | Koleksiyondaki öğelerin sayısını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(package)](#add_package_1) | Yeni bir [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) örneği ekler. |
| clear() | Koleksiyon içindeki tüm [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) öğelerini temizler. |
| [get_package(namespace_uri)](#get_package_namespace_uri_2) | Namespace URI'sine göre [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) alır. |
| [get_packages()](#get_packages__3) | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) dizisini al. |
| [remove(package)](#remove_package_4) | Belirtilen XMP paketini kaldırır. |


### Constructor: XmpPackageBaseCollection() {#XmpPackageBaseCollection__1}


```
 XmpPackageBaseCollection() 
```

[XmpPackageBaseCollection](/imaging/python-net/aspose.imaging.xmp/xmppackagebasecollection/) sınıfının yeni bir örneğini başlatır.

### Method: add(package) {#add_package_1}


```
 add(package) 
```

Yeni bir [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) örneği ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Eklenecek XMP paketi. |

### Method: get_package(namespace_uri) {#get_package_namespace_uri_2}


```
 get_package(namespace_uri) 
```

Namespace URI'sine göre [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| namespace_uri | string | Paketin alınacağı namespace URI. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Belirtilen namespace URI için XMP paketini döndürür. |


### Method: get_packages() {#get_packages__3}


```
 get_packages() 
```

[XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) dizisini al.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | XMP paketlerinin bir dizisini döndürür. |


### Method: remove(package) {#remove_package_4}


```
 remove(package) 
```

Belirtilen XMP paketini kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Kaldırılacak XMP paketi. |

