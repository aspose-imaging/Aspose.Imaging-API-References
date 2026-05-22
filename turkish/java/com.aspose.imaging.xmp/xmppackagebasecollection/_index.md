---
title: "XmpPackageBaseCollection"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XmpPackage koleksiyonunu temsil eder."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

`XmpPackage` koleksiyonunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | `XmpPackageBaseCollection` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyondaki öğe sayısını alır. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | `XmpPackage` yeni bir örnek ekler. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | Belirtilen XMP paketini kaldırır. |
| [getPackages()](#getPackages--) | `XmpPackage` dizisini al. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | `XmpPackage`'i namespaceURI'si ile alır. |
| [clear()](#clear--) | Koleksiyon içindeki tüm `XmpPackage` öğelerini temizler. |
| [iterator()](#iterator--) | Bir koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


`XmpPackageBaseCollection` sınıfının yeni bir örneğini başlatır.

### getCount() {#getCount--}
```
public int getCount()
```


Koleksiyondaki öğe sayısını alır.

Değer: koleksiyondaki öğe sayısı.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


`XmpPackage` yeni bir örnek ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Eklenecek XMP paketi\_. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


Belirtilen XMP paketini kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Kaldırılacak XMP paketi\_. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


`XmpPackage` dizisini al.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - XMP paketlerinin bir dizisini döndürür.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


`XmpPackage`'i namespaceURI'si ile alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paket\_ almak için namespace URI. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


Koleksiyon içindeki tüm `XmpPackage` öğelerini temizler.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


Bir koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir `System.Collections.IEnumerator` nesnesi.
