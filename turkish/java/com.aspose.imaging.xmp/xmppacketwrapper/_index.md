---
title: "XmpPacketWrapper"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Başlık ve kuyruk dahil olmak üzere serileştirilmiş xmp paketini içerir."
type: docs
weight: 21
url: /tr/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Başlık ve kuyruk dahil olmak üzere serileştirilmiş xmp paketini içerir.

XML işleme talimatlarından (PI) oluşan bir çift içeren bir sarmalayıcı, rdf:RDF öğesinin etrafına yerleştirilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | `XmpPacketWrapper` sınıfının yeni bir örneğini başlatır. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | `XmpPacketWrapper` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Başlık işleme talimatını alır. |
| [getMeta()](#getMeta--) | XMP meta bilgisini alır. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | XMP meta bilgisini ayarlar. |
| [getTrailerPi()](#getTrailerPi--) | Sonek işleme talimatını alır. |
| [getPackages()](#getPackages--) | XMP içinde `XmpPackage` dizisini alır. |
| [getPackagesCount()](#getPackagesCount--) | XMP yapısı içinde paket sayısını alır. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Paketi ekler. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Paketi ad alanı URI'sine göre alır. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Paketin XMP sarmalayıcısında mevcut olup olmadığını belirler. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | XMP paketini kaldırır. |
| [clearPackages()](#clearPackages--) | XMP içinde bulunan tüm `XmpPackage` öğelerini kaldırır. |
| [getXmlValue()](#getXmlValue--) | XMP değerini XML temsiline dönüştürür. |
| [toString()](#toString--) | Geçerli nesneyi temsil eden bir XML dizesi döndürür. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


`XmpPacketWrapper` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | İşlem talimatının XMP başlığı. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | İşlem talimatının XMP son ek'i. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | XMP meta verileri. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


`XmpPacketWrapper` sınıfının yeni bir örneğini başlatır.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Başlık işleme talimatını alır.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


XMP meta verisini alır. İsteğe bağlı.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


XMP meta verisini ayarlar. İsteğe bağlı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | XMP meta verisi. İsteğe bağlı. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Sonek işleme talimatını alır.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


XMP içinde `XmpPackage` dizisini alır.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - XMP içinde bulunan `XmpPackage` dizisi.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


XMP yapısı içinde paket sayısını alır.

**Returns:**
int - XMP yapısı içinde bulunan paket sayısı.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Paketi ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Paket. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Paketi ad alanı URI'sine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paket şema URI'si. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Paketin XMP sarmalayıcısında mevcut olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paket şema uri'si. |

**Returns:**
boolean - Belirtilen ad alanı Uri'sine sahip paket XMP sarmalayıcısında mevcutsa true döndürür.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


XMP paketini kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Paket. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


XMP içinde bulunan tüm `XmpPackage` öğelerini kaldırır.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - Dönüştürülmüş XMP değerini XML olarak döndürür.
### toString() {#toString--}
```
public String toString()
```


Geçerli nesneyi temsil eden bir XML dizesi döndürür.

**Returns:**
java.lang.String - Geçerli nesneyi temsil eden bir XML dizesi.
